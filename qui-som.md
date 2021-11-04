---
title: Qui som
layout: page
description: About
bodyClass: page-about
fixed_navbar: true
has_dark_bg: true

---

Som desenvolupadors de treballadors de llengua que estan dedicats a millorar
l'accés a les llengües a l'àmbit digital, sobretot llengües minoritzades.
Formem part de la cooperativa [Col·lectivaT][collectivat], per més informació
sobre nosaltres podeu visitar [la pàgina de la cooperativa][collectivat] i
les nostres xarxes socials.

## Detalls de la tecnologia

Les tecnologies que vam utilitzar són els repositoris de [Tacotron2][nvidia]
i [WaveGlow][waveglow], de l’empresa de NVIDIA publicats amb llicències obertes a github. Un dels
resultats més importants és el codi; és a dir, el nostre fork de [Tacotron2][catotron], que
està modificat per al català, imprescindible per fer servir els models de
català. A més vam desenvolupar un segon repositori [catotron-cpu][catotron-cpu], que és
executable amb els processadors més comuns, els CPUs. Aquesta versió de Catotron utilitza
[MelGan][melgan], que és una alternativa més lleguera i més eficient que WaveGlow.

Per entrenar els models de català vam aprofitar les dades obertes ja
publicades. Les veus resultants estan entrenades amb les dades de [Festcat][festcat], que
també va ser un projecte de la Generalitat, realitzat pels investigadors de la
UPC. Vam utilitzar les millors veus d’aquest conjunt de dades: les veus de
l’Ona i del Pau.

El codi està al github [aquí][catotron] i [aquí][catotron-cpu]; i els models són descarregables [aquí][blog].

Actualment estem treballant a modernitzar l'arquitectura de Catotron, per una experiència millor. Per més informació podeu consultar el [blog post original][blog].

## Suport

Aquesta eina va ser desenvolupat gràcies als projectes "síntesi de la parla
contra la bretxa digital" i "promoció digital de les tecnologies lingüístiques
obertes i lliures en català" subvencionats pel Departament de Cultura. Una part
dels fons provenen dels cabals que atorga la Junta d’Herències de la
Generalitat de Catalunya.

<img src="http://collectivat.cat/img/logo_generalitat.png" width="55%" />

[collectivat]: https://collectivat.cat/ 
[blog]: https://collectivat.cat/blog/2019-12-05-sintesi-de-la-parla-xxnn/
[catotron]: https://github.com/CollectivaT-dev/catotron
[catotron-cpu]: https://github.com/CollectivaT-dev/catotron-cpu
[nvidia]: https://github.com/NVIDIA/tacotron2
[waveglow]: https://github.com/NVIDIA/waveglow/
[tallers]: https://github.com/CollectivaT-dev/TallersParla
[ona]: https://drive.google.com/open?id=1-fdWV-aH5nIRv1rZKQYInsRes2At74xG
[pau]: https://drive.google.com/open?id=1-T2nHQNEE8mXPaT-ulDSAXgdGSzomPMu
[colab1]: https://colab.research.google.com/github/CollectivaT-dev/TallersParla/blob/master/ipynb/catotron_inference.ipynb
[colab2]: https://colab.research.google.com/github/CollectivaT-dev/TallersParla/blob/master/ipynb/catotron_transfer_learn.ipynb
[festcat]: http://festcat.talp.cat/download.php
[melgan]: https://github.com/seungwonpark/melgan
[waveglow_model]: https://drive.google.com/open?id=1WsibBTsuRg_SF2Z6L6NFRTT-NjEy1oTx
[melgan_model]: https://drive.google.com/file/d/1U3LeuaMIVoRvMvfwlHjsRJPWhgTzeIBh
[demo]: http://catotron.collectivat.cat/
[paper]: /etc/INTERSPEECH_2020_Catotron.pdf

