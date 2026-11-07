# 💱 Cotação de Moedas em Tempo Real (Web Scraping + GUI)

Aplicação desktop em Python que automatiza a consulta de cotações financeiras atualizadas em tempo real através de Web Scraping com Selenium e exibe os valores formatados em uma interface gráfica desenvolvida com Tkinter.

---

## 📌 Funcionalidades

- **Automação & Web Scraping:** Coleta em tempo real as cotações do **Dólar**, **Euro**, **Bitcoin** e **Ouro** acessando dinamicamente fontes como Google Finance e Melhor Câmbio.
- **Tratamento de Dados:** Formatação automatizada de strings numéricas para o padrão monetário brasileiro (BRL), ajustando pontuações e casas decimais.
- **Interface Gráfica (GUI):** Janela interativa feita em Tkinter com botões reutilizáveis para exibir ou ocultar os valores calculados de cada moeda.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Automação Web:** [Selenium Webdriver](https://www.selenium.dev/)
- **Interface Gráfica:** [Tkinter](https://docs.python.org/3/library/tkinter.html)

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter o Python instalado na sua máquina e o **Google Chrome** instalado com o driver correspondente.

### 1. Clonar o repositório
```bash
git clone [https://github.com/rafaelxf-dev/pegar-cotacao.git](https://github.com/rafaelxf-dev/pegar-cotacao.git)
cd pegar-cotacao
```

### 2. Instalar as dependências
```bash
pip install selenium
```

### 3. Executar a aplicação
```bash
python main.py
```
