# Dash to Dock
![screenshot](https://github.com/micheleg/dash-to-dock/raw/master/media/screenshot.jpg)

## A dock for the GNOME Shell
This extension enhances the dash moving it out of the overview and transforming it in a dock for an easier launching of applications and a faster switching between windows and desktops without having to leave the desktop view.

For installation instructions and more information visit [http://micheleg.github.io/dash-to-dock/](http://micheleg.github.io/dash-to-dock/).

## Installation from source

The extension can be installed directly from source, either for the convenience of using git or to test the latest development version. Clone the desire branch with git

<pre>git clone https://github.com/micheleg/dash-to-dock.git</pre>
or download the branch from github. A simple Makefile is included. Then run
<pre>make
make install
</pre>
to install the extension in your home directory. A Shell reload is required <code>Alt+F2 r Enter</code> and the extension has to be enabled  with *gnome-tweak-tool* or with *dconf*.

## Bug Reporting

Bugs should be reported to the Github bug tracker [https://github.com/micheleg/dash-to-dock/issues](https://github.com/micheleg/dash-to-dock/issues).

## License
Dash to Dock Gnome Shell extension is distributed under the terms of the GNU General Public License,
version 2 or later. See the COPYING file for details.

## Hacking

Remember to compile the gschemas with "glib-compile-schemas" in the schemas directory.
glib-compile-schemas /home/<USER>/dash-to-dock@micxgx.gmail.com/schemas

To remove an unwanted gschema 
dconf reset -f "/org/gnome/shell/extensions/dash-to-dock/"
dconf reset "/org/gnome/shell/extensions/dash-to-dock"

Then manually copy your schema
cp org.gnome.shell.extensions.dash-to-dock.gschema.xml /usr/share/glib-2.0/schemas/

## Donations

You can

<a href="http://flattr.com/thing/1047592/" target="_blank">
<img src="http://api.flattr.com/button/flattr-badge-large.png" alt="Flattr this" title="Flattr this" border="0" /></a>

or 

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3S5HFFG2BWGPL" target="_blank">
<img src="https://www.paypalobjects.com/en_US/GB/i/btn/btn_donateCC_LG.gif" alt="PayPal — The safer, easier way to pay online."/></a>