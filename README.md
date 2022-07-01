# django_demo
Para ejecutar este proyecto en linux mint ejecuta los siguientes comandos:

git clone https://github.com/jrojas1798/demo_django.git

cd demo_django

source .venv/bin/activate

pip3 install -r requirements.txt

python3 manage.py makemigrations

python3 manage.py runserver

Una vez iniciado el manage.py de manera correcta abrir en el navegador: http://127.0.0.1:8000/admin/ Usuario: jrojas   password: linux
Para ver el entorno de administrador en donde se pueden agregar libros, autores, etc. 
y http://127.0.0.1:8000/ para ver la interface del cliente en donde se muestran los libros disponibles y sus autores. 
