# italics font for comment in vscode 

Here is a simple how it looks like.
<img src="Image/Simple.png" alt="simple" width="500px" >

First step, make sure that you have Operator_mono in your Mac
<img src="Image/installFont.png" alt="installFont" width="500px">

Then,Directly go to the setting, and type the "ditor.tokenColorCustomizations", you will find it on the Settings.json files.
<img src="Image/setting.png" alt="setting" width="500px">
<img src="Image/setting1.png" alt="setting1" width="500px">

Final, directly change by following:
```
"editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          //following will be in italic
          "comment"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  }
```
By the way, you must add few more code in order to complete it
```
  "editor.fontLigatures": true,
  "editor.fontFamily": "Dank Mono, Operator Mono",
    /*if you like, you also can change the font size*/
  "editor.fontSize": 14,
```
<img src="Image/final.png" alt="final" width="500px">

