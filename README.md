LISH Command Utility
====================
Bash utility for Linode's LISH remote management service.

Provides an easy way to send commands to specific machines on a Linode Account, secured using an RSA Key generated by the install process, an enforced with a passphrase.


Requirements
------------

* Bash
* git
* sudo
* openssh


Install
-------

1. Clone the project: ```git clone git@github.com:imobilis/Lish-Command.git```
2. Run ```./lish-command-setup <your linode user account>``` on the project folder and follow instructions.

Don't forget to keep save your newly generated RSA key and passphrase! You'll need the passphrase everytime you want to send commands to LISH using lish-command.

Also, you'll have to allow the new RSA public key into your Linode Account.


Usage
-----

Run ```lish-command <machine> <lish command>``` from a terminal


How to Contribute
-----------------
Just fork the repository and send a pull request ;-)


License
-------
> LISH Command Utility.
> Bash utility for Linode's LISH remote management service.
> Copyright (C) 2013 Juan Traverso Viagas

> LISH Command Utility is free software: you can redistribute it and/or modify
> it under the terms of the GNU General Public License as published by
> the Free Software Foundation, either version 3 of the License, or
> (at your option) any later version.

> LISH Command Utility is distributed in the hope that it will be useful,
> but WITHOUT ANY WARRANTY; without even the implied warranty of
> MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
> GNU General Public License for more details.

> You should have received a copy of the GNU General Public License
> along with LISH Command Utility. If not, see <http://www.gnu.org/licenses/>.
