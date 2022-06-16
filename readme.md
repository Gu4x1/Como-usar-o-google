# COMO USAR O GOOGLE DE FORMA MAIS EFICIENTE


O google é uma das ferramentas de busca mais usadas por todos nós.
mas eu te pergunto

	
### ```VOCÊ SABE REALMENTE COMO USAR O GOOGLE?	```

Neste post irei ensinar alguns truques para agilizar sua busca por um conteudo especifico, sem enrolação e pesquisas que não resultam em dados concretos


# Mas primeiramente irei explicar como o google funciona.

O google é basicamente um indexador de paginas na web, ele possui um *BUSCADOR/CRAWLER* que basicamente vasculha a internet de forma automatizada, em busca de paginas para poder indexalas ao seu motor de busca, alimentando a base de dados para trazer para quem pesquisa sobre aquele determinado assunto.

cada site de busca (google, yahoo, bing, duckduckgo, etc.) possui seu proprio crawler, mas eles basicamente funcionam da mesma forma.

ele funciona pegando a pagina e separando em trechos, como a palavra "ABACATE", ela pode estar em qualquer parte da pagina, no titulo, no conteudo do artigo, nas referencias, etc.

mas ele não busca diretamente por palavras, ele guarda a pagina inteira, então quando queremos uma receita com ABACATE, irá aparecer milhares de resultados que tenha esta palavra em alguma parte de seu conteudo.

Geralmente olhamos para as primeiras paginas, pois elas podem ter mais acessos e ate mesmo pela facilidade que ela foi encontrada na indexação, mas pode acontecer de você não querer realmente aquele conteudo, mas sim por algo mais especifico, como CREME DE ABACATE, porem ainda assim pode ter centenas de resultados que não te agrade, pois é uma pesquisa generalista.

o google trata cada palavra digitada como um "filtro" a ser buscado

então ele pode trazer resultados somente de "creme" e de "abacate"

mas podemos mudar isso usando ***DORKS*** ou ***FILTROS*** para uma busca mais especifica.

REPARE NA QUANTIDADE DE BUSCA ENCONTRADA, pesquisando de forma generalista, e pesquisando com filtro

