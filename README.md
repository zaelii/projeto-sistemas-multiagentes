# ![IMOBIBOT](logo.png)
> Assistente Virtual Inteligente para Atendimento Imobiliário no WhatsApp

## 👨‍🎓 Autor
- **Disraeli Michelangelo Rafael da Costa Filho**

## 💡 Ideia Principal
O **Imobibot** é um assistente virtual inteligente para atendimento de clientes de uma imobiliária via WhatsApp.  
Ele utiliza a plataforma de automação **n8n** integrada com APIs para gerenciar desde o primeiro contato até o agendamento de visitas.  
O sistema pode responder dúvidas automaticamente, enviar catálogos de imóveis, registrar preferências do cliente, manter histórico de interações e agendar visitas com integração ao Google Agenda.  
Com inteligência artificial, o Imobibot aprende as preferências dos usuários para recomendar imóveis de forma personalizada, tornando o atendimento mais rápido, prático e eficiente.

## 🎯 Objetivos
- Facilitar a comunicação entre imobiliária e clientes via WhatsApp.  
- Automatizar respostas a dúvidas frequentes sem necessidade de atendente humano.  
- Agendar visitas e enviar catálogos de forma automática.  
- Registrar e organizar dados dos clientes (preferências, histórico, contatos).  
- Oferecer recomendações personalizadas com base no perfil do cliente.  
- Melhorar a experiência do usuário e aumentar as taxas de conversão.  
- Garantir atendimento 24/7.

## 👥 Público-Alvo
- Pessoas que buscam um novo lar (aluguel ou compra).  
- Jovens, adultos e idosos que procuram apartamento, casa ou mansão.  
- Pessoas que buscam vender imóveis.  
- Usuários com pouca familiaridade com tecnologia, que preferem interações simples pelo WhatsApp.

## 🤖 Agentes Envolvidos
- **Agente de Atendimento**: recebe mensagens, interpreta e responde dúvidas sobre imóveis.  
- **Agente de Recomendação**: utiliza IA para sugerir imóveis com base no perfil e preferências do cliente.  
- **Agente de Agendamento**: interage com o Google Agenda para marcar visitas.  
- **Agente de Cadastro de Imóveis**: registra imóveis fornecidos pela imobiliária ou vendedores no catálogo.  
- **Agente de Follow-up**: envia mensagens automáticas de acompanhamento após visitas ou interações.

## 🧱 Tecnologias Utilizadas
- **n8n**: automação e orquestração de fluxos (escolhido por sua flexibilidade e integração com várias APIs).  
- **Evolution API**: integração com WhatsApp, permitindo envio e recebimento de mensagens em tempo real.  
- **Redis**: gerenciamento rápido de dados temporários e estados de conversas.  
- **Google Docs**: banco de dados inicial para catálogo de imóveis.  
- **Google Agenda**: agendamento de visitas.  
- **Hospedagem em nuvem (Hostinger)**: execução contínua dos serviços.  
- **OpenAI API**: processamento de linguagem natural para entender e responder clientes.

## 📦 Entradas e Saídas Esperadas
**Entradas:**
- Mensagens via WhatsApp.
- Preferências do cliente (tipo de imóvel, localização, faixa de preço).
- Catálogo atualizado de imóveis.
- Horários disponíveis para agendamento.

**Saídas:**
- Lista de imóveis compatíveis com o perfil do cliente.
- Confirmação de agendamento.
- PDF ou link para catálogo de imóveis.
- Mensagens automáticas de acompanhamento.

## 🔁 Interação entre os Agentes
1. O **Agente de Atendimento** recebe a mensagem e identifica a necessidade.  
2. Caso haja pedido de imóveis, o **Agente de Recomendação** consulta o banco de dados e retorna opções.  
3. Se houver interesse, o **Agente de Agendamento** agenda a visita.  
4. O **Agente de Follow-up** envia lembretes e mensagens pós-visita.  
5. O **Agente de Cadastro de Imóveis** atualiza constantemente o catálogo.

## 💰 Custos do Projeto
- **Tokens para ChatGPT (OpenAI API):** R$ 52,00  
- **Manychat (número adicional, não utilizado):** R$ 4,00  
- **VPS Hostinger (plano 2 anos):** R$ 800,00 (parcelado em R$ 38,99/mês)  

## 🗂️ Organização e Planejamento do Projeto
O progresso do projeto será gerenciado no **GitHub Projects**, com:
- Tarefas pendentes.
- Tarefas em andamento.
- Tarefas concluídas.

## 📌 Status Inicial do Projeto
- [x] Ideia discutida e validada com o professor.  
- [x] Estrutura básica do repositório criada.  
- [ ] Quadro no GitHub Projects criado.  
- [ ] Primeiras tarefas definidas e atribuídas.

## 📄 Documentação Futura
- Diagramas de arquitetura.  
- Relatórios de progresso.  
- Scripts de testes.  
- Resultados e conclusões.

## 👨‍🏫 Acompanhamento pelo Professor
Usuário `igorbarcosta` adicionado como colaborador no repositório.
