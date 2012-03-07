Sublime Text 2 Completions for CodeIgniter
==========================================

Ever get sick of typing things like `$this->load->view` or `$this->security->sanitize_filename` when building your CI sites and apps? Well I've gathered together all the functions from the [Codeigniter User Guide] Class Reference so you no longer have to.

Installation
------------

I'm guessing you've already got a copy of [Sublime Text 2].

**Linux**

Download the PHP-Codeigniter.sublime_completions file up above, and drop it in your *~/.config/sublime-text-2/Packages/PHP/* folder. Should work immediately.

**Windows & Mac**

You're going to need to drop it into wherever your Sublime Text config folder is. I haven't used either OS for a couple of months, but seeing as you're clever enough to understand Git and code in PHP, I don't think you'll have too much trouble,

Usage
-----

There are two ways to use the completions:

**The shorthand way**

Type the initial letters in the function you want and press tab - e.g. type `tip` for `$this->input->post`.

* Type `tlv` + tab for `$this->load->view(view, $data, true/false)`.
* Type `txi` + tab for `$this->xmlrpc->initialize($config)`

etc.

**The longhand way**

Just start typing part of the function to get the completion. If you type `waterm` you should see `$this->image_lib->watermark` pop up. If you type `load` you'll see `$this->load->model` and `$this->load->view`, and so on.

What's missing
--------------

I've left out the helper functions for now but will add them later.

[Codeigniter User Guide]: http://codeigniter.com/user_guide
[Sublime Text 2]: http://www.sublimetext.com/2