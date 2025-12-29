# Aplicativo de Controle Finaceiro Familiar com Vibe Coding

 Product Requirement Document Refinado no Copilot Web

```markdown

## 1. Contexto
O aplicativo tem como objetivo simplificar o controle financeiro pessoal por meio de interações em linguagem natural.  
Em vez de formulários ou planilhas complexas, o usuário conversa com o app como se fosse um assistente, tornando o processo mais intuitivo e acessível.

## 2. Problema
- Os aplicativos atuais exigem muitas entradas manuais e oferecem pouca personalização.  
- Isso gera frustração e abandono do hábito de registrar gastos.  
- A solução proposta é oferecer uma experiência conversacional, com recomendações automáticas e personalizadas de economia.

## 3. Público-Alvo
- Pessoas que desejam começar a organizar suas finanças de forma prática e sem complicação.  
- Principalmente iniciantes que nunca usaram ou desistiram de apps financeiros tradicionais.  
- Nota importante: o design deve ser universal, garantindo que o aplicativo ofereça boa experiência para o máximo de usuários possíveis, independentemente de idade, nível de familiaridade com tecnologia ou possíveis limitações físicas/cognitivas.

## 4. Funcionalidades-Chave
1. Registro de gastos via chat: o usuário informa seus gastos em linguagem natural.  
2. Classificação automática: o sistema organiza as transações em categorias (alimentação, transporte, lazer etc.).  
3. Metas financeiras: definição e acompanhamento de objetivos (ex.: guardar R$ 200/mês).  
4. Agente Financeiro: dicas personalizadas de economia e alertas de comportamento financeiro.  
5. Relatórios simples e personalizados: visualização clara de gastos, metas e progresso.  
6. Design Universal: interface acessível, intuitiva e inclusiva, com foco em usabilidade para todos.  
7. Inclusão de múltiplos usuários: possibilidade de adicionar perfis adicionais (como filhos ou dependentes) para que eles possam registrar suas próprias despesas, mantendo a visão consolidada das finanças familiares.

## 5. Entregável da IA
- Plano de MVP (Produto Mínimo Viável):
  - Principais telas:
    - Tela de chat (interação com o assistente).  
    - Tela de metas financeiras.  
    - Tela de relatórios simples.  
    - Tela de gerenciamento de usuários (adicionar/remover perfis).  
  - Recursos necessários:
    - Processamento de linguagem natural (NLP).  
    - Motor de categorização automática.  
    - Sistema de notificações e dicas.  
    - Banco de dados para armazenar transações, metas e perfis de usuários.  
    - Diretrizes de acessibilidade e design universal.  
  - Validação inicial:
    - Testes com grupo piloto de usuários iniciantes e diversos perfis (incluindo pessoas com diferentes níveis de habilidade digital).  
    - Coleta de feedback sobre clareza das conversas, acessibilidade, utilidade das dicas e experiência multiusuário.  
    - Ajustes rápidos com base nas interações reais.
```

Interações com o Loveble:

> Crie um aplicativo de finanças pessoais com base no seguinte PRD (Product Requirement Document). Gostaria que o design fosse em tons de roxo e laranja: {PRD}

> A aplicação ficou perfeita, porém, senti falta da tela inicial para criar uma nova conta e realizar o login. Gostaria também que a receita, despesas e metas vissem zeradas.


Resultado final no Loveble: https://chat-wise-funds.lovable.app


<img width="1340" height="624" alt="image" src="https://github.com/user-attachments/assets/ecc8086e-3124-4cf0-91f8-395f6f283268" />
<img width="1333" height="629" alt="image" src="https://github.com/user-attachments/assets/e7291d00-124b-4475-9a14-92f2a27c19a0" />
<img width="1334" height="583" alt="image" src="https://github.com/user-attachments/assets/3d8fd435-f48a-4de4-8ff5-7b8d49d10b87" />
<img width="1350" height="630" alt="image" src="https://github.com/user-attachments/assets/c9635822-52e5-4f79-9abe-ee97c1490d45" />


# Funcionalidades de Controle Financeiro Familiar

## 1. Dashboard Inicial
- Exibe **saldo atual**, **receitas** e **despesas** de forma clara e resumida.  
- Mensagem de boas-vindas que contextualiza o estado das finanças do usuário.  
- **Ações rápidas** disponíveis:
  - Registrar gasto via chat em linguagem natural.  
  - Criar nova meta financeira.  
  - Ver relatório com análise mensal.  

## 2. Navegação Principal
- Barra inferior com acesso direto às principais áreas:
  - **Início**: visão geral das finanças.  
  - **Chat**: interação conversacional para registrar gastos e receber dicas.  
  - **Metas**: definição e acompanhamento de objetivos financeiros.  
  - **Relatórios**: visualização simples e personalizada dos gastos e progresso.  
  - **Perfis**: gerenciamento de múltiplos usuários (ex.: filhos ou dependentes) que podem registrar suas próprias despesas.  

## 3. Funcionalidades-Chave
- Registro de gastos via chat em linguagem natural.  
- Classificação automática das transações em categorias (alimentação, transporte, lazer etc.).  
- Definição e acompanhamento de metas financeiras.  
- Agente Financeiro com dicas personalizadas de economia e alertas de comportamento.  
- Relatórios acessíveis e personalizados, com gráficos e textos claros.  
- Inclusão de múltiplos usuários para consolidar as finanças familiares.  
- Design Universal: interface inclusiva, intuitiva e acessível para o máximo de usuários possíveis.  

## 4. Diferenciais
- Experiência conversacional em vez de formulários complexos.  
- Foco em iniciantes e pessoas que buscam praticidade.  
- Validação inicial com grupo piloto diverso para garantir acessibilidade e usabilidade.  

## Reflexão

### O que funcionou bem?

As dicas e o aperfeiçoamento do PRD previamente feito no Copilot foi bastante útil para a primeira vez utilizando o Loveble.
Gostei muito da interface "jovem", pois a intenção do protótipo é que um adolescente também utilize.

### O que não funcionou como o esperado?

Com a primeira instrução, o Loveble não gerou a tela de nova conta e login, e também não inegrou com banco de dados para armazenar os inputs.
Após solicitar o login, os créditos acabaram, porém, só falta integrar com banco de dados e refinar ainda mais a aplicação.

### O que aprendeu sobre conversar com IAs?

A IA necessita de contexto e instruções lógicas e detalhadas para retornar o melhor resultado.
