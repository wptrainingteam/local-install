# Local Install

## Description

In this lesson you will learn how to install WordPress locally on your own computer.

## Objectives

After completing this lesson, participants will be able to:

*   Download, install, and configure MAMP.
*   Start MAMP servers.
*   Create a database.
*   Download and install WordPress.

## Target Audience

Who is this lesson intended for? What interests/skills would they bring? Choose all that apply.

* [ ] Users
* [ ] Designers
* [ ] Developers
* [ ] Speakers
* [ ] All

## Experience Level

How much experience would a participant need to get the most from this lesson?

* [ ] Beginner
* [ ] Intermediate
* [ ] Advanced
* [ ] Any

## Type of Instruction

Which strategies will be used for this lesson plan? Choose all that apply.

* [ ] Demonstration
* [ ] Discussion
* [ ] Exercises
* [ ] Feedback
* [ ] Lecture (Presentation)
* [ ] Show & Tell
* [ ] Tutorial

## Time Estimate (Duration)

How long will it take to teach this lesson (in minutes)?

____ minutes

## Prerequisite Skills

Participants will get the most from this lesson if they have familiarity with:

*   Experience downloading and installing programs on your computer.
*   Administrative access to your local machine.
*   Familiarity with the file system of your computer.

## Readiness Questions

*   Have you ever used WordPress?
*   Have you created posts and pages in WordPress?
*   Have you changed a theme in WordPress?
*   Have you ever wanted to look under the hood of WordPress?

## Materials Needed

