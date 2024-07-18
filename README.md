# Instalações Basicas

## Instalação do nodejs
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash
```
Em Seguida feche e abra o terminal e de o seguinte comando

```bash
nvm install --lts
```

Em seguida digite o seguinte comando para verificar a versão do node
```bash
node -v
```

*O terminal deve apresentar uma versão maior que 20*

## Intalação do pdm

```bash
curl -sSL https://raw.githubusercontent.com/pdm-project/pdm/main/install-pdm.py | python3 -
```

Execute o seguinte comando para configurar o pdm 
```bash
curl -sSL https://github.com/marrcandre/django-drf-tutorial/raw/main/scripts/pdm_config_bash.sh | bash
```

Em seguida digite o seguinte comando para verificar a versão do pdm
```bash
pdm -V
```
*O terminal deve apresentar a versão 2.16.1*

## Extensões necessárias

- Python
- Django
- SQLite viewer
- Thunder Client
- Vue Official
