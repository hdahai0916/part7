# task3
## ans

先把html文件和配置文件都放在我自己建的nginx_html文件夹里。
![1](./image/1.png)
启动nginx，把宿主机的8081端口映射到容器的80端口，然后把容器的/usr/share/nginx/html挂载在nginx_html，因为配置文件里的root设置的是这个文件夹。然后把容器要读取的配置文件挂载在之前写的配置文件default.conf。
![2](./image/2.png)
![3](./image/html.png)