*   [MAMP](https://www.mamp.info/en/)
*   [WordPress](https://wordpress.org/download/)
> *   [Slides](https://rawgit.com/wptrainingteam/repo-name/dev/slides/index.html) (included in this repo)

## Notes for the Instructor

*   Ahead of the lesson, make sure you take a look at your own computer setup. If you have MAMP or MAMP Pro already installed on your machine, you may want to run this demo on a virtual box to avoid conflicts with existing software and local sites that you may want to keep on your machine.
*   Sometimes it can take a while to download large files like MAMP or WordPress core. You may want to have a copy of MAMP and the current version of WordPress downloaded and stored on a thumb drive that can be passed around the class before you start the lesson. In the context of the demo, you would still show where to download these files, but would skip the actual live download.
*   MAMP is updated quite often. Please be sure to walk through the lesson plan with a fresh install to be sure it is still up to date.

## Have You Thought About...?

* Challenge 1
* Challenge 2

> What could present challenges to delivering this lesson? Is there anything that can be done in advance to prepare for those challenges?
>
> _For example:_
>
> *  What if there’s no internet available?
> *  What if there’s no projector available?
> *  What if a participant doesn’t has a WordPress site to work with?
> *  What if there aren’t enough computers for everyone?
> *  What if no one has the prerequisite skills? What if there are different opinions about the topic?

## Lesson Overview

* First do this
* Then move on to this
* Finish with this

> The plan for the lesson. Outline form works well.
>
> _For example:_
>
> * Talk about what a theme is
> * Demonstrate how to install and activate a theme
> * Practice exercises to have participants find and install a theme on their own site

## Exercises

**Exercise name**

Short description of what the exercise does and what skills or knowledge it reinforces.

*   Short point or step of the exercise
*   And another one

> These are short or specific activities that help participants practice certain components of the lesson. They should not be fully scripted exercises, but rather something that participants could do on their own. For example, you can create an exercise based on one step of the Example Lesson.

## Assessment

**What does "MAMP" stand for?**

1.  My Computer, Apple, MySQL, PHP
2.  My Computer, Apache, MySQL, PHP
3.  My Apache, MySQL, PHP
4.  Macintosh, Apple, MySQL, PHP

**Answer:** 3\. Macintosh, Apache, MySQL, PHP

**What is the user name and password for any named local install?**

1.  username: root; password: localhost
2.  username: localhost; password: localhost
3.  username: root; password: root
4.  username: localhost; password: root

**Answer:** 3\. username: root; password: root

**What systems can MAMP run on?**

1.  Macintosh</span>
2.  Windows</span>
3.  Macintosh and Windows
4.  Linux
5.  Macintosh, Windows and Linux

**Answer:** 3\. Macintosh and Windows

## Additional Resources

* [WordPress Installation Techniques](https://codex.wordpress.org/WordPress_Installation_Techniques) @ Codex

## Example Lesson

<span style="color: #000000">In order to run WordPress locally, you need to have a server. In this lesson, you will learn to set up a server, create a database and install WordPress on your computer.</span>

### <span style="color: #000000">Install MAMP</span>

<span style="color: #000000">MAMP stands for My Apache, MySQL, and PHP. MAMP is an application you can install on your Mac or Windows PC that allows you to have access to a local server that is running PHP and MySQL. Essentially, MAMP gives you all of the tools you need to run WordPress on your machine, for development and testing purposes.</span> <span style="color: #000000">To install MAMP, go to [https://www.mamp.info/en/downloads/](https://www.mamp.info/en/downloads/). Download the version of MAMP that corresponds with your machine (Mac OS X or Windows). Double click on the downloaded file. This will open the installation dialog. Next we'll follow the prompts in the dialog to complete installation. This course uses the default settings recommended by the install dialog.</span> <span style="color: #000000">[![Screen Shot 2016-01-21 at 2.18.07 PM](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-2.18.07-PM-300x188.png)](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-2.18.07-PM.png)</span>

### <span style="color: #000000">Open and configure MAMP</span>

<span style="color: #000000">Now that MAMP is installed, let's open it up! MAMP has a button to start servers when first started. By clicking on "Preferences" you can select an option to start the Apache HTTP Server and MySQL database server upon starting MAMP.</span> <span style="color: #000000">[![Screen Shot 2016-01-21 at 2.30.41 PM](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-2.30.41-PM-300x229.png)](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-2.30.41-PM.png)</span> <span style="color: #000000">Click on the "preferences" icon. You'll see that there are <del>four</del> five tabbed menu items available.</span> <span style="color: #000000">Click the "Web Server" tab and find the "Document Root." This path is where MAMP expects to find the files associated with your local website. In this case, this is where the WordPress files will need to be located in order to run them on the server. You may change this directory to whatever you want. The default is "/Applications/MAMP/htdocs" on a Mac and "C:/MAMP" on Windows. [![Screen Shot 2016-01-21 at 2.45.14 PM](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-2.45.14-PM-300x230.png)](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-2.45.14-PM.png)</span>

### <span style="color: #000000">Set up a Database</span>

<span style="color: #000000">Next, we will create a database on your new MAMP server. This database will become the database for the locally installed WordPress site.</span> <span style="color: #000000">Go back to the MAMP dialog and click "Open WebStart page."</span> <span style="color: #000000">[![MAMP4](https://make.wordpress.org/training/files/2014/10/MAMP4-1024x471.jpg)](https://make.wordpress.org/training/files/2014/10/MAMP4.jpg) [](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-2.52.37-PM.png) </span> <span style="color: #000000">Using the menu bar at the top of the page, click "Tools -> phpMyAdmin."</span> <span style="color: #000000">The phpMyAdmin dialog will appear: [![Screen Shot 2016-01-21 at 3.12.15 PM](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.12.15-PM-1024x514.png)](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.12.15-PM.png)</span> <span style="color: #000000">Click the "New" link in the left menu sidebar.</span> <span style="color: #000000">In the following dialog, use the name "mydatabase" to name the database:[![Screen Shot 2016-01-21 at 3.12.52 PM](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.12.52-PM-1024x560.png)](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.12.52-PM.png)</span> <span style="color: #000000">Leave the "Collation" option as default.</span> <span style="color: #000000">You now have a database called "mydatabase." Congratulations!</span>

### <span style="color: #000000">Install WordPress</span>

<span style="color: #000000">Now we're ready to install WordPress on our local machine! Go to [https://wordpress.org/download/](https://wordpress.org/download/) to download the most recent version of WordPress. Once you download and copy the WordPress files to your computer, you will be able to install WordPress using the traditional 5 Minute Install.</span> <span style="color: #000000">Move the downloaded zip file to the default server directory, "/Applications/MAMP/htdocs." You could expand the zip file in your downloads folder and move the expanded folder and it's contents, but sometimes the "hidden" system files that are included in WordPress (like the .htaccess file) fail to copy over to new folders if the contents are unzipped. For that reason, we'll leave our zip file zipped while we're moving it.</span> <span style="color: #000000">[![Screen Shot 2016-01-21 at 3.24.02 PM](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.24.02-PM-300x99.png)](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.24.02-PM.png)</span> <span style="color: #000000">In the new"/Applications/MAMP/htdocs" location, double click the WordPress zip file and it will expand.</span> <span style="color: #000000">[![Screen Shot 2016-01-21 at 3.24.28 PM](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.24.28-PM-300x84.png)](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.24.28-PM.png)</span> <span style="color: #000000">Go back to your web browser, and in the black menu bar, click the link "My Website."[![Screen Shot 2016-01-21 at 2.52.37 PM](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-2.52.37-PM-300x188.png)](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-2.52.37-PM.png)The link will take you to a list of websites installed in the directory:</span> <span style="color: #000000">[![Screen Shot 2016-01-21 at 3.24.53 PM](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.24.53-PM-300x175.png)](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.24.53-PM.png)Click the "wordpress" link. This link will take you to the 5 minute WordPress install.</span> <span style="color: #000000">Choose a language, "English" and get ready to enter your database information:</span>

*   <span style="color: #000000">Your "Database Name" is: mydatabase</span>
*   <span style="color: #000000">Your "User Name" is: root</span>
*   <span style="color: #000000">Your "Password" is: root</span>
*   <span style="color: #000000">Your "Database Host" is: localhost</span>
*   <span style="color: #000000">You can leave the "Table Prefix" as the default:  wp_</span>

<span style="color: #000000">[![Screen Shot 2016-01-21 at 3.32.40 PM](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.32.40-PM-300x208.png)](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.32.40-PM.png)</span> <span style="color: #000000">Now, let's click the "Submit" button to run the install. <del>!</del></span> <span style="color: #000000">[![Screen Shot 2016-01-21 at 3.34.15 PM](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.34.15-PM-1024x352.png)](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.34.15-PM.png)</span> <span style="color: #000000">Click the "Run the install button" and then choose a username and password on the next screen. That's it! You're ready to log in!</span> <span style="color: #000000"> [![Screen Shot 2016-01-21 at 3.36.22 PM](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.36.22-PM-300x237.png)](https://make.wordpress.org/training/files/2014/10/Screen-Shot-2016-01-21-at-3.36.22-PM.png)</span> <span style="color: #000000">The link for your new site will be: [http://localhost:8888/wordpress/](http://localhost:8888/wordpress/). You will login at this url: [http://localhost:8888/wordpress/wp-login.php](http://localhost:8888/wordpress/wp-login.php). Congratulations!</span>

## <span style="color: #000000">Exercises</span>

<span style="color: #000000">The following exercises reinforce the skills needed to install WordPress locally:</span> <span style="color: #000000">**Practice Using phpMyAdmin**</span>

*   <span style="color: #000000">Navigate back to phpMyAdmin on your local host.</span>
*   <span style="color: #000000">Click on the name of your database to view the contents of your database now that you have installed WordPress.</span>
*   <span style="color: #000000">When looking at the database tables, scroll to the bottom of the page and click the "check all" box. Then in the dropdown that says "With Selected" choose "Export" and follow the prompts to practice backing up your database.</span>
*   <span style="color: #000000">Practice making a new database within phpMyAdmin.</span>

<span style="color: #000000">**Try Installing a Second WordPress Local Site**</span> <span style="color: #000000">Go through the exercise demonstrated in this lesson again and try setting up a second instance of WordPress on your local machine in a new location.</span>

*   <span style="color: #000000">Make sure the document root matches wherever you'll keep your files for the second instance of WordPress.</span>
*   <span style="color: #000000">Set up a new database using phpMyAdmin.</span>
*   <span style="color: #000000">Extract the WordPress files in a new location on your computer.</span>
*   <span style="color: #000000">Run the famous 5 minute install for your new local site.</span>

### Lesson Wrap Up

![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png) Follow with the Exercises and Assessment outlined above.
