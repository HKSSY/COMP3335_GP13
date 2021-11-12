The Wordfence Web Application Firewall is a PHP based, application level firewall that filters out malicious requests to your site. 

This firewall protects against a number of common web-based attacks as well as a large number of attacks specifically targeted at WordPress and WordPress themes and plugins. It is set up to run at the beginning of WordPress’ initialization to filter any attacks before plugins or themes can run any potentially vulnerable code. For more information, click [**here.**](https://www.wordfence.com/help/firewall/?utm_source=plugin&utm_medium=pluginUI&utm_campaign=docsIcon#firewall-files)

## Setting up the Wordfence firewall

The default setting of the Wordfence firewall is called the Basic WordPress Protection. It’s turned on automatically when you install Wordfence, but to start with it only runs as a WordPress plugin, which doesn’t offer the best level of protection. 

Next coming up, to make the firewall more secure, we can configure the firewall setting to Extended Protection mode.

**To turn on Extended Protection, follow these steps:**

Choose the "Wordfence" and "Firewall" buttons from the left side sidebar menu. After that, click the "MANAGE FIREWALL" button to visit the "Firewall Options" page.

![Wordfence manage firewall button](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/improve_system_security/image/wordfence_manage_firewall_button.png)

On the Firewall Options page, click the "OPTIMIZE THE WORDFENCE FIREWALL" button.

![Wordfence optimize the wordfence firewall button](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/improve_system_security/image/wordfence_optimize_firewall.png)

A popup will appear called "Optimize Wordfence Firewall". Normally, the correct server configuration optimization will be automatically selected for you. You should not need to change this option. 

To prevent any issues during the optimization procedure, click the "DOWNLOAD .HTACCESS" button for downloading a backup file about your server configuration file. Next, click the "CONTINUE" button to optimize the firewall.

![Wordfence popup page for optimize the wordfence firewall](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/improve_system_security/image/wordfence_optimize_wordpress_firewall.png)

If installed successfully, you should see an alert appear with the message "Nice work! The firewall is now optimized." Click the "CLOSE" button to continue.

## Confirm Extended Protection mode enabled

Under the Basic Firewall Options section, you should notice that the protection level is configured to "Extended Protection". You will also see that the firewall starts in Learning Mode. In this mode, the firewall analyses your site traffic for a while so that it can tell the difference between normal traffic and a hack attempt. The Live Mode will be switched automatically by the firewall and starts protecting your site.

![Wordfence basic firewall options](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/improve_system_security/image/wordfence_firewall_protection_level.png)
