Jade Build for Sublime Text 2/3
====================================

Description
-----------

Build system for Jade files, compiles .jade files into .html files.


Prerequisites
-------------

Requires **Node.js** & **Jade** libraries.

Step by step:

1. Install **Node.js**

	Download and install Node.js. You can find it here:
	[http://nodejs.org](http://nodejs.org/)

	Reboot after install it.


2. Installing **Jade**

	Open your console and execute the following command:

	**Windows**: `npm install jade --global`

	**OS X**: `sudo npm install jade --global`


Installing
----------

**OPTION 1 - With the Package Control plugin (recommended)**

The easiest way to install this package is through Package Control.

1. Install the [Package Control Plugin](https://sublime.wbond.net/installation).
Follow the instructions on the website.

2. Open the command panel: `Ctrl+Shift+P` (Linux/Windows) or `Cmd+Shift+P` (OS X) and select '**Package Control: Install Package**'.

3. When the packages list appears type `Jade` and you'll find the **Jade Build**. Select to install it.

4. Now you can compile your Jade files! Launch your build with `Ctrl+B` (Linux/Windows) or `Cmd+B` (OS X).

5. Enjoy your coding.


**OPTION 2 - With Git**

Clone the repository in your Sublime Text "Packages" directory:

    git clone git://https://github.com/mutian/Jade-Build.git Jade-Build

You can find your 'Packages' inside the following directories:

* OS X:
    `~/Library/Application Support/Sublime Text 2/Packages/`
* Windows:
    `%APPDATA%/Sublime Text 2/Packages/`
* Linux:
    `~/.Sublime Text 2/Packages/`


**OPTION 3 - Without Git**

Download the latest source zip from [Github](https://github.com/mutian/Jade-Build) and extract it into a new folder named `Jade Build` in your Sublime Text "Packages" folder.


Using the build
---------------

After installing the package you will find a new options in `Tools > Build system` of your  Sublime menu: **Jade**.

Remember, always you can launch the selected build with `Control+B` (Linux/Windows) or `Command+B` (OS X).




Recommendations
---------------

* Is recommended to use this build with plugin: [Jade](https://github.com/davidrios/jade-tmbundle).
* Also, I recomend the plugin [SublimeOnSaveBuild](https://github.com/alexnj/SublimeOnSaveBuild). Just save your Jade files and transform them into HTML!
* If you want to change the default folder of your generated HTML files into another one, you can edit the build:

  **Exemple:** Save your HTML files into a `html` folder:
  `"cmd": ["jade", "$file:${file_path}/../html/${file_base_name}.html", "--pretty"],`


Author
------

Created by **Mutian** ([http://mutian.info](http://mutian.info/)).

If you need more info you can send email to me: mutian(a)me.com!


Acknowledgements
----------------

Thanks to the **RIA Team** of [Weibo.com](http://weibo.com/) .