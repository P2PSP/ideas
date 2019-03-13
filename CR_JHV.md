# Improving the Jhelioviewer client using conditional replenishment

## Abstract

[JHelioviewer](https://www.jhelioviewer.org/) (available as [open source software](https://github.com/Helioviewer-Project/JHelioviewer-SWHV)) is an interactive streaming system for solar image data (compressed with the JPEG2000 standard). In this project we propose to use Conditional Replenishment (CR) to reduce the traffic between JPEG2000 Interactive Protocol (JPIP) servers and clients, when temporal redundancy is found in the transmitted image sequence. CR can be used to request only those regions of the transmitted images that can not be reused from previous received data and therefore, need to be refreshed.

## Expected deliverables

An improved version of the JHelioviewer player, avaiable as a fork of the main repo.

## Knowledge prerequisites

Java, Git, JPEG2000, JPIP, JHelioviewer.

## Skill level

Average

## Potential mentors

1. [Vicente González Ruiz](https://w3.ual.es/~vruiz/Investigacion/index.html).
2. [José Juan Sánchez Hernández](https://josejuansanchez.org/).
3. [Juan Pablo García Ortiz]().

## Priority

High

## Room

https://gitter.im/P2PSP/CR_JHV

## Repo

https://github.com/vicente-gonzalez-ruiz/JHelioviewer-SWHV

## References

https://www.aanda.org/articles/aa/abs/2017/10/aa30893-17/aa30893-17.html
http://jhelioviewer.org/pub/Mueller+al_CiSE2009.pdf
