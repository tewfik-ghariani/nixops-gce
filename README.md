# NixOps backend for Google Cloud

NixOps (formerly known as Charon) is a tool for deploying NixOS
machines in a network or cloud.

* [Manual](https://nixos.org/nixops/manual/)
* [Installation](https://nixos.org/nixops/manual/#chap-installation) / [Hacking](https://nixos.org/nixops/manual/#chap-hacking)
* [Continuous build](http://hydra.nixos.org/jobset/nixops/master#tabs-jobs)
* [Source code](https://github.com/NixOS/nixops)
* [Issue Tracker](https://github.com/NixOS/nixops/issues)
* [Mailing list / Google group](https://groups.google.com/forum/#!forum/nixops-users)
* [IRC - #nixos on freenode.net](irc://irc.freenode.net/#nixos)

## Developing

To start developing on nixops, you can run:

```bash
  $ nix-shell
  $ poetry install
  $ poetry shell
```
To view active plugins:

```bash
nixops list-plugins
```

and you're ready to go. Run `black`, `mypy`, etc.

