Trabalho Final de Computação Gráfica
Lucas Trentini Bordin

Explicação do trabalho:
O trabalho consiste em uma representação em 3D do jogo Skyscrapers, que costuma 
ser jogado apenas com uma grade 2D. O jogo consiste em preencher uma grade 
com números referentes a tamanhos (andares) de prédios, de forma que os números 
presentes nos lados da grade representem o número de prédios que é possível 
enxergar quando olhando a partir do "chão" naquela linha por aquele lado. Além 
disso, nenhuma linha ou coluna pode contar com dois ou mais prédios do mesmo
tamanho. (Para mais detalhes sobre as regras: https://puzz.link/rules.html?skyscrapers)

A ideia do trabalho é a transformação para 3D deste jogo, para que seja possível
visualizar de fato quantos prédios são visíveis de cada lado sem a necessidade
de abstração. Para isso, foi utilizada uma grade onde podem ser adicionados
voxels para a representação dos andares dos prédios.

Controles:
Clique (botão esquerdo): adicionar voxel em uma face selecionada
Clique (botão direito): remover voxel selecionado
Clique (botão direito - arrastar): mover câmera
Teclas numéricas 0-9: mudar a cor dos próximos voxels adicionados (apenas para demarcação, não afeta as regras do jogo)

Funcionamento:
Ao adicionar um voxel, ele automaticamente apresentará o número do andar de um prédio que representa.
O jogo conta com apenas uma fase, e não faz a detecção automática de quando a fase é
terminada. Isso fica a cargo do jogador (tal qual no jogo original, que é jogado a papel e caneta).
A solução final do jogo está disponível na imagem a seguir: https://imgur.com/HWP4qw5


A página do jogo está presente no arquivo Skyscrapers3D.html.
Para a implementação, foram utilizados como base exemplos de Lee Stemkoski no GitHub.