R-kode til bachelorprojektet bruger følgende pakker:

```r
install.packages(c("cvar", "quantmod", "rugarch", "pheatmap",
                   "gridExtra", "ggplot2", "dplyr", "tidyr", "knitr"))
```
Filerne deler et globalt miljø i R, så nogle bruger objekter fra en tidligere fil. Hvis man ønsker at genskabe projektets resultater køres i samme session denne rækkefølge:

1. t-fordelinger, teststørrelser og teststyrker (Afsnit 4)
2. Genskabte Acerbi plots 
3. Heatmaps og styrkeplots (Afsnit 4) 
4. VaR vs. ES plot
5. GARCH(1,1) (Afsnit 5) 
6. HS & WHS (Afsnit 6)
7. Stabilitet af Z2, Z3 & CC under GARCH
8. DS Backtest og kontrolleret misspecifikation 
9. DS under severity misspecifikation 
10. DS under GARCH frekvens misspecifikation 
11. DS på C25 & Danske Bank 

De fleste filer sætter et fast seed. 
Fuld kørsel tager flere timer. Sænk M for en hurtigere test, dette vil dog (i mindre grad) påvirke resultaterne.
