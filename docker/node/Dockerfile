# Set the base image.
FROM node

# Copy composer.lock and composer.json
COPY composer.lock composer.json /var/www/

# Create and define the application's working directory.
RUN mkdir /app
WORKDIR /app

# Install the application's dependencies into the node_modules's cache directory.
# COPY twitter_service/* ./
RUN npm install
# RUN npm run dev

