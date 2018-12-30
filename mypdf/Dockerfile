FROM tk0miya/sphinx-base-pdf:latest
MAINTAINER Sphinx Team <https://github.com/sphinx-doc/sphinx>

RUN mkdir -p ~/.fonts
ADD ./fonts /usr/local/share/fonts
RUN bash -c "cd ~/.fonts/ && fc-cache -f -v"
WORKDIR /docs
# CMD make xelatexpdf
