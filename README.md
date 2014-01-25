Jade Build for Sublime Text 2/3
===============================


Description
-----------

Build system for Jade, compiles .jade files into .html files.


Prerequisites
-------------

Requires **Node.js** & **Jade** libraries. Step by step:

1. Install **Node.js**

	Download and install Node.js. You can find it here:
	[http://nodejs.org](http://nodejs.org/) .

	Reboot after install it.


2. Install **Jade**

	Open your console and execute the following command:

	* Windows: `npm install jade --global`

	* OS X: `sudo npm install jade --global`


Installation
------------

### OPTION 1 - with Package Control (recommended)

The easiest way to install this package is through Package Control.

1. Install [Package Control](https://sublime.wbond.net/installation), follow instructions on the website.

2. Open command panel: `Ctrl+Shift+P` (Linux/Windows) or `Cmd+Shift+P` (OS X) and select **Package Control: Install Package**.

3. When packages list appears, type `Jade` and you'll find **Jade Build**, select to install it.


### OPTION 2 - with Git

Clone the repository in your Sublime Text "Packages" directory:

    git clone git://https://github.com/mutian/Jade-Build.git Jade-Build

You can find your "Packages" inside the following directories:

* OS X:
    `~/Library/Application Support/Sublime Text 2/Packages/`

* Windows:
    `%APPDATA%/Sublime Text 2/Packages/`

* Linux:
    `~/.Sublime Text 2/Packages/`


### OPTION 3 - without Git

Download the latest source zip from [Github](https://github.com/mutian/Jade-Build) and extract it into a new folder named `Jade Build` in your Sublime Text "Packages" folder.


Usage
-----

After installing, you will find a new options in `Tools > Build system` of your  Sublime menu: **Jade**.

Remember, always you can launch the selected build with `Control+B` (Linux/Windows) or `Command+B` (OS X).



Recommendations
---------------

* Recommend to use with plugin [Jade](https://github.com/davidrios/jade-tmbundle).

* Also, I recommend the plugin [SublimeOnSaveBuild](https://github.com/alexnj/SublimeOnSaveBuild), just save your Jade files and transform them into HTML!

* If you want to change the default folder of your generated HTML files into another one, you can edit the build.

	**Example:** Save your HTML files into a `html` folder:
	`"cmd": ["jade", "$file:${file_path}/../html/${file_base_name}.html", "--pretty"],`


Author
------

Created by **Mutian** ([http://mutian.info](http://mutian.info/)).

For more info, you can send email to me: mutian(a)me.com!


Acknowledgements
----------------

Thanks to the **RIA Team** of [Weibo.com](http://weibo.com/) .
