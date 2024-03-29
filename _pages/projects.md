---
layout: archive
title: "Study systems and research themes"
permalink: /projects/
author_profile: true
---


Here are a few ongoing projects and general areas of research interest:

## Evolutionary quantative genetics, esp. Soay sheep

<img align="left" width="200" height="200" src="/files/small_chewing.gif" title="original video by V Litzke">
Soay sheep are a stone age lineage of sheep that have lived unmanaged on the island of Soay in the St Kilda archipelago since pre-historic times.  When the last human inhabitants of Hirta, the main island in the [St Kilda archipelago](https://www.nts.org.uk/visit/places/st-kilda), left in the 1930s, Soay sheep were moved from Soay to Hirta, where they have continued to live unmanaged.  The Soay sheep population of Village Bay, on Hirta, has been the subject of [a long-term individual-based study](https://soaysheep.bio.ed.ac.uk/) since 1985.  Comprehensive pedigree data and >10,000 complete life histories, combined with extensive trait and environmental data supports a range of studies, including my interests in studying the generation-to-generation mechanics of natural selection in the wild.

## Anthropogenic selection, ELA lake trout and bighorn sheep


<img align="left" width="260" height="170" src="/files/ela_clips.gif" title="original video by J Phipps and A Wallace">
The [IISD Experimental Lakes Area](https://www.iisd.org/ela/) is a wonderful outdoor laboratory for whole-lake experiments.  With [Dak de Kerckhove](https://eeb.utoronto.ca/profile/de-kerckhove-dak/) and others from the [Ontario Ministry of Natural Resources and Forestry](https://www.ontario.ca/page/aquatic-research) we are conducting long-term experiments on the evolutionary consequences of selective harvest.

With [Marco Festa-Bianchet](https://qcbs.ca/member?profile=32) and others in Quebec, Ontario and Alberta, similar work is important in bighorn sheep.  The evolutionary principles are established, but somehow whether they apply to selective trophy hunting is someting that various factions in wildlife management will go to great lengths to deny!

## Measurement of natural selection

<img align="right" width="260" height="170" src="/files/example_theory_papers.gif">

If I have a coherent research theme, it is theory and methods for quantifying natural selection.  Here are a few key outputs from this area (see also [publications](/publications/)):
- how to calculate [selection gradients from arbitrary functions](https://onlinelibrary.wiley.com/doi/full/10.1111/evo.12077)
- how to conceptualise selection when traits affect one another: [linear case](https://onlinelibrary.wiley.com/doi/full/10.1111/evo.12385), [more general treatment](https://onlinelibrary.wiley.com/doi/full/10.1111/evo.12728)
- special considerations in meta-analysis for inferring things like [variability in selection](https://academic.oup.com/evolut/article/66/2/435/6851568) and and the [prevelance of sexually-antagonistic selection](https://onlinelibrary.wiley.com/doi/10.1111/jeb.12950)
- calculation of [selection gradients from exponential functions](https://onlinelibrary.wiley.com/doi/full/10.1111/evo.14486) (like log-link GLMs)
- [dealing with environmental confounders](https://www.biorxiv.org/content/10.1101/2022.06.15.496257v1.full.pdf)

## Data logging

Products like [Arduino](https://www.arduino.cc/) and [Raspberry Pi](https://www.raspberrypi.org/) make all sorts of electronics easy to use.  They allow us to relatively easily hook up all kinds of high quality sensors (commercially available from, for e.g., [here](https://www.adafruit.com/), [here](https://www.dfrobot.com/) and [here](https://www.sparkfun.com/)), and write data to an SD card.  However, there are major challenges to moving custom logger prototypes from the bench (and near-by mains power) to the useful logger deployments in the field.

We are developing an arduino-compatible microcontroller board to help field scientists fully realise this recent democratisation of electronics in field data logging applications.  In particular, we:
- optimise for very low sleeping power consumption
- include high quality temperature-compensated real time clocks for time-stamping data
- include a SD card holder and associated circuitry to minimise its power use

The resulting boards are arduino-like in that they can be programmed using the same development environment, can handle digital and analog inputs, and communicate with peripherals (e.g., sensors) using the same set of serial protocols as can the classic Arduino.  However, depending on sensors used and duty cycle, the boards can last hundreds to thousands of times longer, making deployment with minimal power provision (e.g., 3xAA battery packs) feasible.  See the [GitHub repository here](https://github.com/mbmorrissey/cadalogger) for all open source design files and software library, plus developing documentation and examples.  [Contact us](/contact/) if you want to test a prototype.

Here is an intro to what we are tryign to do (many improvements, including to video documentation, coming soon, funding allowing):

[![A quick intro to cadalogger](https://img.youtube.com/vi/7qkBjCcAluY/0.jpg)](https://youtu.be/G2LDQLVE-7E)
