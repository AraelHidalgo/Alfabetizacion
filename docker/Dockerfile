FROM node:14

# Set the working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY ./modulos/modulo-principal/frontend/package.json ./frontend/package.json
COPY ./modulos/modulo-principal/frontend/package-lock.json ./frontend/package-lock.json

# Install frontend dependencies
RUN cd frontend && npm install

# Copy the frontend source code
COPY ./modulos/modulo-principal/frontend/src ./frontend/src
COPY ./modulos/modulo-principal/frontend/components ./frontend/components
COPY ./modulos/modulo-principal/frontend/views ./frontend/views
COPY ./modulos/modulo-principal/frontend/services ./frontend/services

# Copy backend files
COPY ./modulos/modulo-principal/backend/package.json ./backend/package.json
COPY ./modulos/modulo-principal/backend/package-lock.json ./backend/package-lock.json
COPY ./modulos/modulo-principal/backend/src ./backend/src
COPY ./modulos/modulo-principal/backend/controllers ./backend/controllers
COPY ./modulos/modulo-principal/backend/routes ./backend/routes
COPY ./modulos/modulo-principal/backend/models ./backend/models
COPY ./modulos/modulo-principal/backend/middleware ./backend/middleware

# Install backend dependencies
RUN cd backend && npm install

# Expose the application port
EXPOSE 3000

# Start the application
CMD ["npm", "start", "--prefix", "backend"]