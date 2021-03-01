* What is the shotrtcut key of VS Code for
  - accessing extensions : Ctrl + Shift + X




What are Emmet abbreviations?
What are the Emmett abreviation for ?


How to generate  HTML skeleton fast? Typing "!" and pressing Enter.
Typing  "link:css" and pressing Enter generates ""<link rel="stylesheet" href="style.css">.
Typing "script:src" and pressing Enter generates "<script src=""></script>"
Similarly try "ul>li*3>a" , "button>img*3" etc. Replace 3 with any number you like.
About these shortcuts():  https://medium.com/@kartik2406/web-development-with-vs-code-part-1-emmet-6af80f0f630c 
https://code.visualstudio.com/blogs/2017/08/07/emmet-2.0

Toggle between tabs : Ctrl+tab , Ctrl+Shift+Tab

https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf

Open files in Chromium browser from VSCode,Ubuntu: 
While in a workspace folder in VSCode press Ctrl+Shift+P and select tasks.json.
Block comment what's already there and copy the following code.
        
        {
            "version": "2.0.0",    
            "command": "chromium-browser",
            "linux": {
                "command": "chromium-browser"
            },
            "args": ["${file}"]

        }
Save the tasks.json.
Open the file which need to be opened in the browser. being in that file press Ctrl+Shift+B.
How to open stop files opening on the same tab : File->Preferances-> Search for the setting "editor.enablePreview" , remove the tick. 
