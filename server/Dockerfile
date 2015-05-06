FROM zenithar/nano-hybridircd
MAINTAINER Thibault NORMAND <me@zenithar.org>

USER root
ADD ./config /opt/ircd/etc
RUN chown -R ircd:ircd /opt/ircd

USER ircd
