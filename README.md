1.  Ingresar a la consola del AWS con el email y password proporcionados.
2.	Ingresar a la consola del EC2, Instances e Iniciar la Instancia.
3.	Conectarse mediante SSH a la instancia tomado como nuevo valor de conexión el Public DNS proporcionado por la instancia.
4.	Iniciar el contenerdor Docker de Jenkins mediante el siguiente comando
	docker start nervous_fermat
5.	Ingresar al Jenkins mediante la url http://dominio_instancia:8080/
6.	Ingresar al Jenkins mediante el usuario admin y password admin