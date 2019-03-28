# Micronets API docs

## Create a native desktop application (wrapper) for our hosted swagger editor:

```
sudo npm install nativefier -g
nativefier --name swagger-editor "https://swagger.micronets.in/editor" --file-download-options '{"saveAs": true}'
open ./swagger-editor-darwin-x64/swagger-editor.app # Or just open in Finder
```
