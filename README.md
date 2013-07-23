[<img src="https://travis-ci.org/poacomovamos/poacomovamos.png?branch=master" alt="Build Status" />](https://travis-ci.org/poacomovamos/poacomovamos)

## Bem indo ao Porto Alegre Como Vamos


O Porto Alegre Como Vamos é um movimento da sociedade civil, apartidário, sem fins lucrativos, que pretende trazer o cidadão a participar dos processos que acontecem na cidade, incidindo em políticas públicas e promovendo espaços de interação abertos para a melhoria da cidade. Temos como objetivo contribuir para fortalecimento da democracia e de qualidade de vida, mantendo um compromisso com o desenvolvimento sustentável e com a justiça social. Somos um organismo aberto, com o dever de acolher qualquer pessoa que com ele resolver interagir.

Em 2012 o movimento criou seu primeiro grande projetos na internet com o site "Voto Como Vamos", que proporcionava integração entre os candidatos a vereador da cidade de Porto Alegre com os eleitores através do portal votocomovamos.com.br, que também foi replicado para outras cidades no mesmo ano.


## Guide to Setup & Running

#### Pré requisitos:

* **[NPM ( Node Package Manager )](http://npmjs.org)**: NPM é o gerenciador de pacotes do node.js e ele é necessário para montar o setup de javascript. Pode ser instalado pelo [Homebrew](http://mxcl.github.io/homebrew/) ```brew install npm```

* Node Modules:
	* [Karma.js](http://karma-runner.github.io/0.8/index.html): Test runner utilizado para rodar os testes do javascript.
	A versão canary deve ser instalada ```npm install -g karma@canary```

* **[Sinatra](http://www.sinatrarb.com/)**: Nosso amado framework web que atende a api.
Pode ser instalado pelo gem ```gem install sinatra```

##### Running Tests

Digite ```rake test``` para rodar todos os testes ou ```rake jstest``` para rodar somente os de javascript

##### Running The App

Digite e Divirta-se ``` ruby poacomovamos.rb``` =)