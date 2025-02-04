---
title: "Julie Thesis Results"
author:
- Julie A. Nadeau
- Douglas A. Campbell
date: "2024-03-11"
output:
  html_document:
    df_print: paged
    code_folding: hide
    keep_md: yes
    fig_caption: yes
    toc: TRUE
    toc_float: TRUE   
csl: plos-one.csl
---

```r
Figures<-file.path("..","code","Figures")
```

## Results & Discussion



```r
knitr::include_graphics(file.path(Figures,"LRCplot.png"))
```

<div class="figure">
<img src="../code/Figures/LRCplot.png" alt="PSII electron transport (e- PSII-1 s-1) vs measurement light (µmol photons m-2 s-1) for *Prochlorococcus* strains MED4 (Clade HLI) and MIT9313 (Clade LLIV) after growth under different combinations of light level (30, 90, 180 µmol photons m-2 s-1) and oxygen concentration (2, 25, 250 uM). The green points represent the experimental data, the black line denotes the fitted model (CITATION), and the red points denote residuals." width="100%" />
<p class="caption">PSII electron transport (e- PSII-1 s-1) vs measurement light (µmol photons m-2 s-1) for *Prochlorococcus* strains MED4 (Clade HLI) and MIT9313 (Clade LLIV) after growth under different combinations of light level (30, 90, 180 µmol photons m-2 s-1) and oxygen concentration (2, 25, 250 uM). The green points represent the experimental data, the black line denotes the fitted model (CITATION), and the red points denote residuals.</p>
</div>







```r
knitr::include_graphics(file.path(Figures,"FittedLRCMED4.png"))
```

<div class="figure">
<img src="../code/Figures/FittedLRCMED4.png" alt="Fitted LRC of PSII electron transport (e- PSII-1 s-1) vs measurement light (µmol photons m-2 s-1) for *Prochlorococcus* strain MED4 (Clade HLI) and after growth under different combinations of light level (30, 90, 180 µmol photons m-2 s-1) and oxygen concentration (2, 25, 250 uM), derived from light response curve fits (XXXRefer to Figure). The curves are differentiated by varying oxygen concentrations (colors), with different panels representing different combinations of light levels and growth oxygen concentrations." width="100%" />
<p class="caption">Fitted LRC of PSII electron transport (e- PSII-1 s-1) vs measurement light (µmol photons m-2 s-1) for *Prochlorococcus* strain MED4 (Clade HLI) and after growth under different combinations of light level (30, 90, 180 µmol photons m-2 s-1) and oxygen concentration (2, 25, 250 uM), derived from light response curve fits (XXXRefer to Figure). The curves are differentiated by varying oxygen concentrations (colors), with different panels representing different combinations of light levels and growth oxygen concentrations.</p>
</div>


The FIGURE displays a series of fitted light response curves (LRCs) depicting PSII electron transport for the *Prochlorococcus* strain MED4 under varying environmental conditions. Each panel represents a unique experimental conditions, combining different light intensities (30, 90, 180 µmol photons m^-2 s^-1) with distinct oxygen concentrations (2, 25, 250 µM). The y-axis representes the fitted PSII electron transport rate, while the x-axis represents the corrected photosynthetically active radiation (ActPARCorr). The curves are color-coded to denote different oxygen concentrations: red for 2 µM, green for 25 µM, and blue for 250 µM.
The observations extracted from the light response curves (LRCs) of PSII electron transport in Prochlorococcus strain MED4 provide valuable insights into how photosynthesis responds to changing environmental factors. Notably, we observe that as light intensity increases, the rate of electron transport also rises, indicating that the photosynthetic system becomes more active with greater light exposure. At lower light levels, this increase is gradual, suggesting efficient light utilization, while at higher intensities, there's a point where the system becomes saturated, unable to process additional light effectively. Another finding is the influence of oxygen concentration on electron transport rate. We notice that higher oxygen levels correlate with increased electron transport, especially noticeable under higher light conditions. This suggests that oxygen might play a role in enhancing photosynthetic efficiency, possibly by aiding in the regulation of electron transport or providing additional energy sources. Additionally, the varying responses across different oxygen concentrations highlight the intricate relationship between light availability and oxygen levels in shaping photosynthetic activity. 

Overall, these observations shed light on how *Prochlorococcus* MED4 adjusts its photosynthetic process to environmental changes, offering valuable insights into microbial responses in marine ecosystems.



```r
knitr::include_graphics(file.path(Figures,"FittedLRCMIT9313.png"))
```

<div class="figure">
<img src="../code/Figures/FittedLRCMIT9313.png" alt="Fitted LRC of PSII electron transport (e- PSII-1 s-1) vs measurement light (µmol photons m-2 s-1) for *Prochlorococcus* strain MIT9313 (Clade LLIV) and after growth under different combinations of light level (30, 90, 180 µmol photons m-2 s-1) and oxygen concentration (2, 25, 250 µM), derived from light response curve fits (XXXRefer to Figure). The curves are differentiated by varying oxygen concentrations (colors), with different panels representing different combinations of light levels and growth oxygen concentrations." width="100%" />
<p class="caption">Fitted LRC of PSII electron transport (e- PSII-1 s-1) vs measurement light (µmol photons m-2 s-1) for *Prochlorococcus* strain MIT9313 (Clade LLIV) and after growth under different combinations of light level (30, 90, 180 µmol photons m-2 s-1) and oxygen concentration (2, 25, 250 µM), derived from light response curve fits (XXXRefer to Figure). The curves are differentiated by varying oxygen concentrations (colors), with different panels representing different combinations of light levels and growth oxygen concentrations.</p>
</div>



```r
knitr::include_graphics(file.path(Figures,"EstimatePmax.png"))
```

