php-facebook-login-button
=========================

A php file that generates a facebook button with logo, text is customisable through query string along with font.

This file uses the GD library and requires at a minimum the Tahoma.ttf TrueTypeFont file in the same directory.

Instructions:
=============

Upload the file to your image directory and use it as you would an image file:

&lt;img src="./images/create_fb_button.php" /&gt; <img src="http://www.consof.com/create_fb_button/create_fb_button.php" />

You can change the default text by appending a 'label' value to the query string:

&lt;img src="./images/create_fb_button.php?label=Connect%20with%20my%20Facebook%20Button" /&gt; <img src="http://www.consof.com/create_fb_button/create_fb_button.php?label=Connect%20with%20my%20Facebook%20Button" />

The button will automatically be resized to fit the text.  The label needs to be url encoded.

If you want to use a different font then you need to upload the truetypefont file to the same directory as 
the php file and then specify the file name in the query string:

&lt;img src="./images/create_fb_button.php?font=comicsans.ttf" /&gt; <img src="http://www.consof.com/create_fb_button/create_fb_button.php?font=comicsans.ttf" />

If you have the correct language truetypefont file you can also specify a foreign language:

&lt;img src=".images/create_fb_button.php?label=Facebook%E3%81%A8%E3%82%B3%E3%83%8D%E3%82%AF%E3%83%88&font=ipag.ttf" /&gt;<img src="http://www.consof.com/create_fb_button/create_fb_button.php?label=Facebook%E3%81%A8%E3%82%B3%E3%83%8D%E3%82%AF%E3%83%88&amp;font=ipag.ttf" />
