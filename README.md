# PHP-Fiddle

An easy way to fiddle with PHP code on the command line.

# Installation

Add the following to your `.bash_profile` or `.bashrc` file:

	export PHPFIDDLE=~/web/tests/phpfiddle   # modify the path to this repo accordingly
	alias pf="$PHPFIDDLE/run.sh"             # choose shorthand alias for running a fiddle

Remember to allow execute permissions on `run.sh`.

Now you can simply type

	$ pf
    
(for *p*hp*f*iddle) on any terminal, which will open up MacVim (or your preferred editor) and any changes made to the file will automatically show up in the terminal.

<img src="https://github.com/hwrod/php-fiddle/blob/master/screenshot.png" width="600">
