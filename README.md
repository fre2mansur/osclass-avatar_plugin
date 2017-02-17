# osclass-avatar_plugin

Avatar Plugin

Please edit your user-profile.php add a name attribute on form tag ex: <form name="profile" for picture validation.
Want to Required avatar?

Edit avatar_plugin/index.php line 100, 109 uncomment those lines.
What the plugin does?

The avatar plugin show the profile picture upload button on Register page, Profile page, and admin user page. user can upload thir picture while register.
How to use

Use this code to show the picture of user

Get picture of item user : <?php echo show_avatar(osc_item_user_id()); ?>

Get picture of logged user : <?php echo show_avatar(osc_logged_user_id()); ?>

Get picture of public profile user : <?php echo show_avatar(osc_user_id()); ?>
About

Plugin Name: Avatar Plugin
Version : 1.0.0
Author : Media.Dmj
Website : vithudu.com 
