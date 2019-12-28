# steps to add slides

## 1. Copy and rename [index.html](./index.html)

## 2. [Go to Google slides](https://docs.google.com/presentation)

## 3. Click on file picker (file icon on right hand side)

## 4. Go to Upload and Upload the Targeted PPT

## 5. Click on the PPT

## 6. Go to File > Publish to the web > Embed

## 7. Click Publish and Copy the iframe code snippet

## 8. Remove/delete allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true" from the code snippet

```html
<!-- before -->
<iframe
  src="https://docs.google.com/presentation/d/e/2PACX-1vQT4AZlNL6eLT560lB7KnyrP_EtewXLhBmg9G-49bzg6vNX9YVjpA83L_QnKqo323wziQWVl7DScoWW/embed?start=false&loop=false&delayms=3000"
  frameborder="0"
  width="960"
  height="569"
  allowfullscreen="true"
  mozallowfullscreen="true"
  webkitallowfullscreen="true"
></iframe>

<!-- after -->
<iframe
  src="https://docs.google.com/presentation/d/e/2PACX-1vQT4AZlNL6eLT560lB7KnyrP_EtewXLhBmg9G-49bzg6vNX9YVjpA83L_QnKqo323wziQWVl7DScoWW/embed?start=false&loop=false&delayms=3000"
  frameborder="0"
  width="960"
  height="569"
></iframe>
```

## 9. change width and height property to "100%"

```html
<!-- before -->
<iframe
  src="https://docs.google.com/presentation/d/e/2PACX-1vQT4AZlNL6eLT560lB7KnyrP_EtewXLhBmg9G-49bzg6vNX9YVjpA83L_QnKqo323wziQWVl7DScoWW/embed?start=false&loop=false&delayms=3000"
  frameborder="0"
  width="960"
  height="569"
></iframe>

<!-- after -->
<iframe
  src="https://docs.google.com/presentation/d/e/2PACX-1vQT4AZlNL6eLT560lB7KnyrP_EtewXLhBmg9G-49bzg6vNX9YVjpA83L_QnKqo323wziQWVl7DScoWW/embed?start=false&loop=false&delayms=3000"
  frameborder="0"
  width="100%"
  height="100%"
></iframe>
```

## 10. This step will only work on VS code with a plugin name Live server installed [click hear to install vscode](https://code.visualstudio.com/) [click hear to install Live server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

## 11. After necessary tools are installed open the project in vscode right click on any html file and pick Open with Live server

## 12. This will by default serve all files on [localhost:5500](http://localhost:5500)

## 13. index.html is served by default. To view other html files put a / in front of the url and name of the file
