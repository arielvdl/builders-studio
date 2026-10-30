# Builder Studio — projeto de exemplo

Pasta de projeto exportada do **Builder Studio** (app macOS de gravação e edição de tela).

## Conteúdo

```
projects/AI Demo - Tela Retina Integrada 2026-10-30 11 46 31.builderstudio/
├── project.json          # metadados e configuração da edição
└── recording/
    ├── screen.mp4        # gravação de tela (17s, 3600x2338, 30fps)
    ├── thumbnail.jpg
    └── mouse.json        # trilha de movimento do cursor
```

## Como abrir

1. Instale o Builder Studio no macOS.
2. Copie a pasta `projects/*.builderstudio` para `~/Builder Studio Projects/`.
3. Abra o app e selecione o projeto.

## Formato

`project.json` usa `formatVersion: 1`. Guarda o nome do projeto, a referência à gravação e o `config` da composição (gradiente de fundo, padding, inset, escala, cantos). Os arquivos de mídia ficam em `recording/` e são referenciados por nome de arquivo — por isso o caminho absoluto em `dir` pode ser diferente na sua máquina.

## Observações

- Nenhuma credencial, chave PEM ou token está incluído.
- O `mp4` é a gravação original, sem edição.
