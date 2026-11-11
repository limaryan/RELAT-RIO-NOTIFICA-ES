# RELATÓRIO NOTIFICAÇÕES (v1.2.2)

Aplicação web (HTML/JS puro) com Boletim, Radar, Top 10 e Analistas.

## Publicar no GitHub Pages
1. Crie um repositório e envie `index.html`, `README.md` e `.nojekyll`.
2. Em Settings > Pages, escolha a branch `main` e a pasta `/ (root)`.
3. Abra o endereço gerado.

## Uso
- Clique em "Subir planilha relatório" (.xls/.xlsx). Pode subir vários arquivos (ex.: 2025 e 2026); duplicados são removidos pelo código (coluna C).
- Colunas lidas: C código, G setor notificante, H setor notificado, I data (mês/ano), N classificação, V fato ocorrido, W analista.
- Os dados ficam só no navegador (IndexedDB). NÃO envie as planilhas ao GitHub: contêm registros de pacientes.
- Requer internet para carregar Chart.js e SheetJS (CDN).
- Superintendências: embutidas no `index.html` (variável `SUP`).

## Gráficos
Cada gráfico pode ser redimensionado arrastando o canto inferior direito. Use "Gráficos lado a lado" para alternar o layout e "Restaurar tamanhos" para voltar ao padrão.
