How To Create Child Theme In WordPress without Plugin and Easily. Follow this Step.

You can Simply Download the above file and install in your WordPress website and make some changes in like Template name, Child theme etc, or you can follow the step Mentioned Here. 

Child theme is most important in wordPress. To add more functionality in your theme you need to create child theme, so that functionality don't get affected on updating parents theme. Let's get started and know how to create Child theme....

To add child theme you need two files in child theme folder.

style.css
functions.php
You can add more folder if you want as per you requirements, but these file is necessary because absent of these file WordPress won't treat your child theme as child theme.

Step 1

Log into your website's WordPress Dashboard. Download "WP File manager" plugin to access the files of your WordPress sites.

Screenshot : https://prnt.sc/22plw77

Step 2

Now Open the WP file manager. You will see the file structure of your website.

Screenshot: https://prnt.sc/22pm9r5

Now open the "WP-Content" folder and get into themes folder. Here you will get all the themes list which you download.

Create a folder for your child-theme. You can name anything of folder but i would suggest name as parent theme child. for example see the screenshot

Screenshot: https://prnt.sc/22q0y52

Note: Don't keep space in words while naming the child theme folder or any folder create you in website files.

Step 3

Now it's time to create file inside the child theme folder. Create two files

-- style.css

-- functions.php

Note: Keep the same file name. Don't rename with other name otherwise WordPress won't load it and you will get error of file missing.

Screenshot: https://prnt.sc/22qg58f

You can add some more folder inside it like "css", "js etc. You can add image for child theme cover image. upload image and name with "screenshot.png".

Now inside "style.css" add some line in comment.

Copy the code from above style.css file and paste in your child theme's style.css

In this lines of code, you must have to Template name of your parent theme folder name and Text Domain as child.

This tells WordPress basic info about the theme, including the fact that it is a child theme with a particular parent.

Now add some code in "functions.php"

Again copy the code from above functions.php and paste in your child theme's functions.php

Now activate the child-theme. And start adding custom template and other stuff as per you requirements.

Add those file in "functions.php".

To include file in "functions.php"

**require_once 'yourfile.php';**

just copy the code above without stars and paste in your functions.php file.

That's it.
