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

💻 Como Instalar e Rodar (Uso Local Gratuito)
Este programa foi projetado para rodar diretamente na sua máquina. Siga os passos abaixo:

"Crie uma pasta e cole o codigo disponível"

1. Preparação do Ambiente
Certifique-se de ter o Python instalado em seu computador. No terminal, navegue até a pasta do projeto e instale as dependências:
Digite o comando: pip install -r requirements.txt

2. Criando o "Bot" de Inicialização (Windows)
Para abrir o programa com apenas dois cliques, sem precisar digitar comandos no terminal:

Dentro da pasta do projeto, crie um novo arquivo de texto chamado Rodar_Monitor.bat.

Clique com o botão direito nele, selecione Editar e cole o seguinte código: 
@echo off
streamlit run main.py
pause

Salve e feche o arquivo.

3. Criando Atalho na Área de Trabalho
Para facilitar ainda mais o acesso:

Clique com o botão direito no arquivo Rodar_Monitor.bat que você criou.

Selecione Enviar para > Área de Trabalho (criar atalho).

Agora, sempre que quiser iniciar seu monitor de ataques, basta usar o ícone na sua área de trabalho!

📝 Notas de Versão
O software é 100% gratuito para execução local.

Requer conexão com a internet para carregar os feeds de IPs em tempo real.
