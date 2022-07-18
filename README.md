# DevOPS
Repositorio para configuraciones y templates de DevOPS de ConsiliumBOTS

# TIPS DJANGO Deployment
- Los secrets deben ir almacenados como JSON minificado (sin espacios)

Se puede copiar el deployment de DJANGO usando la plantilla github_actions/Build_And_Deploy_DJANGO.yml
Se requiere cambiar SOLO estas variables:
* ECR_REPOSITORY: #CHANGE_ME
* KUBE_NAMESPACE: #CHANGE_ME
* DEPLOYMENT_NAME: #CHANGE_ME
* CONTAINER_APP_NAME: #CHANGE_ME

_**_Recordar cambiar el nombre del repositorio en el caso condicional de MASTER (linea 49)_**_
