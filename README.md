# env-injector

PLACEHOLDER repository (this is just an idea for a project)

Shell environment injector - set env variables across all shell sessions from anywhere


2 ways/options to handle this:

- Create something very close to [fish universal variables](https://fishshell.com/docs/current/index.html#variables-universal) for zsh and bash.

- Run a daemon that accepts variable assignments and injects those into all running shell sessions (+ some persistency)


### How would this even work?

1) use `preexec` in zsh (native) and in bash ([bash-preexec](https://github.com/rcaloras/bash-preexec/)) to run a command every time the preompt redraws  
2) make this command request env changes from the env injector daemon
3) run the daemon
4) ???
5) profit :rocket:
