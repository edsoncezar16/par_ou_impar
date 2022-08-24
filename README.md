# Par ou ímpar? Aplicando o raciocínio probabilístico de maneira consistente.

Os conceitos fundamentais de estatística sempre geram discussões interessantes, tanto entre o público geral quanto entre profissionais que utilizam a estatística de maneira rotineira em suas atividades.Nesse contexto, talvez nenhum conceito cause mais confusão nas discussões do que o de **probabilidade**. Em particular, mesmo entre profissionais experientes é comum vermos aplicações equivocadas deste conceito.

 Podemos considerar como um exemplo famoso o problema de Monty Hall, resolvido por [Marilyn vos Savant](https://en.wikipedia.org/wiki/Marilyn_vos_Savant) e no qual mesmo doutores (!) em  Matemática discordaram da solução correta antes de verem uma simulação computacional, incluindo o notável Paul Erd&ouml;s. Uma discussão detalhada e envolvente deste caso pode ser vista no livro 
[O andar do bêbado: como o acaso determina nossas vidas](https://www.amazon.com.br/andar-b%C3%AAbado-acaso-determina-nossas/dp/8537818100), de Leonard Mlodinow, que considero um dos melhores livros que já li até hoje!

Recentemente, uma
[enquete](https://www.linkedin.com/feed/update/urn:li:activity:6960402413706985472?updateEntityUrn=urn%3Ali%3Afs_feedUpdate%3A%28V2%2Curn%3Ali%3Aactivity%3A6960402413706985472%29) publicada no Linkedin por Henrique Junqueira Branco, que atua na área de dados como Engenheiro de Machine Learning, perguntava sobre quem tem mais chances de ganhar no par ou ímpar. Vários profissionais e estudantes da área de Ciência de Dados comentaram, e uma quantidade considerável dos participantes votou a favor da escolha 'par' usando argumentos que, embora pareçam plausíveis, estão equivocados quando levamos em conta a definição de probabilidade.

Assim, este projeto tem por objetivo usar a minha experiência acadêmica, com forte ênfase em raciocínio analítico e domínio dos conceitos fundamentais da estatística, e minhas habilidades de programação com a linguagem Python para contribuir com a melhoria da qualidade do raciocínio probabilístico na comunidade de Ciência de Dados, ou mesmo do público geral.

Para atingir esses objetivos, serão [executadas](par_ou_impar.ipynb) as 3 tarefas a seguir:

## Probabilidades iguais
- [x] Mostrar que, considerando o jogo "clássico" de par ou ímpar, onde cada jogador coloca apenas uma mão, isto é, seleciona um número inteiro entre 0 e 5, a probabilidade de o resultado ser par ou ímpar é de 50% cada.

## Raciocínios inconsistentes
Mostrar, através de visualizações e simulações, que os seguintes raciocínios, embora usados por várias pessoas durante a enquete e   aparentemente plausíveis, são equivocados:
- [x] "Cada jogador escolhe um número, que pode ser par ou ímpar. Como par + par = par, ímpar + ímpar = par e par + ímpar = ímpar, há mais possibilidades onde o resultado final é par."

- [x] "Após somar as mãos dos jogadores, há 6 resultados pares possíveis (0, 2, 4, 6, 8, 10) e apenas 5 ímpares (1, 3, 5, 7, 9). Logo, quem escolhe par tem mais chances de ganhar."