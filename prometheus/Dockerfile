FROM prom/prometheus
USER root
ADD prometheus.yml /etc/prometheus
RUN chown -R nobody:nogroup /etc/prometheus/prometheus.yml
RUN chmod 755 /etc/prometheus/prometheus.yml
USER nobody
