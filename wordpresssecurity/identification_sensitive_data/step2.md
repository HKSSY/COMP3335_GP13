After starting the container, let's connect to the WordPress service and install the WooCommerce plugin which is a customizable, open-source eCommerce platform built on WordPress.

## Connect to WordPress Service

Click the "WordPress" button on the navigation bar.

!["WordPress" button on the navigation bar]https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/identification_sensitive_data/image/select_wordpress.png)

On the page, the "Web Preview Port Selector" will try to connect the port 8080, which is configured for WordPress by the docker-compose. If connected successfully, the WordPress installation page will display. Otherwise, press the "Try again" button for reconnecting the port.

## WordPress Basic Setup

Select your preferred language and click the "Continue" button.

![WordPress installation page](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/identification_sensitive_data/image/wordpress_install_page.png)

You should see a welcome page after clicking the "Continue" button. Under the Information needed section, you need to fill out the following fields:

![WordPress Information needed section](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/identification_sensitive_data/image/wordpress_information_needed_section.png)

This screenshot is an example, you may insert your own information for the fields.

After that, click the "Install WordPress" button to finish the installation. Click the "Log In" button to login to the WordPress Admin Dashboard for the next step. 
