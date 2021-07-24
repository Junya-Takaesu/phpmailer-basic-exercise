# Basic Example of PHPMAILER

## The sample code
`index.php` is ready to be used to send an email from command line.
The code is taken from the example code below.

[PHPMailer/gmail.phps at master · PHPMailer/PHPMailer](https://github.com/PHPMailer/PHPMailer/blob/master/examples/gmail.phps)

## Caution
* Must install the PHPMailer package defined in composer.json by executing the command below.
    ```
    composer update
    ```
* Password is not the actual password of your gmail account. It is something called "App passwords". An App password can be generated from the menu as shown in the image below.
  * ![](https://i.imgur.com/dovZdWE.png)
* Google account information is read from environment variables. Set these in advance. Below is example commands that set up google account information.
    ```
    export GOOGLE_EMAIL_ADDRESS=example@gmail.com
    export GOOGLE_APP_PASSWORDS=someapppassword
    ```