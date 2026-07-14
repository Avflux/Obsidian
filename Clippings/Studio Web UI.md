---
title: "JPeetz/Hermes-Studio: Web UI & dashboard for Hermes Agent — chat, memory, skills, terminal, approvals, multi-agent orchestration. Self-hosted."
source: "https://github.com/JPeetz/Hermes-Studio"
author:
published:
created: 2026-07-14
description: "Web UI & dashboard for Hermes Agent — chat, memory, skills, terminal, approvals, multi-agent orchestration. Self-hosted. - JPeetz/Hermes-Studio"
tags:
  - "clippings"
---
[![Hermes Studio — interface web e painel de controle de código aberto para o Hermes Agent, desenvolvido pela NousResearch.](https://private-user-images.githubusercontent.com/88510961/576918996-7eab7817-b21d-4595-9412-ac013761dcd5.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODQwNDE5OTksIm5iZiI6MTc4NDA0MTY5OSwicGF0aCI6Ii84ODUxMDk2MS81NzY5MTg5OTYtN2VhYjc4MTctYjIxZC00NTk1LTk0MTItYWMwMTM3NjFkY2Q1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA3MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwNzE0VDE1MDgxOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWU0OTg3MmJhMGU3OWQ0NWY2YmU2MjgwYjNkOTcxZDA5NDFkMzRkNzdhNDg1OTcwZjE0ZWI4ODE1Y2I0MWNkYWQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.BI4NAkKJUL6C90DBr6fdbeoHo60N6cDswiC9SQR0PqY)](https://private-user-images.githubusercontent.com/88510961/576918996-7eab7817-b21d-4595-9412-ac013761dcd5.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODQwNDE5OTksIm5iZiI6MTc4NDA0MTY5OSwicGF0aCI6Ii84ODUxMDk2MS81NzY5MTg5OTYtN2VhYjc4MTctYjIxZC00NTk1LTk0MTItYWMwMTM3NjFkY2Q1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA3MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwNzE0VDE1MDgxOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWU0OTg3MmJhMGU3OWQ0NWY2YmU2MjgwYjNkOTcxZDA5NDFkMzRkNzdhNDg1OTcwZjE0ZWI4ODE1Y2I0MWNkYWQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.BI4NAkKJUL6C90DBr6fdbeoHo60N6cDswiC9SQR0PqY)

## Estúdio Hermes

**A única interface web do Hermes com um gerenciador de tarefas cron integrado — agende, monitore e controle tarefas autônomas do agente sem precisar acessar um terminal.**

> Não é apenas um wrapper de chat. É um estúdio completo — orquestre equipes multiagentes, aprove ações, navegue pela memória com um gráfico de conhecimento visual, gerencie habilidades e agende tarefas recorrentes, tudo a partir de uma única interface. Desenvolvido para usuários avançados que executam o Hermes Agent localmente.

## O que é o Hermes Studio?

O Hermes Studio é um painel de controle web de código aberto e auto-hospedado para [o Hermes Agent,](https://github.com/NousResearch/hermes-agent) desenvolvido pela [NousResearch](https://nousresearch.com/). Ele transforma o agente de IA do Hermes em um espaço de trabalho completo que você pode controlar a partir do seu navegador — com orquestração multiagente, agendamento de tarefas cron, aprovações de execução, gerenciamento de servidor MCP e mais de 30 recursos que nenhuma outra interface de usuário do Hermes oferece. Funciona com Ollama, OpenAI, Anthropic e qualquer backend compatível com OpenAI. Desenvolvido com React, TypeScript e TanStack. Licença MIT.

---

**Índice**

---

## ✨ Recursos

- 🤖 **Integração com o agente Hermes** — Conexão direta com o gateway e streaming SSE em tempo real
- 👥 **Equipes Multiagentes** — Crie equipes nomeadas de agentes especializados, distribua tarefas para todos os membros ou para membros específicos e acompanhe as atividades ao vivo.
- 🗂️ **Espaços de trabalho com escopo de perfil** — Cada membro da equipe de agentes obtém uma visão isolada do sistema de arquivos por meio de raízes de espaço de trabalho por perfil.
- 🕸️ **Gráfico de Conhecimento Interativo** — Gráfico visual direcionado por força das relações de links wiki da sua memória, com zoom, panorâmica, arrastar de nós e destaques ao passar o mouse.
- 🎨 **Sistema de 8 temas** — Oficial, Clássico, Cinza, Mono — cada um com variantes claras e escuras
- 🔒 **Segurança reforçada** — Middleware de autenticação em todas as rotas da API, cabeçalhos CSP, proteções contra travessia de diretórios e solicitações de aprovação de execução.
- 📱 **PWA com foco em dispositivos móveis** — Paridade total de recursos em qualquer dispositivo via Tailscale
- ⚡ **Transmissão SSE ao vivo** — Saída do agente em tempo real com renderização de chamadas de ferramentas
- 🧠 **Memória e Habilidades** — Navegue, pesquise e edite a memória dos agentes; explore mais de 2.000 habilidades.
- ✅ **Aprovações de Execução** — Aprovar, negar ou permitir sempre comandos do shell do agente a partir da interface do usuário; recibos resolvidos exibidos em linha
- 📦 **Instalação de Skills** — Instale/desinstale/ative/desative skills diretamente do navegador
- 🐦 **Exemplo de Plugin X/Twitter** — Use o Hermes Tweet como um plugin nativo do Hermes Agent para fluxos de trabalho de busca, leitura e ações protegidas no X/Twitter:`hermes plugins install Xquik-dev/hermes-tweet --enable`
- ⏰ **Gerenciador de Tarefas Cron** — A única interface de usuário para agentes com um agendador completo: crie, edite, pause, acione e monitore tarefas; acionadores manuais transmitem eventos de ferramentas ao vivo via SSE diretamente para o cartão de tarefa.
- 🔐 **Permissões e conjuntos de ferramentas** — Configure aprovações, lista de permissões de comandos, conjuntos de ferramentas, scanner de segurança, limites de código e justificativas na interface de Configurações.
- 💾 **Persistência de Sessão** — Tokens de autenticação, sessões e execuções ativas sobrevivem a reinicializações do servidor via Redis (conexões automáticas, fallback controlado)
- 🔀 **Construtor Visual de Fluxos de Trabalho** — Crie e execute fluxos de trabalho de tarefas estruturados em DAG para suas equipes; as tarefas são executadas em ordem topológica com status em tempo real por nó.
- 📋 **Modelos de Tripulação e Condutor** — 7 modelos de tripulação integrados + 4 modelos de condutor (Pesquisar, Construir, Revisar, Implantar), além de permitir salvar e gerenciar os seus próprios; sistema de modelos unificado com `templateType` informações de campo.
- 💰 **Rastreamento de custos** — uso de tokens por equipe (entrada/saída) e custo estimado da API por agente; guia de uso em cada equipe com tabela de preços baseada em modelo e controle de redefinição.
- 🔌 **Gerenciamento de Servidores MCP** — adicione, edite e remova servidores MCP na interface de Configurações; salva diretamente `~/.hermes/config.yaml` e aciona uma atualização automática; nenhuma edição manual de arquivos é necessária.
- 🧬 **Biblioteca de Agentes** — crie, edite e exclua agentes personalizados com prompts de sistema, emojis, rótulos de função e substituições de modelo sob medida; os agentes integrados incluem prompts de sistema predefinidos que você pode copiar e personalizar; os agentes personalizados aparecem no construtor de equipe e no seletor de modelos junto com as personas integradas.
- 🕵️ **Histórico de Auditoria** — linha do tempo cronológica de cada chamada de ferramenta, mensagem do usuário e solicitação de aprovação em todas as sessões; filtre por sessão, tipo de evento e intervalo de datas; expanda os eventos da ferramenta para inspecionar todos os argumentos e resultados.
- 📋 **Clonar Equipe** — duplique qualquer equipe existente com um clique; cria novas sessões para todos os membros e abre a nova equipe imediatamente; disponível no cartão da equipe (ao passar o mouse) e no cabeçalho dos detalhes da equipe.
- 🧪 **Conjunto de testes** — testes unitários vitest para os principais armazenamentos e utilitários (199 testes em 17 arquivos, todos aprovados); testes de fumaça e2e do Playwright para todas as páginas principais; CI do GitHub Actions com indicador de status visível.
- ⚡ **Modo Rápido** — ativação com um clique no editor de bate-papo que ativa a fila de prioridade do Hermes v0.9.0 para modelos OpenAI e Anthropic; persiste por sessão.
- 📋 **Visualizador de Logs** — `/logs` a tela exibe as últimas 500 linhas do `~/.hermes/logs/` registro centralizado do Hermes (v0.8.0); filtros: Todos/Erros, busca em tempo real, cores que indicam o nível de erro, rolagem automática.
- 💾 **Backup e Importação** — backup e restauração de dados do Hermes com um clique a partir das Configurações (Hermes v0.9.0)
- 📡 **iMessage, WeChat e WeCom** — BlueBubbles (iMessage), WeChat e WeCom/Enterprise adicionados às configurações de integração da plataforma, juntamente com Telegram, Discord, Slack e Signal (Hermes v0.9.0)
- 🎯 **Conductor V2** — Orquestração de missões nativa do Gateway com escritório SVG animado (3 layouts: Grade, Mesa Redonda, Sala de Guerra), avatares de agentes em pixel art, integração real com o gateway Hermes, consulta de sessão ao vivo, monitoramento de workers, painel de configurações (seleção de modelo, paralelismo máximo, modo supervisionado), histórico de missões com controle de custos, ações rápidas (Pesquisar/Construir/Revisar/Implantar), controles de abortar/pausar/tentar novamente
- 📊 **Painel de Operações** — Visão unificada de todos os agentes em operação nas equipes e missões do condutor; alternância entre grade e saídas; filtros de status; a aba Operações por equipe também está disponível nas telas de detalhes da equipe.
- 📋 **Quadro Kanban de Tarefas** — Kanban de cinco colunas (Aguardando → A Fazer → Em Andamento → Revisar → Concluído) com recurso nativo de arrastar e soltar em HTML5; crie/edite tarefas com prioridade, tags e links de origem; missões do condutor criam automaticamente tarefas interligadas.
- 📊 **Exibição de Limite de Taxa** — o medidor de uso do provedor agora exibe os cabeçalhos de limite de taxa da API (solicitações/tokens restantes, contagem regressiva de reinicialização) capturados pelo Hermes v0.9.0 a partir das respostas do provedor LLM.
- 🖥️ **Painel de Saúde do Sistema** — barra de rodapé fixa mostrando o uso da CPU (%) em tempo real, memória, uso do disco e tempo de atividade; limites codificados por cores (verde/âmbar/vermelho); opção para ativar/desativar em Configurações → Tela
- 📈 **Gráfico de Uso de Tokens** — O gráfico de área de 14 dias no modal de uso detalha os tokens de entrada e saída diários em todas as sessões.
- 🔬 **Análise de Eventos** — `/analytics` tela com estatísticas agregadas de eventos, gráfico de barras de volume diário e gráfico de frequência das 15 principais ferramentas, obtidos diretamente do armazenamento de eventos SQLite.
- 🪪 **Editor de Arquivos de Identidade** — Configurações → Identidade permite ler e gravar arquivos.htaccess `SOUL.md` diretamente `persona.md` do `CLAUDE.md` navegador; sem necessidade de terminal.
- 🧩 **Visualizador de Padrões e Correções** — `/patterns` tela para navegar pelos padrões aprendidos pelo agente e gerenciar as correções do usuário armazenadas em `MEMORY.md`
- 🕐 **Arquivo do Histórico de Sessões** — navegador de sessões em dois painéis em `/session-history`; classificável por data/modelo/tokens/custo; carrega o histórico completo de mensagens por sessão de forma assíncrona.
- ⚙️ **Inicialização automática do Systemd** — Configurações → Inicialização automática gera e instala uma unidade de serviço de usuário do systemd; instale/inicie/pare/ative/desative/desinstale a partir da interface do usuário com exibição de status em tempo real.

---

## ⏰ Gerenciador de Tarefas Cron — um recurso que nenhuma outra interface de usuário possui.

Todas as outras interfaces web do Hermes/Claude tratam o agente como uma ferramenta de solicitação-resposta. Você envia uma mensagem e recebe uma resposta.

O Hermes Studio é o único que permite **agendar o agente como um processo em segundo plano** — executando prompts automaticamente, de acordo com um temporizador, enquanto você realiza outras tarefas.

Não `crontab -e`. Nada de scripts de shell. Nada de ficar cuidando de crianças.

Na aba Empregos, você pode:

- **Crie tarefas** com um comando de voz em linguagem natural e um agendamento — predefinições (a cada 15 minutos, por hora, diariamente, semanalmente) ou qualquer expressão cron personalizada.
- **Escolha os canais de entrega** — direcione a saída da tarefa para o Telegram, Discord, Slack ou Signal para que você seja notificado quando a execução for concluída.
- **Defina habilidades e contagens de repetição** — associe habilidades específicas a uma tarefa; limite quantas vezes ela se repete automaticamente.
- **Pausar/Retomar** sem excluir — congele uma tarefa durante um feriado e descongele-a na segunda-feira de manhã.
- **Inicie agora com transmissão ao vivo** — execute qualquer tarefa imediatamente e acompanhe os eventos da ferramenta em tempo real, a saída do token e o status de conclusão diretamente no cartão da tarefa — sem polling, sem recarregamento de página.
- **Edite ao vivo** — altere o prompt, a programação ou os canais sem precisar recriar a tarefa.
- **Monitoramento em linha** — expanda qualquer cartão de trabalho para ver as últimas N saídas de execução com registros de data e hora, ou acompanhe um log de eventos SSE ao vivo enquanto uma execução manual está em andamento.
- **Atualização automática** — a lista de tarefas é atualizada a cada 30 segundos; você nunca precisa recarregar.

### O que isso desbloqueia

| Caso de uso | Como |
| --- | --- |
| Resumo diário | Agende um lembrete para "resumir meus e-mails e calendário" todas as manhãs às 7h, entregue no Telegram. |
| verificação de integridade do repositório | Execute uma análise de código todas as noites; receba uma mensagem no Slack somente se forem encontrados problemas. |
| Monitor de preços/dados | Consultar uma API a cada 15 minutos; gerar alertas quando os limites forem atingidos. |
| Relatórios automatizados | Relatório semanal em Markdown gerado nos arquivos do seu espaço de trabalho. |
| Tarefas de manutenção | Eliminar entradas de memória antigas, rotacionar registros, sincronizar dados — de forma programada e automática. |

O gateway já executa as tarefas. O Hermes Studio é o plano de controle que permite gerenciá-las sem a necessidade de um terminal.

---

## Qual a diferença em relação ao espaço de trabalho Hermes?

O Hermes Studio é um fork do [hermes-workspace,](https://github.com/outsourc-e/hermes-workspace) ampliado com:

- ✅ **Gerenciador de Tarefas Cron** — o recurso principal acima; nenhuma outra interface de usuário o possui.
- ✅ **Interface de aprovação de execução** — aprove, negue ou permita sempre ações perigosas do agente a partir do navegador com expansão/contexto e três escopos de aprovação.
- ✅ **Instalação de Skills** — instale, desinstale e ative/desative skills diretamente do registro skillsmp.com no navegador.
- ✅ **Permissões e conjuntos de ferramentas** — configure o modo de aprovações, a lista de comandos permitidos, os conjuntos de ferramentas, a lista de bloqueio de sites, os limites de execução de código e o esforço de justificativa em Configurações.
- ✅ **Tokens de plataformas de bate-papo** — defina os tokens de bots do Telegram, Discord, Slack e Signal na página de configurações de integrações (nenhuma `.env` edição necessária)
- ✅ **Persistência de sessão** — o histórico do chat persiste mesmo após reinicializações do servidor; o backend Redis se conecta automaticamente `localhost:6379` e utiliza o armazenamento de arquivos como alternativa.
- ✅ **Orquestração Multiagente** — Equipes: grupos nomeados de agentes com perfis específicos, despacho paralelo de tarefas, feed de atividades SSE em tempo real, rastreamento do status de cada membro.
- ✅ **Espaços de trabalho com escopo de perfil** — cada agente trabalha dentro de um diretório isolado ( `~/.hermes/profiles/<name>/`) para que as equipes não entrem em conflito no sistema de arquivos.
- ✅ **Gráfico de Conhecimento Interativo** — tela direcionada por força na tela de Memória: zoom, panorâmica, arrastar nós, passar o cursor para destacar conexões, nós dimensionados por grau
- ✅ **Construtor Visual de Fluxos de Trabalho** — Editor de DAG para orquestrar pipelines de tarefas de agentes sequenciais e paralelos; nós, arestas de Bézier, layout automático e execução em tempo real com atualizações de status SSE por nó.
- ✅ **Modelos de Equipe** — 7 modelos integrados em 4 categorias (Equipe de Pesquisa, Análise Detalhada, Equipe Full-Stack, Equipe de Revisão de Código, Estúdio de Conteúdo, Equipe de Operações, Equipe de Sprint); salve seus próprios modelos; preenchimento automático com um clique da caixa de diálogo de criação de equipe
- ✅ **Rastreamento de custos** — Aba de uso em cada tela de detalhes da equipe; contagem de tokens de entrada/saída por agente, obtida da API de sessão do Hermes após cada execução; custo estimado usando uma tabela de preços de modelo integrada; totais por equipe e por membro; controle de reinicialização; requer o modo avançado do Hermes.
- ✅ **Gerenciamento de Servidores MCP** — Configurações → Servidores MCP: adicione/edite/exclua servidores MCP stdio e HTTP; "Salvar na Configuração" grava diretamente `~/.hermes/config.yaml` e aciona automaticamente uma recarga dinâmica; o fallback para cópia em YAML é mantido para ambientes onde o acesso a arquivos não está disponível.
- ✅ **Biblioteca de Agentes** — nova `/agents` tela: crie agentes personalizados com prompts do sistema, emojis, cores, rótulos de função, substituição de modelo e tags; personas integradas vêm com prompts de sistema padrão; agentes personalizados aparecem nos menus suspensos do construtor de tripulação e da galeria de modelos; CRUD completo via `/api/agents` API REST; persistido em`.runtime/agent-definitions.json`
- ✅ **Histórico de Auditoria** — nova `/audit` tela: linha do tempo cronológica entre sessões de todas as chamadas de ferramentas (com fase/argumentos/resultado), mensagens do usuário e solicitações de aprovação; com suporte de `GET /api/audit/`; filtros por sessão, tipo de evento (Chamada de Ferramenta, Mensagem do Usuário, Aprovação) e intervalo de datas; os cartões de eventos de ferramentas se expandem em linha para mostrar os argumentos e o resultado completos; paginação de 50 eventos
- ✅ **Clonar Equipe** — `POST /api/crews/:crewId/clone` duplica nome/objetivo/lista de membros, cria novas sessões para todos os membros em paralelo; botão de clonagem no cartão da equipe (ao passar o mouse) e no cabeçalho da tela de detalhes; navega diretamente para a nova equipe em caso de sucesso; inspirado em xaspx/hermes-control-interface + karmsheel/mission-control-hermes
- ✅ **Compatibilidade com Hermes v0.9.0** — Alternância do Modo Rápido ( `/fast`), `/compress` e `/debug` comandos de barra, campo API\_SERVER\_KEY, backup/importação com um clique, integrações com as plataformas BlueBubbles + WeChat + WeCom, exibição do cabeçalho de limite de taxa no medidor de uso do provedor
- ✅ **Compatibilidade com Hermes v0.8.0** — Tela de visualização de logs ( `~/.hermes/logs/`), indicadores de falha na entrega do cron, campo de script de pré-execução na criação de tarefas
- ✅ **Conductor V2** — Orquestração nativa do Gateway com escritório SVG animado, avatares em pixel art, monitoramento de trabalhadores em tempo real, configurações, histórico de missões, controle de custos, ações rápidas, abortar/pausar/tentar novamente
- ✅ **Painel de Operações** — Visão geral unificada dos agentes em todas as equipes e missões do condutor; alternância entre grade/saídas; filtros de status; também disponível como uma aba de Operações por equipe.
- ✅ **Quadro de Tarefas/Kanban** — Quadro de cinco colunas com funcionalidade de arrastar e soltar, prioridade, etiquetas e links entre origens; missões do condutor criam automaticamente tarefas vinculadas.

---

### 💰 Rastreamento de custos

Cada equipe recebe uma aba **de Uso** em sua tela de detalhes. Após a conclusão de cada execução do agente, o Hermes Studio busca a contagem acumulada de tokens na API de sessão do Hermes e a registra por agente.

A aba mostra:

- **Faixa de KPIs** — total de tokens, divisão de entrada/saída, custo total estimado
- **Detalhamento por agente** — tokens de entrada, tokens de saída, custo estimado por membro; mostra o emblema do modelo e traços para sessões em modo portátil.
- **Redefinir controle** — apague todos os dados de uso de uma equipe a qualquer momento.

As estimativas de custo utilizam uma tabela de preços integrada que abrange Anthropic (Opus, Sonnet, Haiku), OpenAI (GPT-4.1, GPT-4o, o1/o3) e Google (Gemini 2.5 Pro/Flash) com correspondência de modelo difuso e um modelo `__unknown__` alternativo. Os preços são apenas para referência.

Os dados do token exigem o modo avançado do Hermes (um backend Hermes conectado). As sessões no modo portátil exibem traços com um aviso.

---

### 📋 Modelos de tripulação

Montar uma equipe do zero a cada vez se torna repetitivo. Os modelos permitem que você comece com uma composição comprovada:

**Modelos integrados (7 no total, 4 categorias):**

| Categoria | Modelo | Composição |
| --- | --- | --- |
| Pesquisar | Equipe de Pesquisa | Luna (analista), Ada (revisora), Kai (coordenador) |
| Pesquisar | Análise Detalhada | Luna + Roger (analistas), Kai (coordenador) |
| Engenharia | Esquadrão Completo | Kai (coordenador), Roger (front-end), Sally (back-end), Max (DevOps), Ada (QA) |
| Engenharia | Equipe de Revisão de Código | Ada (executora), Luna (revisora), Nova (segurança) |
| Criativo | Estúdio de Conteúdo | Bill (coordenador), Luna (redatora), Roger (revisor) |
| Operações | Equipe de Operações | Max (coordenador), Sally e Kai (executores) |
| Operações | Equipe de Sprint | Kai (coordenador), Roger e Sally (executores), Ada (revisora) |

Clicar em **Modelos** no cabeçalho Equipes abre uma galeria com filtros. Selecionar um modelo fecha a galeria e preenche automaticamente a caixa de diálogo Nova Equipe com o nome, o objetivo e a lista de membros do modelo — edite qualquer coisa antes de confirmar.

Os modelos criados pelo usuário são salvos `.runtime/templates.json` e permanecem mesmo após reinicializações. Você pode excluí-los da galeria a qualquer momento (os modelos integrados são protegidos).

---

## 📸 Capturas de tela

> **Novas capturas de tela dos recursos em breve** — equipes, gráfico de conhecimento, análises e fluxo de trabalho visual já estão disponíveis; as imagens estão sendo capturadas de uma nova implantação desta semana.

### Características originais

| Tarefa agendada | Arquivos |
| --- | --- |
| [![imagem](https://private-user-images.githubusercontent.com/88510961/576967096-f13f35fd-0538-4515-9902-1cbe9fb99d71.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODQwNDE5OTksIm5iZiI6MTc4NDA0MTY5OSwicGF0aCI6Ii84ODUxMDk2MS81NzY5NjcwOTYtZjEzZjM1ZmQtMDUzOC00NTE1LTk5MDItMWNiZTlmYjk5ZDcxLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA3MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwNzE0VDE1MDgxOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWE1MDM5MDNiMTI3ZWM2OTU4MmUwMzRiOWU1NmQ4YzFkYmZlYjVkYjkzNWRjNmEzM2FkYWZiMWE1YzM2NmFmZWEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.kwbo5ZzDCiMVEOQUZ8PgTMuqDaEtyt5aYwtuW4vSP-0)](https://private-user-images.githubusercontent.com/88510961/576967096-f13f35fd-0538-4515-9902-1cbe9fb99d71.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODQwNDE5OTksIm5iZiI6MTc4NDA0MTY5OSwicGF0aCI6Ii84ODUxMDk2MS81NzY5NjcwOTYtZjEzZjM1ZmQtMDUzOC00NTE1LTk5MDItMWNiZTlmYjk5ZDcxLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA3MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwNzE0VDE1MDgxOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWE1MDM5MDNiMTI3ZWM2OTU4MmUwMzRiOWU1NmQ4YzFkYmZlYjVkYjkzNWRjNmEzM2FkYWZiMWE1YzM2NmFmZWEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.kwbo5ZzDCiMVEOQUZ8PgTMuqDaEtyt5aYwtuW4vSP-0) | [![Arquivos](https://github.com/JPeetz/Hermes-Studio/raw/main/docs/screenshots/files.png)](https://github.com/JPeetz/Hermes-Studio/blob/main/docs/screenshots/files.png) |

| terminal | Memória |
| --- | --- |
| [![terminal](https://github.com/JPeetz/Hermes-Studio/raw/main/docs/screenshots/terminal.png)](https://github.com/JPeetz/Hermes-Studio/blob/main/docs/screenshots/terminal.png) | [![Memória](https://github.com/JPeetz/Hermes-Studio/raw/main/docs/screenshots/memory.png)](https://github.com/JPeetz/Hermes-Studio/blob/main/docs/screenshots/memory.png) |

| Habilidades | Configurações |
| --- | --- |
| [![Habilidades](https://github.com/JPeetz/Hermes-Studio/raw/main/docs/screenshots/skills.png)](https://github.com/JPeetz/Hermes-Studio/blob/main/docs/screenshots/skills.png) | [![imagem](https://private-user-images.githubusercontent.com/88510961/576966607-f62d3378-ad68-4516-81ff-eceb952d2e7d.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODQwNDE5OTksIm5iZiI6MTc4NDA0MTY5OSwicGF0aCI6Ii84ODUxMDk2MS81NzY5NjY2MDctZjYyZDMzNzgtYWQ2OC00NTE2LTgxZmYtZWNlYjk1MmQyZTdkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA3MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwNzE0VDE1MDgxOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWJmYWVhZTIzMWRiMWYyZjY4ZGE5MjNhYzQ5NTkwNDMyNmM2YjJhODI3NmE0NTQwYTk4ZjE4ZDQ0MTk1NWUwYTEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.__d7SYqTKfaV_8P4gBKmqHrLfFkFvDuYiJTkc11anLA)](https://private-user-images.githubusercontent.com/88510961/576966607-f62d3378-ad68-4516-81ff-eceb952d2e7d.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODQwNDE5OTksIm5iZiI6MTc4NDA0MTY5OSwicGF0aCI6Ii84ODUxMDk2MS81NzY5NjY2MDctZjYyZDMzNzgtYWQ2OC00NTE2LTgxZmYtZWNlYjk1MmQyZTdkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA3MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwNzE0VDE1MDgxOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWJmYWVhZTIzMWRiMWYyZjY4ZGE5MjNhYzQ5NTkwNDMyNmM2YjJhODI3NmE0NTQwYTk4ZjE4ZDQ0MTk1NWUwYTEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.__d7SYqTKfaV_8P4gBKmqHrLfFkFvDuYiJTkc11anLA) |

### Novidade no estúdio Hermès

| Recurso | Descrição |
| --- | --- |
| **Equipes Multiagentes** | Crie equipes nomeadas de agentes especializados, distribua tarefas para todos os membros ou para membros específicos e acompanhe as atividades de cada agente em tempo real. |
| **Construtor de Fluxo de Trabalho Visual** | Gráfico de nós SVG para pipelines de agentes — adicione tarefas, conecte arestas entre elas, layout automático via ordenação topológica, detecção de ciclos. |
| **Gráfico de conhecimento interativo** | Gráfico SVG direcionado por força das relações de links wiki da sua memória — amplie, mova, arraste os nós, passe o mouse para destacar os vizinhos. |
| **Análise de uso** | Gráficos de tokens/custos de 14 dias, detalhamento da frequência de uso das ferramentas, mapa de calor do volume de sessões. |
| **Arquivo do histórico da sessão** | Navegue, filtre e reproduza todas as sessões anteriores com metadados de token e custo. |
| **Gerenciador de Tarefas Cron** | Agende tarefas recorrentes do agente com expressões cron, status em tempo real e histórico de execuções. |
| **Inicialização automática do Systemd** | Instalação/desinstalação de serviços com um clique, com painel de status diretamente nas Configurações. |

*📷 Capturas de tela para cada um dos itens acima serão adicionadas esta semana.*

---

## 🚀 Início Rápido

O Hermes Studio funciona com qualquer backend compatível com OpenAI. Se o seu backend também expuser as APIs do gateway Hermes, recursos avançados como sessões, memória, habilidades, aprovações e tarefas serão desbloqueados automaticamente.

### Pré-requisitos

- **Node.js 22+** — [nodejs.org](https://nodejs.org/)
- **Um backend compatível com OpenAI** — local, auto-hospedado ou remoto.
- **Opcional:** Python 3.11 ou superior, caso deseje executar um gateway Hermes localmente.

### Passo 1: Inicie seu backend

Aponte o Hermes Studio para qualquer backend que suporte:

- `POST /v1/chat/completions`
- `GET /v1/models` recomendado

Exemplo de configuração do gateway Hermes:

```
git clone https://github.com/NousResearch/hermes-agent.git
cd hermes-agent
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -e .
hermes setup
hermes --gateway
```

Se você estiver usando outro servidor compatível com OpenAI, basta anotar o URL base dele.

### Passo 2: Instale e execute o Hermes Studio

```
# In a new terminal
git clone https://github.com/JPeetz/Hermes-Studio.git
cd Hermes-Studio
pnpm install
cp .env.example .env
printf '\nHERMES_API_URL=http://127.0.0.1:8642\n' >> .env
pnpm dev                   # Starts on http://localhost:3000
```

> **Verifique:** Abra `http://localhost:3000` e conclua o fluxo de integração. Primeiro, conecte o backend e, em seguida, verifique se o chat funciona. Se o seu gateway expuser as APIs do Hermes, os recursos avançados aparecerão automaticamente.

### Variáveis de ambiente

```
# OpenAI-compatible backend URL
HERMES_API_URL=http://127.0.0.1:8642

# Optional provider keys for Hermes gateway-managed config
ANTHROPIC_API_KEY=your-key-here

# Optional: password-protect the web UI
# HERMES_PASSWORD=your_password

# Optional: override Redis URL (defaults to redis://localhost:6379)
# REDIS_URL=redis://localhost:6379
```

> **Redis is optional.** Hermes Studio automatically tries to connect to a local Redis instance for session persistence. If Redis isn't running, it silently falls back to file-based storage — no configuration needed.

---

## 🧠 Local Models (Ollama, LM Studio, vLLM)

Hermes Studio supports two modes with local models:

### Portable Mode (Easiest)

Point Hermes Studio directly at your local server — no Hermes gateway needed:

```
# Start Ollama
OLLAMA_ORIGINS=* ollama serve

# Start Hermes Studio pointed at Ollama
HERMES_API_URL=http://127.0.0.1:11434 pnpm dev
```

Chat works immediately. Sessions, memory, skills, and jobs show "Not Available" — that's expected in portable mode.

### Enhanced Mode (Full Features)

Route through the Hermes gateway for sessions, memory, skills, jobs, and tools:

**1\. Configure your local model in `~/.hermes/config.yaml`:**

```
provider: ollama
model: qwen2.5:7b # or any model you have pulled
custom_providers:
  - name: ollama
    base_url: http://127.0.0.1:11434/v1
    api_key: ollama
    api_mode: chat_completions
```

**2\. Enable the API server in `~/.hermes/.env`:**

```
API_SERVER_ENABLED=true
```

**3\. Start the gateway and workspace:**

```
hermes gateway run          # Starts on :8642
HERMES_API_URL=http://127.0.0.1:8642 pnpm dev
```

All workspace features unlock automatically — sessions persist, memory saves across chats, skills are available, and the dashboard shows real usage data.

> **Works with any OpenAI-compatible server** — Ollama, LM Studio, vLLM, llama.cpp, LocalAI, etc. Just change the `base_url` and `model` in the config above.

---

## 🐳 Docker Quickstart

The Docker setup runs both the **Hermes Agent gateway** and **Hermes Studio** together.

### Prerequisites

- **Docker**
- **Docker Compose**
- **Anthropic API Key** — [Get one here](https://console.anthropic.com/settings/keys) (required for the agent gateway)

### Step 1: Configure Environment

```
git clone https://github.com/JPeetz/Hermes-Studio.git
cd Hermes-Studio
cp .env.example .env
```

Edit `.env` and add your API key:

```
ANTHROPIC_API_KEY=your-key-here
```

> **Important:** The `hermes-agent` container requires `ANTHROPIC_API_KEY` to function. Without it, the gateway will fail to authenticate.

### Step 2: Start the Services

```
docker compose up
```

This starts two services:

- **hermes-agent** — The AI agent gateway (port 8642)
- **hermes-studio** — The web UI (port 3000)

### Step 3: Access the Workspace

Open `http://localhost:3000` and complete the onboarding.

> **Verify:** Check the Docker logs for `[gateway] Connected to Hermes` — this confirms the workspace successfully connected to the agent.

---

Hermes Studio is a **Progressive Web App (PWA)** — install it for the full native app experience with no browser chrome, keyboard shortcuts, and offline support.

### 🖥️ Desktop (macOS / Windows / Linux)

1. Open Hermes Studio in **Chrome** or **Edge** at `http://localhost:3000`
2. Click the **install icon** (⊕) in the address bar
3. Click **Install** — Hermes Studio opens as a standalone desktop app
4. Pin to Dock / Taskbar for quick access

> **macOS users:** After installing, you can also add it to your Launchpad.

### 📱 iPhone / iPad (iOS Safari)

1. Open Hermes Studio in **Safari** on your iPhone
2. Tap the **Share** button (□↑)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add** — the Hermes Studio icon appears on your home screen
5. Launch from home screen for the full native app experience

### 🤖 Android

1. Open Hermes Studio in **Chrome** on your Android device
2. Tap the **three-dot menu** (⋮) → **"Add to Home screen"**
3. Tap **Add** — Hermes Studio is now a native-feeling app on your device

---

## 📡 Mobile Access via Tailscale

Access Hermes Studio from anywhere on your devices — no port forwarding, no VPN complexity.

### Setup

1. **Install Tailscale** on your Mac and mobile device:
	- Mac: [tailscale.com/download](https://tailscale.com/download)
		- iPhone/Android: Search "Tailscale" in the App Store / Play Store
2. **Sign in** to the same Tailscale account on both devices
3. **Find your Mac's Tailscale IP:**
	```
	tailscale ip -4
	# Example output: 100.x.x.x
	```
4. **Open Hermes Studio on your phone:**
	```
	http://100.x.x.x:3000
	```
5. **Add to Home Screen** using the steps above for the full app experience

> 💡 Tailscale works over any network — home wifi, mobile data, even across countries. Your traffic stays end-to-end encrypted.

---

## 🖥️ Native Desktop App

> **Status: Planned** — A native Electron-based desktop app is on the roadmap.

The desktop app will offer:

- Native window management and tray icon
- System notifications for agent events and mission completions
- Auto-launch on startup
- Deep OS integration (macOS menu bar, Windows taskbar)

**In the meantime:** Install Hermes Studio as a PWA (see above) for a near-native desktop experience — it works great.

---

## ☁️ Cloud & Hosted Setup

> **Status: Planned**

A fully managed cloud version of Hermes Studio is planned:

- **One-click deploy** — No self-hosting required
- **Multi-device sync** — Access your agents from any device
- **Team collaboration** — Shared mission control for your whole team
- **Automatic updates** — Always on the latest version

Features pending cloud infrastructure:

- Cross-device session sync
- Team shared memory and workspaces
- Cloud-hosted backend with managed uptime
- Webhook integrations and external triggers

---

## ✨ Feature Details

### 💬 Chat

- Real-time SSE streaming with tool call rendering
- Multi-session management with full history
- Markdown + syntax highlighting
- Chronological message ordering with merge dedup
- Inspector panel for session activity, memory, and skills

### 🧠 Memory

- Browse and edit agent memory files
- Search across memory entries
- Markdown preview with live editing

### 🧩 Skills

- Browse 2,000+ skills from the registry
- View skill details, categories, and documentation
- Install, uninstall, and toggle skills directly from the browser
- clawhub CLI fallback with inline install instructions when gateway doesn't support native install
- Loading spinners and success toasts on all skill actions

### ✅ Execution Approvals

- Real-time approval card when agent requests dangerous commands
- Expand full command and context before deciding
- Approve once, approve for session, or always-allow with a single click
- Deny to block the action immediately
- Resolved receipt shown inline in chat after every decision
- Global badge in sidebar when approvals are pending on another screen
- Dual-strategy resolution: native gateway endpoint → chat command fallback

### ⏰ Cron Job Manager

The only browser-based UI for scheduling Hermes agent tasks. No other Hermes or Claude web interface has this.

- View all scheduled tasks with live status indicators (active, paused, error)
- Create jobs: natural-language prompt + schedule preset or custom cron expression
- Delivery channels: route output to Telegram, Discord, Slack, or Signal
- Assign skills and set repeat limits per job
- Edit any field on a live job without recreating it
- Pause and resume without losing configuration
- Trigger immediately on demand
- Expand any job card to read recent run output inline
- Auto-refreshes every 30 seconds

### 👥 Multi-Agent Crews

Coordinate multiple AI agents working in parallel toward a shared goal — all from a single UI.

- **Create crews** — give each crew a name, a goal, and up to 8 agent members
- **Persona agents** — pick from specialised personas (Roger / Frontend, Sally / Backend, Ada / QA, Kai / General, and more) each with a role label, emoji, and colour
- **Per-member model** — assign any model to any agent independently
- **Dispatch tasks** — send a prompt to all agents simultaneously or target a specific member
- **Live activity feed** — SSE events from all crew members stream into a unified timeline in real time; tool calls, messages, and errors are colour-coded
- **Status indicators** — idle / running / done / error shown with animated pulse on each member card
- **"Open chat"** link on every member card navigates directly to that agent's chat session
- **Persistence** — crews and their member status survive server restarts (file-backed crew store)

### 🔀 Visual Workflow Builder

The Crew detail screen's **Workflow tab** is a full DAG editor for building and running structured task pipelines.

- **SVG canvas** — pure-SVG rendering; no external graph library required; pan, zoom (0.2×–4×), and node drag with pointer capture
- **Add tasks** — each task has a label, a full prompt sent to the agent, and an assignee (any crew member or "all agents")
- **Draw dependencies** — activate Connect mode, click a source node then a target to draw a bezier edge with arrowhead; a dependency means the target task only runs after the source completes
- **Cycle detection** — creating a cycle shows an immediate error and discards the edge; server-side validation also rejects cycles on save
- **Auto Layout** — Kahn's BFS topological sort lays nodes out in parallel columns, left-to-right, with vertical centering per layer
- **Persistent** — workflow is saved per crew in `.runtime/workflows.json` (file-backed, same pattern as the crew store)
- **Run Workflow** — click Run to execute tasks in topological order: root tasks dispatch in parallel; each layer waits for all its tasks to complete (via SSE `run_end` events) before the next layer dispatches
- **Live node status** — each node shows a colour-coded tinted border and badge: idle → running (green pulse) → done (indigo) → error (red); active edges also highlight in green
- **Edge deletion** — click any edge (wide invisible hit area) to remove the dependency
- **Task edit panel** — click a node to open a right-side panel showing full prompt, assignee, dependencies, live status; double-click to edit inline

### 🗂️ Profile-Scoped Workspaces

Every crew member can be assigned a named profile that scopes their file system access to an isolated directory.

- Each profile resolves to `~/.hermes/profiles/<name>/` — auto-created on first use
- The File Explorer sidebar shows the profile's workspace root, not the global workspace
- All file operations (read, write, upload, delete, rename, mkdir) are profile-aware
- Path traversal is prevented server-side — profile names are validated, `../` is rejected
- The active profile drives the file explorer in the main chat screen via `useActiveProfile` hook

### 🕸️ Interactive Knowledge Graph

The Memory screen's graph view is now a fully interactive force-directed canvas — not a static circle.

- **Force-directed layout** — nodes spread naturally; hubs cluster, orphans spread to the edges; computed synchronously on load (280 iterations of Coulomb repulsion + Hooke spring attraction)
- **Node sizing by degree** — highly-connected hubs appear larger; isolated nodes stay small
- **Node type colours** — guide, project, reference, concept, note each get a distinct palette; legend shown only when typed nodes exist in the data
- **Hover highlights** — hover any node to illuminate its direct connections and dim everything else to 22% opacity; a glow ring marks the hovered node
- **Zoom** — mouse wheel (non-passive, doesn't scroll the page) + +/− buttons; 0.25×–4× range
- **Pan** — drag the background to move the viewport
- **Node drag** — drag individual nodes to reposition them; position is pinned for the session
- **Stats counter** — `N nodes · M edges` shown in the bottom-right corner

### 🔐 Permissions & Toolsets

- Approvals mode selector (auto / always / never)
- Approval timeout control
- Command allowlist editor — tag-input for shell commands that bypass Tirith
- Toolset add/remove
- Website blocklist toggle + domain editor
- Code execution limits
- Reasoning effort selector
- All settings persist live via the config API

### 🔗 Integrations

- skillsmp.com API key for skill marketplace access
- Tokens de plataformas de bate-papo — defina tokens de bots do Telegram, Discord, Slack e Signal diretamente da interface do usuário, sem precisar editar.`.env`

### 📁 Arquivos

- Navegador de arquivos de espaço de trabalho completo
- Navegue pelos diretórios, visualize e edite arquivos.
- Integração do editor Monaco

### 💻 Terminal

- Terminal PTY completo com suporte multiplataforma
- Sessões de shell persistentes
- Acesso direto ao espaço de trabalho

### 🎨 Temas

- 8 temas: Oficial, Clássico, Cinza, Monocromático — cada um com variantes claras e escuras.
- O tema persiste ao longo das sessões.
- Suporte completo ao modo escuro em dispositivos móveis

### 💾 Persistência da Sessão

- As sessões de bate-papo e o histórico de mensagens permanecem ativos após reinicializações do servidor.
- Os tokens de autenticação persistem mesmo após reinicializações — sem necessidade de novo login.
- O estado de desduplicação de execuções ativas persiste — nenhuma execução duplicada é executada ao reiniciar.
- O backend Redis se conecta automaticamente `localhost:6379` na inicialização; caso o Redis não esteja disponível, ele utiliza o armazenamento de arquivos como alternativa.
- Substitua por `REDIS_URL` um Redis remoto ou não padrão.

### 🔒 Segurança

- Middleware de autenticação em todas as rotas da API
- Cabeçalhos CSP via meta tags
- Prevenção de travessia de diretórios em rotas de desinstalação de arquivos, memória e habilidades.
- Limitação de taxa em endpoints
- Proteção opcional por senha para a interface web.
- Aprovações de execução — comandos perigosos exigem aprovação explícita do usuário.

---

## 🔧 Solução de problemas

### "O espaço de trabalho carrega, mas o chat não funciona"

O espaço de trabalho detecta automaticamente as capacidades do seu gateway na inicialização. Verifique seu terminal em busca de uma linha como:

```
[gateway] http://127.0.0.1:8642 available: health, models; missing: sessions, skills, memory, config, jobs
[gateway] Missing Hermes APIs detected. Update Hermes: cd hermes-agent && git pull && pip install -e . && hermes --gateway
```

**Correção:** Certifique-se de ter a versão mais recente do Hermes Agent com suporte estendido para gateways.

```
git clone https://github.com/NousResearch/hermes-agent.git
cd hermes-agent && pip install -e . && hermes --gateway
```

### "Conexão recusada" ou espaço de trabalho travado durante o carregamento

Seu gateway Hermes não está em execução. Inicie-o:

```
cd hermes-agent
source .venv/bin/activate
hermes gateway run
```

### Ollama: o chat retorna vazio ou o modelo mostra "Offline"

Certifique-se de que seu arquivo `~/.hermes/config.yaml` tenha a `custom_providers` seção e `API_SERVER_ENABLED=true` esteja em `~/.hermes/.env`. Veja [Modelos Locais](#-local-models-ollama-lm-studio-vllm) acima.

Certifique-se também de que o Ollama esteja em execução com o CORS ativado:

```
OLLAMA_ORIGINS=* ollama serve
```

Use `http://127.0.0.1:11434/v1` (não `localhost`) como URL base.

Verificar: `curl http://localhost:8642/health` deve retornar `{"status": "ok"}`.

### "Usando NousResearch/hermes-agent upstream"

O hermes-agent upstream suporta chat básico via `hermes --gateway`, mas versões mais antigas podem não incluir endpoints estendidos (sessões, memória, habilidades, configuração). O Hermes Studio funcionará em **modo portátil** com chat básico. Para obter todos os recursos, certifique-se de ter a versão mais recente:`cd hermes-agent && git pull && pip install -e .`

### Docker: "Não autorizado" ou "Conexão recusada" para hermes-agent

Se estiver usando o Docker Compose e recebendo erros de autenticação:

1. **Verifique se sua chave de API está configurada:**
	```
	cat .env | grep ANTHROPIC_API_KEY
	# Should show: ANTHROPIC_API_KEY=sk-ant-...
	```
2. **Visualize os registros do contêiner do agente:**
	```
	docker compose logs hermes-agent
	```
	Procure por erros de inicialização ou avisos de chave de API ausente.
3. **Verifique o ponto de extremidade de integridade do agente:**
	```
	curl http://localhost:8642/health
	# Should return: {"status": "ok"}
	```
4. **Reinicie com novos contêineres:**
	```
	docker compose down
	docker compose up --build
	```
5. **Verifique os registros do espaço de trabalho para obter o status do gateway:**
	```
	docker compose logs hermes-studio
	```
	Procure por: `[gateway] http://hermes-agent:8642 mode=...`— se aparecer `mode=disconnected`, o agente não está funcionando corretamente.

### Docker: "comando webapi do Hermes não encontrado"

O `hermes webapi` comando mencionado em documentos antigos não existe. O comando correto é:

```
hermes --gateway   # Starts the FastAPI gateway server
```

A configuração do Docker usa `hermes --gateway` automaticamente — nenhuma ação é necessária se estiver usando `docker compose up`.

---

## 🗑️ Desinstalar

Execute o script incluído a partir da pasta do projeto:

```
bash scripts/uninstall.sh
```

Isto irá:

1. Pare e desative o serviço systemd (se estiver instalado).
2. Encerre qualquer `server-entry.js` processo em execução.
3. Solicite a confirmação e, em seguida, exclua a pasta do projeto (incluindo `.runtime/` os dados).

**Locais de dados removidos com a pasta do projeto:**

| Arquivo | Conteúdo |
| --- | --- |
| `.runtime/events.db` | Banco de dados SQLite para análise |
| `.runtime/costs.json` | Histórico de custos do token |
| `.runtime/crews.json` | Tripulações de agentes salvas |
| `.runtime/workflows.json` | Fluxos de trabalho da equipe |
| `.runtime/agent-definitions.json` | Definições de agentes personalizados |
| `.runtime/local-sessions.json` | Metadados da sessão |
| `.runtime/templates.json` | Modelos de mensagens |

**Etapas manuais após o script:**

- **Armazenamento local do navegador** — abra Ferramentas de desenvolvedor → Aplicativo → Armazenamento → Armazenamento local → limpe a entrada para `http://localhost:<port>`
- **`~/.hermes/`** — Este item pertence ao Hermes Agent, não ao Hermes Studio. Não o exclua a menos que também esteja desinstalando o Hermes Agent.
- **Redis** — se você usou proteção por senha, os tokens de sessão no Redis expirarão naturalmente (ou serão `redis-cli FLUSHDB` limpos imediatamente).

---

[![Logotipo do Hermes Studio — painel de orquestração de agentes de IA](https://private-user-images.githubusercontent.com/88510961/576920256-2b24e3bc-fb37-4fd9-922a-641113e4e3a4.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODQwNDE5OTksIm5iZiI6MTc4NDA0MTY5OSwicGF0aCI6Ii84ODUxMDk2MS81NzY5MjAyNTYtMmIyNGUzYmMtZmIzNy00ZmQ5LTkyMmEtNjQxMTEzZTRlM2E0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA3MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwNzE0VDE1MDgxOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWM1NTYwMDdlMTY1NDk0MTE5ZjZiMTIwM2VkMDgwZDI3Mzk1ZTgzMzFhMDQwOWRiNmY5Yjg4YTQ2ODI5OTlmMmQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.lk4iNT8jWytTKnCgT0aUQ7RgE3TyvPmjJpVy1NdGS5A)](https://private-user-images.githubusercontent.com/88510961/576920256-2b24e3bc-fb37-4fd9-922a-641113e4e3a4.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODQwNDE5OTksIm5iZiI6MTc4NDA0MTY5OSwicGF0aCI6Ii84ODUxMDk2MS81NzY5MjAyNTYtMmIyNGUzYmMtZmIzNy00ZmQ5LTkyMmEtNjQxMTEzZTRlM2E0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA3MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwNzE0VDE1MDgxOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWM1NTYwMDdlMTY1NDk0MTE5ZjZiMTIwM2VkMDgwZDI3Mzk1ZTgzMzFhMDQwOWRiNmY5Yjg4YTQ2ODI5OTlmMmQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.lk4iNT8jWytTKnCgT0aUQ7RgE3TyvPmjJpVy1NdGS5A)

## 🗺️ Roteiro

| Recurso | Status |
| --- | --- |
| Bate-papo + Transmissão SSE | ✅ Enviado |
| Arquivos + Terminal | ✅ Enviado |
| Navegador de memória | ✅ Enviado |
| Navegador de habilidades | ✅ Enviado |
| PWA móvel + Tailscale | ✅ Enviado |
| Sistema de 8 temas | ✅ Enviado |
| Interface do usuário de aprovações de execução | ✅ Versão 1.1.0 lançada |
| Instalação/Alternância de Habilidades | ✅ Versão 1.2.0 lançada |
| Interface do usuário do gerenciador de tarefas cron | ✅ Versão 1.3.0 lançada |
| Configurações de permissões e conjuntos de ferramentas | ✅ Versão 1.4.0 lançada |
| Persistência de sessão (Redis) | ✅ Versão 1.5.0 lançada |
| Orquestração Multiagente (Equipes) | ✅ Versão 1.6.0 lançada |
| Espaços de trabalho com escopo definido por perfil | ✅ Versão 1.6.0 lançada |
| Gráfico de conhecimento interativo | ✅ Versão 1.6.0 lançada |
| Painel de Métricas da Tripulação/Agente | ✅ Versão 1.7.0 lançada |
| Construtor de fluxo de trabalho visual (editor DAG) | ✅ Versão 1.8.0 lançada |
| Modelos de tripulação | ✅ Versão 1.9.0 lançada |
| Controle de custos por equipe | ✅ Versão 1.10.0 lançada |
| Protocolo do Cliente MCP | ✅ Versão 1.11.0 lançada |
| Biblioteca de agentes (agentes personalizados) | ✅ Versão 1.12.0 lançada |
| Registro de auditoria | ✅ Versão 1.13.0 lançada |
| Conjunto de testes + crachás de CI | ✅ Versão 1.15.0 lançada |
| Tripulação de Clones | ✅ Versão 1.14.0 lançada |
| Assistente de Configuração | ✅ Versão 1.16.0 lançada |
| Compatibilidade com Hermes v0.8.0 + v0.9.0 | ✅ Versão 1.17.0 lançada |
| Sistema de projeto v1.0 | ✅ Versão 1.16.0 lançada |
| Paleta de comandos (Ctrl+K) | ✅ Versão 1.18.0 lançada |
| Painel de Saúde do Sistema | ✅ Versão 1.18.0 lançada |
| Gráfico de séries temporais de utilização de tokens | ✅ Versão 1.18.0 lançada |
| Análises do State.db | ✅ Versão 1.18.0 lançada |
| Editor de Arquivos de Identidade | ✅ Versão 1.18.0 lançada |
| Visualizador de Padrões e Correções | ✅ Versão 1.18.0 lançada |
| Arquivo do histórico da sessão | ✅ Versão 1.18.0 lançada |
| Inicialização automática do Systemd | ✅ Versão 1.18.0 lançada |
| Condutor V2 (orquestração de gateway) | ✅ Versão 1.20.0 lançada |
| Painel de Operações | ✅ Versão 1.19.0 lançada |
| Quadro de Tarefas/Kanban | ✅ Versão 1.19.0 lançada |
| Aplicativo nativo para desktop (Electron) | 🔜 Planejado |
| Versão em nuvem/hospedada | 🔜 Planejado |

---

## ⭐ História das Estrelas

## 💛 Apoie o projeto

O Hermes Studio é gratuito e de código aberto. Se ele está economizando seu tempo e otimizando seu fluxo de trabalho, considere apoiar o desenvolvimento:

**ETH:** `0xdfa8ac0f37d1129af72d0c4c6c0dff22e7a816b7`

Toda contribuição ajuda a manter este projeto em andamento. Obrigado 🙏

---

## 🤝 Contribuindo

Contribuições (PRs) são bem-vindas! Consulte o [arquivo CONTRIBUTING.md](https://github.com/JPeetz/Hermes-Studio/blob/main/CONTRIBUTING.md) para obter as diretrizes.

- Correções de bugs → abra um PR diretamente
- Novos recursos → abra uma solicitação primeiro para discutir
- Questões de segurança → consulte [SECURITY.md](https://github.com/JPeetz/Hermes-Studio/blob/main/SECURITY.md) para obter informações sobre divulgação responsável.

---

[![Rodapé do Hermes Studio — interface de usuário web auto-hospedada para o Hermes Agent.](https://private-user-images.githubusercontent.com/88510961/576919610-2e86734f-b189-49b7-9f4d-1048fd75dbd5.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODQwNDE5OTksIm5iZiI6MTc4NDA0MTY5OSwicGF0aCI6Ii84ODUxMDk2MS81NzY5MTk2MTAtMmU4NjczNGYtYjE4OS00OWI3LTlmNGQtMTA0OGZkNzVkYmQ1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA3MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwNzE0VDE1MDgxOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTBmM2NkMTBjM2M4NTRhMTE5OTkyYjlkMmNkMzIxNGEwN2E0NDk4M2Y2MTI1NGYyM2RlMTU4N2I0ZWFkNWM2NGQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.rDeZoptRoPfO_W-nyfBe_LnOuFe_toVB1sTGNCNl6Ec)](https://private-user-images.githubusercontent.com/88510961/576919610-2e86734f-b189-49b7-9f4d-1048fd75dbd5.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODQwNDE5OTksIm5iZiI6MTc4NDA0MTY5OSwicGF0aCI6Ii84ODUxMDk2MS81NzY5MTk2MTAtMmU4NjczNGYtYjE4OS00OWI3LTlmNGQtMTA0OGZkNzVkYmQ1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA3MTQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwNzE0VDE1MDgxOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTBmM2NkMTBjM2M4NTRhMTE5OTkyYjlkMmNkMzIxNGEwN2E0NDk4M2Y2MTI1NGYyM2RlMTU4N2I0ZWFkNWM2NGQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.rDeZoptRoPfO_W-nyfBe_LnOuFe_toVB1sTGNCNl6Ec)

## 📄 Licença

MIT — consulte [o arquivo LICENSE](https://github.com/JPeetz/Hermes-Studio/blob/main/LICENSE) para obter detalhes.

---

## 🙏 Agradecimentos

O Hermes Studio é baseado no [hermes-workspace](https://github.com/outsourc-e/hermes-workspace), desenvolvido por [@outsourc-e e](https://github.com/outsourc-e) distribuído sob a licença MIT.

---

<sub><font dir="auto"><font dir="auto">Construído com ⚡ por</font> </font><a href="https://github.com/JPeetz"><font dir="auto"><font dir="auto">@JPeetz</font></font></a> <font dir="auto"><font dir="auto">— baseado no</font> </font><a href="https://github.com/outsourc-e/hermes-workspace"><font dir="auto"><font dir="auto">espaço de trabalho Hermes</font></font></a> <font dir="auto"><font dir="auto">por @outsourc-e</font></font></sub>