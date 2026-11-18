<p align="center">
  <a href="README.md"><b>English</b></a>
  &nbsp;·&nbsp;
  <a href="README.fr.md">Français</a>
  &nbsp;·&nbsp;
  <a href="README.es.md">Español</a>
</p>

# project_miss_ucao

Django site for a Miss contest. The models in `miss_mister_ucao/models.py` are `Miss` and `Vote`. The views are the candidate list, a vote, and the results:

- `/` candidate list
- `/vote/<miss_id>/` vote
- `/get_results/` results

The published site linked from the old README is [miss-ucao.onrender.com](https://miss-ucao.onrender.com/). `Procfile` is present for that host.

```bash
pip install -r requirements.txt
python manage.py runserver
```
