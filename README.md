# Detroit Email Tool

[Website](http://rubyworks.github.com/detroit-email) /
[Report Issue](http://github.com/rubyworks/detroit-email/issues) /
[Development](http://github.com/rubyworks/deroit-email)


## Description

The Email tool is used to send out project announcements to a set of
email addresses.

By default it generates a *release announcement* based on a projects
metadata. Release announcements can be customized via _parts_, including
a project's README file.

Fully custom messages can also be sent by setting the message field,
and or by using a message file.

Email account settings default to environment variables so they need
not be set independently for every project.

    @server    ENV['EMAIL_SERVER']
    @from      ENV['EMAIL_FROM']
    @account   ENV['EMAIL_ACCOUNT'] || ENV['EMAIL_FROM']
    @password  ENV['EMAIL_PASSWORD']
    @port      ENV['EMAIL_PORT']
    @domain    ENV['EMAIL_DOMAIN']
    @login     ENV['EMAIL_LOGIN']
    @secure    ENV['EMAIL_SECURE']


## Installation

### Using RubyGems

  $ gem install detroit-email


## Copyrights

Copyright (c) 2011 Rubyworks

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

