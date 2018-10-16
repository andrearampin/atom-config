# Atom Configs

[Atom](https://github.com/atom) is a free and open-source text and source code editor for macOS, Linux, and Microsoft Windows with support for plug-ins written in Node.js, and embedded Git Control, developed by GitHub. Atom is a desktop application built using web technologies.

## Install packages

To track installed packages as well, you will need to run:

```
apm list --installed --bare > ./package.list
```

And add that file to Git also. To restore, use:

```
apm install --packages-file ./package.list
```

## Update standard config

```
cp config.cson ~/.atom
```
