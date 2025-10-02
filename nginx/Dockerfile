FROM nginx:alpine

COPY custom.html /usr/share/nginx/html/index.html

EXPOSE 80 
#"Hey, Docker, my app runs on port 80 inside the container".

CMD ["nginx", "-g", "daemon off;"]
# "Hey, Docker, when you start a container from this image, run Nginx in the foreground".
#not to run in the background (daemon mode), but instead stay in the foreground.