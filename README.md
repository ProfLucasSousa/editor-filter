# Mini Editor de Imagem com CSS Filter

Projeto didático que demonstra como combinar JavaScript, DOM e a propriedade CSS `filter` para editar uma imagem diretamente no navegador.

## Funcionalidades

- Ajuste de brilho, contraste e saturação.
- Conversão para escala de cinza ou sépia.
- Controle de desfoque e inversão de cores.
- Visualização do CSS gerado em tempo real.
- Botão para restaurar os valores iniciais.
- Layout responsivo.

## Tecnologias

- HTML5
- CSS3
- JavaScript

## Como executar

Não há dependências ou etapa de build. Abra o arquivo `index.html` no navegador ou use um servidor local:

```bash
python -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Estrutura

- `index.html`: interface e controles.
- `style.css`: layout e responsividade.
- `script.js`: leitura dos controles e aplicação dos filtros.

A imagem inicial é carregada do Picsum Photos e exige conexão com a internet.
