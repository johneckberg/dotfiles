# dotfiles

This repository contains my bash dotfiles. Files in the home directory (~) are symbolic links to the actual configuration files stored in this version-controlled repository.
Workflow

The core idea is to avoid placing configuration files directly in the home directory. Instead, a dedicated directory, ~/dotfiles, holds all the real configuration files.
This ~/dotfiles directory is a Git repository, with its remote hosted on GitHub. Standard configuration files like ~/.bashrc, ~/.vimrc, or ~/.hgrc are just symbolic links pointing to their corresponding files inside ~/dotfiles.

