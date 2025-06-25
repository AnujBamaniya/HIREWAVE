FROM php:8.2-apache

# Enable Apache mod_rewrite
RUN a2enmod rewrite

# Copy project files into Apache server root
COPY . /var/www/html/

# Set correct permissions (optional but good)
RUN chown -R www-data:www-data /var/www/html

# Expose port 80
EXPOSE 80
