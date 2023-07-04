## Usage:
    upm [option] [action] [arguments]

## Description:
    upm stands for Universal Package Manager.
    It is a wrapper for your native package manager that is agnostic to distribution

## Options:
    -h, --help        Shows this menu
    -r, --recheck     Prompt the user for input before continuing
    -v, --version     Shows current version of upm

## Actions:
    update            Refresh repositories and install all pending updates
    search            Search installed repositories for all packages listed in <arguments>
    install           Install all packages listed in <arguments>
    remove            Remove all packages listed in <arguments>

## Examples:
    upm update        Updates all packages
    upm search vim    Searches for the vim package
    upm install vim   Installs the vim package
    upm remove vim    Uninstalls for the vim package

## Supported Operating Systems:
    linux

## Supported Package Managers:
    yay
    pacman
    xbps-install
    apt
    dnf
