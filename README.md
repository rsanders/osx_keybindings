osx_keybindings
===============

DefaultKeyBinding.dict for OSX to be more emacs-y. Cribbed together
from various places on the net, including:

http://www.hcs.harvard.edu/~jrus/Site/cocoa-text.html
https://developer.apple.com/library/mac/#documentation/Cocoa/Reference/ApplicationKit/Classes/NSResponder_Class/Reference/Reference.html
http://www.cocoabits.com/KeyBindingsEditor/Manual/index.html
http://www.hcs.harvard.edu/~jrus/Site/selectors.html   
From: http://cocoadev.com/wiki/KeyBindings

Usage
=====

Install this file like so:

    cp -i DefaultKeyBinding.dict ~/Library/KeyBindings
    
You'll need to restart any running programs before the new bindings
will take effect. Programs that use their own text editing widgets
won't see these keybindings. That includes most Java programs, many
text editors, IDEs, etc.
