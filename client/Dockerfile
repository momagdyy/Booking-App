FROM node:16-alpine

# Set the working directory in the container
WORKDIR /app

# Copy package.json and yarn.lock to the working directory
COPY package.json yarn.lock ./

# Install dependencies using yarn
RUN yarn install

# Copy the rest of the application code to the container
COPY . ./

# Build the React application
RUN yarn build

# Use a lightweight web server to serve the build (e.g., serve)
RUN yarn global add serve

# Expose the port that the app will run on
EXPOSE 3000

# Start the application
CMD ["serve", "-s", "build", "-l", "3000"]