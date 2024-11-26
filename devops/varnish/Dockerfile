# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Alin Voinea <contact@avoinea.com>" \
      org.label-schema.name="ploneconf2024-varnish" \
      org.label-schema.description="Plone Conf 2024 Varnish image." \
      org.label-schema.vendor="Alin Voinea"

COPY etc/varnish.vcl /etc/varnish/default.vcl
