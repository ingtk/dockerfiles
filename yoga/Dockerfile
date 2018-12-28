FROM perl

RUN cpanm https://github.com/toritori0318/p5-Yogafire/tarball/master --force

RUN mkdir .ssh

ADD .ssh/* .ssh/
ADD .yoga .yoga
