PixelGrid Studio - Documentação
📌 Visão Geral
O PixelGrid Studio é uma aplicação web interativa para criação de arte pixelada com recursos avançados de pintura. Permite pintar células completas, metades (horizontal, vertical) e diagonais, com suporte para modos claro e escuro, além de exportação em PNG e JSON.

✨ Funcionalidades
Pintura avançada:

Pintura completa de células

Pintura de metades (superior, inferior, esquerda, direita)

Pintura de diagonais (duas direções e seus complementos)

Gerenciamento de cores:

Seletor de cores personalizado

Paleta de cores pré-definidas (Tailwind CSS)

Temas:

Modo claro e escuro

Exportação:

Exportar como imagem PNG (alta qualidade)

Exportar como arquivo JSON para continuar depois

Importação:

Carregar projetos salvos em JSON

Responsivo:

Adapta-se a diferentes tamanhos de tela

🛠️ Tecnologias Utilizadas
HTML5, CSS3 (com variáveis CSS)

JavaScript puro (Vanilla JS)

html2canvas para exportação de PNG

Clip-path CSS para formas avançadas

🚀 Como Usar
Seleção de cor:

Use o seletor de cores ou escolha uma cor pré-definida

Modo de pintura:

Selecione no menu suspenso como deseja pintar (completo, metades, diagonais)

Pintura:

Clique e arraste para pintar na grade

Toque e arraste em dispositivos touch

Limpar:

Use o botão "Limpar Tudo" para reiniciar

Exportação:

PNG: Gera uma imagem da sua arte

JSON: Salva o projeto para continuar depois

Importar: Clique com botão direito ou duplo clique no botão "Exportar Arquivo"

Tema:

Alterne entre modo claro e escuro com o botão correspondente

⚙️ Estrutura do Código
HTML: Estrutura da interface

CSS: Estilos e temas (usando variáveis CSS)

JavaScript:

initializeGrid(): Cria a grade de células

paintCell(): Lógica de pintura

renderCell(): Atualiza a visualização

Funções de exportação/importação

Manipulação de eventos

📦 Exportação/Importação
Exportar PNG
Gera uma imagem em alta resolução (5x escala) da arte atual.

Exportar/Importar JSON
Estrutura do arquivo:

json
{
  "cols": 10,
  "rows": 15,
  "cells": [
    {"full": "#3b82f6", "top": null, "bottom": null, ...},
    ...
  ]
}
Importar: Use o menu de contexto (botão direito) ou duplo clique no botão "Exportar Arquivo"

🌙 Modo Escuro
Alterna automaticamente todas as cores da interface usando variáveis CSS.

📱 Responsividade
A interface se adapta a telas menores, reorganizando os controles verticalmente.
