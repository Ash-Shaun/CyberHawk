# CyberHawk : Anti-Theft Application for Windows Laptops
[![Build Status](https://travis-ci.org/Ash-Shaun/CyberHawk.svg?branch=master)](https://travis-ci.org/Ash-Shaun/CyberHawk)

Laptops change the ways of communication, it provides an advantage of communicating with anyone virtually through video conferencing, email, etc., and it also provides a facility to store contact numbers, email id’s, in memory which reduces the concept of File-System to store personal information. Company related information and documents can be viewed anywhere and can be shared with anyone. Because of its <b>light weight</b> and <b>small size</b>, it can be stolen very easily and the confidential-information of any organization or personal details of people stored in the phone memory can be easily exposed. My project's aim is to put forward a technique through which the thief, who steals any laptop installed with <i>CyberHawk</i>, gets captured and the user can make him/her stop misusing any confidential information. This application includes Socket communication, Reverse TCP where you can send video clips and photos to  owner even under a firewall, unlike Email which includes only text. It gives the information about the thief by sending the snapshots and a small video clip of the thief to an alternate account, which helps us to recognize the thief.



## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

1. Python 3.5
2. PyQt 5.6
3. MySQL ([XAMPP](https://www.apachefriends.org/download.html) Server Preferred)

The complete Prerequisite can be obtained from [requirements.txt](https://github.com/Ash-Shaun/CyberHawk/blob/master/requirements.txt)

### Installing

CyberHawk can run on Python 3.5. 

Before you proceed to start the application, you need to change the DB variables to suite your needs
```
#Change line <b>89</b> in /CLIENT/main.py
#Change line <b>5</b> in /MASTER/db.py
db = MySQLdb.connect("localhost","<username>","<password>","<DB name>")
```

OPTIONAL: phpMyAdmin SQL Dump of DB I used during development
```
#You can import it through phpMyAdmin if you need
Filename: credentials.sql
DB name: credentials
Table name: Master , Client
```

```
# To open Client window
$ cd CLIENT/
$ python main.py
```
## Screenshots

Client

![Client](https://raw.githubusercontent.com/Ash-Shaun/CyberHawk/master/client.JPG)

Master

![Master](https://raw.githubusercontent.com/Ash-Shaun/CyberHawk/master/Master.JPG)
![Master](https://raw.githubusercontent.com/Ash-Shaun/CyberHawk/master/master2.JPG)
## Usage

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.


## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

