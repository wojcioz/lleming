# Use an official node runtime as a parent image
FROM node:14

# Set the working directory in the container to /app
WORKDIR /app

# Add the current directory contents into the container at /app
ADD . /app

# Install any needed packages specified in package.json
RUN npm install

# Make port 8080 available to the world outside this container
EXPOSE 8080

# Run npm run serve when the container launches
CMD ["npm", "run", "serve"]