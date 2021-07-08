# Teste de Automação para QA - CI&T
Este é um desafio criado para a nossa seleção de uma pessoa Engenheira de Software que irá atuar na função de QA.

Leia atentamente todo o conteúdo desse documento antes de começar qualquer execução!

Instruções Gerais Iremos utilizar o site https://opentdb.com/ para realizar nosso teste, onde faremos alguns cenários utilizando a linguagem Gherkin.

À princípio, daremos um modelo para que você apenas crie os passos da automação. Depois, será necessário criar um teste baseado numa descrição de cenário. Por fim, você terá que criar um cenário que ache adequado para a situação. Conforme as descrições dos passos estão mais abaixo.

O teste pode ser feito em qualquer linguagem de programação e com qualquer framework de teste de interface. Fica a seu critério escolher que se adequa mais ao seu perfil e / ou ao seu conhecimento.

A entrega desse teste deve ser feita através do seu repositório Git pessoal (GitHub, Bitbucket, etc).

Qualquer dúvida que tenha, basta entrar em contato conosco que teremos o maior prazer em te ajudar!

Critérios para avaliação Organização de código, arquitetura e boas práticas de programação Criação de casos de testes utilizando Gherkin Utilização de algum padrão de desenvolvimento de automação Como foi a utilização do framework de automação e da linguagem de programação Estruturação de relatórios (diferencial) Facilidade na execução dos testes (por exemplo, utilização do Docker) (diferencial)

Primeira parte Temos o seguinte cenário, escrito em Maxixe, que devemos automatizar:

Funcionalidade: Busca no Banco de Questões Cenário: Busca por questão inexistente Dado que navego para uma página de busca do banco de questões E digito 'Ciência: Computadores' no campo de busca Quando clico no botão de buscar Então visualizo uma mensagem de erro com o texto 'Nenhuma pergunta encontrada.'

Você irá agora pegar esse cenário e realizar uma automação dele no site anterior anteriormente.

Segunda parte Agora, estamos com a seguinte informação de um novo cenário que temos que testar para o usuário final:

Precisamos fazer uma busca na categoria por Ciência: Computadores e verificar se a listagem de questões está com 25 itens e se o controle de paginação irá aparecer. Com essa informação em mãos, vamos para a posição desse cenário de teste. Leve em consideração o que foi feito previamente e tente escrever o cenário em Gherkin antes de começar qualquer código.

Terceira parte Por fim, você terá que criar um cenário novo que não foi descrito anteriormente. A ideia aqui é realmente ver como você faria um cenário do zero, criando o Gherkin e depois fazendo a automação dele. Abuse e use do que foi feito anteriormente para te ajudar!

Considerações finais Aqui, finalizamos o teste! Espero que conseguido fazer tudo com bastante carinho e atenção! Aguardamos pelo seu envio e, assim que fizermos a avaliação, iremos te dar um retorno com feedbacks a respeito.

Esperamos também que tenha gostado e que tenha aprendido um pouco conosco!

Até breve!
