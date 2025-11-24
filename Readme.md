# U-Turn Blackout+ Color Editor

Just a HTML/JavaScript/CSS Color Editor for the U-TURN Blackout+. Because editing a PDF files is to 90s.

**⚠️ Disclaimer: This tool is not official U-TURN software and comes with no warranty. If you create a design using this editor and submit it to U-TURN, there's no guarantee that the colors will be correctly interpreted or produced. It's intended solely for personal visualization. For official orders, please continue to use the official U-TURN template PDF.**

# Direct Start

Link: https://lofi42.github.io/U-TURN-Blackout-color-editor/blackout-color-editor.html


# Usage

Just open `blackout-color-editor_allinone.html` in a browser – no build or server required. That's it ...

The `blackout-color-editor.html` needs the `img` directory with the logo files. It's included in the `allinone` file

# Features
* Flood Fill Painting: Click on grey zones to fill them with a selected color.
* Color Palette: Choose from a predefined set of 13 colors.
* Mirror Mode: Toggle symmetrical coloring for left/right sides.
* Logo Overlay Toggle: Show/hide logos (e.g., "blackout", "uturn") on predefined positions.
* Design Export/Import: Copy/paste or upload JSON to share or reuse designs.
* Save to File: Download the current design as a .json file.
* Reset Button: Revert the design to the initial grey canvas.

# Technical Notes

* Works with an image-based canvas.
* Uses flood-fill logic to identify and color connected areas.
* Logos are positioned via <img class="logo-overlay"> layers absolutely placed on top of the canvas.
    * The `allinone` file includes all images as base64 data image.
* All UI logic is in a single HTML file using plain JavaScript.

## License

This project is licensed under the terms of the Beerware License – or, if you prefer, the Weedware License.

### THE BEER-WARE LICENSE" (Revision 42):
<lofi42@gmail.com> wrote this file. As long as you retain this notice,  
you can do whatever you want with this stuff. If we meet some day and  
you think this stuff is worth it, you can buy me a beer in return.

### OR, if you prefer:

### THE WEED-WARE LICENSE" (Revision 420):
<lofi42@gmail.com> wrote this file. As long as you retain this notice,  
you can do whatever you want with this stuff. If we meet some day and  
you think this stuff is worth it, you can roll me a joint in return. ✌️🌿
