<p align="center">
  <a href="README.md">English</a>
  &nbsp;·&nbsp;
  <a href="README.fr.md"><b>Français</b></a>
  &nbsp;·&nbsp;
  <a href="README.es.md">Español</a>
</p>

# project_miss_ucao

Site Django pour un concours Miss. Les modèles dans `miss_mister_ucao/models.py` sont `Miss` et `Vote`. Les vues sont la liste des candidates, un vote et les résultats :

- `/` liste des candidates
- `/vote/<miss_id>/` vote
- `/get_results/` résultats

Le site publié indiqué par l'ancien README est [miss-ucao.onrender.com](https://miss-ucao.onrender.com/). `Procfile` est présent pour cet hébergement.

```bash
pip install -r requirements.txt
python manage.py runserver
```
