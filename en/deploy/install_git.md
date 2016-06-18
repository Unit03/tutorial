
### Windows

You can download Git from [git-scm.com](http://git-scm.com/). You can hit "next next next" on all steps except for one; in the 5th step entitled "Adjusting your PATH environment", choose "Use Git and optional Unix tools from the Windows Command Prompt" (the bottom option). Other than that, the defaults are fine. Checkout Windows-style, commit Unix-style line endings is good.


### MacOS

Download Git from [git-scm.com](http://git-scm.com/) and just follow the instructions.

### Linux

It's possible that Git is already installed. To verify this, run:

    git --version

If Git tells us the version it's installed - we're ready to go! If not - terminal will inform us that it couldn't find the `git` command - Git should be available via your package manager, so try:

#### Debian or Ubuntu

    $ sudo apt-get install git

#### Fedora (up to 21)

    $ sudo yum install git

#### Fedora (22+)

    $ sudo dnf install git
