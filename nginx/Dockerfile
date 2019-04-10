FROM nginx:alpine

# Wipe the default config
RUN rm /etc/nginx/conf.d/default.conf \
 && rm /etc/nginx/nginx.conf

# Copy custom config file from the current directory
COPY ./my_default.conf /etc/nginx/conf.d/default.conf
COPY ./base/my_nginx.conf /etc/nginx/nginx.conf
