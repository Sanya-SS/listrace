# Step 1: Use the official NGINX base image
FROM nginx:latest

# Step 2: Set the working directory inside the container
WORKDIR /usr/share/nginx/html

# Step 3: Copy the local website files to the container
COPY . /usr/share/nginx/html

# Step 4: Expose port 80 to allow external access
EXPOSE 8070

# Step 5: Start NGINX (this is done by default in the nginx image)
CMD ["nginx", "-g", "daemon off;"]
