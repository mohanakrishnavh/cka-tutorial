# Node offical image with 18-apline tag
FROM node:18-alpine
# Create an app directory
WORKDIR /app
# Copy files from current directory to current directory of container
COPY . .
# Install all the dependencies
RUN yarn install --production
# Execute the container
CMD ["node", "src/index.js"]
# Expose the port to access the application
EXPOSE 3000