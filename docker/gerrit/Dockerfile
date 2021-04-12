ARG GERRIT_VERSION=3.3.3
FROM gerritcodereview/gerrit:${GERRIT_VERSION}

WORKDIR /var/gerrit/etc
COPY gerrit.config .
COPY secure.config .