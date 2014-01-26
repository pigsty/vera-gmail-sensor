## Scope ##

This package contains a plugin for the Micasaverde Vera home automation gateway

## Features ##

This plugin scans the Atom feed of the specified GMail account at regular intervals for new mail matching the configured Labels. 

You need to configure GMail with 2 Labels and rules to apply the Labels to incoming mail. One Label will turn the sensor on (tripped), one will turn it off. If the on Label has a more recent mail in than the off Label, then the sensor is tripped.

You can run multiple instances of this plugin with different labels.

## Usage ##

I used this to implement location-based events in Vera, by setting up a dedicated GMail account and telling the iOS Find Friends app to send email notifications to that account. Because this account is dedicated for this purpose I am not too worried about the password being stored in clear text in Vera.

## Limitations ##

Password for your mail account is not encrypted when stored in Vera. My intention was to always have a dedicated GMail account for Vera to listen to email alerts on, so this is not an issue for me.

## License ##

Copyright © 2013 Chris Birkinshaw

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/