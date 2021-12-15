% prepara repo para despliegue
release: sh -c 'cd decide && python manage.py migrate'
% comando para lanzar web
web: sh -c 'cd decide && gunicorn decide.wsgi --log-file -'
