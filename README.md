# nginx-php-phpadmin-fpm

# To build from source you need to clone the git repo and run docker build:

	git clone https://github.com/ggolfko/docker-laravel.git

# Running:
	docker-compose up -d
	docker-compose down
# ########
	docker images
	docker ps

# Add php extendtions
	docker exec -it <container ID> docker-php-ext-install pdo pdo_mysql
	docker restart <container ID>
		
	
