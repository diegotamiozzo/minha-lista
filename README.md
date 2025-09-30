# 📦 Sistema de Solicitação de Materiais

![Version](https://img.shields.io/badge/version-1.4%20Beta-blue)
![Python](https://img.shields.io/badge/python-3.8+-green)
![Flask](https://img.shields.io/badge/flask-2.0+-red)
![License](https://img.shields.io/badge/license-MIT-yellow)

Aplicação web para requisição de materiais com pesquisa em banco de dados e geração automática de PDFs profissionais.

---

## 🚀 Funcionalidades

* Interface moderna e responsiva
* Pesquisa inteligente de materiais
* Seleção de itens com quantidade e unidade
* Prevenção de duplicados
* Geração de PDF personalizado com timestamp

---

## 🛠️ Tecnologias

* **Backend:** Python (Flask, SQLite, Pandas, FPDF, PyTZ)
* **Frontend:** HTML5, CSS3, JavaScript (jQuery), Bootstrap, Google Fonts

---

## 🔧 Instalação

```bash
# Clone o repositório
git clone https://github.com/diegotamiozzo/minha-lista.git
cd minha-lista

# Crie e ative um ambiente virtual
python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate  # Linux/Mac

# Instale as dependências
pip install -r requirements.txt

# Execute a aplicação
python app.py
```

Acesse em: **[http://localhost:5000](http://localhost:5000)**

---

## 🌐 Deploy

Exemplo no **Heroku**:

```
web: python app.py
```

```bash
heroku config:set FLASK_ENV=production
git push heroku main
```

Também compatível com **Render**, **Railway** e **PythonAnywhere**.

---

## 🤝 Contribuição

1. Fork este repositório
2. Crie uma branch (`git checkout -b feature/minha-feature`)
3. Commit e push
4. Abra um Pull Request

---

## 👨‍💻 Autor

**Diego Tamiozzo**

---

<div align="center">

**Desenvolvido  por Diego Tamiozzo**


</div>
