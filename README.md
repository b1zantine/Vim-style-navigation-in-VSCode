# Vim-style-Navigation-in-VSCode
Keybindings for Vim style Navigation in Visual Studio Code

Copy the below code into the `keybindings.json` file in Visual Studio Code. Since there is no command mode in VSCode, the navigation has to be done pressing the `ctrl` key in Windows and Linux.

~~~js
[
	{ "key": "ctrl+h",                    "command": "cursorLeft",
                                     		 "when": "editorTextFocus" },
	{ "key": "ctrl+j",                    "command": "cursorDown",
                                     		 "when": "editorTextFocus" },
	{ "key": "ctrl+k",                    "command": "cursorUp",
                                     		 "when": "editorTextFocus" },
	{ "key": "ctrl+l",                    "command": "cursorRight",
                                     		 "when": "editorTextFocus" }
]
~~~
