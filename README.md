## Objetivo

O principal objetivo desse teste é saber como você sairia em tarefas do dia a dia e qual o tipo de solução que você pode dar para determinadas tarefas do dia a dia. Não tenha o objetivo de fazer o teste no menor tempo possível e sim com a maior qualidade que você conseguir. 

## Descrição

Você irá desenvolver um aplicativo para listagem de seriados consumindo a api do site TVmaze. É esperado que esse aplicativo contenha as seguintes features listadas abaixo:

* Listagem de séries
	* Você deve listar todas as séries contidas na API utilizado o esquema de paginação fornecido pela API.
	* Deve ser possível realizar buscas pelo nome da série.
	* Você deve mostrar no mínimo o nome e a imagem de poster da serie na listagem e busca.
	* Ao clicar em uma série, o aplicativo deve mostrar o detalhamento da mesma.

* Detalhamento de uma série
	* O detalhamento deve mostrar as seguintes informações:
		- Nome
		- Poster
		- Dias em que a serie vai ao ar e o horário
		- Genêros
		- Sumário
		- Listagem de episódios separados por temporada
	* Deve ser possível salvar a serie favorita, para isso você deve utilizar Core Data para armazenamento local.
	* Ao clicar em um episódio deve ser possível visualizar as informações do mesmo.

* Detalhe do episódio
	* Devem ser mostradas as seguintes informações sobre o episódio:
		- Nome
		- Número
		- Temporada
		- Sumário
		- Imagem, caso exista

* Series Favoritas
	* Você deve mostrar todas as series marcadas como favorita em ordem alfabética.
	* Você deve ser capaz de excluir uma série da lista de favoritas.
	* Ao clicar em uma série, deve ser possível visualizar o detalhe da mesma.

### Extra

* Busca de Pessoas
	* Você deve criar uma busca de pessoas listando o nome e a imagem da mesma
	* Ao clicar na pessoa, o aplicativo deve mostrar o detalhamento da mesma

* Detalhamento de pessoa
	* O detalhamento da pessoa deve mostrar as seguintes informações:
		- Nome
		- Imagem
		- Series que ele já participou
	* Ao clicar em uma série, deve ser exibido o detalhamento da mesma. 

## Observações

Não será apresentado nenhum mockup de interface, já que um dos critérios avaliados é também sua noção de UI/UX. Não esperamos uma obra prima de design em seu aplicativo, mas queremos um aplicativo que respeite as guidelines da plataforma e que não tenha problemas de usabilidade. 

## Requisitos

* Xcode 7.3+
* Swift 2.2
* iOS 8.0+
* Storyboards
* Adaptive Design
* CocoaPods
	* Documente todos os Pods utilizados e o motivo da sua escolha no arquivo Readme.md do seu repositório. 

## API:

Você pode ler a documentação da API no site [TVmaze](http://www.tvmaze.com/api).

## Critérios de Avaliação:

* Códigos e classes bem organizados.
	* Caso deseje, você pode utilizar o mesmo styleguide que utilizamos na HE:labs para organizar seu código e projeto:	
		- [Swift](https://github.com/helabs/swift-style-guide)
* Interface com boa usabilidade seguindo as guidelines da plataforma.
* Seguir bem a proposta solicitada. Quer adicionar uma nova feature para deixar seu teste ainda melhor? Termine todas as tarefas pedidas antes.
* Testes unitários é um plus.
* As tarefas extras também são um plus.
