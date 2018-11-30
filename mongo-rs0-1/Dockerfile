FROM mongo


# Workdir config directory
WORKDIR /usr/src/configs

# Copy config files into container
COPY mongo.conf .

EXPOSE 27017

CMD ["--config", "./mongo.conf"]