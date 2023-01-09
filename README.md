# QA e QE: A evolução da carreira de Qualidade

## Introdução

Acredito que desde o primeiro dia na área de tecnologia, por volta de 2008, eu escuto que "[o papel do QA está com os dias contados](https://talkingabouttesting.com/2015/02/25/a-extincao-do-profissional-de-qa/)" dentro dos times de desenvolvimento de software. Nunca dei muita credibilidade, pois notava que ainda era possível agregar valor na entrega do produto e me sentia seguro com isto. Até que, depois de um tempo, as complexidades das entregas aumentaram, os prazos reduziram e as cobranças por sistemas cada vez com mais qualidade se tornaram mais comuns e, neste cenário, o que estava fazendo apenas como um QA acabou perdendo espaço e foi necessário começar uma "evolução".

Neste texto, quero trazer o tema: "A pessoa QA, como conhecíamos no passado não está com os dias contados, mas precisa evoluir!"

Mas, antes de seguir com conteúdo, é extremamente importante deixar algumas premissas alinhadas: 
- O que será dito neste conteúdo diz respeito apenas à evolução de carreira do analista dentro dos times. Em momento algum será dito (mesmo que nas entrelinhas) que devemos abrir mão da qualidade nos nossos projetos. **Qualidade é inegociável e é responsabilidade de todos os envolvidos!**
- Neste texto tratarei apenas de hard skills da área técnica da evolução na carreira de QA para QE. Tópicos como conhecimento de negócio, soft skills e afins são e sempre serão necessários para qualquer evolução dentro da carreira, seja ela para o lado técnico ou para o lado "gerencial", pois fazem parte de ambas.

## O que são QA e QE?

Para contextualizar e definir o que penso para as siglas, QA e QE, que vou comentar no texto, vou fazer uma breve descrição de cada uma delas aqui:

**QA:** A pessoa QA (Quality Analyst), ou QAA (Quality Assurance Analyst), é a responsável por garantir que os requisitos ou critérios de aceite levantados no começo do planejamento do produto estejam satisfeitos depois que o produto foi desenvolvido. Na grande maioria dos times, as atividades atribuídas aos QAs são relacionadas ao planejamento de Casos de Teste e execução manual deles. 

