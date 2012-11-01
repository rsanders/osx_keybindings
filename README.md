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


Related Tweaks
==============

Some applications, such as RubyMine / IntelliJ, will interpret
alt/option + key as unicode character entry in some cases.  This
workaround may help:

 Open System Preferences
 Switch to International pane
 Select the Input Menu tab
 Scroll down all the way to the the bottom
 Put a check next to Unicode Hex Input
 Now, close the System Preferences and set your Input Menu to Unicode Hex Input using the menu in the Menu bar
 Key combinations now work without issue in IDEA.

The side effect of this, however, is that you lose the ability to use
Alt+ combinations to get special characters; you can switch back to
your native Input and get them back, however.
