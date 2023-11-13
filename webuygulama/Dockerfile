# Resmi Nginx imajını kullan
FROM nginx

# /usr/share/nginx/html dizinine index.html dosyasını kopyala
COPY index.html /usr/share/nginx/html

# Nginx'i çalıştır
CMD ["nginx", "-g", "daemon off;"]
# docker build -t my-web-app .  -> imaj alma komutu 
# docker run -p 8080:80 my-web-app -> imajı çalıştırma komutu