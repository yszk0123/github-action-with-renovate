FROM debian:9.9-slim

LABEL "com.github.actions.name"="Hello World"
LABEL "com.github.actions.description"="Write arguments to the standard output"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="http://github.com/yszk0123/github-action-with-renovate"
LABEL "homepage"="http://github.com/actions"
LABEL "maintainer"="Yuji Suzuki <y0suzuki0123@gmail.com>"

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
