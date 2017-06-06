FROM debian:jessie-backports

RUN git clone https://github.com/rbenv/ruby-build.git
RUN bash cd ruby-build
RUN bash ./install.sh
RUN gem install imap-filter
    