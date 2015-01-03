# Website Workflow

This is the basis of my workflow. I use Jade for quick HTML writing, SASS in .sass for quick css, Bourbon, Neat, and Bitters for styling and structure, and Jekyll for modularization. This includes a .codekit so you don't have to set custom settings. If your workflow is similar, feel free to use.

This project is based and inspired by Devtips. [the channel](https://www.youtube.com/user/DevTipsForDesigners) was a crucial part to becoming self-taught and is a great source of information for beginners and experienced users. I still used some of his information in the documentation here. 

## How to install/use

In order to get this super fantastic workflow follow this simple step: 

* If you haven't installed ruby on your computer, install it. 
* Then run in your terminal `$ gem install jekyll`
* Make sure you have Codekit installed. It can be found [here](https://incident57.com/codekit/).
* Move/`cd` to a folder, always in your terminal, in which you want to insert the *Website-Workflow*
* Run `git clone https://github.com/alexanderhblack/Website-Workflow.git`
* Then `cd Artists-Theme`
* `jekyll serve --watch`
* Open Codekit and set the project to this directory
* Make sure the files within Jade are exporting into the _includes folder.
* **DONE**

That's it! With this, you can start your own projects. Just make sure you know how to use [Jade](http://jade-lang.com), [SASS](http://sass-lang.com), [Jekyll](http://jekyllrb.com), and [Bourbon](http://bourbon.io).

## Brief Notes

* For some reason, it wouldn't stop including the Jade folder into _site when Jekyll finishes compiling. If you can fix this, feel free to get in touch and I'll give credit down here.
* If you use Codekit, you won't have to set anything up. 
* You don't have to use Codekit, it just so happens that I use it over Prepros or manual terminal for everything except Jekyll (since it doesn't support Jekyll yet.) Just make sure you have whatever program you use for compiling export the .jade files as .html into the _includes folder. That's all you need to do. 
