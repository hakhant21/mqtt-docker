FROM eclipse-mosquitto

RUN mkdir -p /etc/mosquitto/data

RUN chown -R mosquitto:mosquitto /etc/mosquitto

CMD ["mosquitto", "-c", "/etc/mosquitto/mosquitto.conf"]