[Local Ghost installation steps](https://docs.ghost.org/v1.0.0/docs/install-local)
=
Note: default port seems to be 2368

1. Install necessary modules
```
$ sudo yarn global add ghost-cli@latest
$ yarn add ghost
```

2. Install Ghost local itself
```
$ mkdir ghost && cd ghost && ghost install local
✔ Checking system Node.js version
✔ Checking current folder permissions
ℹ Checking operating system [skipped]
ℹ Checking MySQL is installed [skipped]
✔ Checking for latest Ghost version
✔ Setting up install directory
✔ Downloading and installing Ghost v1.5.2
✔ Finishing install process
✔ Configuring Ghost
✔ Setting up instance
✔ Running database migrations
✔ Validating config
✔ Starting Ghost
You can access your blog at http://localhost:2368/

Ghost uses direct mail by default
To set up an alternative email method read our docs at https://docs.ghost.org/docs/mail-config
```

Resources
-
* [Getting started](https://docs.ghost.org/v1.0.0/docs/getting-started-guide)
* [Using as NPM module](https://docs.ghost.org/v1.0.0/docs/using-ghost-as-an-npm-module)