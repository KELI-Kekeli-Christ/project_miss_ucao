<p align="center">
  <a href="README.md">English</a>
  &nbsp;·&nbsp;
  <a href="README.fr.md">Français</a>
  &nbsp;·&nbsp;
  <a href="README.es.md"><b>Español</b></a>
</p>

# project_miss_ucao

Sitio Django para un concurso Miss. Los modelos en `miss_mister_ucao/models.py` son `Miss` y `Vote`. Las vistas son la lista de candidatas, un voto y los resultados:

- `/` lista de candidatas
- `/vote/<miss_id>/` voto
- `/get_results/` resultados

El sitio publicado que indicaba el README anterior es [miss-ucao.onrender.com](https://miss-ucao.onrender.com/). `Procfile` está presente para ese alojamiento.

```bash
pip install -r requirements.txt
python manage.py runserver
```
