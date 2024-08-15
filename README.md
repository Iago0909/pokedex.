Pokédex

Introdução ao Projeto

O Projeto a seguir é uma Pokedex criada usando uma API para mostrar o pokémom solicitado e suas evoluções baseadas no anime "Pokemon"

Tecnologias Utilizadas

Javascript: Linguagem de Programação Interpretada Estruturada
Html: Linguagem de Marcação
CSS: Linguagem de Estilização
Api's: para conseguirmos pegar os pokémons e seus dados

Importações Necessárias

Usamos esta importação para poder utilizar uma fonte que encaixar mais com o contexto do projeto

* * /* Importa a fonte 'Oxanium' do Google Fonts */
* @import url("https://fonts.googleapis.com/css?family=Oxanium:wgh@300;400;500;600;700;800&display=swap");

utilizamos esta Const para acionar a API que será utilizada em nossa pokedex para mostrar os dados e imagem dos pokemons

 // Faz uma requisição à API do Pokémon
  const APIResponse = await fetch(`https://pokeapi.co/api/v2/pokemon/${pokemon}`);

  Funcionalidade
esta forma serve para que possamos alocar o número ou nome do pokémon desejado
<form class="form">
      <input type="search" class="input__search" placeholder="Encontrar Pokémon" required>
      </label>
    </form>
ja essas classes que serão estilizadas para ficar dentro dos parâmetros da imagem servem para mostrar o Número, Nome, Peso e Altura do pokemon antes escolhido
<h1 class="pokemon__data">
      <span class="pokemon__number"></span>
      <span class="pokemon__name"></span>
    </h1>

   <h1 class="pokemon__infos">
      <span class="pokemon__height"></span>
      <span class="pokemon__weight"></span>
   </h1>

Link para visualização completa no Site Vercel

• https://vercel.com/iago0909s-projects/pokedex
