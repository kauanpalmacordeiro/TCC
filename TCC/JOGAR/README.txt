BET — SIMULADOR / V4

ARQUIVOS
- jogar.html
- jogar.css
- jogar.js
- assets/audio/*
- CREDITOS-AUDIO.txt

CAMINHOS PREPARADOS PARA O PROJETO FINAL
- Voltar ao início: ../INICIO/index.html
- TCC: ../TCC/tcc.html
- Quem: ../QUEM/quem.html

ALTERAÇÕES DA V4
- Pontos agora são progresso permanente: zerar o saldo NÃO apaga os pontos.
- Recomeçar com R$ 100 preserva pontos e níveis já comprados.
- Pontos, upgrades, tema, símbolos, máquina e preferências de áudio ficam salvos no localStorage.
- Música e efeitos sonoros têm botões independentes.
- É possível deixar a música ligada e desligar apenas os efeitos, ou o contrário.
- Playlist ambiente ampliada com mais 3 faixas longas (4–5 min) além das anteriores.
- Desktop/notebook: caça-níquel e painéis são compactados de forma responsiva para caber na viewport sem precisar rolar a página.
- Em telas muito baixas o JS aplica apenas o scale mínimo necessário para manter tudo dentro da tela.
- Cards dos upgrades estão maiores e agora explicam claramente o que cada melhoria altera.
- Personalização foi separada em três dimensões: FIGURAS, DESIGN DA MÁQUINA e TEMA DA PÁGINA.
- Os quatro designs da máquina agora mudam de fato a carcaça: Clássica, Arcade, Cofre e Orbit.
- O tema da página continua independente: Roxo, Vermelho, Amarelo ou Ciano, sempre combinado ao preto.

PONTOS
- Se perder R$ 100 numa rodada, recebe 100 pts.
- Se receber R$ 100 em prêmio, recebe 100 pts.
- Os pontos só diminuem quando o usuário compra um upgrade.
- Saldo zerado: dinheiro volta a R$ 100 ao recomeçar; pontos e upgrades permanecem.

UPGRADES
1) Chance de ganho
N0 base | N1 +5% | N2 +7,5% | N3 +10% | N4 +15% | N5 +20%
Custos: 10.000 / 40.000 / 140.000 / 480.000 / 1.600.000 pts

2) Multiplicador de ganho
100% / 107,5% / 115% / 125% / 140% / 160%
Custos: 15.000 / 55.000 / 180.000 / 600.000 / 1.900.000 pts

3) Prêmio de risco (jackpot de 9 iguais)
200x / 230x / 270x / 320x / 400x / 500x
Custos: 20.000 / 75.000 / 240.000 / 780.000 / 2.400.000 pts

PERSONALIZAÇÃO
- Figuras: frutas, cassino, cores, países e aleatório.
- Máquina: Clássica, Arcade, Cofre e Orbit.
- Página: Roxo + preto, Vermelho + preto, Amarelo + preto e Ciano + preto.
- Máquina e página são escolhas separadas.

TESTE
O botão TESTE R$ 1M continua presente para acionar rapidamente o evento final.

ÁUDIO
- Botão MÚSICA: controla somente a playlist ambiente.
- Botão EFEITOS: controla clique, giro, paradas, vitória, upgrade, circuito e vidro.
- Os efeitos essenciais estão locais dentro de assets/audio/.
- A playlist tenta faixas longas da internet; se elas não carregarem, usa ambient_long.ogg local automaticamente.
- Para permitir áudio no navegador, clique em ENTRAR NO JOGO primeiro.
