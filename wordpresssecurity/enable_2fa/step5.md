Two Factor Authentication (2FA) is a method of securing your account. The benefit of this approach is to ensure that you're the only person who can access your account, even if someone knows your password. Before you start, you need to install an authenticator application like Google Authenticator, Authy, or Duo on your device.

## Install Authentication Service on WordPress

To enable 2FA service, you need to install and activate the "Two factor Authentication" plugin on the WordPress plugin search page.

![WordPress Two Factor Authentication plugin search result](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/enable_2fa/image/wordpress_2fa_search_page.png)

## Setup the 2FA plugin

Upon activation, you need to visit the "Two Factor Auth" page and scroll down to the "Current one-time password" section. The plugin will now show you a QR code which you need to scan using an authenticator app, which can generate a temporary one-time password for the accounts that you save in it.

![The page for 2FA plugin](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/enable_2fa/image/2fa_scan_qr_code_config.png)

## Import the QR code to Authenticator App

In this scenario, we will be using Google Authenticator. You can follow this tutorial by using a different app if you want, it is because they all work the same way.

First, click on the "Scan a QR code" button in your authenticator app:

![Scan QR code on Google Authenticator app](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/enable_2fa/image/google_2fa_scan_qr_code.png)

The app may ask permission to access the camera on your phone. You need to allow this permission for scanning the QR code shown on the plugin’s "Current one-time password" section.

Once you are finished, the app starts showing a one-time password that you can use to log in.

![The result on Google Authenticator app](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/enable_2fa/image/google_2fa_import_done.png)

## Enable 2FA Service

Follow the screenshot to activate two factor authentication:

![Enable 2FA service](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/enable_2fa/image/activate_2fa.png)

Click on the "Save Changes" button to save your settings.

Try to log out of your WordPress account and re-login it. Now each time you log in to your WordPress website, you will be asked to enter the authentication code generated by the app on your phone.

![2FA request](https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/enable_2fa/image/2fa_request.png)
