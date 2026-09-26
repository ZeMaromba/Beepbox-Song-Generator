# BeepBox Song Generator

Gerador de trilhas caóticas e aleatórias para BeepBox a partir de texto em Morse. O projeto transforma caracteres em sequências de notas, com variações de escala, repetições, lacunas e exportação em formato JSON compatível com BeepBox.

## O que ele faz

- recebe texto em um campo de entrada;
- converte cada caractere em código Morse;
- gera notas com base em uma escala escolhida;
- aplica repetições e preenchimento de lacunas;
- permite ajustar BPM, compassos, ticks e tamanho da nota;
- exporta a música em um arquivo JSON para importar no BeepBox.

## Tecnologias

- HTML
- JavaScript
- Canvas para visualização da música
- Web Audio API para reprodução simples

## Como rodar localmente

1. Clone o repositório:

```bash
git clone https://github.com/ZeMaromba/Beepbox-Song-Generator.git
cd Beepbox-Song-Generator
```

2. Abra o arquivo `index.html` no navegador.

Se preferir rodar com um servidor local:

```bash
python -m http.server 8000
```

Depois abra no navegador:

```text
http://localhost:8000
```

## Como usar

- Digite o texto no campo principal.
- Ajuste as opções de:
  - escala;
  - número de repetições;
  - BPM;
  - compassos por barra;
  - ticks por batida;
  - preenchimento de lacunas.
- A música será gerada automaticamente enquanto você digita.
- Clique no botão de reprodução para ouvir a trilha.
- Use a função de exportação para baixar o JSON e importar no BeepBox.

## Estrutura do projeto

- `index.html` — interface principal
- `generator.js` — lógica da geração musical
- `README.md` — documentação do projeto

## Observações

Este projeto foi pensado como uma ferramenta criativa e experimental para gerar música caótica e pouco previsível. A ideia central é transformar texto em música usando variações aleatórias e regras simples de escala, sem depender de uma composição tradicional.

## Licença

Este projeto não possui uma licença definida no momento. Se você pretende usar ou compartilhar o código publicamente, vale verificar se a licença é necessária antes de publicar em produção.

## Autor

ZeMaromba

## Link do repositório

https://github.com/ZeMaromba/Beepbox-Song-Generator
