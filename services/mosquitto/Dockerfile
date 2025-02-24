# Use the Eclipse Mosquitto image
FROM eclipse-mosquitto:latest

# Expose MQTT ports
EXPOSE 1883 9001 1884 9002

# Start Mosquitto
CMD ["mosquitto", "-c", "/etc/mosquitto/mosquitto.conf"]

