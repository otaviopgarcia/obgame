# Ate Voce

**Ate Voce** e um jogo de luta 2D para navegador. O jogador atravessa uma trilha, enfrenta ondas de zumbis e encontra o outro personagem no final do caminho.

## Como jogar

1. Abra o arquivo `atevoce.html` no navegador ou sirva a pasta com um servidor local.
2. Escolha entre **Tavio** e **Beckman**.
3. Clique em **Comecar** ou pressione **Enter**.
4. Percorra a trilha, derrote todos os zumbis de cada onda e alcance o outro personagem.

Ao chegar ao destino, aparece a cena final com os dois personagens se reencontrando.

## Controles

### Teclado

| Acao | Controles |
|---|---|
| Andar para a esquerda | `A` ou `Seta para a esquerda` |
| Andar para a direita | `D` ou `Seta para a direita` |
| Pular | `W`, `Seta para cima` ou `Espaco` |
| Soco | `J` |
| Defender | `K`, `Shift esquerdo` ou `Shift direito` |
| Selecionar personagem | `Seta para a esquerda` ou `Seta para a direita` |
| Iniciar o jogo | `Enter` |

### Dispositivos moveis

Em telas de toque, botoes aparecem na parte inferior da tela:

| Botao | Acao |
|---|---|
| `◀` | Andar para a esquerda |
| `▶` | Andar para a direita |
| `⤒` | Pular |
| `🛡` | Defender |
| `👊` | Socar |

## Combate

- Os personagens possuem pontos de vida exibidos no canto superior esquerdo.
- Pressione o botao de soco duas vezes em sequencia para realizar um combo.
- Defender reduz o dano recebido e diminui o empurrrao.
- Zumbis possuem ataques e quantidade de vida diferentes.
- Se o personagem perder todos os pontos de vida, ele retorna ao checkpoint.
- Complete todas as ondas para liberar o caminho ate o final da trilha.

## Executando localmente

Como o jogo usa imagens locais, recomenda-se abrir pelo servidor HTTP da propria pasta:

```powershell
cd C:\Users\otavi\Desktop\obgame
python -m http.server 8000
```

Depois, acesse `http://localhost:8000/atevoce.html` no navegador.
