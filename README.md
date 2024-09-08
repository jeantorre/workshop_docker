# Executando no Docker
## Clonando o repositório
```bash
git clone https://github.com/jeantorre/workshop_docker.git
```

## Construindo imagem Docker (building)
```bash
docker build -t primeira-imagem-docker .
```
## Transformando em container
```bash
docker run -d -p 8501:8501 --name meu-container primeira-imagem-docker
```

# Executando em Python
## Clonando o repositório
```bash
git clone https://github.com/jeantorre/workshop_docker.git
```
## Instalando bibliotecas (caso não tenha o Poetry)
```bash
pip install pipx
pipx install poetry
pyenv local 3.12.4
poetry install
poetry env use 3.12.4
```

## Instalando bibliotecas (caso tenha o Poetry)
```bash
pyenv local 3.12.4
poetry install
poetry env use 3.12.4
```
