Wordfence Live Traffic shows you what is happening on your site in real-time, including user logins, hack attempts, and requests that were blocked by the Wordfence Firewall. You can monitor and block suspicious activity using Wordfence live traffic. For more information, please visit [**this**](https://www.wordfence.com/help/tools/live-traffic/?utm_source=plugin&utm_medium=pluginUI&utm_campaign=docsIcon) documentation.

## Configure the Live Traffic function

You can view it by visiting the "Wordfence" and "Tool" buttons from the left side sidebar menu. The default setting of traffic logging mode is "SECURITY ONLY". In this case, for analyzing the traffic we will change the logging mode to "ALL TRAFFIC" and click the "SAVE CHANGES" button to save the change.

![Select all traffic logging mode](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/improve_system_security/image/wordfence_live_traffic_mode.png)

Try to logout of your WordPress account and re-login the account with the wrong password. After that, login with the correct password, click the "Wordfence" and "Tool" buttons from the left side sidebar menu to the Live Traffic page. Scroll down the page, you can see all logged traffic. 

![View log data from live traffic page](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/improve_system_security/image/wordfence_view_log_data.png)

Click the view button to check the traffic detail:

![View log data from live traffic page](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/improve_system_security/image/wordfence_view_log_data_detail.png)

You can analyze the activity detail by "WHOIS LOOKUP" tool to track the owner's register information. If the activity is suspicious, you may click the “Block IP” button to block that IP address. Note that if you use the button to block an IP address it is a temporary block controlled by the option “How long is an IP address blocked when it breaks a rule”. You can find this option in the “Rate Limiting” section on the “Firewall Options” page.
