php-facebook-login-button
=========================

A php file that generates a facebook button with logo, text is customisable through query string along with font.

This file uses the GD library and requires at a minimum the Tahoma.ttf TrueTypeFont file in the same directory.

Instructions:
=============

Upload the file to your image directory and use it as you would an image file:

&lt;img src="./images/create_fb_button.php" /&gt;

You can change the default text by appending a 'label' value to the query string:

&lt;img src="./images/create_fb_button.php?label=Connect with my Facebook Button" /&gt;

The button will automatically be resized to fit the text.  The label can he url encoded if neccessary.

If you want to use a different font then you need to upload the truetypefont file to the same directory as 
the php file and then specify the file name in the query string:

&lt;img src="./images/create_fb_button.php?font=comicsans.ttf" /&gt;
