# Dotfiles

After cloning this repo, run `install` to automatically set up the development
environment. Note that the install script is idempotent: it can safely be run
multiple times.

Dotfiles uses [Dotbot](https://github.com/anishathalye/dotbot) for installation.

> **Warning**: If you want to give these dotfiles a try, you should first fork
> this repository, review the code, and remove things you don’t want or need.
> Don’t blindly use my settings unless you know what that entails. Use at your
> own risk!


## Making Local Customizations

You can make local customizations for some programs by editing these files:

* `git` : `~/.gitconfig_local`

  > Plus, copy the `git/gitconfig_user_sample` file, rename it to
  > `git/gitconfig_user`, and configure as you need.


## License

The code is available under the [MIT license](LICENSE) by [Joao Fernandes](
https://github.com/ojoaofernandes).
