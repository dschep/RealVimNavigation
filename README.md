# RealVimNavigation
[fman](https://fman.io) plugin for vim key style navigation.

## Usage
 * `h` or `l` switches panes
 * `j` moves cursor up one
 * `k` moves cursor down one
 * `d` Move the file to trash
 * `x` Move the file to trash


This is a modified version of VimNavigation plugin for fman without the `shift` key requirement.

## Installation

Install with [fman's built-in command for installing plugins](https://fman.io/docs/installing-plugins).

## Problems

The `move_to_bottom` doesn't always go to the bottom. It goes to the last entry in the current directory. Fman sorts all directories at the top and files afterwards.
