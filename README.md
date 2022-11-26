## Presentación del repositorio

### Construido con 🛠️

* [Terraform]() Lenguaje utilizado
* [Docker]() Contenedores de aplicaciones


### Pasos para implementarlo localmente

Con Terraform y Docker previamente instalados, se deben seguir los pasos siguientes: 

* Como primer paso, se debe iniciar terraform con el comando <code>terraform init</code>, esto para inicializar terraform dentro de la carpeta y descarga archivos que emplean los modulos.

* Posteriormente <code>terraform apply --auto-apply</code>, terraform valida que no haya recursos en sus archivos de estado, si detecta cambios crea y ejecuta un plan para crear los recursos.

* Si Terraform no encuentra ningun error, ejecutando <code>docker ps</code> desde terminal, esta mostrará los contenedores programados y en ejecución. Deberiamos ser capaces de ingresar al contenedor de Jenkins desde <code>http://localhost:8080</code>.

### Autor ✒️

* **Pablo Perez** - *Trabajo Inicial* - [pprezp](https://github.com/pprezp)

---
⌨️ con ❤️ por [pprezp](https://github.com/pprezp) 😊
