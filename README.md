# Pokedex
Projeto realizado em React para o trabalho avaliativo do primeiro bimestre.

Nome: Vitor Hugo de Oliveira        Código: 24073

Link do Surge: https://special-rake.surge.sh/

Imagens do projeto:

Tela Home:
![image](https://user-images.githubusercontent.com/92445126/160137369-c9098a2b-ff22-46ea-a664-9a8050b26e36.png)

Tela da lista de Pokemons:
![image](https://user-images.githubusercontent.com/92445126/160142175-66d177c0-871e-4376-bace-30e78b09d138.png)

Tela Detalhes do Pokemon:
![image](https://user-images.githubusercontent.com/92445126/160142355-b9c16c99-6d2b-4515-af11-170c8643be41.png)

Projeto:

Renderização dos 20 primeiros pokemons na tela Home:

Ao acessar a página inicial do site, você será recebido com uma exibição dos 20 primeiros Pokémon. Isso permite que os usuários tenham uma visão geral dos Pokémon disponíveis de forma rápida e fácil.

Botão de adicionar a uma lista e ver detalhes:

Cada Pokémon exibido na tela inicial será acompanhado por um botão que permite ao usuário adicioná-lo a uma lista pessoal. Além disso, ao clicar em um Pokémon específico, os usuários terão a opção de visualizar detalhes adicionais sobre ele.

Botão de detalhes Troca de páginas que troca para a página de detalhes:

Ao clicar no botão de detalhes em um Pokémon na tela inicial, os usuários serão direcionados para uma página separada que contém informações mais detalhadas sobre aquele Pokémon específico. Isso inclui detalhes como imagem, movimentos e tipo do Pokémon.

Renderização na tela de detalhes da imagem, movimentos e o tipo do pokemon:

Na página de detalhes de cada Pokémon, os usuários poderão ver uma representação visual do Pokémon por meio de sua imagem. Além disso, serão exibidos os movimentos que o Pokémon pode aprender e o tipo ao qual ele pertence, fornecendo uma compreensão mais completa de suas habilidades e características.

Recursos:

Configuração do Projeto:

Crie um novo projeto React usando o Create React App:
npx create-react-app 'nome do arquivo'

Navegue até o diretório do projeto:
cd pokemon-app

Instale a biblioteca Axios para fazer requisições HTTP:
npm install axios

Alguns dos componentes já estâo instalados nas pastas do arquivo, mas caso se faça necessário:

Configuração do Ambiente:

Instale o Node.js no seu computador, se ainda não o tiver.
Abra o terminal (ou prompt de comando) e execute o seguinte comando para instalar o React CLI: 

npm install -g react-cli.

Isso permite que você crie e gerencie projetos React.

Criação do Projeto:

No terminal, navegue até o diretório onde deseja criar o projeto.
'cd 'nome da pasta'
Execute o comando 
'npx react init NomeDoProjeto' 
para criar um novo projeto React.
Aguarde até que o processo de instalação esteja completo.

Contudo caso não queira acessar pelo link anexado, utilize o local host com as seguintes instruções:

Scripts Disponíveis no diretório do projeto, você pode executar:

'npm start'
Executa o aplicativo no modo de desenvolvimento.
Abra http://localhost:3000 para visualizá-lo em seu navegador.

A página será recarregada quando você fizer alterações.
Você também pode ver erros de lint no console.

'npm test'
Inicia o executor de teste no modo de observação interativo.

'npm run build'
Cria o aplicativo para produção na pasta de construção.
Ele agrupa corretamente o React no modo de produção e otimiza a construção para obter o melhor desempenho.

A compilação é reduzida e os nomes dos arquivos incluem os hashes.
Seu aplicativo está pronto para ser implantado!

'npm run eject'
Nota: esta é uma operação unilateral. Depois de ejetar, você não pode voltar!

Se não estiver satisfeito com a ferramenta de compilação e as opções de configuração, você poderá ejetar a qualquer momento. Este comando removerá a dependência de compilação única do seu projeto.

Em vez disso, ele copiará todos os arquivos de configuração e as dependências transitivas (webpack, Babel, ESLint, etc) diretamente no seu projeto para que você tenha controle total sobre eles. Todos os comandos, exceto ejetar, ainda funcionarão, mas apontarão para os scripts copiados para que você possa ajustá-los. Neste ponto você está sozinho.

Você nunca precisa usar ejetar. O conjunto de recursos selecionados é adequado para implantações pequenas e médias e você não deve se sentir obrigado a usar esse recurso. No entanto, entendemos que esta ferramenta não seria útil se você não pudesse personalizá-la quando estiver pronto para isso.

Obrigado por chegar até aqui, espero que tenha costado do meu projeto e tenha montado um bom time com os pokemons disponibilizados.