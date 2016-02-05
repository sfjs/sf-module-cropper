# Image Cropper Widget
Module provides ability to crop user image on client side.

## Usage Example

```html
<label class="item-form item-file">
    <span class="item-label">Image Cropper</span>
    <input type="file" class="js-sf-cropper" data-name="image" data-preview="#cropper-preview">
    <span id="cropper-preview"></span>
</label>
```

Cropper preview:

![cropper-preview](https://cloud.githubusercontent.com/assets/12486924/12550729/ad25ddd8-c376-11e5-80c8-bfba0eba4251.jpg)


## Options
* **data-format** - how to send data: cropped or full size with coordinates to crop on server *Default: "cropped" Optional: "full"*
* **data-ajax-image** - preloading of image through ajax request *Default: "false" Optional: url of image to preload*
* **data-template** - pass custom html template of cropper
* **data-ajax-address** - request address for submitting (if there is no form) *Default: "false" Optional: request URL*
* **data-ratio** - locked aspect ratio *Default: false*
* **data-filename-selector** - node selector to place filename. If starts with space - global search of node (document) otherwise inside the node (if the node is input, then from parent node)
* **data-info** - what info to show *Default: [] Example: </b> data-info="ratio,origSize,croppedSize"*
* **data-preview** - selector of preview element *Default: ""*
* **data-save-btn-text** - save button text *Default: "Save"*
* **data-close-btn-text** - save button text *Default: "Close"*
* **data-custom-btn-class** - pass custom class to btns *Default: ""*
* **data-adjust** - selector of element which triggers crop-modal *Default: ""*  If starts with space - global search of node (document) otherwise inside the node (if the node is input, then from parent node)

### Installation

    npm install -g gulp
    npm install

### Building

    gulp build
    

## License

Copyright (c) 2016 Alex Chepura, Yauheni Yasinau and contributors. Released under an [MIT license](https://github.com/sfjs/sf-module-cropper/blob/master/LICENSE).
