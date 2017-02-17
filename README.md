# Avatar plugin for Osclass

## What the plugin does?
The avatar plugin show the profile picture upload button on Register page, Profile page, and admin user page. user can upload thir picture while register.

## How to use
Use this code to show the picture of user
* Get picture of item user: <?php echo show_avatar(osc_item_user_id()); ?>
* Get picture of logged user: <?php echo show_avatar(osc_logged_user_id()); ?>
* Get picture of public profile user: <?php echo show_avatar(osc_user_id()); ?>

## Required avatar field?
* Edit user-profile.php add a name attribute on form tag ex: <form name="profile"> for picture validation.
* Edit avatar_plugin/index.php and uncomment lines 100, 109.

## Requirements
Osclass 3.6 or greater

## Author
* [Fre2Mansur](https://github.com/fre2mansur)

## Licence
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  
See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see [http://www.gnu.org/licenses/](http://www.gnu.org/licenses/).
