<div align="center">
    <img src="cover.png">
</div>

## 👀 What is reXera?
reXera is a hosting account and support management system especially designed to work with MOFH (MyOwnFreeHost). reXera currently has a limited number of features which are listed below:

![AppVeyor](https://img.shields.io/badge/Licence-GPL_2.0-lightgrey)
![AppVeyor](https://img.shields.io/badge/Version-Coming_Soon-lightgrey)
![AppVeyor](https://img.shields.io/badge/Build-Passed-lightgreen)
![AppVeyor](https://img.shields.io/badge/Interface-Tabler-lightgreen)
![AppVeyor](https://img.shields.io/badge/Development-In_Progress-lightred)
![AppVeyor](https://img.shields.io/badge/Dependencies-PHP,_MySQL,_cUrl-lightred)

### 🎮 Features
- User Management
- Theme Management
- Support Management
- Administrative Access
- Integration With:
	- MOFH (MyOwnFreeHost)
	- Google reCAPTCHA 
	- CryptoLoot
	- hCaptcha
	- GoGetSSL
	- SitePro
	- SMTP
- Update Manager
- Multi-langual

## 🤸 Getting Started

### 🚅 Requirements
Your server needs to meet the following minimum requirements to run Xera:
- PHP v7.2 or above.
- MySQL v5.7 or above.
- A valid, trusted SSL certificate.

### 💾 Installation 
The installation of reXera is much easier than you think!
- Download the latest reXera installation file [here](https://github.com/mahtab2003/Xera/releases/latest). 
- Extract the file and upload the contents to your web hosting account. 
- Create a new database for reXera.
- Go to ```https://{your.domain}/{xera-directory}/install.php``` and click on the 'Get Started' button.
- Set your website's ```Website URL```, ```Cookie Prefix```, enable ```CSRF Protection``` and hit the 'Next Step' button.
- Edit the database credentials and click on the 'Next Step' button (this will automatically import tables and records to the database).
- Register an admin account and login to your admin panel. 
- Replace the logo and favicon located in ```assets/img/``` with your own.
- Setup SMTP (see below for some services you can use).
- All done! 

### 📧 SMTP
Here are some widely used SMTP services. They have free plans with some limitations, most importantly though, they are compatible with reXera.
- [Mailgun](https://www.mailgun.com/). (**Important Note**: Mailgun seems to offer only a trial plan for a month, and without adding a credit card you are only authorized to send emails to 5 recipients. As such, you may want to choose another service.)
- [Mailjet](https://mailjet.com/).
- [SendGrid](https://sendgrid.com/free/).

### 🤔 Help
If you require assistance, please proceed to [our forum](https://fourm.xera.eu.org/), where you can find the answers to many questions and also ask your own.  
You can also [open an issue here](https://github.com/mahtab2003/Xera/issues/new) if you have discovered a bug or have an issue, although the forum is still the preferred way, especially for feature requests. In any way, please ensure your topic has not been previously discussed, and if it has contribute to that discussion instead of making a new one when you can.

## ©️ Copyright
This build is created and maintained by [ChippyTech](https://github.com/chippytech). Code released under [the GPL-2.0 license](LICENSE).
