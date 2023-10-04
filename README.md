# 23-2-parcial-a
1. Instala Docker en tu pc
2. Crea la instancia de MySQL = $ docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=mypw -d mysql
3. Construye la imágen docker = $ docker run build -t "desired_image_name" .
4. Corre el contenedor = $ docker run "desired_image_name"
