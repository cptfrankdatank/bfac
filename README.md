*BFAC*
---

An automated tool that checks for backup artifacts that may disclose the web-application's source code.

~~~

				  _____   _______  _______  _______
				(  ___ \ (  ____ \(  ___  )(  ____ \
				| (   ) )| (    \/| (   ) || (    \/
				| (__/ / | (__    | (___) || |
				|  __ (  |  __)   |  ___  || |
				| (  \ \ | (      | (   ) || |
				| )___) )| )      | )   ( || (____/\
				|/ \___/ |/       |/     \|(_______/
				
				-:::Backup File Artifacts Checker:::-
	___An automated tool that checks for backup artifacts that may discloses the web-application's source code___
			Author: Mazin Ahmed | <mazin AT mazinahmed DOT net> | @mazen160
~~~

## Description
BFAC (Backup File Artifacts Checker) is an automated tool that checks for backup artifacts that may disclose the web-application's source code. The artifacts can also lead to leakage of sensitive information, such as passwords, directory structure, etc.

**BFAC's goal is to be an *all-in-one tool* for backup-file artifacts black-box testing.**

## Usage

| Description                                               | Command                                                               |
|-----------------------------------------------------------|-----------------------------------------------------------------------|
| Help                                                      | `bfac --help`                                                         |
| Check a single URL                                        | `bfac --url http://example.com/test.php`                              |
| Check a list of URLs                                      | `bfac --list testing_list.txt`                                        |
| Single URL with a higher level                            | `bfac --url http://example.com/test.php --level 2`                    |
| Single URL while specifying values for valid status codes | `bfac --url http://example.com/test.php --valid-status-codes 200,302` |
| Single URL and showing only the results                   | `bfac --no-text --url http://example.com/test.php`                    |
| Limit the test to exposed DVCS tests                      | `bfac --dvcs-test --url http://example.com/`                          |

## Requirements
* Python2 or Python3
* requests

## Installation [Optional]
`sudo python setup.py install`

## Compatibility
The project currently supports all platforms that run Python.
The project is compatible with both Python 2 and Python 3.

## Community Contribution
Contribution from the community to the BFAC project is very welcome. If you find a bug, have an idea for a feature, ideas to reconstruct the code to work better, or anything else, feel free to submit an issue or a pull request.

## Legal Disclaimer
This project is made for educational and ethical testing purposes only. Usage of BFAC for attacking targets without prior mutual consent is illegal. It is the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program.

## License
The project is currently licensed under GNU GPLv3.0 License.

## Author
*Mazin Ahmed*
* Website: [https://mazinahmed.net](https://mazinahmed.net)
* Email: *mazin AT mazinahmed DOT net*
* Twitter: [https://twitter.com/mazen160](https://twitter.com/mazen160)
* Linkedin: [http://linkedin.com/in/infosecmazinahmed](http://linkedin.com/in/infosecmazinahmed)

