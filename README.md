cassandra-macosx-prefspane
========================

This Preferences pane for Cassandra.

![Screenshot](https://github.com/remysaissy/cassandra-macosx-prefspane/raw/master/doc/screenshot%20started.png)

Functionalities
---------------

* Runs on MacOSX Snow Leopard, Lion and Moutain Lion
* Indicates if the server is running
* Manual start/stop of the Cassandra server
* Enable/disable automatic startup of the server at boot
* Keep your plist’s customizations safe
* Homebrew’s launchd plist is migrated
* Enable/disable automatic startup don’t delete the launchd plist
* Automatic update
* New versions install automatically
* A green label at the top right corner informs you that you should restart your system preferences

Localization
------------

* English
* French
* Simplified Chinese
* Spanish
* Brazilian / Portugese

Prerequisites
-------------

It does not embed a Cassandra Server. Therefore, you first have to install Cassandra.
A simple way to do it is by using Homebrew to install Cassandra.

$brew install cassandra

Installation
------------

1.	Download the latest version: https://github.com/remysaissy/cassandra-macosx-prefspane/raw/master/download/Cassandra.prefPane.zip
2.	Unzip Cassandra.prefPane.zip
3.	Double click on Cassandra.prefPane. This will install it in your System Preferences

Note: To Mountain Lion users. This application is presently not on the app store and therefore it is not signed. You can still install it but don't be surprised to have an alert about it.

Contributing
------------

Want to contribute? Great!

1. Fork it.
2. Create a branch (`git checkout -b my_cassandra_prefspane`)
3. Commit your changes (`git commit -am "Added Installer"`)
4. Push to the branch (`git push origin my_cassandra_prefspane`)
5. Create an [Issue][1] with a link to your branch
6. Enjoy a refreshing Diet Coke and wait

[1]: https://github.com/remysaissy/cassandra-macosx-prefspane/issues