<div class="figure">
<img src="../code/Figures/EstimatePmax.png" alt="Analysis of Maximum PSII Electron Transport Rate (Pmax) for *Prochlorococcus* MED4 (Clade HLI) and MIT9313 (Clade LLIV). Pmax,  derived from light response curve fits (FIGURE)), is plotted vs. measurement oxygen concentrations, with error bars representing the standard error of the estimate. Data is grouped by strain and growth light level, colours indicate different growth oxygen levels." width="100%" />
<p class="caption">Analysis of Maximum PSII Electron Transport Rate (Pmax) for *Prochlorococcus* MED4 (Clade HLI) and MIT9313 (Clade LLIV). Pmax,  derived from light response curve fits (FIGURE)), is plotted vs. measurement oxygen concentrations, with error bars representing the standard error of the estimate. Data is grouped by strain and growth light level, colours indicate different growth oxygen levels.</p>
</div>
The analysis of Maximum PSII Electron Transport Rate (Pmax) for Prochlorococcus strains MED4 (Clade HLI) and MIT9313 (Clade LLIV) provides insights into the relationship between Pmax and oxygen concentration in their growth environment. In figure \@ref(fig:EstimatePmax) , Pmax values, derived from light response curve (FIGURE \@ref(fig:LRCplot), are plotted against measured oxygen concentrations. The error bars represent the standard error of the estimate, ensuring the reliability of the data. The figure is arranged with each row representing a different growth light level and each column corresponding to one of the two strains. Oxygen concentrations are color-coded for clarity: red for 2 µM, green for 25 µM, and blue for 250 µM.

Across both strains, a trend is observed, indicating that Pmax values exhibit variation corresponding to changes in oxygen concentration. Specifically, strain MED4 demonstrates relatively consistent Pmax values across different oxygen concentrations, although with minor fluctuations. Since Pmax remains reletively stable across varying oxygen concentrations, this suggests that the cells are constitutively adapted to cope with changes in oxygen levels. we hypothesis that MED4 possess inherent mechanisms or traits that enable them to maintain consistent Pmax values regardless of fluctuations in oxygen concentrations. this could indicate a genetic predisposition or a long-term adaptation to the prevailing environmental conditions. (ADD BIOINFORMATIC HERE)

However, strain MIT9313 exhibits more pronounced differences in Pmax values, particularly evident between the lowest (2 µM) and highest (250 µM) oxygen levels. These findings underscore the strain-specific responses of *Prochlorococcus* to varying oxygen concentrations, suggesting a significant influence of oxygen levels on the PSII electron transport capacity of these strains. Since Pmax valuex show significant changes in the response to a change in oxygen concentrations, it suggests that the cells are capable of acclimating to different oxygen concentrations over time. In this case, the cells adjust their physiological processes or regulatory mechanisms in response to changes in environmental oxygen levels. This acclimation process may involve the activation or suppression of certain genes, the modulation of metabolic pathways, or changes in cellular structure or function to optimize photosynthetic efficiency in varying oxygen environments.

In conclusion, the analysis of Maximum PSII Electron Transport Rate (Pmax) in Prochlorococcus strains MED4 (Clade HLI) and MIT9313 (Clade LLIV) provides valuable insights into the intricate interplay between Pmax and oxygen concentration within their growth environment. From this analyses, it becomes evident that while MED4 strain displays a consistent Pmax across varying oxygen concentrations, indicating constitutive adaptation to cope with changes in oxygen concentrations, MIT9313 strain displays significant changes in Pmax across varying oxygen concentrations, indicative of acclimation over time to different oxygen concentrations. 



```r
knitr::include_graphics(file.path(Figures,"DualPamLRC.png"))
```

<div class="figure">
<img src="../code/Figures/DualPamLRC.png" alt="PSII electron transport (e- PSII-1 s-1) vs measurement light (µmol photons m-2 s-1) for *Prochlorococcus* strains PCC9511 (Clade HLI) and MIT9313 (Clade LLIII) after growth under different combinations of light level (30, 90, 180 µmol photons m-2 s-1) and oxygen concentration (2, 25, 250 µM). The blue and red points represent the experimental data." width="100%" />
<p class="caption">PSII electron transport (e- PSII-1 s-1) vs measurement light (µmol photons m-2 s-1) for *Prochlorococcus* strains PCC9511 (Clade HLI) and MIT9313 (Clade LLIII) after growth under different combinations of light level (30, 90, 180 µmol photons m-2 s-1) and oxygen concentration (2, 25, 250 µM). The blue and red points represent the experimental data.</p>
</div>

fitted LRC 
- MED4 and MIT9313 show significant short term responses of electron transport to decreasing oxygen. 
- Growth under 2 µM O~2~ diminishes the short term effects of changing measurement oxygen, indicating growth acclimation to oxygen status. 

pmax 
- Strain MED4 shows increasing Pmax values across increasing measurement oxygen concentrations, indicating short term responses to varying oxygen levels. Pmax also incresses with increasing light levels and with growth at 25 µM O~2~. Consistent with (citation).
- Strain MIT9313 shows interactive effects of measurement oxygen, growth oxygen concentration and growth light on Pmax values. particularly between the lowest (2 µM) and highest (250 µM) oxygen concentrations, indicating acclimating adaptation to varying oxygen levels.
- These findings underscore the influence of longterm growth and short term oxygen concentrations on the PSII electron transport capacity of *Prochlorococcus* strains, with significant changes in Pmax values indicating cellular capability to acclimate to different oxygen concentrations over time.

ETRI ETRII
- Directly comparing PSI to PSII electron transport shows that in MED4 growth under 25 µM O~2~ decreases PSI electron transport. 
- In contrast, in MIT9313, PSI electron transport remains more consistent across growth O~2~ concentration. 

