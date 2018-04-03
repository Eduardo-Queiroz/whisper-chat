## Executando o exemplo

O exemplo supõe que há um nó do Whisper v5 em execução que expõe uma interface RPC na URL http://localhost:8545. Para isso, você pode usar gethcom os seguintes parâmetros:`geth` with the folloing parameters:

    $ geth <usual p2p flags> --shh --rpc --rpccorsdomain '*'

--shh é a opção que habilita o Whisper v5 para o nó.

--rpcativa a interface HTTP RPC e --rplccorsdomain '*'desativará essa verificação irritante do CORS no navegador. Escusado será dizer que isto só é aceitável porque este é um exemplo.

Então, clone este repositório e baixe as dependências:

    $ npm install

Por fim, inicie o exemplo com:

    $ npm run dev

O exemplo deve ser iniciado e o aplicativo estará disponível em http://localhost:8080.

