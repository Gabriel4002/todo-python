# 🖥️ TODO Simples para Aprendizado de Django

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Django](https://img.shields.io/badge/Django-5.2.6%2-006400)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

## 📌 Sobre o Projeto
Este projeto foi desenvolvido com o objetivo de praticar e utilizar o framework web Django e integração com banco de dados.


## 🚀 Funcionalidades
- **Inserir Notas: Cadastrar uma nova nota.**
- **Visualizar Todas as Notas: Exibir todos as notas cadastrados.**
- **Atualizar Notas: Modificar notas já cadastradas.**
- **Deletar Notas: Excluir notas selecionados.**

## 🛠 Tecnologias Utilizadas
- [Python](https://www.python.org/)
- [Django](https://www.djangoproject.com/) Framework para a interface web

## 📁 Estrutura do Projeto
```
todo-python/
├── automacaoescolar/
│    └── automacao/
│        └── migrations/
│             └── ...
│        └── templates/
│             └── ...
│        └── ...
│    └── automacaoescolar/
│        └── ...
│    └── db.sqlite3
│    └── manage.py
├── main.py
├── README.md               # Este arquivo
├── requirements.txt  # Bibliotecas necessárias
└── .gitignore        
```
## ▶️ Como executar

1. Clone o repositório:
```bash
git clone https://github.com/Gabriel4002/todo-python.git
cd todo-python
```

2. Crie um ambiente virtual (opcional, mas recomendado):
```bash
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
.venv\Scripts\activate   # Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Crie um 'superuser':
```bash
py manage.py createsuperuser
```

5. Inicie o servidor:
```bash
cd automacaoescolar
python manage.py runserver
```
- Isso gerará um localhost que poderá ser acessado para vizualização da pagina inicial.

6. Vizualizar as notas:
```bash
Vá até a URL da aplicação, adicione um "/" e em seguida a palavra "todos/"
```
- Você irá para a pagina de vizualização de notas ja criada, se você não fez nenhuma alteração, não haverá nada na página.

7. Gerenciar as notas:
```bash
Vá até a URL da aplicação, adicione um "/" e em seguida a palavra "admin/"
```
- Você irá para a pagina de administração do django, nela você pode adicionar, editar e excluir notas. Para isso basta ir até a seção cujo o nome é "AUTOMACAO", clicar em "Add" para adicionar uma nota e em "Change" para editar alguma nota já criada

## 📝 Observações

- A aplicação utiliza um banco de dados SQLite local, que será automaticamente criado no diretório do projeto ao inserir o primeiro registro.
- O código é um exemplo básico e um pontapé inicial para o desenvolvimento da segunda parte do projeto "automacao-escolar-python".

## ✍️ Autor

Gabriel Lobato  
[LinkedIn](https://www.linkedin.com/in/gabriel-lobato-314096371)

---

> Este projeto foi desenvolvido como parte do meu aprendizado sobre Python e Django