![image](https://user-images.githubusercontent.com/45929092/174152198-ddbc4087-a5a9-4c43-bf92-b87ea5ea3f6a.png)

4.010.000 - 342.000 = 3,668,000 (3 milhões 668 mil) de paginas que não continham oque voce realmente queria

é gritante a diferença de resultados, certo?

agora que você entendeu como funciona, chega de enrolação e vamos para ***oque realmente interessa!***

## FILTROS DE PESQUISA/DORKS

**TODOS OS FILTROS PODEM SER COMBINADOS PARA UMA MELHOR BUSCA**

Para OPERADORES usamos eles diretamente  ( "" , | , - , + , (), *, ~, &)
para FILTROS usamos ( nomedofiltro:palavra

como no exemplo da imagem o primeiro e talvez o ***mais util*** filtro/operador que irei apresentar é o ***"entre aspas"***


| Operador          | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
|    " "      |  Busca pela sequencia exata que esta escrito                               |        "sopa de abacate"          |

este filtro pesquisa ***exatamente*** pela junção destas palavras, e não por cada uma delas, trazendo exatamente como você pesquisou, sem margem de erros
é muito util pra uma frase, citação, contexto especifico.


| Filtro          | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
| filetype          |   Busca pelo tipo de arquivo                              |         filetype:pdf         |
| ext              | Busca pelo tipo de extensão de arquivo                   | ext:pdf |

Busca por um tipo especifico de arquivo, somente pdf neste caso, é util para busca de livros, papers, documentos etc
mas podemos incluir qualquer formato de arquivo que ela encontra ( doc, xls, pdf, mp3, epub, bkp, txt, ps, ppt, rar, etc.

o ideal é pesquisar da seguinte forma:
```
"livro de jardinagem" filetype:pdf
```

| Filtro          | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
|     intitle      |  Busca pela frase no titulo da pagina                                |         intitle:Prefeitura         |


busca pela palavra que esta EXATAMENTE no titulo da pagina, e não em seu conteudo


| Filtro          | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
| intext          |  Busca pela frase contida no texto da pagina                               |       intext:Curriculo           |

Busca pela palavra dentro de um texto, artigo, pagina

	
| Filtro          | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
|  inurl         | apenas resultados que apareçam na url especifica                                | inurl:facebook.com                  |
| site | resultados no site especifico | site:facebook.com | 

busca apenas no site que foi selecionado, neste caso o facebook, não trazendo resultados de fora do facebook, é util pra achar algo que esta em um site que você sabe que contenha o conteudo que vc busca. 

exemplo:
```
inurl:facebook.com "Grupo de pesca"
site:facebook.com "Grupo de pesca"
```

ele vai trazer somente grupos de pesca dentro do site facebook


| Filtro          | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
|    link       | Busca por paginas que tenham o link pesquisado               | link:orkut.com                 |

Este filtro tras menções a um link dentro de uma pagina, como um link do seu site em algum outro site



| Filtro          | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
| allinpostauthor          | Busca pelo nome do autor                |     allinpostauthor:Alberto             |

Filtro para buscar por um artigo de um autor especifico, funciona para pesquisa em blogs


# OPERADORES

Usamos OPERADORES para "turbinar" a pesquisa ( "" , | , - , + , (), *, ~, &)

misturamos eles com os filtros para melhor filtragem, precisamos repetir o filtro apos o operador para funcionar.

| Operador          | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
|    \|        |  Procura por UM termo OU outro             |   site:facebook.com \| site:orkut.com            |

pesquisa por resultados no facebook ``OU`` no orkut, filtrando apenas para estes 2 sites


| Operador        | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
|     &          |  E /and              |       site:facebook.com & site:orkut.com            |

Procura pelo resultado no facebook ``E`` no orkut



| Operador        | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
| ( )          | Combinação de operadores               |      (site:facebook.com \| site:twitter.com) & intext:"login"          |

Usado para combinar filtros, neste caso procurar pela palavra login no facebook e no twitter



| Operador        | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
|   -        |  Exclui algo da pesquisa              | intext:Fernando -Pessoa                 |

usado para ocultar um resultado que não queiramos, neste caso pesquisar por fernando mas que não tenha nada sobre fernando pessoa, trazendo tudo que NÃO for relacionado a ele


| Operador        | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
|   *        |  qualquer outra coisa               |  site:facebook.*                |

Este operador traz tudo que tiver apos a palavra buscada, neste caso não traz somente facebook.com mas tras facebook.ch / .fr .jp 

exemplo
``
site:facebook.* -site:facebook.com
``

ele vai trazer facebook.qualquercoisa menos facebook.com

| Operador        | Descrição                                          | Exemplo                              |
| :-------------- |:---------------------------------------------------| :------------------------------------|
|  after/before         | resultados entre a data especifica                |    ext:pdf & (before:2022-01-01 after:2021-01-01)           |

before = antes
after = depois

traz pdf que foram postados somente entre a data especifica, bom para pesquisar algo em um ano especifico

mas podemos usar no proprio google o filtro

![image](https://user-images.githubusercontent.com/45929092/174188782-1739be05-670f-42d6-a474-5a1fae1fb300.png)



# Busca reversa de imagem

podemos tambem usar a função de busca reversa de imagem pelo google, ela basicamente procura por uma imagem que você passe pra ela.

exemplo:
você achou a imagem de um quadro e quer ver quem é o possivel autor, se existe a imagem em outra resolução, aonde esta imagem foi postada ou referenciada, ate mesmo para saber aonde fica aquele lugar


na aba IMAGENS possui o icone de uma camera
![image](https://user-images.githubusercontent.com/45929092/174189454-77f97436-ff7e-41a3-b97b-63401dd38b6e.png)

nesta aba possui 2 formas de pesquisa, ou passando a url da imagem, ou enviando a imagem para o google

baixei uma imagem da monalisa, e somente enviei para a pesquisa reversa e o resultado foi 
- Nome do autor
- Referencias de imagens 
- Outros tamanhos/resolução da imagem

![image](https://user-images.githubusercontent.com/45929092/174189898-389bd2cc-38e5-48b2-99d3-41e6acbd5108.png)

Enviando a imagem do cristo redentor ele me trouxe o seguinte resultado
![image](https://user-images.githubusercontent.com/45929092/174190110-20c1d25f-d6c2-4aa0-b556-f340ad65a991.png)


Bom espero ter te ajudado a entender um pouco melhor do poder de busca do google, e que suas pesquisas sejam cada vez mais direcionadas e acertivas com estas dicas
TAMO JUNTO!

