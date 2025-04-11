Compactador de Imagens

Um compactador de imagens baseado em HTML, CSS e JavaScript que permite reduzir o tamanho de imagens JPG e PNG sem perda significativa de qualidade. Suporta dois modos de compressão: redução de resolução e redução de cores (mantendo a resolução original), com pré-visualização em tempo real e indicadores de tamanho e resolução.
Funcionalidades
Suporte a JPG e PNG: Carregue imagens nos formatos mais comuns.

Modos de Compressão:
Reduzir Resolução: Diminui as dimensões da imagem proporcionalmente ao nível de compactação.

Sem Reduzir Resolução: Mantém as dimensões originais, reduzindo o número de cores para compactação.

Pré-visualização em Tempo Real: Veja a imagem original e compactada lado a lado, com atualização dinâmica ao ajustar o slider.

Indicadores: Exibe resolução (largura x altura em pixels) e tamanho do arquivo (em KB) para ambas as imagens.

Slider Interativo: Ajuste o nível de compactação de 10% (mínima) a 100% (máxima) com debounce para melhor desempenho.

Download: Baixe a imagem compactada como PNG.

Não é necessário servidor local, pois o projeto usa apenas recursos estáticos.

Carregue uma Imagem:
Clique no campo de upload e selecione uma imagem JPG ou PNG.

Escolha o Modo de Compressão:
Use os botões de rádio para alternar entre "Reduzir Resolução" e "Sem Reduzir Resolução".

Ajuste a Compactação:
Mova o slider para definir o nível de compactação (10% = mínima, 100% = máxima).

Baixe a Imagem:
Clique no botão "Baixar Imagem" para salvar a versão compactada como PNG.

Tecnologias Utilizadas

HTML5: Estrutura da página e canvas para manipulação de imagens.

CSS3: Estilização moderna com sombras, transições e layout responsivo.

JavaScript: Lógica de compressão, manipulação de canvas e eventos interativos.

