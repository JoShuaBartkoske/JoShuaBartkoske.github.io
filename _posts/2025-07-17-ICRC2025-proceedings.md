---
layout: post
title: "My ICRC 2025 Proceedings"
date: 2025-07-17
toc: True
---

* TOC
{:toc}

This blog post will show everything in the current text and figures of my ICRC 2025 Proceedings for those interested in learning more from my poster. This includes figures and text that may only appear in either the poster or proceedings but not it both. 
<!-- 
This does also include text and figures not seen in either poster or official proceedings.
-->

<h1>Asteroid Occultations with VERITAS: Observations and Considerations</h1>
<h2>Abstract</h2>
<p>
Occultations, the covering up of one celestial body by another celestial body, have been used in astronomy for millennia to learn about the sun and moon. Since 2018, VERITAS has implemented a program to detect predicted asteroid occultations, where an asteroid covers up a star. VERITAS has attempted to observe over 100 occultations to date and successfully observed 20 occultations. With these occultations, VERITAS can directly measure the smallest angular diameters of any instrument or technique in the optical for stars between magnitude 9 and 13. Each angular diameter is measured by fitting the diffraction pattern observed by the central VERITAS pixel at the start and end of an occultation. Once a planned FADC upgrade is complete, VERITAS will begin a program to search for serendipitous occultations within its full field of view (3 deg). Serendipitous occultations of sub-km trans-Neptunian objects (TNOs) have the potential to constrain models of solar system formation. This presentation will detail how VERITAS predicts and observes occultations as well as the overall status of the asteroid occultation program and future steps for observing occultations of both asteroids and TNOs.
</p>

<h2>Introduction</h2>
<p>
Occultations have been used to measure angular diameters of stars since A. Arnulf’s first
measurement of the diameter of Regulus in 1936 [1]. Since that time, lunar occultations (the
moon occulting stars) have been measured the angular diameters of hundreds of stars down to
1 milliarcsecond (mas) [2]. By nature of their increased distance from the observer, asteroid
occultations can push angular diameter measurements down to sub-mas values using the same
techniques as lunar occultations. The angular diameters of most stars are below 1 milliarcsecond.
Asteroid occultations have been used to directly measure the smallest stellar angular diameters of
any instrument in optical wavelengths as demonstrated by the Very Energetic Radiation Imaging
Telescope Array System (VERITAS) [3]. For additional details about the background of asteroid
occultations and comparison with other sub-mas methods see [2].
</p>
<p>
VERITAS is an array of four imaging atmospheric Cherenkov telescopes (IACTs) in southern
Arizona located at the Fred Lawrence Whipple Observatory (FLWO). By nature of being focused
on capturing the faint blue Cherenkov radiation in the atmosphere, IACTs are capable of unfiltered
optical observations with maximum sensitivity in approximately the B-band. Since 2018, the
asteroid occultation program at VERITAS has observed more than 20 successful occultations
of stars ranging from magnitude 9.9 to 13.3 in the V-band. With other techniques, stars with
dim magnitudes are difficult to directly measure their angular diameters, which are necessary in
determining model-independent values for stars’ effective temperature and radii [4]. By measuring
stars farther away from us and at dimmer magnitudes, we start measuring stars that are probing the
edges of stellar models and their accuracy in predicting sizes of stars. In particular, cool low-mass
stars are of interest in astronomy because of the difference between their expected sizes and their
directly measured sizes [5].
</p>

<h2>Occultation Program Overview</h2>
<p>
After the successful detection of two asteroid occultations in 2018 [3], VERITAS included
asteroid occultations in its long-term observing plan, with 5 hours of dedicated observing time
each season. Below is an overview of the VERITAS occultation program including our hardware,
predictions, and observations.
</p>
<h3>Hardware</h3>
<p>
In order to observe the fringes around occultation shadows, an IACT needs an optical data
acquisition system (DACQ) capable of sampling rates faster than 300 Hz. VERITAS uses an off-
the-shelf DATAQ DI-710-ELS, which we call the VERITAS enhanced current monitor (ECM). The
ECM is hooked up to either 2 or 4 photomultiplier (PMT) pixels on each of the four VERITAS
cameras with a maximum sampling rate of 4800 Hz. On each camera, those pixels include the
central pixel and at least one background pixel to reject spurious terrestrial events.
</p>
<h3>Occultation Predictions and Observations</h3>
<p>
There are two main tools for predicting asteroid occultations: Occult1 and OccultWatcher
(OW)2. Occult is an active prediction software developed by David Herald that needs to run every
month with 3 different ephemeris databases. OW is a passive software that updates its list of
predictions regularly based on internal calculations as well as user-added predictions. Predictions
from both tools are based on the observer’s location and are accurate for up to 1 month.
</p>
<p>
When making predictions for VERITAS, there are filters in Occult to only consider IACT-
feasible occultations (within dark time, above 20 degrees elevation, m𝑉 13.5, and no moonlight)
while also selecting only occultations longer than 0.5 seconds in duration and a predicted probability
10% (Fig. 1: Not viable 38%).
</p>
<p>
Each observation is scheduled to begin 3 minutes before the time of occultation and last for
5 minutes. The absolute time marker can be calculated in the offline analysis. The precision of
the ECM’s absolute timing is 0.1 seconds. Some of the main issues that prevent observations are
weather, engineering issues, and higher priority targets (Fig. 1: Not observed 30%).
</p>
<p>
Even when observations are successfully scheduled and observed, there are other issues that
arise. The first issue is that, due to uncertainties in an asteroid’s orbital parameters or a star’s
position, the occultation shadow does not fall over VERITAS. These are our non-detections (Fig.
1: No detection 24%). In some isolated cases, weather can be at play and lead to non-detections as
well. The second issue to arise during observations is a saturated pixel due to the predictor and/or
observer setting a gain that is too low for the background light being observed in the region of the
</p>

<h2>Occultation Outcomes</h2>
<p>

</p>

<h2>Occultation Program Considerations</h2>
<p>
</p>
<h3></h3>
<p>
</p>
<h3></h3>
<p>
</p>
<h3></h3>
<p>
</p>
<h3></h3>
<p>
</p>
<h3></h3>
<p>
</p>
<h3></h3>
<p>
</p>
<h3></h3>
<p>
</p>

<h2>Conclusions and Future Steps</h2>
<p>

</p>
