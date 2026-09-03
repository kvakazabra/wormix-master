FROM php:8.2-cli
WORKDIR /app
EXPOSE 3137
CMD ["sh", "-c", "if [ ! -f /app/preloader.swf ]; then echo 'ERROR: preloader.swf not found in ./wormix-app. Please place the required files in this directory before starting the container.'; exit 1; fi; php -S 0.0.0.0:3137 -t /app"]