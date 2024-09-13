

#Nombre	Alias	Ubicacion
# Juan A. Piñango	Alfa	Venezuela
# Abraham Malave	Bravo	Venezuela
# Nesyabel Moreno	Charlie	Venezuela
# Juan C. Fernandez	Delta	Venezuela



# Para Delta 
 1. (Delta) debe crear el repositorio "hg_1_delta" más el archivo README.md
 
 2. (Delta) crea la rama develop y anexar un archivo PULL_REQUEST_TEMPLATE.md dentro del repositorio /docs, 
    luego hacer merge con main el archivo PULL_REQUEST_TEMPLATE.md debe contener el template de ejemplo
    docs/PULL_REQUEST_TEMPLATE.md

 3. Los usuarios deben hacer fork del repositoio cuando los pasos anteriores esten listos
 
 4. Cada usuario debe enviar 1 archivo con extensión "txt" con el nombre de su alias al repositorio:
    feature/alfa
    feature/bravo
    feautre/charlie
    feature/echo (solo si existe echo en el equipo)
    
 5. (Delta) solo aceptara cada feature de pull request, con petición de merge a la rama develop
    branch feature -> branch develop
    
 6. (Delta) debe enviar los cambios de la rama develop a la rama(principal) main   
 
 7. Los integrantes del proyecto deben hacer una actualización de su sucursal(repositorio) local
    git remote add upstream url_del_repositorio_delta
    git fetch upstream
    git switch main
    git merge upstream/main 
