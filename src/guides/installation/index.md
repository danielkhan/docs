# Installing Node

This page describes the various ways to install Node depending on your platform
and personal preference.

## Using an Installer
This is the easiest way to get started on *Windows* and *OS X*. Simply download
the installer from [nodejs.org][nodejs org], run it and follow the steps.
This will install the `node` binary along with the Node Package
Manager `npm` on your system.


### See if it worked
```bash
$ node -v
v0.12.4 # The exact version number may vary
```

### Update npm
[*npm*][npmjs org] helps you to install and manage third party packages on your system.
Although it comes with the Node installer, there may be already a newer
version available. So let's try to update it just in case.

Please note that you need to run this as administrator on Windows or via `sudo`
on your Mac and may be prompted for your password after running this command.

```bash
$ <sudo> npm install npm -g
$ npm -v
2.11.3 # The exact version number may vary
```

## Using a Package Manager
On most *Linux* blends as well as *OS X* package managers can be used to fetch
and install software.


[nodejs org]: https://nodejs.org/
[npmjs org]: https://npmjs.org/
