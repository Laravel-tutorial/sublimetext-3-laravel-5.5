Sublime Text 3 Code Completions for Laravel 5.5
==========================================


Contributing
------------

This repository was created so that the community could contribute for the benefit of us all. Fork this repository, make changes, and submit a pull-request.



Installation
------------

I'm guessing you've already got a copy of [Sublime Text 3].


Available at Package Manager! just search for laravel 5.5 .

Or you can just git clone this repo into your Packages folder.

git clone https://github.com/Laravel-tutorial/sublimetext-3-laravel-5.5.git



**Linux**

Download the *sublimetext-laravel* file up above, and drop it in your *~/.config/sublime-text-3/Packages/PHP/* folder. Should work immediately.

**Windows & Mac**

Download the *sublimetext-laravel* file up above, and drop it to *%appdata%\Sublime Text 3\Packages\PHP\* folder. Should work immediately

Usage
-----

Just start typing and up will pop the Laravel functions in question.
By default Sublime Text only triggers on characters, so if you’re trying to auto-complete by typing “$” it isn’t going to work. Instead of "$table->text", try typing "table->text" and you should see the list pop up.

Tips
-----

To make $this work, add the $ character as a trigger in your Sublime Text preferences / settings:

"auto_complete_triggers": [ {"selector": "text.html", "characters": "<$"} ],

The < is there by default for HTML purposes, and the $ is added for PHP.


What's missing
--------------


I've included every Laravel function I could find, but if I've missed anything out, I'd appreciate it if you let me know.

[Laravel User Guide]  https://laravel.com/docs/master

[Sublime Text 3]   http://www.sublimetext.com/3





