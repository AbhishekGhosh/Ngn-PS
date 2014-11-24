Ngn-PS CMS
=========

Light CMS Designed For Nginx but Licensed under Apache2! 

I'll code this CMS using Github Editor! 1 file per day. 

PHP is inferior langugage but ordinary people basically can not install even Jekyll. JSON is FATFREE. Lua would be better though.

25th November 2014

Let us start with the Nginx configaration. You need a server. May be DigitalOcean or Linode. 512 MB is enough. We'll use 3 php files and 3 directories. You'll SSH and cd to `/usr/share/nginx/html`. First remove all default file and create a content folder there by running `rm -r * && mkdir content`. We should create a backup folder `mkdir backup`. Let us make a folder named spine. `mkdir spine`. chmod all to 777. `sudo chmod * -R  && ls`. Story will end if you run this command at /. 

3 directories are created. Our text editor is nano. With that `WYSIWYG Editor`, we'll write the `html` files. I can give you a basic php based text editor, you can change it to some complicated `WYSIWYG Editor`. Practically, it is better to use a `WYSIWYG Editor` on another directory and copy the HTML output in out content ceating nano advanced text editor.

Syntax highlighting is important. Run `apt-get install python-pygments`. I am creating 3 directories in this repo. That ends today's story. Real time CMS development.

