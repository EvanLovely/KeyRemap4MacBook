![Diamond Keys Style](http://www.evanlovely.com/tricky-name/wp-content/uploads/2013/03/1363396671.jpg)

# Functionality #

* Caps Lock + keys on your home = arrow keys — then hitting using some keys on your home row result in arrow keys being pressed. Super handy. We like keyboard shortcuts because we don't have to take our hands off the home row of the keyboard to head to the mouse; a similar loss of momentum happens when you leave for the arrow keys & come back. I find it to be a huge productivity booster. You have two arrow layout options:
    1. Diamond Keys Style - j/k/l/i makes left/down/right/up on your cursor. Same feeling as the real arrow keys. My preference.
    2. Vim Keys - h/j/l/k makes left/down/right/up on your cursor. For Vim users; they love it.
* FN — Hyper Key, aka holding all four modifier keys (ctrl, shift, cmd, & option). Allows easy assigning of global keyboard shortcuts as this combo is rarely used. Hat tip to [Brett Terpstra for the Hyper concept](http://brettterpstra.com/2012/12/08/a-useful-caps-lock-key/). He used the Caps Lock though. I like FN better.
* Tapping Shift = Escape; Holding Shift = Shift — Usually tab is 'ok', where escape is 'cancel'. This puts them much closer together. Only applies to the left shift. Brett uses it on his Caps Lock key, and since I moved it down to FN, I brought the universal "cancel" up closer.


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