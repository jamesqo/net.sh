# sh.net

A couple of scripts that make it less painful to use Git Bash for .NET devs.

## Installation

```bash
cd /tmp
git clone git@github.com:jamesqo/sh.net
cd sh.net
chmod a+rx install && ./install
```

The experience is best if you are running the shell as admin, since then you won't have to answer a bunch of UAC dialogs.

## Features

sh.net adds a number of helpful commands to Git Bash, including:

- devenv (Visual Studio)
- msbuild
- csc (the C# compiler)

## Usage

```bash
csc Class.cs
msbuild Your.sln # or Your.csproj
devenv Your.sln
```

## License

[MIT](LICENSE)
