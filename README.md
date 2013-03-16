# Functionality #

* Holding FN = Hyper Key, aka holding all four modifier keys (ctrl, shift, cmd, & option). Allows easy assigning of global keyboard shortcuts as this combo is rarely used. Hat tip to [Brett Terpstra for the Hyper concept](http://brettterpstra.com/2012/12/08/a-useful-caps-lock-key/). He used the Caps Lock though. 
* Tapping FN = Escape. It’s still in the code from when Brett put it in there. I saw no harm in leaving. Shame it’s just as far away as escape.
* Holding Caps Lock then hitting using some keys on your home row result in arrow keys being pressed. Super handy. You have two options:
	* Diamond Keys Style - j/k/l/i makes left/down/right/up on your cursor. Same feeling as the real arrow keys. My preference.
	* Vim Keys - h/j/l/k makes left/down/right/up on your cursor. 


# How to Set Up #

* Go to System Preferences > Keyboard > Modifier Keys. Set Caps Lock to No Action. 
* Install [PCKeyboardHack](http://pqrs.org/macosx/keyremap4macbook/pckeyboardhack.html.en). Set it to map the Caps Lock Key to key code 62 (right control key). Now holding Caps Lock is like holding the right control.
* Install [KeyRemap4MacBook](http://pqrs.org/macosx/keyremap4macbook/index.html.en).
* Clone this repo in ` ~/Library/Application Support\ ` so that way you should see this path to the KeyRemap4MacBook settings file: ` ~/Library/Application Support/KeyRemap4MacBook/private.xml ` 
	* Optionally, you could go to the KeyRemap4MacBook settings under “Misc & Uninstall” and click “Open private.xml” then paste the contents of my private.xml in there. 
* Reload the XML on the “Change Key” tab
* Enable the top 5 rules that just appeared.

* * * 

## Optionally get your Caps Lock back ##

Search the KeyRemap4MacBook rules for “simultaneous key presses caps lock” and enable the rule that says if you press both shifts at the same time, you gets Caps Lock. Makes sense to me!

## Why I moved Hyper off Caps Lock to FN ##

I at first tried using Brett’s Hyper style to use my arrows, but then I couldn't do modifier keys with arrow keys like shift and right to select text. Deal killer for me (sure he has a way around it). So I’m using the absent right control key.