# Dados derivados do MMU-FRiP

Os ficheiros `P*.json` e `manifest.json` desta pasta derivam do dataset MMU-FRiP
(Kaggle, DOI 10.34740/KAGGLE/DSV/15068715), licença CC BY-SA 4.0
(https://creativecommons.org/licenses/by-sa/4.0/).

Alterações: pose 3D (HybrIK, SMPL-24) de participantes escolhidos, rodada para uma vista lateral comum, convertida
em metros, reduzida a 15 fotogramas por segundo e arredondada ao centímetro; fases e medidas calculadas por
`src/lib/tugPhases.ts` (ver `scripts/side_view.py` e `validation/cases.val.ts`).

Estes ficheiros são partilhados nos mesmos termos (CC BY-SA 4.0). O código da app tem a sua própria licença, a decidir.
O dataset não traz declaração de ética nem de consentimento: confirmar com os autores antes de publicar.
