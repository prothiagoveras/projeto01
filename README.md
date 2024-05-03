# Meu Primeiro Projeto Django 
Este é meu primeiro projeto Django, que aborda as bases da framework.

## Instituição para baixar, editar e executar local 
1. Clone o projeto 
```bash
git clone https://github.com/prothiagoveras/projeto01.git
```
2. Entre na pasta do projeto e crie um abiente virtual python
```bash
cd projeto01
```
```bash 
python -m venv .venv
```
3. Ative o ambiente virtual
no windos:
```bash
.venv\Scripts\activate
```
no Linux:
```bash
souce .venv/bin/activate
```
4. Instale as dependências
```bash
pip install -r requirements.txt
```
5. Execute as migrações
```bash
python manage.py migrate
```
6. Execute o servidor
```bash
python manage.py runserver
```

