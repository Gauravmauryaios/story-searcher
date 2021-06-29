# search story

#TEST AND RUN THE JINAAA

## How to run the projects

### Jina
```bash
cd search_stories
python app.py search
```

### Rasa
```bash
cd rasa
```

Action Server
```bash
python -m rasa run actions 
```

Rasa Core Server
```bash
rasa run -p 5007 --cors "*" --debug
```

### Flask Test Webpage
```bash
cd rasa
python app.py
```

## More details on Jina and Rasa

### Jina

```bash
python3 -m venv env/search_story_env
source env/search_story_env/bin/activate

pip install -U cookiecutter && cookiecutter gh:jina-ai/cookiecutter-jina
```
