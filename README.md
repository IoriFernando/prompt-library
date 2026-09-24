# Prompt Library

Biblioteca aberta e versionada de prompts para estudo, pesquisa, experimentação
e aplicações com modelos de linguagem.

<table>
  <tr>
    <td width="220" align="center">
      <img
        src="./sao-benedito.jpg"
        alt="Imagem de São Benedito"
        width="200"
      >
    </td>
<td>
  <p align="justify">
    <em>
      “Fortificai a minha vontade para cumprir bem os meus deveres.
      Vinde orientar-me nas horas decisivas da vida. Dai-me confiança
      nos desânimos e sofrimentos. Sede o meu companheiro nas horas de
      solidão e desconforto.”
    </em>
  </p>

  <p align="right">
    — <strong>Oração de São Benedito</strong>
  </p>
</td>
  </tr>
</table>

## Sobre o projeto

Este repositório reúne prompts reutilizáveis, documentados e organizados por
área de aplicação. Cada prompt apresenta seu objetivo, entradas esperadas,
forma de interação e versão, tornando seu uso mais claro e seus resultados mais
fáceis de reproduzir.

O projeto busca promover:

- instruções claras e fáceis de adaptar;
- aprendizagem e experimentação estruturadas;
- rastreabilidade entre diferentes versões;
- comparação de resultados entre modelos;
- evolução contínua baseada em testes e uso real.


## Início rápido

1. Escolha um prompt no [catálogo](#catálogo).
2. Abra o arquivo e preencha as variáveis indicadas entre colchetes.
3. Copie o conteúdo do prompt, sem o bloco de metadados entre `---`.
4. Envie o conteúdo ao modelo de linguagem de sua preferência.
5. Durante a conversa, siga as etapas e responda às solicitações do prompt.


## Organização do repositório

```text
prompt-library/
├── prompts/
│   └── education/
│       ├── README.MD
│       └── estudo-didatico.md
├── LICENSE
├── README.md
└── sao-benedito.jpg
```

Os prompts ficam agrupados por categoria. O nome dos arquivos utiliza letras
minúsculas e hífens, facilitando links, buscas e automações.

## Padrão dos prompts

Cada arquivo começa com um cabeçalho YAML contendo informações como:

- título, resumo e objetivo;
- público-alvo e metodologia;
- entradas obrigatórias e opcionais;
- idioma, categoria e etiquetas;
- versão e licença.

Depois do cabeçalho vem o texto que será enviado ao modelo. Variáveis editáveis
devem aparecer de forma visível, como `[INSERIR TÓPICO]`.

## Versionamento

Os prompts seguem o formato `MAJOR.MINOR.PATCH`:

- **MAJOR:** mudança que altera significativamente o comportamento ou o fluxo;
- **MINOR:** nova capacidade compatível com o funcionamento anterior;
- **PATCH:** correção de escrita, clareza ou pequenos ajustes de instrução.

## Boas práticas de uso

- Revise referências, citações e informações importantes geradas pelo modelo.
- Forneça contexto suficiente para reduzir respostas genéricas.
- Não inclua dados pessoais, confidenciais ou sensíveis nas variáveis.
- Compare os resultados ao trocar de modelo ou modificar o prompt.
- Registre a versão utilizada quando precisar reproduzir uma experiência.

Prompts orientam o comportamento do modelo, mas não garantem precisão factual.
Em estudos acadêmicos, confirme as informações em fontes primárias confiáveis.

## Contribuições

Contribuições podem incluir novos prompts, exemplos, correções ou melhorias de
documentação. Ao adicionar um prompt:

1. escolha a categoria apropriada;
2. use um nome de arquivo descritivo em `kebab-case`;
3. inclua o cabeçalho YAML e as variáveis necessárias;
4. descreva claramente o fluxo e os critérios de parada;
5. atualize o catálogo deste documento.

## Licença

Na medida permitida por lei, os prompts e a documentação deste repositório foram
dedicados ao domínio público por meio da [CC0 1.0 Universal](./LICENSE).

Você pode copiar, modificar e distribuir este material, inclusive para fins
comerciais, sem pedir autorização ou fornecer atribuição. O reconhecimento da
autoria é bem-vindo, embora não seja obrigatório.
