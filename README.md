# [Jabbermacs](http://strudelline.net/jabbermacs)

A docker image with jabber.el (ubuntu 14.04 with emacs 24.3)

## Getting started

    docker run --rm -ti jamesandariese/jabbermacs /jabber <username>@<domainpart>[/resource] [hostname]

If the hostname to connect to is not the same as the domainpart of your JID, use the hostname
option.  Otherwise, skip it.  If you wish to specify a resource, do so.  Otherwise, it will
default to jabbermacs.

## Using jabber.el

#### Jabber.el specific
* `C-x C-j C-r`
  Go back to roster
* `C-c TAB`
  Info menu
* `C-x C-j C-l`
  Go to recent notifications

#### General Emacs
* `C-x C-b`
  Go to buffer (try a user's last name and hitting tab)
* `C-h m`
  Help on mode key bindings

## Todo

* priority specification
