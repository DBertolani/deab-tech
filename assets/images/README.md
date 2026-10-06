# Imagens da DEAB Tech

Coloque os arquivos de imagem do site nesta pasta.

## Arquivos usados pela página inicial

### Logo principal
**Caminho:** `assets/images/logo.png`

- Preferência: PNG com fundo transparente.
- Recomenda-se arquivo quadrado, por exemplo 512x512 px.
- Usado no cabeçalho, seção institucional e rodapé.
- O site possui um fallback com a letra "D" caso a imagem ainda não esteja disponível.

### Imagem para compartilhamento
**Caminho:** `assets/images/og-image.jpg`

- Tamanho recomendado: 1200x630 px.
- Usada quando a página for compartilhada em WhatsApp, Facebook, LinkedIn etc.
- Deve representar a DEAB Tech e não precisa conter muito texto.

## Favicon
Os favicons ficam em:

`assets/images/favicon/`

Arquivos esperados:

- `favicon-48.png` — favicon principal.
- `apple-touch-icon.png` — ícone para dispositivos Apple, recomendado em 180x180 px.

Também é possível manter versões adicionais nessa pasta, como 32x32, 192x192 e 512x512.

## Estrutura final

```
assets/
└── images/
    ├── logo.png
    ├── og-image.jpg
    ├── README.md
    └── favicon/
        ├── favicon-48.png
        ├── apple-touch-icon.png
        └── README.md
```

**Importante:** não altere os nomes/caminhos acima sem também atualizar as referências no HTML.
