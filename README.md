# mestrado


No arquivo [yaml](https://github.com/siliconemonster/mestrado/blob/main/prompts.yaml), você encontrará todos os prompts utilizados na pesquisa.

Abaixo temos um exemplo:

```yaml
experimentos:
  - nome: "Experimento 1 - Geração a partir de prompt"
    prompts:
      - id: 1001
        texto: "gerar linha de baixo sem nenhum outro instrumento"
        resultados: [1001-ETTA-1, 1001-ETTA-2, 1001-ETTA-3, 1001-OV-1, 1001-OV-2, 1001-SN-1, 1001-SN-2, 1001-UD-1, 1001-UD-2]
```

Para encontrar o áudio desejado, basta buscar pelo id do resultado do experimento específico, como por exemplo ```1001-ETTA-1```, na pasta [audio](https://github.com/siliconemonster/mestrado/tree/main/audio).