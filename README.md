# Bedrock JSON UI Editor V2

Editor visual para criar/testar uma prévia de JSON UI do Minecraft Bedrock.

## Novidades da V2
- Fundo personalizado da prévia: escolha uma print do Minecraft pela galeria.
- A print fica atrás dos elementos e não é incluída no JSON exportado.
- Controle de opacidade do fundo.
- Ajuste da imagem: Preencher, Encaixar ou Esticar.
- O fundo fica salvo no navegador para continuar o trabalho depois.
- Resolução da tela altera automaticamente a proporção da área de edição.
- Zoom pelo botão e pelo scroll/pinça com o navegador.
- Mantém o editor visual e a exportação da V1.

## Como usar
1. Abra `index.html` ou publique os arquivos no GitHub Pages.
2. Toque em **🖼️ Fundo Minecraft**.
3. Escolha uma captura de tela do Minecraft.
4. Monte o menu por cima da captura para conferir visualmente a posição.
5. Exporte o JSON quando terminar.

### Observação
A V2 ainda usa o formato de preview simplificado:
`{ screen: {width,height}, elements: [...] }`.
O fundo é somente uma referência visual do editor e não altera o JSON exportado.

## GitHub Pages
Envie `index.html`, `style.css`, `app.js` e `README.md` para o repositório e ative o GitHub Pages.
