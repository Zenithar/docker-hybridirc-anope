FROM zenithar/nano-hybridircd
MAINTAINER Thibault NORMAND <me@zenithar.org>

# Become root for following commands
USER root
ADD ./config /opt/ircd/etc
RUN chown -R ircd:ircd /opt/ircd

# Restore unprivilegied account
USER ircd
