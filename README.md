# 🧠 Automação TJSP — Consulta de Processos com Selenium e Exportação em Relatório

## 📋 Descrição do Projeto
Este projeto automatiza a **consulta de processos judiciais no portal do TJSP** a partir de uma planilha Excel contendo números de processo.  
Ele acessa o site, realiza a busca individual de cada processo, coleta dados relevantes e salva tudo em um **relatório `.txt` organizado**.  

💡 **Benefício prático:** elimina o trabalho manual repetitivo de pesquisar cada número de processo e copiar informações — economizando **horas de trabalho por dia** em escritórios jurídicos e departamentos administrativos.  

---

## ⚙️ Tecnologias Utilizadas
- **Python 3**
- **Selenium WebDriver** (automação de navegador)
- **OpenPyXL** (leitura de planilhas Excel)
- **WebDriverWait / Expected Conditions**
- **Manipulação de arquivos TXT**
- **Estrutura escalável para tratamento de erros**

---

## 🚀 Como Executar
```bash
# 1️⃣ Clonar o repositório
git clone https://github.com/seu_usuario/automacao-tjsp.git
cd automacao-tjsp

# 2️⃣ Instalar as dependências
pip install selenium openpyxl

# 3️⃣ Adicionar o arquivo de dados
# Certifique-se de ter o arquivo "DadosProcessamento.xlsx" na mesma pasta

# 4️⃣ Executar o script
python main.py
