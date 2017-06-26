FROM base/archlinux

# Setup system
RUN pacman -Sy --noconfirm nginx

# Provide nginx configuration
ADD nginx.conf /etc/nginx/nginx.conf

# Setup command
CMD nginx -g "daemon off;"
