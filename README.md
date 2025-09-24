# 📡 Radar de Licitação

O **Radar de Licitação** é uma aplicação desenvolvida para automatizar a coleta e análise de editais de licitações públicas no Brasil.  
Com ele, empresas e profissionais conseguem acompanhar oportunidades em tempo real, sem precisar navegar manualmente em dezenas de portais.

---

## 🚀 Funcionalidades

- 🔎 **Busca automática** em portais oficiais (ComprasGov, PNCP, entre outros).  
- 📬 **Alertas inteligentes** por e-mail ou mensagem (WhatsApp/Telegram).  
- 📊 **Dashboard analítico** com filtros por região, modalidade, órgão e valor.  
- 🗄️ **Histórico estruturado** dos editais coletados.  
- ⏱️ **Agendamento automático** para rodar diariamente ou em intervalos definidos.  

---

## 🛠️ Tecnologias

- **Backend:** Python (FastAPI/Django)  
- **Coleta de dados:** Requests, BeautifulSoup, Selenium  
- **Banco de dados:** PostgreSQL  
- **Dashboards:** Streamlit / React  
- **Infra:** Docker + Nginx (deploy em VPS/Cloud)  

---

## 📦 Instalação

### Pré-requisitos
- Python 3.11+  
- PostgreSQL  
- Docker (opcional)  

### Passos
```bash
# Clonar o repositório
git clone https://github.com/fayzerlol/radar-licitacao.git
cd radar-licitacao

# Criar ambiente virtual
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Instalar dependências
pip install -r requirements.txt
