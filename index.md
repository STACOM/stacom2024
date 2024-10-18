---
layout: single
author_profile: false
classes:
  - wide
header:
  image: /images/marrakesh_01.jpg
gallery:
  - url: /images/photos/stacom2024_01.jpg
    image_path: /images/photos/stacom2024_01.jpg
    alt: ""
    title: "STACOM 2024"
  - url: /images/photos/stacom2024_02.jpg
    image_path: /images/photos/stacom2024_02.jpg
    alt: ""
    title: "STACOM 2024"
  - url: /images/photos/stacom2024_03.jpg
    image_path: /images/photos/stacom2024_03.jpg
    alt: ""
    title: "STACOM 2024"
---

<!--
{: .notice--info}
<div stule="margin: 0px 50px 0px 50px;">
<div style="text-align: center; margin-bottom: 1em;"><strong><font size="+2">SUBMISSION IS EXTENDED TO 30 June 2024</font></strong></div>

The regular paper submission has been extended to <strong>Sunday, 30 June 2024 23:59:59 <a href="https://www.timeanddate.com/worldclock/timezone/utc-12" target=_blank>UTC-12</a></strong>, but we request all participants to submit title and abstract as a placeholder by <strong>24 June 2024</strong>.

<div style="text-align: left; margin-top: 1em;">
Current submission clock:
<div style="text-align: center;">
<iframe src="https://free.timeanddate.com/clock/i9fcat4q/n3926/fs18/tct/pct/ftb/tt0/tm1/th1/ta1/tb2" frameborder="0" width="366" height="23" allowtransparency="true"></iframe>
</div>
</div>
</div>
-->

<!-- {: .notice--info}
<div style="text-align: center; margin-bottom: 1em;"><strong><font size="+2"><a href="papers">Accepted papers are available</a></font></strong></div> -->

{: .text-justify}
The **Statistical Atlases and Computational Modeling of the Heart (STACOM)** workshop has been running annually at MICCAI since 2010. The 15th edition of STACOM workshop is going to be held in conjunction with the [MICCAI 2024](https://conferences.miccai.org/2024/en/) in Marrakesh, Morocco. The STACOM workshop is aiming to create a collaborative forum for young/senior researchers (engineers, biophysicists, mathematicians) and clinicians, working on: statistical analysis of cardiac morphology and dynamics, computational modelling of the heart and fluid dynamics, data/models sharing, personalisation of cardiac electro-mechanical models, quantitative image analysis and translational methods into clinical practice.

<!--
<div style="text-align: center;"><a href="https://equinocs.springernature.com/service/STACOM2024" target="_blank" class="btn btn--info btn--large" style="margin-top: 10px; padding-left: 50px; padding-right: 50px;">Submit Your Paper</a></div>
-->

{% include figure popup=true image_path="/images/photos/STACOM2024.jpg" caption="STACOM 2024 Workshop" %}

{% include gallery caption="Other photos from STACOM 2024." %}

### Awards

Congratulations to **Bruno Viti** for receiving **Best Oral Presentation** for his paper:

{: .notice--success}
<div>
<span style="font-size:150%;">Gaussian Process Emulators for Few-Shot Segmentation in Cardiac MRI</span><br>
<span style="font-size:125%;">Bruno Viti<sup style="font-size:x-small;">1,5</sup>, Franz Thaler<sup style="font-size:x-small;">3,4</sup>, Kathrin Lisa Kapper<sup style="font-size:x-small;">1,5</sup>, Martin Urschler<sup style="font-size:x-small;">2,5</sup>, Martin Holler<sup style="font-size:x-small;">1,5</sup>, and Elias Karabelas<sup style="font-size:x-small;">1,5</sup></span><br>
<div style="font-size:smaller;">
<sup style="font-size:x-small;">1</sup> Department of Mathematics and Scientific Computing, University of Graz, Austria<br>
<sup style="font-size:x-small;">2</sup> Institute for Medical Informatics, Medical University of Graz, Austria<br>
<sup style="font-size:x-small;">3</sup> Institute of Computer Graphics and Vision, Graz University of Technology, Austria<br>
<sup style="font-size:x-small;">4</sup> Gottfried Schatz Research Center: Medical Physics and Biophysics, Medical University of Graz, Austria<br>
<sup style="font-size:x-small;">5</sup> BioTechMed-Graz, Graz, Austria
</div>
</div>
{: .text-center} 

and to **Patryk Rygiel** for receiving **Best Poster Presentation** for his paper:

{: .notice--success}
<div>
<span style="font-size:150%;">Global Control for Local SO(3)-Equivariant Scale-Invariant Vessel Segmentation</span><br>
<span style="font-size:125%;">Patryk Rygiel<sup style="font-size:x-small;">1</sup>, Dieuwertje Alblas<sup style="font-size:x-small;">1</sup>, Christoph Brune<sup style="font-size:x-small;">1</sup>, Kak Khee Yeung<sup style="font-size:x-small;">2,3</sup>, and Jelmer M. Wolterink<sup style="font-size:x-small;">1</sup></span><br>
<div style="font-size:smaller;">
<sup style="font-size:x-small;">1</sup> Department of Applied Mathematics, University of Twente, The Netherlands<br>
<sup style="font-size:x-small;">2</sup> Department of Surgery, Vrije Universiteit Amsterdam, The Netherlands<br>
<sup style="font-size:x-small;">3</sup> Amsterdam Cardiovascular Sciences, Microcirculation, The Netherland
</div>
</div>
{: .text-center} 

### Schedule

The STACOM 2024 programme is split into morning session for the regular papers and afternoon session for the CMRxRecon and MBIAS challenges. 

#### Morning session: regular papers

{% include schedule %}

#### Afternoon session: challenges

{% include challenge.html 
title="Multiclass Bi-Atrial Segmentation Challenge" 
url="https://codalab.lisn.upsaclay.fr/competitions/18516" 
image="/images/mbas2024.png" 
description="Building from the 2018 left atrium challenge, this Multi-class Bi-Atrial Segmentation (MBAS) challenge broadens to include both left and right atriums as well as their walls, focusing on multi-class machine learning from LGE-MRIs to enhance ablation for atrial fibrillation patients. The challenge objective is to benchmark methods for segmentation and biomarker identification, such as atrium volume and fibrosis, using 200 multi-center 3D LGE-MRIs with each scan meticulously labelled by three experts." %}

Schedule:

{% include schedule_mbias %}

{% include challenge.html 
title="Cardiac MRI Reconstruction Challenge" 
url="https://cmrxrecon.github.io/2024/Home.html"
image="/images/CMRxRecon-Poster 2024.jpg"
description="The objective of establishing the Cardiac MRI Reconstruction challenge is to provide a benchmark that enables the broader research community to contribute to the important work of accelerated CMR imaging with universal approaches that allow more diverse applications and better performance in real-world deployment in various environments. There are two tasks in this challenge: *multi-contrast CMR reconstruction* and *random sampling CMR reconstruction*." %}

Schedule:

{% include schedule_cmrxrecon %}

