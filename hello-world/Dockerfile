FROM debian:9.5-slim

LABEL "com.github.actions.name"="Hello World"
LABEL "com.github.actions.description"="Just Testing Stuff..."
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="https://github.com/MartinHeinz/github-actions"
LABEL "homepage"="https://martinheinz.dev"
LABEL "maintainer"="Martin Heinz <martin7.heinz@gmail.com>"

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
