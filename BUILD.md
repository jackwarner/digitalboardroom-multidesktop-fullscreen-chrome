## Packaging

The current build script is a .bat files for Windows. For quick, non-scripted builds on macOS, you can use:

- In Chrome, bring up the Extensions management page by going to this URL: `chrome://extensions`

- If Developer mode is off, turn it on

- Click the Pack extension button. A dialog appears.

- In the Extension root directory field, specify the path to the extension's folder—for example, c:\myext. (Ignore the other field; you don't specify a private key file the first time you package a particular extension.)

- Click OK. The packager creates two files: a .crx file, which is the actual extension that can be installed, and a .pem file, which contains the private key.


See http://www.adambarth.com/experimental/crx/docs/packaging.html for more
