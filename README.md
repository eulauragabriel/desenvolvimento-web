# ✨ Aplicação UNES

> Desenvolvedora: Laura Gabriel Gonçalves
> 
> Matéria: Desenvolvimento Web
> 
> Curso: Desenvolvimento de Software Multiplataforma - 1º Semestre

### 🌱 Tecnologias Utilizadas:
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white&color=75c775"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white&color=75c775"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&color=75c775"/>
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white&color=75c775"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white&color=75c775"/>

### 🔧 Executando a Aplicação:

#### Requisitos Prévios:
- Python instalado em sua máquina.
- Banco de dados MySQL configurado localmente.

#### Passos para Execução:
1. **Clonar o Repositório:**
```bash
git clone https://github.com/eulauragabriel/site-unes
```
2. **Entrar na pasta src:**
```bash
cd site-unes/src
```
3. **Instalar as Dependências:**
```bash
pip install -r requirements.txt
```
4. **Configurar o Banco de Dados:**

- Certifique-se de que seu banco de dados MySQL esteja em execução localmente.
- Configure as credenciais do MySQL no arquivo `app.py`:
  ```python
  app.config["MYSQL_Host"] = "localhost"
  app.config["MYSQL_USER"] = "seu_usuario_mysql"
  app.config["MYSQL_PASSWORD"] = "sua_senha_mysql"
  app.config["MYSQL_DB"] = "fatec"
  ```
6. **Executar a Aplicação:**
```
flask run
```
6. **Acessar a Aplicação no Navegador:**
```
http://127.0.0.1:5000/
```

### 📎 Estrutura de Pastas:
src/

| - app.py

| - static/ 

| - templates/ 

| - requirements.txt

- **`app.py`:** Arquivo principal da aplicação Flask.
- **`static/`:** Pasta que armazena arquivos estáticos, como CSS e imagens.
- **`templates/`:** Pasta que contém os arquivos HTML que compõem as páginas da aplicação.
- **`requirements.txt`:** Arquivo de texto que lista as dependências necessárias para a aplicação.
