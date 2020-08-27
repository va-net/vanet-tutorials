# Installing Flare

Flare is a fully featured and easy to use Crew Center for Infinite Flight. It integrates with VANet with almost no effort from the VA and can be customized to your liking.

## Server Requirements
* PHP 7.2 or later
* PHP PDO Extension
* PHP cURL Extension
* MySQL/MariaDB
* FTP Access

## Upload
To upload Flare, a FTP Client such as [FileZilla](https://filezilla-project.org/) or [CyberDuck](https://cyberduck.io/) is required. 
The latest version of Flare can be downloaded from [Flare's GitHub Releases](https://github.com/va-net/flare/releases/).

## Installation
Flare installation is quick and simple. Simply head to your website, where you will be redirected to the install Flare page.

![Flare Installation](https://i.ibb.co/rmvGK0y/Screenshot-2020-08-27-Install-Flare.png)

Enter your VA's name (eg. Delta Virtual), callsign prefix (eg. DLVA) and VANet API Key. This API Key is your Airline API Key which can be retrieved 
from https://vanet.app/airline/. Flare will check that the key you enter is indeed an airline key and not a personal API Key.

Next, enter your database details.

![Flare Database Setup](https://i.ibb.co/KygJypZ/Screenshot-2020-08-27-Install-Flare-1.png)

After that, save your information then click **Continue with Installation** then enter the details of your first admin user. And you're done! Now, you can login
at https://YOURURLHERE/index.php. 

Congratulations! You have installed Flare!
