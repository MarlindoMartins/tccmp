# Usar imagem PHP com Apache
FROM php:8.0-apache

# Copiar código da API para o container
COPY index.php /var/www/html/

# Expor a porta 80
EXPOSE 80

CMD ["apache2-foreground"]
