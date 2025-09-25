# RenderLouis
Essai déploiement

### Installation

```bash
 py -m venv .venv
 .venv\Scripts\Activate
 pip install -r requirements.txt
```

### Execution
```bash
 fastapi dev main.py
```
## DOCKER
### Build
```bash
 docker build --tag render .
```
### Execution de l'image -> conteneur
```bash
 # -it : mode interactif
 # --rm : supprimer l'instance après execution
  docker run -it --rm -p 8000:8000 --name renderinstance render
```