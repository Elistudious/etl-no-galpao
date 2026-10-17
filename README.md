# 🚚 ETL no Galpão

Uma animação interativa que explica **ETL (Extract, Transform, Load)** usando algo que quase todo mundo já viu: um galpão de logística.

A ideia veio de um bico que fiz em uma logística de e-commerce. Vendo o caminho que cada pacote percorre até chegar na mão do cliente, percebi que era exatamente o que fazemos com dados em um pipeline.

## Como o galpão vira um pipeline

| No galpão | No pipeline de dados |
|---|---|
| Caminhão chega e descarrega | **Extract**: buscar os dados na fonte |
| Robôs separam cada pacote por esteira | **Transform**: classificar por regra |
| Leitor confere o código de rastreio | Validação de dados |
| Pacote na esteira errada volta e é corrigido | Tratamento de erros e reprocessamento |
| Gaiola e doca despacham pro caminhão certo | **Load**: gravar no destino, em lotes |

## O que dá pra fazer na página

- **Chamar caminhão** e acompanhar o fluxo completo.
- **Modo pressa**: os robôs erram mais e você vê a correção acontecendo.
- **Modo automático** e **velocidade 2x**.
- Cards de cada etapa com "No galpão" e "No código" (exemplos em pandas).

## Como rodar

É um único arquivo HTML, sem dependências. Abra o `index.html` no navegador.


