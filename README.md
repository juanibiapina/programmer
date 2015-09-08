# Como se tornar melhor em programação

## Tópicos Gerais

### Organização:

Trata da organização geral da pessoa e não apenas do código.

Eu sou da opinião de que o trabalho de programação e todas as atividades
envolvidas são um reflexo da nossa organização mental. Quando a pessoa se torna
mais organizada, isso fica visível em suas práticas. Quando as práticas se
aprimoram, ela também se torna uma pessoa mais organizada.

Organização facilita o entendimento do código, seja provendo documentação de
como instalar ou utilizar o software, ou justificando o porquê de certas
decisões terem sido tomadas. Isso vai ser extremamente importante pra
mantenedores do projeto em alguns anos.

Os itens seguintes são alguns indicadores de organização:

- Commits
  - Uma mudança conceitual por commit
  - Mensagens descrevem o porquê da mudança
  - Seguem um padrão único
- Estrutura de diretórios
  - Arquivos divididos em pastas
  - Cada conceito, app ou camada está em um diretório diferente
- Documentação
  - Usa um README pra descrever seu software
  - Descreve o porquê, quando necessário

Esse é o [guia de estilo do git que eu
recomendo](https://github.com/agis-/git-style-guide). É importante tentar
praticá-lo no seu dia a dia. Algumas práticas são universais (como uma mudança
lógica por commit), outras podem ser adaptadas às necessidades do time, desde
que haja um entendimento dos princípios por trás de cada uma.

Uma pessoa uma vez me falou: "Mas você perde muito tempo escrevendo mensagens
de commit!". Não tenha medo de dedicar bastante tempo às mensagens. Anos
depois, alguém completamente sem contexto vai precisar ler essa mensagem pra
entender o que aconteceu, e essa pessoa vai perder muito menos tempo se você
fizer uma mensagem bem feita. Com o tempo, você também vai aprender a escrever
as mensagens mais rapidamente. Como tudo, é apenas uma questão de prática. Além
disso, se uma mensagem está muito difícil de ser escrita, é um indicador de que
o commit pode não estar bom. Talvez seja o caso de revisar se esse ele está
fazendo pouca ou muita coisa. Não tenha meda de desfazer e fazer novamente.

### Qualidade de código

Aspectos práticos de qualidade de código.

Como passamos a maior parte do tempo lendo código, a legibilidade é um dos seus
aspectos mais importantes. Além disso, no fim das contas, o código é o único
lugar que reflete precisamente todas as decisões e regras de negócio. Por isso
é importante manter sua qualidade.

Algumas características de código de qualidade:

- Nenhuma duplicação
- Não violam a Lei de Demeter
- Tratamento de erros não polui o código
- Trata erros significativos, ao invés de situações criadas por outro código
    ruim
- Nomes
  - Revelam intenção
  - Pronunciáveis
  - Sem piadinhas
  - Refletem conceitos do domínio
  - São consistentes
- Funções
  - Tem apenas uma responsabilidade (que é deduzível pelo nome)
  - Usam poucos parâmetros
  - Tem poucas linhas
- Classes
  - Tem apenas uma responsabilidade (que é deduzível pelo nome)
- Comentários
  - Explicam apenas o que realmente não pode ser expresso em código
- Formatação
  - Uniforme
  - Linhas curtas
  - Usa espaços pra separar conteúdo
