# PHP + Slim Framework

Proyecto de PHP + Slim Framework con lo justo y necesario para funcionar

# Pasos a seguir

1. Descargar el repositorio dentro de la carpeta htdocs de nuestro xampp
2. Utilizar el comando ``composer install`` para instalar Slim y Psr7.
3. Utilizar el comando ``php -S localhost:666 -t app`` para levantar el servidor.
4. Realizar un pedido GET a http://localhost:666 para revisar que todo funcione correctamente.
5. ¡Tu turno, a seguir codeando! 

# Subir a Vercel

6. Crear una cuenta en vercel, conectarla con su github.
7. Fork al proyecto y subirlo a su porpio github.

![{4DEE5655-BC9A-4AB8-875B-082F1BFABA6E}](https://github.com/user-attachments/assets/bbdeffed-69a6-4c01-80e1-25f130c5609a)

9. Crear la aplicación en vercel como "Other".

![{B5C8C8D9-2D6E-40D8-9704-480182E3E2BF}](https://github.com/user-attachments/assets/6bdf7fc9-3248-42dd-8338-e6304fa2a3c2)
 
10. Cuando le den a deploy, va a intentar pero va a fallar. Es normal.

![{0BDDB108-C09D-4594-860F-79D01DB32068}](https://github.com/user-attachments/assets/e0beabf4-6748-411a-b28c-8b71e39a6396)

12. Ir al proyecto, ir a las settings. Cambiar en la configuración la versión de node a 18x. No olvidar darle a save.

![{69AB7FFC-9727-4ABB-82AA-0DA55F433C15}](https://github.com/user-attachments/assets/622db8d6-31e0-450b-bf6a-697075eb7cd6)

13. Una vez hecho el cambio, se puede hacer un re-deplpoy para probar que funcione. Esto se hace desde la pestaña deployments.

![{651D93B4-1431-427B-B5DB-4C49D50EE2C6}](https://github.com/user-attachments/assets/9e82d9d7-b227-4474-bf5d-08389307c394)

14. Hasta acá, debería funcionar la ruta por defecto.

![{DBE96A3F-B9B8-401F-A6A8-225395F3E350}](https://github.com/user-attachments/assets/56ad3c14-685e-4c4f-ac0b-8240bf0aadfd)

15. Configurar PostgressSQL. Crear la base en la pestaña Storage.

![image](https://github.com/user-attachments/assets/e5e85cd5-a26a-43e9-a7e7-4a9ec5ef1088)

![image](https://github.com/user-attachments/assets/0ad3ebec-cffd-4ced-9bb1-4cb8c2867aa6)

16. Conecten la DB al proyecto. Configuración por defecto.

![{1193C9FB-1DD8-41CD-888A-2E6D80EBAD69}](https://github.com/user-attachments/assets/2b50ff6a-99e4-47f8-b9d9-21d7667ce851)

17. Busquen la opción de conexión para arcghvos .env, como el que estamos utilizando en el proyecto.
    Cuando le den a Copy Snippet se va a copiar todo al portapapeles.
    Pueden darle a view secret para ver todas las claves secretas. Esta información es importante para el próximo punto.
    
![image](https://github.com/user-attachments/assets/6e4bf14c-e2ac-4331-991e-7d7d40492439)

19. Pegar las configuraciones de entorno (environment) en la configuración de nuestro proyecto.

![{D85BFD0B-B7C4-4125-8726-D7A3572DA315}](https://github.com/user-attachments/assets/f47da39e-2f15-4bf2-8fe6-7cfde62c38f0)

![{C4B00CFD-679D-4E4C-A39C-27036B93FEEF}](https://github.com/user-attachments/assets/a9c9d467-26cc-492c-87b7-26e8aea3c86c)

- Si colocan el cursor en la primer key, y le dan a pegar a lo que copiamos antes, se va a completar todo automáticamente.

![{894DA115-E411-4CD7-8C9B-B79EC7D1C1E6}](https://github.com/user-attachments/assets/e1b74245-06f0-455f-9e8b-3bf97e38833c)

- No olvidar darle a save!!

20. 
