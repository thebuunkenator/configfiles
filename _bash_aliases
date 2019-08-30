if [ -n "$BASH_VERSION" ]; then
    # include .bashrc if it exists
    if [ -f "$HOME/.bashrc" ]; then
	. "$HOME/.bashrc"
    fi
fi

# set PATH so it includes user's private bin if it exists
if [ -d "$HOME/bin" ] ; then
    PATH="$HOME/bin:$PATH"
fi


export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
# Setting PATH for Python 2.7
# The orginal version is saved in .bash_profile.pysave
PATH="/Library/Frameworks/Python.framework/Versions/2.7/bin:${PATH}"
export PATH



# Enable tab completion
source ~/git-completion.bash

# colors!
green="\[\033[0;32m\]"
blue="\[\033[0;34m\]"
purple="\[\033[0;35m\]"
reset="\[\033[0m\]"

fortune | cowsay -f tux

function mkcd()
{
	mkdir $1 && cd $1
}
# Change command prompt
source ~/git-prompt.sh
export GIT_PS1_SHOWDIRTYSTATE=1
# '\u' adds the name of the current user to the prompt
# '\$(__git_ps1)' adds git-related stuff
# '\W' adds the name of the current directory
export PS1="$purple\u$green\$(__git_ps1)$blue \W $ $reset"

# added by Anaconda2 2.5.0 installer
export PATH="/Users/erik/anaconda/bin:$PATH"

# added by Miniconda2 4.2.12 installer
export PATH="/Users/erik/miniconda2/bin:$PATH"

##
# Your previous /Users/erik/.bash_profile file was backed up as /Users/erik/.bash_profile.macports-saved_2017-02-06_at_09:46:06
##

# MacPorts Installer addition on 2017-02-06_at_09:46:06: adding an appropriate PATH variable for use with MacPorts.
export PATH="/opt/local/bin:/opt/local/sbin:$PATH"
# Finished adapting your PATH environment variable for use with MacPorts.


# added by Anaconda3 4.3.1 installer
export PATH="/Users/erik/anaconda/bin:$PATH"

export LANG=en_US.UTF-8
# added for flutter
export PATH="/Users/erik/bin/flutter/bin:$PATH"

test -e "${HOME}/.iterm2_shell_integration.bash" && source "${HOME}/.iterm2_shell_integration.bash"
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_202.jdk/Contents/Home
export ANDROID_HOME=/usr/local/share/android-sdk
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_202.jdk/Contents/Home
export ANDROID_HOME=/usr/local/share/android-sdk
