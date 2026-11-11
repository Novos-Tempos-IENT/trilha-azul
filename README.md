# Trilha Azul

Jogo educativo de lógica e pensamento computacional com 50 fases. O jogador prevê o algoritmo e movimenta a bolinha usando as setas do teclado.

## Executar

Abra `trilha-azul.html` em um navegador moderno. O jogo é autocontido, não carrega bibliotecas ou imagens externas e pode ser usado sem conexão depois de baixado.

## Raspberry Pi

Copie `trilha-azul.html` para o Raspberry Pi. Na pasta do arquivo, inicie um servidor local:

```bash
python3 -m http.server 8080
```

No Chromium, abra `http://localhost:8080/trilha-azul.html`. Para acesso de outro aparelho na mesma rede, troque `localhost` pelo endereço IP local do Raspberry Pi.
