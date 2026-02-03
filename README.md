# 💸 App de Organização de Finanças Pessoais da Flávia Sales com Vibe Coding

PRD refinado no Copilot WEB

""
## PRD – Aplicativo de Organização de Finanças Pessoais
## Contexto
Criar um aplicativo de organização financeira pessoal que funcione por meio de conversas em linguagem natural, permitindo que o usuário registre e acompanhe seus gastos sem depender de formulários complexos ou planilhas.

## Problema
A maioria dos aplicativos de finanças exige entradas manuais extensas e oferece pouca personalização, o que desmotiva os usuários. O desafio é tornar o controle financeiro simples, natural e personalizado, com recomendações automáticas que incentivem hábitos saudáveis de economia.

## Público-Alvo
- Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicação.
- Iniciantes em educação financeira.
- Usuários que buscam planejar um futuro com mais segurança e tranquilidade.
- Todos os perfis de usuários, incluindo pessoas com diferentes níveis de letramento digital, idades e necessidades de acessibilidade.

## Princípio de Design Universal
O aplicativo deve ser projetado com Design Universal, garantindo que a experiência seja inclusiva e acessível para o maior número possível de pessoas. Isso significa:
- Interface clara e intuitiva.
- Suporte a diferentes formas de interação (texto, voz).
- Compatibilidade com recursos de acessibilidade (ex.: leitores de tela, contraste adequado).
- Linguagem simples e compreensível.

## Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações.
3. Definição e acompanhamento de metas financeiras (ex.: poupar R$ 200/mês).
4. Agente Financeiro que envia dicas de economia personalizadas.
5. Relatórios simples e personalizados, com visualização clara de gastos.
6. Potes financeiros (baseados na teoria de T. Harv Eker) para organizar o dinheiro em categorias como Necessidades, Diversão, Educação, Investimentos etc.
7. Acessibilidade garantida: design universal aplicado em todas as telas e interações.

## Entregável de IA (MVP)
- Principais telas:
  - Tela de chat (interação principal).
  - Tela de metas financeiras.
  - Tela de relatórios e potes.
- Recursos necessários:
  - Processamento de linguagem natural (NLP).
  - Motor de categorização automática de gastos.
  - Sistema de notificações para dicas e alertas.
  - Recursos de acessibilidade integrados.
- Validação inicial:
  - Testar com grupo piloto de usuários iniciantes e diversos perfis.
  - Medir engajamento (quantidade de registros feitos via chat).
  - Avaliar clareza das recomendações e relatórios.
  - Verificar usabilidade com pessoas que utilizam recursos de acessibilidade.
""


Interações com o LOVABLE

> Crie um app de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): (PRD)

> Eu gostaria que tivesse na página inicial as informações de saldo com receitas e despesas, além do assistente virtual, para que o usuário já veja imediatamente a movimentação do seu saldo ao inserir um gasto ou uma receita na conversa com o assistente.

> Percebi que os valores de Potes Financeiros não estão atualizando à medida que eu informo os valores para o assistente.

> Gostaria que você fizesse algumas modificações:

1- Percebi que quando eu informei um valor de gasto com viagem acima do ideal (pote financeiro), o assistente não me alertou sobre o gasto excessivo, que pode atrapalhar a atingir minhas metas. Quero que o assistente seja mais atento ao estilo do usuário e dê dicas e alertas para que o usuário consiga realmente organizar suas finanças mas com foco em atingir as metas cadastradas ou se não tiver metas, sempre alertar quanto ao gasto excessivo que possa comprometer algum plano ou emergência futura. 
2- Outra coisa, eu gostaria que o assistente se comportasse também como um agente/consultor financeiro, por exemplo, se o usuário fizer perguntas sobre finanças, então que ele responda. Por exemplo, “qual o melhor tipo de investimento?”. Que o assistente seja capaz de responder com base no estilo do usuário.
3- Mais uma coisa, peço que exclua a funcionalidade-chave “Potes financeiros”, pois não achei intuitiva para o usuário, que pode se confundir com os conceitos.
4- Criar um relatório que consolide o resultado final das finanças do usuário separadas por mês (exibindo os últimos 12 meses), por exemplo, Janeiro/2026: Saldo R$40,00; Dezembro/2025: Saldo -R$ 152,00.

