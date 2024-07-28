# COMANDOS PARA EJECUCION DEL TEMPLATE EN CLOUDFORMATION:
---------------------------------------------------------

1.ESTAR EN LA MISMA RUTA DONDE SE UBICAN LOS ARCHIVOS Y SUBIR ESTOS ARCHIVOS A UN BUCKET S3 CON EL COMANDO:

aws s3 cp --recursive . s3://BUCKET-NAME/

2.CREAR EL STACK EN CLOUDFORMATION USANDO URL de Amazon S3 Y COPIAR EL URL del objeto (main.yaml):

https://BUCKET-NAME.s3.amazonaws.com/main.yaml

3.FINALMENTE DAR EN SIGUIENTE Y ELEGIR UN ROL PARA QUE CLOUDFORMATION TENGA LOS PERMISOS SOBRE LOS RECURSOS A CREAR Y DAR EN EJECUTAR PARA QUE EMPIECE LA CREACION.

4.ESTRUCTURA DE CARPETAS Y ARCHIVOS (modulo):

.
├── compute
│   └── compute.yaml
├── database
│   └── database.yaml
├── elasticache
│   └── elasticache.yaml
├── main.yaml           
├── network
│   └── network.yaml
├── readme.md
├── secret
│   └── secret.yaml
├── security
│   └── security.yaml
└── test.yaml

# AWS-CALCULATOR (APP-ECOMMERCE):
-------------------------------------------------------------------------------
https://calculator.aws/#/estimate?id=f428799fdbc06039b7703e26a6bc8b63276caf65





