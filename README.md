# Flutecrafter

Editor de partituras e player com **som real de flauta transversal**, no mesmo formato do Saxcrafter (PWA em um único `index.html`).

- Grade de notas de **C4 a D7** (extensão da flauta em dó): criar, mover, esticar, acordes, ímã, compassos sem limite.
- **Painel de digitação**: mostra a flauta com as teclas pressionadas em verde para a nota selecionada, ouvida ou tocada (acompanha o ▶).
  Quando há outra digitação, ela aparece menor no canto; tocar nela troca as duas.
- Botão 🎶 **Digitação**: tabela completa de C4 a D7 (39 notas, 16 com digitação alternativa).
- Salvar na biblioteca do app ou numa pasta, exportar MIDI, WAV, JSON e partitura em PDF; importar MIDI e projetos.
- Partitura para flauta em dó, flautim ou flauta alto em sol.

## Publicar
Coloque todos os arquivos desta pasta na raiz do repositório do GitHub Pages (index.html, sw.js, manifest.json, manifest.webmanifest e os ícones).

## Som
Gravações reais da flauta do **Versilian Studio Community Sample Library 2** (CC0 / domínio público), obtidas pelo repositório
[tonejs-instruments](https://github.com/nbrosowsky/tonejs-instruments) (MIT), processadas para 22,05 kHz com loop pitch-sincronizado.
Estão embutidas no `index.html`, então o app funciona offline depois da primeira visita.
