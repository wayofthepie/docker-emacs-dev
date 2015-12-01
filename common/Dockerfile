FROM fedora:23

ENV HOME /root

RUN dnf update -y && dnf install -y vim curl git make gcc emacs

RUN cd ${HOME} && mv .emacs.d .emacs.bak

RUN git clone --recursive https://github.com/syl20bnr/spacemacs ~/.emacs.d


