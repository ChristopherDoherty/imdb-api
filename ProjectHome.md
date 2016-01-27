## Donations/Donativos ##
Feel free to donate/Esteja à vontade para doar:

[![](https://www.paypal.com/en_GB/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=544K7W9JHGJH6&lc=GB&item_number=IMDBDLL&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donate_LG%2egif%3aNonHosted)

## Attention ##
I have made another api, for tv series. It uses the site TheTVDB.com instead of IMDb.
Check it out!

# Description: #

This is a simple API to access IMDb information about movies and tv series.
This was developed with visual studio 2008 and the solution has two projects, the actual API, that creates a dll and a commented test project to show how to use the api. Those are available in the Source section, and now in the downloads section also. In the Downloads section, it's available the most recent version of the dll, ready to be used. In the Downloads section there is also a .chm file with the API and test project documentation.

# Basic functions: #

  * Searchs a movie or a tv-show by title or by ID (if the search is by ID, it loads the right page immediatly, if not, it may load the correct page or a result page with a list of several movies/tv series with that title.

  * Gets the links of a result list page and send them to the main application, where the user must choose one. Then it parses the choosen title and send the information to the user.

  * It allows to get the title, link to imdb, year of release, url to the cover, imdb user rate, the first of the directors, the genres, plot, info of all the actors (or the number selected) listed in the main title page (name, link to actor page, link to picture and character) and the runtime.

  * It is possible to refresh some fields of the title, choosed by the user, without changing all of them.


If you try this and come across some kind of problem, please report it to me.


jpmassena@gmail.com

---


# Descrição: #

Isto é um API simples para aceder a informações sobre filmes e série de TV contidas no IMDb. Foi desenvolvido com o Visual Studio 2008 e a "solution" contém dois projectos, o API em si, que cria um dll e um projecto de teste comentado que demonstra o uso do api. Estes ficheiros estão disponíveis na secção de "Source" e agora também na secção de downloads. Na secção de "Downloads" está a versão mais recente do dll, pronta a ser utilizada. Nesta secção também se encontra um ficheiro .chm que contém a documentação do API e do projecto de teste.

# Funções básicas: #

  * Procura filme ou séries por título ou ID (se a procura é por ID, ele vai directamente à página correspondente, senão pode ir à página correcta ou a uma página com uma lista de resultados com o título procurado.

  * Obtem os links da página de resultados de procura e envia uma lista à aplicação principal onde o utilizador escolhe um dos resultados. Depois o api faz o parse da pagina escolhida e envia a informação à aplicação principal.

  * As informações que podem ser obtidas são: o título original, o link para IMDb, ano de lançamento, url para a capa, pontuação IMDb, o 1º realizador, géneros, sinopse, informação sobre todos os actores (ou só os primeiros "x" que decidir) listados na página normal do título (nome, link para a pagina, link para a foto e personagem desempenhada) e o tempo de duração.

  * É possível actualizar alguns dos campos, escolhidos pelo utilizador, sem alterar os outros.


Se experimentar este software e encontrar algum erro ou bug, por favor informe-me.


jpmassena@gmail.com