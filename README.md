•	Caixas de Diálogo
o	prompt
o	alert
o	confirm
•	Temporizadores
o	setInterval
o	setTimeout
•	Funções
o	Função anônima com argumento
o	Função anônima sem argumento
o	Função anônima com retorno
o	Função auto-executável - não será aceita a mesma do Module Pattern
o	Função com nome
o	Função aninhada/local - declarar uma função dentro de outra
o	Passagem de uma função como parâmetro para outra função - ambas as funções precisam ser implementadas pelo aluno
o	Função Flecha - Arrow Function
•	Eventos
o	Evento de carregamento do documento - onload
o	Evento de movimento do mouse
o	Evento de teclado - usar charCode ou keyCode
o	Eventos de formulário - usar onfocus e onblur
o	Imprimir alguma propriedade/atributo do objeto event recebido como parâmetro na função tratadora de evento
o	Propagação de eventos no modelo bolha (usar target e currentTarget, ou seja, disparar o evento em um elemento filho e capturar em um elemento pai)
•	Acesso aos elementos DOM do HTML
o	Via referência DOM pelo id do elemento HTML - acesso sem uso do getElementByID ou querySelector, o id do objeto DOM é o próprio nome da variável
o	Via getElementByID()
o	Via getElementsByName()
o	Via getElementsByTagName()
o	Via seletores CSS usados na função querySelector() ou querySelectorAll()
•	Tratadores de Evento
o	Especificar o tratador de evento inline - registro do evento no HTML
o	Especificar o tratador de evento no modo tradicional - registro do evento no JS com prefixo on via atributo de um objeto DOM
o	Especificar o tratador de evento com a função addEventListener - registro do evento no JS
o	Usar o operador this em funções tratadoras de eventos.
•	Objetos Nativos
o	Usar pelo menos 3 métodos de manipulação de array
o	Usar laço de repetição (for..in ou for..of ou forEach)
o	Usar pelo menos 3 métodos para manipulação de string
o	String Template - a String com crase e ${}
o	Manipulação do CSS de forma nativa via atributo style e classList
•	Objetos
o	Criar objeto usando função construtora ou notação literal
o	(Obrigatório) Criar objetos a partir da definição de classes do ES6 - a classe precisa ser definida em arquivo separado, sendo o nome do arquivo em letras minúsculas no estilo dashed-case e nome da classe em UpperCamelCase
o	Usar herança prototipal nativa ou herança de classes do ES6
•	Qualidade do código
o	Usar um Style Guide - apresentar o uso de pelo menos 10 regras do style escolhido (sugerido AirBnb)
o	Usar um Lint - corrigir todos os problemas informados pelo lint (sugerido JSHint - usar o arquivo .jshintrc disponível no moodle)
o	Usar strict mode - em todos os arquivos
o	Usar Module Pattern com função auto-executável ou o conceito de módulo do ES6 com operadores export e import
o	Usar pasta assets e subpastas resources e libraries para organizar o código
o	Usar let ou const ao invés de var
o	Nomes de arquivos HTML, JS e CSS minúsculos e separados por hífen (dashed-case)
•	Formulário
o	Validação de formulário com onsubmit usando os métodos tradicionais - é a fase executada após a validação via HTML5
o	Validação de formulário com HTML5 API
	Customizar as mensagens nos balões de mensagem
	Usar os atributos de validação dos inputs - required ou type="email" ou outros
	Usar expressões regulares para validação - usar no atributo pattern do respectivo input
o	Ler e escrever em elementos input com a propriedade value
o	Alterar o conteúdo de elementos div ou p com a propriedade innerHTML ou textContent
o	Manipulação de elemento de listagem, como checkbox, radio ou select
o	Acesso aos elementos de um formulário via hierarquia (caminho) de objetos, ou seja, array forms e elements
•	jQuery
o	Uso de seletores CSS - id, classe e tag
o	Uso de seletores CSS hierárquicos estáticos - ancestral/descendente, pai/filho, anterior/próximo
o	Uso de seletores hierárquicos dinâmicos, ou seja, via métodos do JQuery - parent/children/next
o	Efeitos fade ou slide
o	Especificar o tratador de algum evento para um elemento DOM via jQuery - deve ser um evento diferente do ready
o	Manipulação do CSS via função css() e addClass() ou removeClass()
o	Manipulação do conteúdo de um input e div usando jQuery
o	Aplicar um plugin do jQuery (por exemplo, jQuery Mask Plugin)
•	Web Storage - LocalStorage ou SessionStorage
o	Leitura e escrita de dados simples - dados primivos como string, number, boolean
o	Leitura e escrita de JSON - dado transformado a partir de um objeto
o	Criar e guardar um dado em um Cookie
•	Requisições assíncronas
o	Requisições AJAX para uma implementação funcional do backend em ExpressJS na plataforma Node
o	(Obrigatório) Requisições AJAX para uma API Fake - JSON Server 
o	Requisições AJAX para uma API Rest pública qualquer (Busca CEP API ou IBGE API ou outra).

