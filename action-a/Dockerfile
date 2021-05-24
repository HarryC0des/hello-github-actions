FROM debian:9.5-slim

ADD dos2unix entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
