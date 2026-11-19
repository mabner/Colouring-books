# Traço & Anzol — Guia de diagramação (versão de trabalho)

## Objetivo e estado
Especificação inicial para converter as 32 fichas e 32 ilustrações existentes no repositório em um miolo A4 vertical. **Não representa aprovação de prova gráfica, validação científica, nem arquivo pronto para impressão.** Os PNGs originais devem permanecer intactos.

## Formato e encadernação
- Página final: **210 × 297 mm (A4, retrato)**.
- Imagens em preto e branco, sem títulos sobre a arte; ficha informativa na página oposta.
- Uma ilustração por frente de folha, para reduzir marcas de materiais de pintura sobre a próxima ilustração.
- Margens iniciais **de trabalho**: interna 18 mm; externa 12 mm; superior 12 mm; inferior 15 mm. Ajustar após definir encadernação e prova de impressão.
- Sangria: apenas quando a arte ou fundo ultrapassar a linha de corte; ponto de partida 3 mm, condicionado à gráfica. **Não ampliar uma arte com moldura até sangrar**.
- Manter uma área livre ao redor das molduras e não cortar componentes técnicos dos desenhos.
- Exportação final deverá usar perfil, padrão PDF e imposição definidos pela gráfica; evitar presumir CMYK ou 300 ppi apenas pela existência dos PNGs.

## Paginação física: folhas esquerda/direita
Em livros ocidentais, páginas **pares ficam à esquerda (verso)** e **ímpares à direita (frente/recto)**. Para que cada ficha esteja à esquerda da arte correspondente à direita, não se deve iniciar a dupla na página física 1.

**Proposta de miolo com 68 páginas físicas (17 grupos de 4):**
- p. 1: abertura / folha de rosto (direita).
- p. 2–65: 32 duplas — ficha na página par; ilustração na página ímpar.
- p. 66: encerramento / nota editorial.
- p. 67: créditos e informações editoriais (direita).
- p. 68: verso final livre (ou página de testes/observações).
  
Para a ilustração editorial de índice **n** (1–32):
- página física da ficha: **2 × n**
- página física da ilustração: **2 × n + 1**

Exemplos: 01 = ficha 2 / arte 3; 10 = ficha 20 / arte 21; 32 = ficha 64 / arte 65.

**Atenção:** A decisão sobre impressão em folhas soltas com verso em branco, páginas destacáveis, papel e tipo de encadernação pode exigir outro projeto físico. O plano acima é uma proposta de miolo em livro encadernado com páginas duplas visíveis.

## Página esquerda — ficha
Hierarquia sugerida:
1. Número editorial e título.
2. Nome científico, somente quando a ficha tratar de espécie identificada.
3. Tema e identificação (1 parágrafo curto).
4. Sugestões de paleta: 3–5 combinações relevantes.
5. Curiosidade/contexto: 1 parágrafo.
6. Observação técnica: quando pertinente, em corpo discreto.

A ficha deve caber em uma página e não deve repetir avisos genéricos extensos em todas as duplas. Evitar linguagem que transforme diagramas ornamentais em instruções de montagem.

## Página direita — ilustração
- Centralizar o PNG sem distorcer; preservar proporção original.
- Evitar esticar até A4, recortar molduras ou cortar pontas de varas e elementos externos.
- Preservar branco natural para colorir; não aplicar meios-tons automaticamente.
- Conferir manualmente arte em escala de 100% e em amostra impressa.
- Não converter nem sobrescrever os PNGs-mestre ao montar protótipos.

## Resolução: cálculo obrigatório por imagem
- Identificar dimensões reais do PNG (pixels), sem confiar no campo DPI de metadados.
- Calcular ppi efetivo no **tamanho real colocado**: pixels / (largura ou altura impressa em polegadas).
- A meta de referência para arte raster é **300 ppi efetivos**, mas traços muito finos podem exigir mais ou tratamento vetorial; confirmar com gráfica.
- Registrar imagens abaixo da meta em relatório de pré-impressão. **Não declarar que a imagem está em 300 ppi apenas por alterar metadados ou ampliar por interpolação**.

## Revisões antes de fechar
- Correspondência exata entre número, ficha e imagem, segundo `manifesto.json`.
- Conferência de nomes científicos, nomes populares e regiões de ocorrência.
- Verificação visual da anatomia e de equipamentos realistas (especialmente linhas, reel foot, passadores, anzóis e montagens).
- Verificação de texto em português, acentuação, legibilidade, margens, contraste e páginas pares/ímpares.
- Conferência em prova gráfica de papel/gramatura, eventual transparência no verso e facilidade de uso com lápis e marcadores.
- Registrar aprovação por página antes de exportar o PDF final.

## Arquivos de referência
- `../manifesto.json`: caminhos de imagem/ficha em ordem.
- `../sumario.md`: sumário editorial.
- `CHECKLIST_EDITORIAL.md`: validações de texto e arte.
- `PAGINACAO.md`: mapa exato das 32 duplas.
