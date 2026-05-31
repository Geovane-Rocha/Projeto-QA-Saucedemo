# 🛒 Projeto QA — SauceDemo E-commerce

Projeto completo de Quality Assurance aplicado ao e-commerce 
[SauceDemo](https://www.saucedemo.com), cobrindo testes manuais 
e automatizados.

---

## 🎯 Objetivo

Demonstrar habilidades práticas em QA através de um projeto 
completo — desde a identificação de bugs até a automação de testes.

---

## 🧪 O que foi testado

- ✅ Fluxo de Login — válido, inválido e usuário bloqueado
- ✅ Catálogo de Produtos — filtros e ordenação
- ✅ Carrinho — adicionar e remover produtos
- ✅ Checkout — fluxo completo de compra
- ✅ Logout do sistema

---

## 📂 Estrutura do Projeto

| Pasta | Conteúdo |
|-------|----------|
| `bug-reports/` | Bugs encontrados durante os testes |
| `test-cases/` | Casos de teste documentados |
| `automacao/` | Testes automatizados com Selenium e Pytest |
| `evidencias/` | Prints e GIFs dos bugs encontrados |

---

## 🤖 Testes Automatizados

| Arquivo | Testes | Cenários |
|---------|--------|----------|
| `test_login.py` | 5 testes | Login válido, inválido, carrinho, checkout, logout |
| `test_produtos.py` | 3 testes | Filtros de preço, nome e remoção de produto |
| `test_usuarios.py` | 2 testes | Usuário bloqueado e detalhes do produto |

**Total: 10 testes automatizados — todos passando ✅**

📊 [Ver Relatório HTML dos Testes](https://htmlpreview.github.io/?https://github.com/Geovane-Rocha/projeto-qa-saucedemo/blob/main/automacao/relatorio.html)

---

## 🐛 Bugs Encontrados

| ID | Título | Severidade |
|----|--------|------------|
| BUG-001 | Seta do filtro não abre o dropdown | Baixo |
| BUG-002 | Imagem do produto não aparece no carrinho | Médio |
| BUG-003 | Campo de quantidade não permite edição | Médio |
| BUG-004 | Botão Remove visível após Reset App State | Baixo |
| BUG-005 | Checkout aceita números em campos de nome | Alto |

---

## 🛠️ Tecnologias Utilizadas

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,selenium,github,vscode&theme=dark" />
</p>

- **Python** — linguagem de programação
- **Selenium** — automação de testes web
- **Pytest** — framework de testes
- **Git/GitHub** — versionamento

---

## ▶️ Como Executar os Testes

```bash
# Clone o repositório
git clone https://github.com/Geovane-Rocha/projeto-qa-saucedemo.git

# Entre na pasta de automação
cd projeto-qa-saucedemo/automacao

# Instale as dependências
pip install selenium pytest webdriver-manager pytest-html

# Execute os testes
pytest -v

# Gere o relatório HTML
pytest -v --html=relatorio.html --self-contained-html
```

---

## 👤 Autor

**Geovane Rocha**
- GitHub: [Geovane-Rocha](https://github.com/Geovane-Rocha)
- LinkedIn: [Geovane Rocha](https://linkedin.com/in/geovane-rocha-594ab5b2)

---

<p align="center">
  <i>"Qualidade não é um ato, é um hábito." — Aristóteles</i>
</p>