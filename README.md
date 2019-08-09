# ProjetoTeste

**** README *****
- Este projeto foi desenvolvido utilizando SprintBoot e banco de dados em memória JPA.

-- Passo a Passo para rodar este web service;
1) Importar projeto na ferramente Sprint Tool Suite;
2) Na máquina que irá rodar o web service, será necessário criar a pasta "apiGoldenRaspeberry" dentro do "C:";
2.1) Colocar csv dentro desta nova pasta;
3) Para rodar o webservice, abrir a classe "ApiGoldenRaspeberryApplication.java";
3.1) Clicar com botão direito > "Run As" > "Sprint Boot App";
4) Abrir navegador e abrir url "http://localhost:8095/apiGoldenRaspeberry"
4.1) Isto fará com que retorne o produtor com maior intervalo entre dois prêmios, e o que obteve dois prêmios mais rápido;

OBS: é possível também ao final da url adicionar "/min" ou "/max" para retornar somente um dado desejado.

-- Para rodar os testes de integração.
1) Abrir a classe "MainControllerTest.java", clicar com botão direito > "Run As" > "JUnit Test";

OBS: Foram criados 4 testes. Retornando tudo, o produtor com maior intervalo entre dois prêmios, 
	 o que obteve dois prêmios mais rápido e outro com retorno não encontrado.
