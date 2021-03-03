# Desafio Java
### _Posição: Analista Desenvolvedor Java Pl/Sr_

## Introdução
<p>Nossa equipe lida diariamente com a sustentação e criação de novos produtos. Uma das principais tecnologias usada é o Java, que também é o foco desse processo seletivo. <br/>
Dito isso, gostaríamos de entender um pouco do seu grau de conhecimento e como podemos explorar todo o seu potencial, e com esse intuito, bolamos esse pequeno desafio. Logo abaixo, vamos simular, em escala bem simples, um cenário de uma implementação bem parecido com o que lidamos no dia a dia, esperamos que para essa implementação seja construída do zero uma <b>aplicação web</b> bem simples. 
</p>

Ao término, vamos avaliar os seguintes pontos: 
- Cumprimento do prazo;
- O resultado funcional; 
- Tratamento de exceções;
- POO;
- Padrões de projeto utilizados;
- Clean code (qualidade de codigo);

Será considerado como diferencial o uso de:
- Controle de versão;
- Testes unitarios;
- Gerenciador de dependencias;

Então, vamos lá ;-) 

# _Projeto: Controle Financeiro_
Entrou um novo projeto na fila de implementação de nossa equipe com a seguinte descrição: 
- <b>Desenvolver uma aplicação _WEB_ simples que ajude nossos usuários a fazerem seu controle financeiro, basicamente, contas a receber e a pagar. </b>

Após uma reunião com equipe, foi definido que a melhor solução, com menor esforço possível, seria a seguinte:
- Para avaliarmos o conceito no mercado, não será necessário realizar regras complexas, tampouco de segurança, como controle de usuários e login. 
- Devemos construir apenas uma tela simples, listando despesas e receitas. 
- Haverá um botão para criar novos registros, informando Descrição (texto), Tipo (receita ou despesa), Vencimento (data), Status (boleano para checar se o lançamento foi efetivado)  e Valor (valor monetário).
- Deve haver também um totalizador informando o valor total de despesas, receitas e a diferença entre os mesmos.
- Se sobrar tempo: devemos apresentar um gráfico simples, Total Receitas x Total Despesas. 
- Logo abaixo poderá visualizar um prototipo, não precisa segui-lo a risca, é só pra ter uma ideia de como pensamos, porém, você tem liberdade para fazer do seu jeito.

### _Protótipo:_
![alt text](https://github.com/sefaz-acre/desafio-java/blob/main/prototipo-desafio-java.PNG?raw=true)


### _Tecnologias: Sugestões_
- Aplicação Web (monolito);
- Linguagem: Java 8;
- Servidor: Tomcat, Glassfish ou Wildfly;
- Banco de dados: relacional (postgres, mysql, mariadb);
- Use MVC na definição de camadas;
- Não definimos a tecnologia web do java, sugerimos o uso do JSF, mas não é problema usar JSP ou stack do html5 (html, css e js), desenvolva da forma que se sente mais confortavél;
- Não é permitido uso dos frameworks Spring e Quarkus;


### _Entregas: O que esperamos receber_
- Se ao analisar o desafio, você acreditar que não conseguirá concluir dentro do prazo que estipulamos, nos comunique com uma proposta de prazo dentro da sua realidade.
- Precisamos que sejam disponibilizados os fontes da aplicação, sugerimos que seja em um repositórios de fontes, ex: github
- É muito importante que consigamos testar sua aplicação funcionando, então que tal uma documentação básica (bem simples) de compilação e instalação/execução, scripts sql se ouver, etc…

E é isso, boa sorte no processo, estamos ansiosos pra conhecer seu trabalho!
