FROM node:18

RUN apt-get update && apt-get install -y \
    nano \
    curl \
    vim \
    iputils-ping \
    net-tools \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /app
COPY ./app /app

CMD ["node", "app.js"]