**QE:** A pessoa QE (Quality Engineer), ou QAE (Quality Assurance Engineer), possui os mesmos objetivos que um QA, acrescidos de pontos importantes, como mindset de Qualidade e objetivos técnicos, envolvendo automações, camadas de integração, atividades próximas aos times de Desenvolvimento e DevOps, preocupação com requisitos não funcionais, como performance, e outros. Isto torna o QE um dos próximos passos na carreira (se formos avaliar com um viés técnico) do QA, principalmente se formos analisar aqueles que  trabalham como no modelo [T-Shaped](https://softwaretester.careers/t-shaped-software-tester/) ou outros. 

A tabela abaixo ilustra, de maneira objetiva, quais as principais características de cada um dos papéis:


-- | **QA** | **QE**
-- | --  | --
Planejamento de Testes | Sim, essa etapa é essencial independente do papel. | Sim, essa etapa é essencial independente do papel.
Execução Manual de Testes | Sim, a maioria dos testes  trabalhados estão na camada de testes de sistema e são executados de maneira manual. | Com o foco mais voltado para atividades automatizadas, só realiza a execução manual quando necessário (devido a tempo, viabilidade técnica, etc.)
Automação de Testes Funcionais | Apesar de não ser o foco do papel, faz um pouco de automação para evitar algumas tarefas repetitivas. | Como uma das principais atividades, a automação de testes é planejada e implementada desde o início do trabalho visando garantir a qualidade do software o quanto antes.
Atuação em Testes Não Funcionais | - | É um dos responsáveis por realizar este tipo de testes devido a capacidade técnica e conhecimento.
Apoio técnico sobre Testes aos times de Desenvolvimento e DevOps | - | Quando se trata de Qualidade, deve ser capaz de ajudar em todas as etapas do desenvolvimento de software, desde o início do planejamento/codificação até a entrega em esteiras de CI/CD.

Existem ainda outros tipos de carreiras que tenho visto no mercado que surgiram a partir do QA, como Software Development Engineer in Test (SDET), Software Engineer in Test, porém neste conteúdo, não vou entrar em detalhes sobre quais são as diferenças entre elas e o QE, visto que não é o objetivo aqui.

## Por que é necessário evoluir?

Voltando ao tema da evolução, com o [advento do Ágil](https://agilemanifesto.org/iso/ptbr/manifesto.html) e a necessidade de entregas cada mais vez mais rápidas, mecanismos automatizados de integração e entrega contínua, as atividades da pessoa QA, como eram feitas, acabaram se tornando gargalo para os times, pois processos manuais interrompem esteiras bem planejadas e acabam atrasando, por algum motivo, a release. 

Para solucionar este problema, digo, visando a melhoria contínua do processo de desenvolvimento, a pessoa QA precisa se adaptar às necessidades do time e, neste caso em específico, criar maneiras de executar suas tarefas mais rapidamente (sem perder qualidade), de forma paralela (se possível), e incluir suas validações no fluxo automático. A forma de se fazer isto é automatizar os testes. Testes de sistema ou funcionais automatizados, se bem planejados e arquitetados, podem facilmente ser executados de maneira paralela, sem a necessidade de uma intervenção manual e se tornar um step da entrega. E começando a pensar e a realizar este tipo de tarefa, a pessoa QA está começando a assumir tarefas de um QE, isto é, evoluindo em sua carreira.

Vale ressaltar que os testes automatizados devem ser planejados e derivados a partir do mesmo processo que o papel da pessoa QA utilizava ao levantar os Casos de Teste necessários para validar um determinado fluxo, requisito ou cenário, portanto, todos os conhecimentos, teóricos e práticos, da disciplina de Qualidade de Software devem se fazer presentes em uma pessoa QE.

Com a automação já frequente no fluxo das entregas, a pessoa QE consegue focar em diversas outras atividades que visam acrescentar valor ao produto. E, como exemplos de atividades que podem ser adicionadas ao portfólio do QE, temos os testes que exigem uma capacidade de acessar camadas de serviços, como [Testes de Contrato](https://pactflow.io/blog/what-is-contract-testing/), ou testes que validam pontos não funcionais da aplicação, como [Testes de Performance](https://www.guru99.com/performance-testing.html). E, seguindo um viés técnico, ainda existem atividades que podem permear o desenvolvimento (apoiando os desenvolvedores em situações onde o background de Qualidade pode ser útil, como o apoio na adoção de [Testes de Mutação](https://www.guru99.com/mutation-testing.html)) e a parte de delivery, CI/CD e cloud (colaborando com os times de DevSecOps e SREs).

Deve-se mencionar que, ao se associar a estes novos modelos de trabalho onde a agilidade é necessariamente importante, alguns termos e abordagens foram criados nos últimos anos e estão, de certa forma, ligados ao papel QE, como [Shift Left Testing](https://www.testim.io/blog/shift-left-testing-guide/), onde atividades de testes que eram executadas no final do processo de desenvolvimento começam a ser realizadas já nas primeiras etapas, e [Pirâmide de Testes](https://martinfowler.com/articles/practical-test-pyramid.html), que define camadas onde determinados tipos de testes serão aplicados.

Importante frisar que atividades manuais ainda serão necessárias para o QE, porém, seguindo boas práticas (inclusive citadas em artigos sobre pirâmides de teste), estas tarefas serão focadas em funcionalidades que não são passíveis de automação (ou o custo-benefício é baixo) e cenários pontuais para validação final do produto.

## E como evoluir?

Muito foi falado sobre sobre o que é e o por quê dar o próximo passo na carreira, então, além das diversas referências citadas por todo o texto, ficarão aqui algumas sugestões minhas de como começar este movimento. Lembrando que, como de praxe, a curiosidade deve ser sempre uma característica de todos aqueles que trabalham com Qualidade de Software, portanto não se atenham apenas a estas indicações.
Seguem alguns links:
- [Agile Testing: A Practical Guide for Testers and Agile Teams](https://www.amazon.com.br/Agile-Testing-Practical-Guide-Testers/dp/0321534468): Para começar, acredito que a leitura básica para entender como funcionam os testes dentro de times ágeis.
- [Agile Testing Condensed - Edição PT-BR](https://leanpub.com/agiletesting-condensed-brazilian-portuguese-edition/c/AgileTesters-MTC21): Uma tradução muito bem realizada pelo Felipe Knorr e pelo Paulo Gonçalves sobre o livro de mesmo nome que, como o próprio nome já diz, condensa as informações do livro Agile Testing.
- [Código Limpo](https://www.amazon.com.br/C%C3%B3digo-limpo-Robert-C-Martin/dp/8576082675/) e [O Codificador Limpo](https://www.amazon.com.br/codificador-limpo-conduta-programadores-profissionais/dp/8576086476/): Livros essenciais para quem está começando ou que já está na área de desenvolvimento há algum tempo.
- [5 Tools To Deliver High-Quality Software using Java](http://www.eliasnogueira.com/ebook-5-tools-java-developers/): Ebook grátis onde são apresentadas 5 ferramentas para utilizar como QE.
- [Engenharia de Software Moderna](https://www.amazon.com.br/Engenharia-Software-Moderna-Marco-Valente/dp/6500019504/): Livro que contempla um amplo conjunto de princípios e práticas para o desenvolvimento de software.
- [O testador está morto](https://www.youtube.com/watch?v=nGaiS2o1QRw): Vídeo onde é abordado o tema sobre a evolução da carreira.
- [Roadmap: QA Engineer](https://roadmap.sh/qa/): Roadmap traçando os principais conhecimentos necessários para evolução da carreira.
- [Anti-Patterns de Automação de Testes](https://medium.com/codex/anti-patterns-of-automated-software-testing-b396283a4cb6): Artigo muito útil para entender que não basta sair automatizando testes de qualquer forma. 

Alguns criadores de conteúdos e cursos que contribuem muito com a comunidade e que possuem um bom material:
- [Elias Nogueira](http://www.eliasnogueira.com/)
- [Paulo Gonçalves](https://github.com/PauloGoncalvesBH)
- [Walmyr Lima](https://talkingabouttesting.com/)
- [Bruno Batista](https://github.com/brunobatista25)
- [Júlio de Lima](https://www.juliodelima.com.br/)

E, para aqueles que estão começando na área, todo o material acima acrescido de conceitos básicos de testes de software, uma vez que esta base é o passo inicial para carreira em Qualidade de Software:
- [Syllabus CTFL](https://bcr.bstqb.org.br/docs/syllabus_ctfl_3.1br.pdf): Material de estudo gratuito da principal certificação de testes.
- [Syllabus CTF-AT](https://bcr.bstqb.org.br/docs/syllabus_ctfl_at_2014br.pdf): Material de estudo gratuito de uma das principais certificações da atualidade.
- [Base de Conhecimento em Teste de Software](https://www.amazon.com.br/Base-Conhecimento-em-Teste-Software/dp/8580630533/): Livro de referência para os profissionais iniciantes na área. 

## Conclusão

Enfim, resumidamente, o papel da pessoa QA como conhecemos não vai acabar, mas é necessário começar a trabalhar, para muitos, fora da zona de conforto, para dar o próximo passo na carreira. Ou seja, se pretende seguir a carreira técnica dentro da área de Qualidade, é importante que saiba que itens cada vez mais próximos da camada de desenvolvimento podem ser exigidos. 

Muitos já começaram a fazer a transição e ainda não haviam se dado conta, e para estes a sugestão é não parar no meio do caminho. Automação é um bom ponto, mas é só a ponta do iceberg. A tecnologia não para de evoluir e não podemos parar também.

Claro que ainda vão existir vagas para QAs, no entanto, estas serão cada vez mais pontuais  e/ou voltadas para cargos de senioridade de início de carreira.

**E você, o que acha?**
