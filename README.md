# Blog Django - M3 UF6

## Introducció
Blog desenvolupat amb Django com a projecte d'aprenentatge del mòdul M3-UF6.
Permet gestionar posts, autors i etiquetes, amb una interfície web basada en Bootstrap 5.

## Instal·lació ràpida

```bash
# 1. Clona el repositori
git clone https://github.com/esteveab2000/Projecte_Django.git
cd Projecte_Django

# 2. Instal·la les dependències
pip install -r requirements.txt

# 3. Executa les migracions
python manage.py migrate

# 4. (Opcional) Carrega les dades d'exemple
python manage.py loaddata blog/fixtures/initial_data.json
```

## Execució del projecte

```bash
python manage.py runserver
```

Accedeix a: [http://127.0.0.1:8000](http://127.0.0.1:8000)

Panel d'administració: [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)
