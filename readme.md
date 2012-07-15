Sublime Text 2 Completions for CodeIgniter
==========================================

Ever get sick of typing things like `$this->load->view` or `$this->security->sanitize_filename` when building your CI sites and apps? Well I've gathered together all the functions from the [CodeIgniter User Guide] Class Reference so you no longer have to.

Installation
------------

I'm guessing you've already got a copy of [Sublime Text 2].

**Linux**

Download the *PHP-codeigniter.sublime-completions* file up above, and drop it in your *~/.config/sublime-text-2/Packages/PHP/* folder. Should work immediately.

**Windows & Mac**

Download the *PHP-codeigniter.sublime-completions* file up above, and drop it to *%appdata%\Sublime Text 2\Packages\PHP\* folder. Should work immediately

Usage
-----

Just start typing and up will pop the CodeIgniter functions in question.

By default Sublime Text only triggers on characters, so if you’re trying to auto-complete by typing “$this” it isn’t going to work. Instead, try typing “this” and you should see the list pop up.

Tips
----

To make `$this` work, add the `$` character as a trigger in your Sublime Text preferences / settings:

`"auto_complete_triggers": [ {"selector": "text.html", "characters": "<$"} ],`

The `<` is there by default for HTML purposes, and the `$` is added for PHP.


What's missing
--------------

I've included every CodeIgniter function I could find, but if I've missed anything out, I'd appreciate it if you let me know.

[CodeIgniter User Guide]: http://codeigniter.com/user_guide
[Sublime Text 2]: http://www.sublimetext.com/2