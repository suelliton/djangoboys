###DjangoBoys

####Como utilizar:

######Clone este repositório

```
git clone https://github.com/franklindias/djangoboys.git
```

######Dentro da pasta do projeto, crie sua virtualenv
```
python3 -m venv myenv
``` 

######Ative o virtualenv
```
source myvenv/bin/activate
``` 


######Instale as bibliotecas requeridas do projeto
```
pip install -r requirements.txt
```

######Crie os migrates necessários, caso precise
```
python manage.py makemigrations
```

######Crie o banco de acordo com o migrate criado
```
python manage.py migrate
```

######Execute o projeto e SEJA FELIZ!!!
```
python manage.py runserver
```