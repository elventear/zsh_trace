# zsh_trace
ZSH Plugin to Enable Tracing of ZSH init process

Generates a tracing log of the init process of `zsh`. It has been shamelessly 
lifted from a [StackOverflow](http://stackoverflow.com) 
[solution](http://stackoverflow.com/questions/4351244/can-i-profile-my-zshrc-zshenv) 
by [Dennis Williamson](http://stackoverflow.com/users/26428/dennis-williamson).

## Usage:

In your `.zshrc` file:

    # .zshrc first commands
    # source plugin
    source /path/to/zsh_trace.plugin.zsh
    # enable tracing
    zsh_trace_start()

    # .zshrc last commands
    zsh_trace_end()

