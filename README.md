# frost
https://idroot.us/install-xwiki-ubuntu-22-04/
server {
       listen 80;
         listen [::]:80;

       root /var/www/your_domain/html;
        index index.html index.htm index.nginx-debian.html;

        server_name your_domain www.your_domain;

        location / {
                try_files $uri $uri/ =404;
        }
}



/etc/nginx/sites-available/your_domain
