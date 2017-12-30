# garkbit: Emit the current project's VirtualBox VM instance name

> But before you arrived here sir, you left here.

# EXAMPLE

```console
$ sh -c 'cd some-vagrant-project && garkbit'
vagrant-netbsd-pkgsrc_default_1514659746064_66081
```

# REQUIREMENTS

* [coreutils](https://www.gnu.org/software/coreutils/coreutils.html)

In other words, a UNIX-like system featuring `sh` and `awk`. If you have the unhappy task of working with a Windows environment, you can try running garkbit within a shim like cygwin, MSYS, MinGW, Git Bash, bash on Ubuntu on Windows AKA Windows Linux Subsystem. Good luck.

# INSTALL

1. Clone this git repository.
2. Add this `lib` directory to your system's `PATH` environment variable.
