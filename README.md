# Istruzioni-PipeLine
Cosa fare per avere una PipeLine
## Fase 1
1. ==Repository remote== su github con l'api node pubblica del prof e privata nostra suggerisce un git ignore template, selezionare Node nel git ignore si inseriscono gli elenchi di file e cartelle che non devono andare sotto controllo versione

2. ==Dev machine== si lavora in locale e si testa in locare su i nostri portatili 
3. ==VPS== ha una cartella di production con il progetto dove viene clonato il progetto da gitHub e verrà  configurato, fatto girare sul server (`sudo systemctl enable nodejs`)
4. Dopo aver pushato dalla Dev machine dovrai fare il Pull manuale sul tuo VPS


## Fase 2
1.  Avere il pull automatico sul server  dal main branch
2.  Avere un branch di staging per i betatester e sviluppatori 
3. 
