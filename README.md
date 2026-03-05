# 📡 Cyber Threat Monitor PRO

Um dashboard interativo de inteligência de ameaças cibernéticas desenvolvido em Python. O sistema mapeia tentativas de ataques em tempo real ao redor do mundo, utilizando feeds de dados reais da comunidade de segurança.

![Demonstração do Projeto](https://img.shields.io/badge/Status-Ativo-brightgreen)
![Python](https://img.shields.io/badge/Python-3.8+-blue)

## 🚀 Funcionalidades
- **Live Feed:** Conexão com a API DShield (SANS Institute) para rastrear IPs maliciosos ativos.
- **Globo Interativo:** Visualização geoespacial 3D usando Plotly com projeção ortográfica.
- **Análise por Alvo:** Seleção dinâmica de países para monitoramento de tráfego.
- **Logs de Eventos:** Painel de console simulando registros de SOC (Security Operations Center).
- **Resiliência de Rede:** Sistema de fallback automático para garantir a operação mesmo sob bloqueios de firewall.

## 🛠️ Tecnologias Utilizadas
- [Streamlit](https://streamlit.io/) - Framework para a interface web.
- [Plotly](https://plotly.com/python/) - Gráficos e mapas interativos.
- [Requests](https://requests.readthedocs.io/) - Consumo de APIs REST.
- [Open-Meteo API](https://open-meteo.com/) - Validação de conectividade de rede.

## 📦 Como rodar o projeto
1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/cyber-monitor-pro.git](https://github.com/SEU_USUARIO/cyber-monitor-pro.git)