Endless Run 🏃‍♂️

Protótipo de jogo 3D no estilo endless runner, inspirado no Subway Surfers, desenvolvido em C# com Unity 2022.3 LTS (2022.3.14f1).

Mostrar imagem

▶️ Assista ao gameplay no YouTube:
LINK: https://youtu.be/Kq0jPZdDg2Q?si=cHABr86EE8GrtS5D

🎮 Sobre o projeto:

O jogador corre sem parar por uma pista gerada de forma contínua, desviando de obstáculos e coletando moedas. O objetivo do projeto foi praticar os fundamentos de desenvolvimento de jogos: geração procedural de cenário, física, colisões, animação e interface.

✨ Funcionalidades:
 - Pista infinita com reciclagem de plataformas (detalhes abaixo)
 - Personagem animado: animação de corrida e de queda ao colidir
 - Obstáculos que encerram a partida e exibem a tela de Game Over
 - Moedas colecionáveis
 - HUD com distância percorrida e moedas coletadas
 - Controles: mover para a esquerda, para a direita e pular (o personagem não anda para trás)
 
⚙️ Como funciona a pista infinita:

Em vez de criar e destruir cenário o tempo todo, o jogo usa três plataformas que se revezam:

 1 - Cada plataforma carrega um conjunto diferente de obstáculos e moedas.
 2 - Quando o jogador chega à segunda plataforma, a primeira (já fora da tela) é reposicionada à frente da terceira.
 3 - Um cálculo baseado em ângulo garante que as plataformas não se sobreponham ao serem reposicionadas.

Essa técnica (semelhante a um object pooling) mantém o uso de memória constante, por mais longa que seja a partida.

🖼️ Capturas de tela
<p align="center"> <img src="https://github.com/OverComeTm/Endless-Run/assets/70177226/9008ea7e-b1af-4d2d-8dfd-5c77ca55c580" width="45%" /> <img src="https://github.com/OverComeTm/Endless-Run/assets/70177226/5edc724b-dba7-4e0a-a1f5-f13bc565e738" width="45%" /> <img src="https://github.com/OverComeTm/Endless-Run/assets/70177226/b567358b-43cd-484d-8745-25098cca0d3e" width="45%" /> <img src="https://github.com/OverComeTm/Endless-Run/assets/70177226/dbb7b302-e1d5-4880-aa7a-a62900c43855" width="45%" /> <img src="https://github.com/OverComeTm/Endless-Run/assets/70177226/753cba76-699c-4d10-9de0-09ad5cfa965a" width="45%" /> <img src="https://github.com/OverComeTm/Endless-Run/assets/70177226/6e37f967-bf05-4f3a-aee8-99609b2c7e7e" width="45%" /> <img src="https://github.com/OverComeTm/Endless-Run/assets/70177226/9b12ead5-068d-4bf8-a5f6-80dd8998e020" width="45%" /> <img src="https://github.com/OverComeTm/Endless-Run/assets/70177226/0ebe4d59-586f-46db-9987-a1316b2ea34c" width="45%" /> <img src="https://github.com/OverComeTm/Endless-Run/assets/70177226/89b9ca4a-8446-4346-ac46-b507d23ec5c2" width="45%" /> </p>

🛠️ Tecnologias:
 - C#
 - Unity 2022.3 LTS (2022.3.14f1)
 
▶️ Como executar:
1 - Clone o repositório:
     "bash
     git clone https://github.com/alexsousaadev/Endless-Run.git"
2 - No Unity Hub, instale o editor 2022.3.14f1 (ou outra versão 2022.3 LTS) e clique em Add project from disk para abrir a pasta do projeto.
3 - Abra a cena principal em Assets/Scenes/ <!-- confirme o nome da cena --> e clique em Play.

🚧 Próximos passos
Efeitos sonoros e trilha
Mais animações (pulo, desvio lateral)
Mais variedade de obstáculos e objetos na pista
Aumento gradual de velocidade e dificuldade

👤 Autor

Alex Sousa: GitHub · LinkedIn

Projeto desenvolvido durante a graduação em Engenharia de Software (FACEF, Franca/SP).


