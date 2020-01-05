# CrudAngularPhpMysql

Se deben ejecutar ambos proyectos por separado. El proyecto angular se ejecuta de la forma usual con ng serve, y se lo visualiza en algún 
puerto en particular, como ser http://localhost:4200

El proyecto php se lo puede ejecutar con xammp. Para ello se colocan los ficheros php de este proyecto en alguna subcarpeta de htdocs 
dentro de xammp, por ejemplo: C:\xampp\htdocs\crud

Una vez hecho esto se levanta el servidor apache y mysql de xammp y se puede acceder a los ficheros con la ruta http://localhost/crud

Debe asegurarse crear previamente la base de datos que se está utilizando en phpMyAdmin. No es necesario especificar la ruta de la base 
de datos mysql ya que xammp la busca (por su nombre) por defecto en el puerto: http://localhost/127.0.0.1

