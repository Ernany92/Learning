# 📡 Cyber Threat Monitor PRO

Um dashboard interativo de inteligência de ameaças cibernéticas desenvolvido em Python. O sistema mapeia tentativas de ataques em tempo real ao redor do mundo, utilizando feeds de dados reais da comunidade de segurança.

![Status](https://img.shields.io/badge/Status-Ativo-brightgreen)
![Python](https://img.shields.io/badge/Python-3.8+-blue)

## 🚀 Funcionalidades
- **Live Feed:** Conexão com a API DShield (SANS Institute) para rastrear IPs maliciosos ativos.
- **Globo Interativo:** Visualização geoespacial 3D usando Plotly com projeção ortográfica.
- **Análise por Alvo:** Seleção dinâmica de países para monitoramento de tráfego.
- **Logs de Eventos:** Painel de console simulando registros de SOC (Security Operations Center).
- **Resiliência de Rede:** Sistema de fallback automático para garantir a operação em diferentes ambientes.

## 🛠️ Tecnologias Utilizadas
- [Streamlit](https://streamlit.io/)
- [Plotly](https://plotly.com/python/)
- [Requests](https://requests.readthedocs.io/)
- [Open-Meteo API](https://open-meteo.com/)

## 💻 Como Instalar e Rodar
1. **Clone ou baixe** este repositório para uma pasta em seu computador.
2. Certifique-se de ter o Python 3.8+ instalado.
3. No terminal (dentro da pasta do projeto), instale as dependências:
   ```bash
   pip install -r requirements.txt

## Criando um Atalho de Inicialização (Windows)
Para facilitar o acesso, criamos um script de execução rápida:

Na pasta do projeto, crie um arquivo chamado Rodar_Monitor.bat.

Clique com o botão direito nele, selecione Editar e cole o código abaixo:

Snippet de código
@echo off
streamlit run main.py
pause

Salve o arquivo. Agora basta criar um atalho deste .bat na sua Área de Trabalho.

📝 Nota: Este software é de código aberto e destinado para fins educacionais e de monitoramento local.
Requer conexão com a internet para carregar os feeds de IPs em tempo real.


