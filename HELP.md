# Solución

## Actividad 1

1. Clonación del repositorio despues del fork y creación de rama-a a partir de main

    ![image](https://github.com/user-attachments/assets/4af286dc-8a3d-4ca4-b070-0b50dd8d51ad)

2. Creación de los archivos que creo convenientes

    ![image](https://github.com/user-attachments/assets/d7095149-4a63-43ad-b7a7-9b3ee3f73a8f)

3. Guardar cambios

    ![image](https://github.com/user-attachments/assets/c32000e2-0389-4e7b-8796-7f175452e906)
 

## Actividad 2

1. Creacion de .gitignore con las reglas dadas
   
   ![image](https://github.com/user-attachments/assets/7ba2dba6-9670-4746-9ce1-c8b9ac58b039)

## Actividad 3

1. Las carpetas sin contenido llamadas 'other' y 'another' serán incluidas

   ![image](https://github.com/user-attachments/assets/63c803b8-6b55-4df3-8084-15248d0acd9b)

## Actividad 4

1. Creación de la rama-b

   ![image](https://github.com/user-attachments/assets/0124037a-adf3-4840-bb51-29234b502436)

2. Cambios aplicados a los archivos

    ![image](https://github.com/user-attachments/assets/25b1e8b2-7d2f-4121-aa8b-e0f2e7015d4e)

   ![image](https://github.com/user-attachments/assets/523ee698-a955-4bdb-b4ce-e6416f48712e)

    ![image](https://github.com/user-attachments/assets/56e4ee99-0349-4666-b79b-bb5d2b2aa8df)

   ![image](https://github.com/user-attachments/assets/b2b458b8-a11e-4646-8f39-e21281cfab29)

3. Guardando cambios

   ![image](https://github.com/user-attachments/assets/97bbb750-4821-43d5-8414-113b53f09269)

4. Fusionar rama-b con la rama-a

   ![image](https://github.com/user-attachments/assets/3d05f0ef-42da-404f-a829-53a44d9edcad)


## Actividad 5

1. Traer la rama remota hotfix/main al repositorio local

   ![image](https://github.com/user-attachments/assets/53c03438-4565-4596-9321-2e3f89344fb2)

2. Ver todos los commits de la rama hotfix/main

   ![image](https://github.com/user-attachments/assets/1bafc1d5-0e92-475c-b219-50a105f58cfd)

3. Volver a la rama-a y aplicar git cherry-pick con el hash del commit 'fix: issue 2'

   ![image](https://github.com/user-attachments/assets/7f846515-c009-4241-90a1-082ff4da95f1)

4. Como git señala conflictos, se solucionan manualmente dejando que los archivos en 'fix issue-2' se conserven por lo cual se hace git add y git commit

    ![image](https://github.com/user-attachments/assets/6c6da531-09c7-4dfc-b142-6a0e4a591e47)

5. Se suben los cambios al repositorio remoto:

   ![image](https://github.com/user-attachments/assets/6765b6ff-acf0-4d57-a8a4-d487b9b46083)

## Actividad 6

1. Cambios hechos en rama-a antes de aplicar git stash

    ![image](https://github.com/user-attachments/assets/0f8ecea9-e7dd-40e8-88d5-e4cca6173037)

2. Aplicando git stash en el archivo en rama-a antes de cambiar a rama-b

   ![image](https://github.com/user-attachments/assets/6bf0b209-b7d0-40d6-a96b-a86a8b1317ee)

3. Cambiando a rama-b

   ![image](https://github.com/user-attachments/assets/a628d893-ce23-46e0-aa5a-6a8dcd75dd61)

4. Cambios hechos en rama-b antes de aplicar git stash

   ![image](https://github.com/user-attachments/assets/271a1fdc-3312-4f4f-87ca-4b3c411e2994)

5. Aplicando git stash en el archivo en rama-b

   ![image](https://github.com/user-attachments/assets/7bfea9e4-1a4d-4c92-a94e-2faea0e38b33)

6. Ver la lista de cambios sin commit:

    ![image](https://github.com/user-attachments/assets/96302c41-4fcd-4ab5-a35b-3e8a314fb920)

## Actividad 7

1. Primero volver a la rama-a

    ![image](https://github.com/user-attachments/assets/30790aed-8379-423b-9d6f-df7cef0e2ba5)


2. Para declarar una versión de mi proyecto en cuestión se usará git tag, luego de declarar la versión en local se procede a subir esa declaración al repositorio remoto

   ![image](https://github.com/user-attachments/assets/563e0e24-aa21-4670-b704-5b80a8ac6808)

# Extras

## Actividad 1

1. Efectuando cambios y guardandolos para que pasen al staging-area:

    ![image](https://github.com/user-attachments/assets/fd8bb291-159f-413c-8b3f-0a417601e7d5)

2. Aplicar git add

   ![image](https://github.com/user-attachments/assets/48495f6a-5700-49f3-9bcd-6ed36514a0f4)

3. Para quitar los cambios del staging-area, es necesario usar el comando git restore --staged donde se señala que solamente se debe devolver los cambios unicamente en staging-area

   ![image](https://github.com/user-attachments/assets/9a7434cc-7429-4e49-a5e2-59f0e970a33b)

4. El IDE marca que los cambios ya no están en el staging-area

   ![image](https://github.com/user-attachments/assets/d53a0963-d12b-47ea-b2e0-fdbb8be24d4b)

## Actividad 2

1. Para tal fin se usaría el comando git reset --hard el cual aplica los cambios hasta el area de trabajo.

    ![image](https://github.com/user-attachments/assets/ac50fa32-47f5-4452-bc8e-3f2a3db622bd)
  
2. se visualiza el estado de los commits anteriores

    ![image](https://github.com/user-attachments/assets/552cc930-f04b-4bc9-989c-e5ead3e112ea)

   
3. luego de eso, se aplica un git push con --force para aplicar esos cambios a la rama remota

   ![image](https://github.com/user-attachments/assets/69fc5e80-32d7-43c5-934f-95c0fd7c5524)


    








