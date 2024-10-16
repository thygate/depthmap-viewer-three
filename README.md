# depthmap-viewer-three

Simple web-based interactive depthmap viewer. Using [threejs](https://threejs.org/) to render a plane with a displacement map.

`Drag-and-drop` images with combined-rgb-and-depth-horizontally into the window to view them.

LIVE at https://thygate.github.io/depthmap-viewer-three

## Example input image

![example](src/assets/roots2_rgbd.png)
>Image was generated with stable diffusion using [AUTOMATIC1111's Stable Diffusion Web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) and [stable-diffusion-webui-depthmap-script](https://github.com/thygate/stable-diffusion-webui-depthmap-script).

## Running

The following installs dev and non-dev dependencies, including `three` for
rendering, and `serve` which is used to serve the website locally:

```
npm clean-install
npm start
```

To install for production without dev dependencies (namely, without `serve`)
run the following then host the files anywhere you want:

```
npm clean-install --production
```