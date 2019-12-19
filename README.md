# env-injector

PLACEHOLDER repository (this is just an idea for a project)

Shell environment injector - set env variables across all shell sessions from anywhere


2 ways/options to handle this:

- Create something very close to [fish universal variables](https://fishshell.com/docs/current/index.html#variables-universal) for zsh and bash.

- Run a daemon that accepts variable assignments and injects those into all running shell sessions (+ some persistency)
