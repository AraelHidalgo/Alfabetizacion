FROM node:14

# Set the working directory
WORKDIR /usr/src/app

# Copy package.json and package-lock.json
COPY ./frontend/package.json ./frontend/package-lock.json ./

# Install frontend dependencies
RUN npm install

# Copy the frontend source code
COPY ./frontend/src ./frontend/src
COPY ./frontend/components ./frontend/components
COPY ./frontend/views ./frontend/views
COPY ./frontend/services ./frontend/services

# Expose the port the app runs on
EXPOSE 8080

# Command to run the application
CMD ["npm", "start"]