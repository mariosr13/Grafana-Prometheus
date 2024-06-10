No puedo subir el Alertmanager, pero si que me deja subir el archivo de configuracion, lo que tendriamos que hacer es descargarnos AlertManager desde la pagina de prometheus y meterle el archivo de configuracion llamado alertmanager.yml
y una vez estemos dentro de la carpeta ejecutar el alertamanager con el siguiente comando: "./alertmanager --config.file=alertmanager.yml"
