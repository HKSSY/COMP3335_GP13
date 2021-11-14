When your website gets hacked or your server crashes, you may lose all data, if you did not have any backup. So, your WordPress website data is important.

Although other security measures are essential, backups are the ultimate insurance. If the worst were to happen, your website with all related files and databases will stay safe and can be restored in a short time. You can create your own manual backups, but you may forget to backup your data, so, installing a plugin that can help you schedule automatic backups can save your time.

Next coming up, we will install and configure the UpdraftPlus plugin on WordPress to back up your website.

## Install UpdraftPlus plugin on WordPress

To enable schedule automatic backup service, you need to install and activate the "UpdraftPlus WordPress Backup Plugin" plugin on the WordPress plugin search page.

![WordPress UpdraftPlus plugin search result](https://raw.githubusercontent.com/HKSSY/COMP3335_GP13/main/wordpresssecurity/backup_wordpress_data/image/wordpress_backup_search_page.png)

## Setup the UpdraftPlus plugin

Upon activation, you will jump to the "Installed Plugins" page. On the page, a popup will be displayed, click the "Press here to start" button to start configuring this plugin.

![Click the button to configure the UpdraftPlus plugin](https://raw.githubusercontent.com/HKSSY/COMP3335_GP13/main/wordpresssecurity/backup_wordpress_data/image/updraftplus_popup.png)

When you first time opens the Backup/Restore page, a popup will appear a tour. You may click the "NEXT" button in the popup to read the tour or click the little close button to close the popup.

![UpdraftPlus plugin tour popup](https://raw.githubusercontent.com/HKSSY/COMP3335_GP13/main/wordpresssecurity/backup_wordpress_data/image/updraftplus_first_backup.png)

You may see the "Settings" button on the top side of the page. Click it to begin the files and database backup schedule of your site.

![UpdraftPlus settings button](https://raw.githubusercontent.com/HKSSY/COMP3335_GP13/main/wordpresssecurity/backup_wordpress_data/image/updraftplus_setting_button.png)

You can select the frequency to backup your website data and retain how many backups for you. This screenshot is an example, you may configure your own backup frequency and the number of backups to retain.

![UpdraftPlus backup setting configuration](https://raw.githubusercontent.com/HKSSY/COMP3335_GP13/main/wordpresssecurity/backup_wordpress_data/image/updraftplus_backup_config.png)

By default, UpdraftPlus stores the backups locally on the server. To use a remote storage location, in the "Choose your remote storage" section, select where you want to store your backup files.

After that, scroll down the page, you can see the "Save Changes" button to save your configuration. 

## Run your first-time backup

Click the "Settings" button on the top side and click the "Backup Now" on the next scheduled backups section for your first-time backup.

![UpdraftPlus backup now button](https://raw.githubusercontent.com/HKSSY/COMP3335_GP13/main/wordpresssecurity/backup_wordpress_data/image/updraftplus_backup_now.png)

A popup window will be displayed, you may select what data for backup. By default setting is to backup all website data, click "Backup Now" to backup.

The backup takes anywhere from a few seconds to several minutes to complete. Once finish the backup, backup is successful popup will be displayed. Scroll down the page, in the "Existing backups" section, you may see all available backups.

![UpdraftPlus existing backup](https://raw.githubusercontent.com/HKSSY/COMP3335_GP13/main/wordpresssecurity/backup_wordpress_data/image/updraftplus_exisiting_backup.png)
