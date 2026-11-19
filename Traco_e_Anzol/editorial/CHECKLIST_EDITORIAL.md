# Traço & Anzol — Checklist editorial e técnico

**Estado inicial:** revisão documental preliminar. As fichas consultadas já usam seções uniformes (identificação, paleta, curiosidade e observação técnica). A revisão abaixo **não significa** que as 32 artes estejam tecnicamente aprovadas para impressão.

## Critérios por página

- [ ] Conferir título, número editorial e arquivo em `manifesto.json`.
- [ ] Conferir descrição da ficha **contra a própria ilustração** (não apenas contra o título).
- [ ] Verificar nomenclatura científica e nome popular quando aplicáveis.
- [ ] Rever detalhes anatômicos: boca, nadadeiras, escamas, barbilhões, manchas e proporções.
- [ ] Rever compatibilidade da modalidade com vara, carretilha/molinete, linha e posicionamento das mãos.
- [ ] Distinguir **vara** de **linha**: linha passa por passadores e sai do **rod tip** sem retornar fisicamente à vara durante a formação do loop.
- [ ] Nas carretilhas de fly: **um único pé de fixação**; linha conectada à carretilha, sem parecer sair da roupa.
- [ ] Em montagem de baitcasting: carretilha sobre a vara, com passadores adequados; em spinning, molinete abaixo da vara.
- [ ] Em surfcasting: conferir suporte, formato e ligação da chumbada, snap, giradores e chicote.
- [ ] Nós de pesca ilustrados não devem ser apresentados como tutorial operacional sem revisão passo a passo.
- [ ] Avaliar se hachuras deixam áreas suficientes para colorir e se traços continuam distinguíveis na prova física.
- [ ] Conferir que não há letras aleatórias, marcas comerciais involuntárias ou figuras impossíveis.
- [ ] Aprovar ficha **e arte** separadamente, registrando data/versão.

## Pontos identificados na leitura inicial do repositório

| Entrada | Situação | Encaminhamento |
|---|---|---|
| 01 — Amanhã na Corredeira | A ficha explica corretamente o papel da linha de fly e do controle pela mão livre. | Conferir se o PNG que está na `main` é a última versão aprovada e se a linha sai do reel, passa pelos passadores e forma o loop apenas após o rod tip. |
| 07 — O Conjunto de Fly | A ficha especifica um único pé de fixação para a carretilha. | Conferir desenho correspondente. |
| 10 — Tucunaré-açu | Ficha usa `Cichla temensis` e menciona ocelo caudal. | Conferir padrão morfológico na arte e se há generalizações por fase de vida. |
| 12 — Traíra | A ficha já qualifica `Hoplias malabaricus` como nome tradicional de complexo de espécies. | Preservar ressalva; não apresentar a identificação artística como laudo taxonômico. |
| 15 — Pintado | A ficha corretamente adverte que bagres não têm escamas grandes. | Conferir a arte para não representar escamas de peixe ósseo escamado. |
| 20 — Nós e Acessórios | A ficha diz que os nós são ornamentais, não tutoriais. | Manter ressalva até auditoria dos passos e voltas. |
| 27 — Betara e Pampo | A ficha reconhece múltiplas espécies sob nomes populares regionais. | Identificar espécies específicas somente se a ilustração permitir. |
| 29 — Chumbadas e Chicotes | A ficha exige revisão de snaps, giradores, derivações e chumbadas. | Não apresentar como montagem operacional testada. |
| 32 — O Canto do Pescador | A ficha pede a versão com um único pé de carretilha. | Confirmar que a arte publicada é a versão aprovada. |

## Política de correções

1. Preservar PNG aprovado até que uma correção nova também seja aprovada.
2. Modificar fichas em commits pequenos, com justificativa factual.
3. Não introduzir dados técnicos não verificáveis como fatos científicos ou recomendações obrigatórias.
4. Resolver divergências entre texto e imagem **antes** da diagramação definitiva.
5. Manter documentação de revisão e de exportação no subdiretório `editorial/`.

## Estado atual

- Estrutura de 32 duplas localizada no repositório.
- Revisão inicial de amostra de fichas realizada.
- Auditoria visual e de resolução dos 32 PNGs **pendente**; conector de GitHub não fornece acesso confiável ao conteúdo binário para essa conferência.
- Nenhum arquivo de ilustração é alterado nesta etapa.
