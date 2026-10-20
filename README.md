# 💸 Fine- App de Organização de Finanças Pessoais com Vibe Coding

App para pessoas com zero ou pouca experiência com tecnologia ou ferramentas de I.A. No estilo "conversa amigável".

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# PRD - Organizador de Finanças Pessoais Conversacional
## Visão Geral
Criar uma aplicação de organização de finanças pessoais baseada em conversação, permitindo que o usuário registre receitas, despesas, metas e consulte sua situação financeira por meio de mensagens de texto ou voz.
O sistema deve agir como um "Agente Financeiro Pessoal", oferecendo uma experiência simples, amigável e educativa, semelhante a uma conversa entre amigos.
O objetivo principal é eliminar a complexidade dos aplicativos financeiros tradicionais e aumentar a frequência de uso através de uma interface conversacional intuitiva.
---
# Problema
Muitas pessoas desejam controlar suas finanças, mas abandonam rapidamente os aplicativos existentes porque:
- Exigem preenchimento manual excessivo.
- Possuem interfaces complexas.
- Utilizam termos financeiros difíceis.
- Não oferecem acompanhamento personalizado.
- Não incentivam a criação do hábito financeiro.
Como consequência, os usuários perdem visibilidade sobre seus gastos e têm dificuldade em economizar ou atingir metas financeiras.
---
# Objetivo do Produto
Permitir que qualquer pessoa organize sua vida financeira apenas conversando com o aplicativo de forma natural.
Exemplos:
"Gastei R$ 25 com lanche."
"Recebi meu salário de R$ 3.000."
"Quanto eu já gastei este mês?"
"Estou guardando dinheiro para uma viagem."
O sistema deverá interpretar automaticamente as informações, registrar os dados e fornecer orientações financeiras personalizadas.
---
# Público-Alvo
### Primário
- Pessoas iniciando sua organização financeira.
- Usuários sem experiência com planilhas.
- Pessoas com baixa familiaridade tecnológica.
- Jovens adultos iniciando controle financeiro.
### Secundário
- Pessoas que já utilizam apps financeiros, mas buscam algo mais simples.
- Usuários interessados em usar Inteligência Artificial para auxiliar no planejamento financeiro.
---
# Proposta de Valor
Transformar o controle financeiro em uma conversa simples, amigável e sem burocracia.
Enquanto aplicativos tradicionais exigem formulários e múltiplas etapas, o usuário apenas conversa com o sistema.
---
# Personalidade do Agente Financeiro
O Agente Financeiro deve atuar como um amigo organizado e confiável.
Características:
- Amigável
- Motivador
- Educativo
- Empático
- Não julgador
- Objetivo
- Linguagem acessível
Evitar:
- Linguagem excessivamente técnica
- Críticas ao usuário
- Tom formal ou corporativo
Exemplo:
Usuário:
"Gastei R$ 50 com pizza."
Resposta:
"Perfeito 😊. Registrei R$ 50 em Alimentação. Este foi seu terceiro gasto com delivery nesta semana."
---
# Design System
## Estilo Visual
Aplicação moderna, amigável e minimalista.
Inspirada em:
- Nubank
- Copilot
- Duolingo
- Notion
---
## Paleta de Cores
Cor Primária:
#4F46E5
Cor Secundária:
#10B981
Cor de Destaque:
#F59E0B
Fundo Claro:
#F8FAFC
Texto Principal:
#1E293B
Texto Secundário:
#64748B
Erro:
#EF4444
Sucesso:
#22C55E
---
## Tipografia
Fonte Principal:
Inter
Fonte Secundária:
Poppins
---
## Componentes
- Cards arredondados
- Botões grandes
- Navegação simplificada
- Interface acessível
- Ícones intuitivos
- Dashboard limpo
- Chat semelhante a aplicativos de mensagens
---
## Acessibilidade
- Contraste adequado
- Fonte escalável
- Botões com área de toque ampliada
- Linguagem simples
- Compatibilidade com modo escuro
---
# Funcionalidades do MVP
## 1. Registro de Transações por Chat
Permitir registro de receitas e despesas através de linguagem natural.
Exemplos:
"Gastei R$ 20 em doces."
"Gastei R$ 60 com gasolina."
"Recebi R$ 1.500 de um freela."
O sistema deve extrair:
- Tipo
- Valor
- Categoria
- Descrição
- Data
---
## 2. Classificação Automática
O sistema deverá categorizar automaticamente as transações.
Categorias iniciais:
- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Contas
- Investimentos
- Outros
O usuário poderá alterar a categoria manualmente.
---
## 3. Registro por Voz
Permitir que o usuário fale naturalmente.
Fluxo:
Voz → Transcrição → Interpretação → Registro
---
## 4. Metas Financeiras
Permitir criação e acompanhamento de metas.
Exemplos:
- Economizar R$ 500 por mês
- Comprar um celular
- Fazer uma viagem
- Montar reserva de emergência
Informações:
- Nome da meta
- Valor objetivo
- Valor acumulado
- Data opcional
---
## 5. Dashboard Financeiro
Apresentar visão simples da situação financeira.
Indicadores:
- Saldo atual
- Total de receitas
- Total de despesas
- Economia do mês
- Progresso das metas
---
## 6. Insights Inteligentes
O Agente Financeiro deverá gerar recomendações automáticas.
Exemplos:
"Você gastou 20% mais com alimentação neste mês."
"Reduzindo dois pedidos por semana você pode economizar aproximadamente R$ 120 por mês."
"Você está próximo da sua meta de reserva de emergência."
---
## 7. Histórico de Conversas
Armazenar interações para dar contexto às conversas futuras.
Exemplos:
"Quanto gastei com alimentação este mês?"
"Quanto economizei desde janeiro?"
---
# Fluxos Principais
## Fluxo 1 - Registrar Despesa
Usuário:
"Gastei R$ 35 na farmácia."
Sistema:
- Detecta valor
- Classifica como Saúde
- Registra operação
Resposta:
"Perfeito 😊. Registrei R$ 35 em Saúde."
---
## Fluxo 2 - Registrar Receita
Usuário:
"Recebi meu salário de R$ 3.500."
Sistema:
- Identifica receita
- Registra entrada
Resposta:
"Ótimo! Recebi uma entrada de R$ 3.500 na sua conta."
---
## Fluxo 3 - Consulta Financeira
Usuário:
"Quanto já gastei este mês?"
Sistema:
- Calcula despesas
Resposta:
"Neste mês você registrou R$ 1.245 em despesas."
---
## Fluxo 4 - Criar Meta
Usuário:
"Quero guardar R$ 5.000 para uma viagem."
Sistema:
- Cria meta
Resposta:
"Meta criada 🎯. Vamos acompanhar sua evolução rumo aos R$ 5.000."
---
# Estrutura de Dados
## Usuário
id
nome
email
data_criacao
objetivo_financeiro
---
## Transação
id
usuario_id
tipo
valor
categoria
descricao
data_transacao
data_criacao
---
## Meta
id
usuario_id
nome
valor_objetivo
valor_atual
data_limite
status
---
## Conversa
id
usuario_id
mensagem
resposta
data
---
# Telas do MVP
## Tela 1 - Boas-vindas
Objetivo:
Conhecer o usuário.
Perguntas:
- Como gostaria de ser chamado?
- Qual seu principal objetivo financeiro?
---
## Tela 2 - Chat Principal
Funcionalidades:
- Texto
- Voz
- Registro financeiro
- Consultas
- Recomendações
---
## Tela 3 - Dashboard
Exibir:
- Saldo
- Receitas
- Despesas
- Metas
---
## Tela 4 - Metas
Criar, editar e acompanhar metas.
---
## Tela 5 - Relatórios
Visualizações simples:
- Gastos por categoria
- Evolução mensal
- Comparação entre períodos
---
# Métricas de Sucesso
## Produto
- Usuários ativos semanais
- Retenção de 7 dias
- Retenção de 30 dias
---
## Engajamento
- Quantidade de transações registradas
- Número de metas criadas
- Conversas por usuário
---
## Validação da Hipótese
Hipótese:
"Pessoas registram mais gastos quando utilizam conversa natural em vez de formulários."
Indicadores:
- Mais de 70% dos registros realizados via chat
- Crescimento do número médio de registros por usuário
- Retenção superior à observada em aplicativos financeiros tradicionais
---
# Requisitos Não Funcionais
- Interface responsiva
- Mobile First
- Tema claro e escuro
- Respostas rápidas (< 3 segundos)
- Segurança dos dados
- LGPD compliance
- Criptografia de dados sensíveis
---
# Futuras Versões
- Integração bancária (Open Finance)
- Importação automática de extratos
- Planejamento financeiro avançado
- Detecção de gastos recorrentes
- Alertas inteligentes
- Planejamento de investimentos
- Compartilhamento financeiro familiar
```
## Capturas de tela do app

<img width="1477" height="792" alt="captura app fine 3" src="https://github.com/user-attachments/assets/31b337ec-eca0-44e9-9005-83e3f29e4137" />

> Interações com o chat via texto e voz ("achei cem reais na rua") e criação de metas pelo chat.

<img width="1606" height="812" alt="captura app fine 1" src="https://github.com/user-attachments/assets/77bf8c29-a88c-4f59-a871-793249bf3015" />

> Aba "Seu Painel"

<img width="1482" height="782" alt="captura app fine 2" src="https://github.com/user-attachments/assets/69be9969-c3a2-4ad4-b489-21b31014bbb3" />

> Aba Metas

https://github.com/user-attachments/assets/fa9a1b40-3703-436a-98d9-bc7dc5d651ff

> Vídeo da aba "Relatórios", mostrando as interações com gráficos e auto classificação dos gastos.

## Resumo
Nome: Fine - O Lovable criou o app com o nome "Fino", alterei para "Fine" por ter semelhança com a palavra finance, do inglês.
Cor: Fugindo do tom padrão de verde associado ao dinheiro, este tom de azul possui um equilíbrio para transmitir clareza e conforto para o usuário para que ele sinta o controle de suas finanças.
Interação: Texto e voz operando normalmente, o agente analisa e classifica os gastos automaticamente. Na captura anexada acima escrevi "gastei 45 no cinema e 25 de gasolina", então o assistente identificou cinema como lazer e gasolina como transporte.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
