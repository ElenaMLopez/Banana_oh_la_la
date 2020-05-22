# Ejercicios

---

## Estos son los pasos para la persona que ejerce de Compi1:

- [ ] Forkear este repositorio. En tu perfil editar el nombre y llamarlo 'Custom_Banana_oh_la_la'.

- [ ] Tu **compi2 tiene que *forkear* el repositorio que acabas de obtener en tú perfil**, el tuyo, no de mi perfil. Tambien tiene que clonarse en local el repositorio con `git clone <url_repo_compi1>.
> Es un paso importante así que aseguraros de que estáis tomando los repositorios correctos o nada de lo siguiente va a funcionar. :wink: 

- [ ] Dar permisos en el repositorio que acabas de *forkear* al Compi2, obiamente el tiene que *clonar* tu repo 'Custom Banana_oh_la_la' (bajárselo a su ordenador local con `git clone <url_tu_repo>`).

- [ ] Ahora tienes que bajarte tú, tu recién forkeado repo a tú ordenador:
  ```git clone <url_tu_repo>```

- [ ] Cámbiate a la rama 'practica' (esta ya existe no tienes que crearla :octocat:):
  ```git checkout practica```

- [ ] En el directorio raíz (y estando en la rama 'practica'), elimina el archivo index.html. 

- [ ] Renombra el archivo 'index-participante1.html' y llámalo index.html a secas.

- [ ] Entra en el directorio 'styles' y elimina el archivo 'style.css'.

- [ ] Renombra el archivo 'style-participante1.css' a 'style.css'. Esto junto con lo anterior va a cambiar la página bastante. 

- [ ] Comprobar los cambios: Ejecuta el archivo 'index.html' y mira como se ve la página. Si ves algo así está todo bien.

![cocoa](https://user-images.githubusercontent.com/27022503/82645857-daf4a800-9c13-11ea-899b-dd677e1a9f56.png)

- [ ] Haz un commit con los cambios y súbelo, como no hemos cambiado de rama deberías subirlo a la rama compi1:
``` git commit -m "Tu mensaje"
     git push origin compi1 -u #Esto sube el primer commit a github y crea la rama en el remoto
```
- [ ] ¡Hora de lanzar un PR! Ve a github y lanza el PR como se ha explicado en el taller :smiley: 


#### ¡¡¡Felicidades!!! Has lanzado un PR :tada:  :tada:  :tada: :clap: 

---
---

## Estos son los pasos para la persona que ejerce de Compi2:

- [ ] Clónate en local el repo 'Custom Banana_oh_la_la' de **Compi1**. Esto baja el repo a tu ordenador y es ahí donde harás los cambios:
```git clone <url_custom_banana_oh_la_la>```

- [ ] Acepta los permisos para trabajar con el repositorio 'Custom_Banana_oh_la_la' de Compi1. Puedes ver una notificación en Github o directamente hacerlo desde tu correo electrónico (te habrá llegado un mail comentándote si quieres colaborar en ese proyecto :handshake:).

- [ ] Cambiar a la rama 'practica':
```git checkout practica```

- [ ] Desde practica crea una rama llamada 'compi2' y muévete a ella:
```git checkout -b compi2```

- [ ]  En el directorio raíz (y estando en la rama 'compi2'), elimina el archivo index.html.

- [ ]  Renombra el archivo 'index-participante2.html' y llámalo index.html a secas.

- [ ]  Entra en el directorio 'styles' y elimina el archivo 'style.css'.

- [ ]  Renombra el archivo 'style-participante2.css' a 'style.css'. Esto junto con lo anterior va a cambiar la página bastante.

- [ ] Comprobar los cambios: Ejecuta el archivo 'index.html' y mira como se ve la página. Si ves algo así está todo bien.

![Mango](https://user-images.githubusercontent.com/27022503/82650163-96203f80-9c1a-11ea-86d7-dd1318c5ed8c.png)

- [ ] Realiza un commit y ve a la rama 'practica':
```git checkout practica```

- [ ] Traete la rama compi2 a la rama práctica con un merge:
```git merge compi2```

- [ ]  Pushea los cambios a Github:
```git push origin practica -u```
(Esto tiene que dar un error. ¿Sabes por qué? ¿Que dice la consola?)

- [ ] Baja a tu local lo que haya en la rama 'practica' de github:
```git pull origin practica```
(Esto va a generar un conflicto, no te preocupes, es lo que queremos)

- [ ] Resuelve el conflicto, recuerda que lo tuyo es lo que está en la parte de arriba y lo que viene de github en la parte de abajo. Para simplificar quédate con lo tuyo. 

- [ ] Guarda todo, haz un commit y vuelve a hacer el `git push origin practica`

#### ¡¡¡Felicidades!!! Has resuelto un conflicto!!! :tada:  :tada:  :tada: :clap: 
