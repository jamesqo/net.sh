# sh.net

A couple of scripts that make it less painful to use Git Bash for .NET devs.

## Installation

Just run this from your terminal:

```bash
cd /tmp
git clone git@github.com:jamesqo/sh.net
cd sh.net
chmod a+rx install && ./install
```

## Features

sh.net adds a number of helpful commands to Git Bash, including:

- devenv (Visual Studio)
 - vs (shorthand for `devenv *.sln`)
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