> Fiquei na dúvida se posso alterar minhas metas. Na página de teste não há opção. Também não está abrindo a opção de cadastrar nova meta. Eu gostaria que essas opções estivessem disponíveis.

Resultado final no LOVABLE: https://wise-words-wallet.lovable.app

<img width="782" height="690" alt="Captura de Tela 2026-02-02 às 22 49 12" src="https://github.com/user-attachments/assets/bc24ad63-bb61-46b6-bba2-8143a119c66a" />

<img width="725" height="696" alt="Captura de Tela 2026-02-02 às 22 51 19" src="https://github.com/user-attachments/assets/c3eeb67f-06a9-4649-aa9f-7629aa7520b8" />

<img width="716" height="688" alt="Captura de Tela 2026-02-02 às 22 52 23" src="https://github.com/user-attachments/assets/722ba4e6-35b4-4d6c-bdd3-b463cf18869f" />

<img width="729" height="691" alt="Captura de Tela 2026-02-02 às 22 53 26" src="https://github.com/user-attachments/assets/ad41992f-6384-455a-8753-a7511c4c9a2d" />

<img width="717" height="693" alt="Captura de Tela 2026-02-02 às 22 54 37" src="https://github.com/user-attachments/assets/f345a912-7bd8-49f2-bb43-978ad90456d4" />

# Finanças Fácil

**Finanças Fácil** é um aplicativo de organização financeira pessoal que transforma o controle de gastos em uma experiência simples, acessível e conversacional. Ideal para quem busca praticidade, clareza e autonomia na gestão do dinheiro.

---

## 🧭 Visão Geral

O app foi desenvolvido com base em princípios de Design Universal, garantindo acessibilidade, linguagem simples e navegação intuitiva. Ele atende desde iniciantes em finanças até usuários com diferentes níveis de letramento digital.

---

## 👥 Público-Alvo

- Pessoas que desejam começar a organizar suas finanças sem complicação.
- Iniciantes em educação financeira.
- Usuários que buscam segurança e tranquilidade no planejamento financeiro.
- Pessoas com diferentes idades, níveis de habilidade digital e necessidades de acessibilidade.

---

## 🔑 Funcionalidades

### 1. Chat Inteligente com Linguagem Natural
- Registro de gastos e receitas com frases como:  
  `gastei 50 reais no almoço`  
  `recebi 3000 de salário`
- Agente financeiro virtual que responde perguntas e oferece análises personalizadas.
- Sugestões automáticas de economia e planejamento.

### 2. Metas Financeiras
- Criação de metas com título, valor objetivo, valor atual, categoria e prazo opcional.
- Acompanhamento visual do progresso com porcentagem e valor restante.
- Organização por categorias como Investimentos, Lazer, Educação etc.

### 3. Relatórios Personalizados
- Resumo mensal com saldo atual, receitas e despesas.
- Gráficos por categoria de gastos (Moradia, Alimentação, Compras, etc.).
- Histórico mensal com detal


  
## Reflexão:
## O que funcionou bem?
  O refinamento do PRD feito previamente no Copilot ajudou bastante, pois o LOVABLE tem apenas 3 interações gratuitas por dia.
### O que não funcionou como o esperado?
  Esperava que o LOVABLE permitisse mais interações gratuitas por dia, pois levei dois dias para finalizar meu app em razão dessa limitação.
### O que aprendeu sobre conversar com IAs?
  Aprendi que quanto maior o refinamento, mais claro for o prompt, melhor será o resultado.
