# nwjs-react-devtools-webview-example

Reference NW.js issue: `https://github.com/nwjs/nw.js/issues/4878`

Demonstrate that React Devtools is not working when React app is inside a Webview

React Devtools has been modified to add `"chrome-extension://*"` to the `manifest.json` permissions array.

## how to run

Clone the repository then open a command line to the repository and run:

`nw\nw.exe --load-extension=react-devtools react-app`

NW.js 0.25.2 (Windows x64) is included to make this very easy to test.

Screenshot:

![Screenshot](screenshot.png)

## Author(s)

Frank Hale <frankhale@gmail.com>

## License 

GNU GPL v3 - see [LICENSE](LICENSE)