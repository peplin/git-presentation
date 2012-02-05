!SLIDE bullets

# Getting Git

http://git-scm.com/

* Windows: Cygwin with git, openssh and corkscrew packages
* Linux: from distro's package manager
* Mac OS X: from Homebrew (http://mxcl.github.com/homebrew/

!SLIDE commandline

# .gitconfig

    $ git config --global user.name \
            "Chris Peplin"

    $ git config --global user.email \
            "cpeplin@ford.com"

!SLIDE commandline

    $ cat ~/.gitconfig
    [user]
        name = Chris Peplin
        email = cpeplin@ford.com
    [color]
        status = auto
        branch = auto
        interactive = auto
        diff = auto
