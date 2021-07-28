FIREBASE

Creamos un nuevo proyecto 
 
![image](https://user-images.githubusercontent.com/78773980/127407232-da5407c8-3daf-4950-8971-7a8ff891fcb2.png)

![image](https://user-images.githubusercontent.com/78773980/127407275-433d2a8e-2b4b-42e9-98ba-a780a2411fa9.png)

Deshabilitamos  Google Analytics para este proyecto y creamos

![image](https://user-images.githubusercontent.com/78773980/127407417-d741dfc7-922f-4f69-8926-45bce25da8d1.png)

Dentro de nuestro proyecto vamos al apartado de compilación

![image](https://user-images.githubusercontent.com/78773980/127407445-1a7bb356-b371-4f5e-b493-2298b66e3a3d.png)

Y seleccionamos autenticación

![image](https://user-images.githubusercontent.com/78773980/127407469-12e12765-4a0c-4dd4-86fb-df23780164aa.png)

Seleccionamos editar en correo y contraseña

![image](https://user-images.githubusercontent.com/78773980/127407488-49618c68-0785-416f-b158-b22f945b134d.png)

Habilitaos y guardamos 

![image](https://user-images.githubusercontent.com/78773980/127407512-10100032-f147-4744-82d6-14b39e67f6dc.png)

Vamos a configuración del 

![image](https://user-images.githubusercontent.com/78773980/127407575-dd092403-8f63-4531-8dd6-c4d07de37036.png)

![image](https://user-images.githubusercontent.com/78773980/127407664-ae817f08-ded4-472f-95c6-165beade21e0.png)
![image](https://user-images.githubusercontent.com/78773980/127407685-6c098472-7246-41ed-beac-9ab3736da2a6.png)
![image](https://user-images.githubusercontent.com/78773980/127407697-3371a625-a68e-4ddd-9973-3fa084dde9d4.png)
![image](https://user-images.githubusercontent.com/78773980/127407708-69a3bd77-4cbb-44c2-8bb2-79e5253b0f92.png)

Copiamos los 

![image](https://user-images.githubusercontent.com/78773980/127407732-77afa4b0-c7e1-40f8-959e-7f6125080075.png)

Vamos al proyecto en angular y buscamos environment.ts

![image](https://user-images.githubusercontent.com/78773980/127407751-bb2174f2-2eb6-4622-ba47-e22ea6797f95.png)

Ponemos una coma después de false y pegamos el código

![image](https://user-images.githubusercontent.com/78773980/127407766-63fa549e-4963-42ac-ae9b-ec5b337cecfe.png)

Y corregimos errores

![image](https://user-images.githubusercontent.com/78773980/127407790-89c6a62c-eddd-4825-a5cc-e5750761e365.png)

**Instalamos bootstrap ** 

Con el comando: npm install bootstrap jquery popper.js
Se creara una carpeta en node_modules: bootstrap

![image](https://user-images.githubusercontent.com/78773980/127407942-97e22cff-da08-48b3-8b5a-676a846ac554.png)

**Configuración de los estilos**
Ahora debemos incluir los nuevos estilos dentro del fichero "angular.json" para que nuestra aplicación reconozca los cambios que hemos realizado:

![image](https://user-images.githubusercontent.com/78773980/127407977-cef302c8-0122-4902-943f-69a069eb9fa6.png)

En el apartado de scripts agregamos también Bootstrap y las 2 dependencias que hemos instalado al inicio.(jquery y popper)

![image](https://user-images.githubusercontent.com/78773980/127407991-632cbb54-16b5-4c20-9274-8799d323f621.png)

Para que los cambios tengan efecto recargamos nuestra aplicación (ng serve --open). Con estos sencillos pasos hemos incluido Bootstrap. Y queda instalado.
**BOOTSWATCH**
Agregamos las url del código fuente de bootswatch

![image](https://user-images.githubusercontent.com/78773980/127408053-68168d6c-2bcf-44ab-bd77-b8b674dae119.png)

**ANGULAR/FIRE**
Escribimimos en la terminal firebase login para acceder al proyecto creado en firebase

![image](https://user-images.githubusercontent.com/78773980/127408087-99d9e8b2-a37c-46b3-8f99-a952d139c993.png)

Ahora instalamos angularfire con el comando: ng add @angular/fire
Escribimos el nombre de nuestro proyecto y creara los ficheros 

![image](https://user-images.githubusercontent.com/78773980/127408111-121602ad-0192-4980-83ed-2a22f6433f06.png)
![image](https://user-images.githubusercontent.com/78773980/127408117-5cbcb563-0d5e-4390-9d0c-a56acd3bf989.png)

**INSTALAMOS FIREBASE**
Instalamos con el comando: npm i firebase	

![image](https://user-images.githubusercontent.com/78773980/127408184-62ec3d4f-5b41-4777-ac7b-4b0f2cc5d168.png)








