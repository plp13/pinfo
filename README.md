# Note by plp13
This is not the official repo. It's a fork that attempts to address a few
bugs and missing features, specifically:
* Bugfix: Black screen upon terminal window resize
* Bugfix: Program crashes when 'man' command fails (e.g. because the requested
  manual page doesn't exist)
* New feature: Support https URLs
* Bugfix: Pressing 'p' while at the beginning of a man page would crash the
  program
* Bugfix: Program hangs on startup if the TERM environment variable isn't set
* Bugfix: Program sometimes won't reset the terminal upon abnormal exit

A [pull request](https://github.com/baszoetekouw/pinfo/pull/38) with these has
been submitted.

# Pinfo
Pinfo is user-friendly, console-based viewer for Info documents.
Hope you like it :)

Until version 0.6.8, Pinfo was maintained by Przemek Borys. His old project
page is still available at http://pinfo.sourceforge.net/. Unfortunately,
Przemek is no longer active, and development was taken over by Bas Zoetekouw
and moved to Alioth: https://alioth.debian.org/projects/pinfo/.
Since 2014 (version 0.6.10), development has moved to Github:
https://github.com/baszoetekouw/pinfo

See man page (pinfo.1) for details.

    Copyright (C) 1999       Przemek Borys <pborys@dione.ids.pl>
    Copyright (C) 2005-2006  Bas Zoetekouw <bas@debian.org>
                             Nathanael Nerode <neroden@fastmail.fm>
    Copyright (C) 2007-2016  Bas Zoetekouw <bas@debian.org>

    This program is free software; you can redistribute it and/or modify it
    under the terms of version 2 of the GNU General Public License as
    published by the Free Software Foundation.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program; if not, write to the Free Software
    Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA

