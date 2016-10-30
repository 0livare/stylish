## Setup

This project is written in SCSS.  In order to to get usable CSS, the SCSS needs to be transcompiled.  This should be done via Compass because although there is no Compas specific functionality at the time of writing this README, that may change in the future.

1. To set up Compass on your computer:
	1. Install Ruby on your computer using the [Ruby Installer](http://rubyinstaller.org/)
	1. Add the Ruby bin folder to your `PATH`.  
		1. This is likely `C:\RubyXX-x64\bin`
		1. You will have to open a new terminal and possibly restart your computer after making changes to your path.
	1. Ensure it's up to date 
		`$ gem update --system`
	1. Install compass
		`$ gem install compass`
1. To transcompile the files:
	1. `cd` to the root of the project on your computer
	1. Run `$ compass compile`
1. Transcompile whenever SCSS files are changed:
	1. `cd` to the root of the project on your comptuer
	1. Run `$ compass watch`
