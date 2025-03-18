FROM eclipse-mosquitto

RUN mkdir -p /etc/mosquitto/data

RUN chown -R mosquitto:mosquitto /etc/mosquitto

EXPOSE 1883 9001

CMD ["mosquitto", "-c", "/etc/mosquitto/mosquitto.conf"]