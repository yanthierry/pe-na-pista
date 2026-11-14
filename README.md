# Pé na Pista

Jogo de corrida para celular controlado pelo corpo, no estilo Kinect: a câmera frontal detecta seus movimentos e a Capi, uma capivara corredora, repete tudo na pista.

## Como jogar

1. Abra o jogo no navegador do celular (o endereço precisa ser `https`, senão a câmera não é liberada).
2. Apoie o celular deitado, com a tela virada para você, e afaste-se uns 2 metros.
3. Fique parado até o esqueleto ficar verde. A corrida começa em seguida.

| Movimento | O que faz |
| --- | --- |
| Correr no lugar | Avança (quanto mais rápido, mais longe) |
| Passo para o lado ou inclinar o tronco | Troca de pista |
| Pular | Passa as barreiras baixas |
| Agachar | Passa sob as traves altas |
| Esticar o braço num soco | Quebra as paredes |
| Levantar as duas mãos | Joga de novo |

São 60 segundos e três mundos: Céu Pixel, Cidade Neon e Vulcão Arcade. Também dá para jogar por toque (deslizar e tocar) ou pelo teclado (setas e X).

## Publicar no GitHub Pages

Em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`. O jogo fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Tecnologia

Um único arquivo, `index.html`, sem etapa de build. A detecção de pose usa o MediaPipe Pose Landmarker, carregado da internet na primeira partida com câmera. A imagem da câmera é processada no próprio aparelho e não é enviada a lugar nenhum.

