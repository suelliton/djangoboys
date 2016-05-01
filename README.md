###DjangoBoys

####Como utilizar:

######Clone este repositório
```sh
$ git clone https://github.com/franklindias/djangoboys.git
```

######Dentro da pasta do projeto, crie sua virtualenv
```sh
$ python3 -m venv myvenv
``` 
crie exatamente como este nome: "myvenv", pois este é o que coloquei pra ignorar no .gitignore (evitar que a pasta do virtualenv vá para o git)

######Ative o virtualenv
```sh
$ source myvenv/bin/activate
``` 

######Instale as bibliotecas requeridas do projeto
```sh
$ pip install -r requirements.txt
```

######Crie os migrates necessários, caso precise
```sh
$ python manage.py makemigrations
```

######Crie o banco de acordo com o migrate criado
```sh
$ python manage.py migrate
```

######Execute o projeto e SEJA FELIZ!!!
```sh
$ python manage.py runserver
```