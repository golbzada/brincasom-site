# Predefinição (Preset): Efeito de Livros Sobrepostos (Fan Effect)

Este preset recria o efeito visual de apresentação de livros/apostilas em leque da coleção **Leitura Inteligente (Saberes)**, permitindo que os livros se sobreponham suavemente ao passar o mouse (Desktop) ou ao clicar/tocar (Mobile).

## Arquivos:
- `presets/fan-books-effect.css`: Estilos de posicionamento em leque, rotação, elevação, sombras e responsividade.

## Estrutura HTML:

```html
<div class="stage-fan">
  <div class="fan-5-books">
    <div class="cv cv-1" onclick="this.classList.toggle('active')">
      <img src="asset/images/apostila01_rimas.png" alt="Apostila 01 - Rimas">
    </div>
    <div class="cv cv-2" onclick="this.classList.toggle('active')">
      <img src="asset/images/apostila02_aliteracao.png" alt="Apostila 02 - Aliteração">
    </div>
    <div class="cv cv-3" onclick="this.classList.toggle('active')">
      <img src="asset/images/apostila03_conciencia_de_palavras.png" alt="Apostila 03 - Consciência de Palavras">
    </div>
    <div class="cv cv-4" onclick="this.classList.toggle('active')">
      <img src="asset/images/apostila04_conciencia_silabica.png" alt="Apostila 04 - Consciência Silábica">
    </div>
    <div class="cv cv-5" onclick="this.classList.toggle('active')">
      <img src="asset/images/apostila05_conciencia_fonemica.png" alt="Apostila 05 - Consciência Fonêmica">
    </div>
  </div>
</div>
```
