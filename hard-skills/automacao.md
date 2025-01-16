---
description: O know-how básico sobre Melhoria Contínua, destinado a todos os trainees.
icon: user-robot
---

# Automação

"_A primeira regra de qualquer tecnologia utilizada nos negócios é que a automação aplicada a uma operação eficiente aumentará a eficiência. A segunda é que a automação aplicada a uma operação ineficiente aumentará a ineficiência._"\
&#xNAN;_- Bill Gates_

Automação é um dos pilares da Mottu. Acreditamos fortemente em utilizar tecnologia e dados para tornar a jornada dos clientes cada vez mais valiosa, _no-touch_ e sem fricção. Diversos setores, como a área de multas, manutenção, e até mesmo os mais "humanizados" como suporte ao cliente, contam com ferramentas de automação que buscam fazer mais com cada vez menos capital humano.

Existem 3 ferramentas cruciais para automação que todo trainee deve conhecer ao menos o básico: **Python**, **NiFi**, e **Power Automate**.

### Python para Automação

#### Básico:

* Introdução
  * Sintaxe básica (variáveis, operadores, condicionais, loops)
  * Estruturas de dados: listas, dicionários, conjuntos
* Manipulação de arquivos
  * Leitura e escrita de arquivos (TXT, CSV, JSON)
  * Uso de bibliotecas como “os” para manipulação de diretórios e arquivos
* Automação de tarefas simples
  * Tarefas de repetição com loops
  * Scripts para backup automático de arquivos

#### Intermediário:

* Automação com APIs
  * Requisições HTTP com requests (GET, POST, autenticação, etc.)
  * Integração com APIs REST para tarefas automáticas
* Automação com manipulação de dados
  * Processamento de dados com pandas
  * Uso de openpyxl e xlsxwriter para manipulação de planilhas Excel
* Automação com tarefas agendadas
  * Uso de cron (Linux) ou Agendador de Tarefas (Windows) para execução automática de scripts Python
  * Configuração de scripts para executar em horários específicos
* Web scraping básico(Gambiarra)
  * Extração de dados de páginas web com BeautifulSoup e Selenium

### &#x20;NiFi

#### Básico

* Introdução ao NiFi
  * Conceitos fundamentais: Process Group, Processor, Connection, FlowFiles
  * Navegação na interface e criação de um fluxo básico
* Processadores essenciais
  * GetFile, PutFile, LogAttribute
  * Processadores de roteamento e filtragem (RouteOnAttribute, RouteOnContent)
* Manipulação de dados simples
  * Modificação de dados usando ReplaceText e UpdateAttribute
  * Configuração de transformações simples em fluxo

#### Intermediário:

* Integração com bancos de dados
  * Configuração de ExecuteSQL e PutDatabaseRecord
  * Conexão com bases de dados para leitura e escrita em fluxos de dados
* Integração com APIs e sistemas externos
  * Configuração de InvokeHTTP para automação de chamadas a APIs
  * Configuração de PostHTTP para enviar dados de forma automática
* Automatização de processos complexos
  * Manipulação de arquivos de diversos formatos (CSV, JSON, XML)
  * Transformação de dados com JoltTransformJSON para estruturação em JSON
  * Agendamento de fluxos e configuração de triggers automáticos
* Monitoramento e alertas
  * Configuração de alertas usando PutEmail ou integração com sistemas de notificação

### &#x20;Power Automate para Fluxos Automatizados de Trabalho

#### Básico:

* Introdução ao Power Automate
  * Conceitos e tipos de fluxos: automatizado, instantâneo e agendado
  * Criação de fluxos básicos com gatilhos de eventos (por exemplo, e-mails recebidos ou novos arquivos no OneDrive)
* Integração com Microsoft 365
  * Conexões com Outlook, SharePoint, OneDrive e Excel
  * Fluxos básicos para automatizar ações como arquivamento automático de e-mails e notificações
* Automação de processos comuns
  * Envio de notificações automáticas e aprovação de fluxos
  * Movimentação de dados entre listas e bibliotecas do SharePoint

#### Intermediário:

* Automatização com condições e loops
  * Uso de condições (if/else) e loops para tomadas de decisão
  * Criação de fluxos que incluem aprovação em vários níveis
* Automação com conectores de terceiros
  * Integração com APIs externas, sistemas CRM, ou ferramentas de produtividade
  * Configuração de conectores personalizados para sistemas específicos
* Manipulação e transformação de dados
  * Automação de planilhas Excel com Power Automate
  * Processamento de dados de entrada e saída em formulários e documentos PDF
* Criação de bots e fluxos automáticos
  * Integração com Power Virtual Agents para automação de atendimento
  * Gatilhos automáticos para fluxos complexos baseados em chatbots
