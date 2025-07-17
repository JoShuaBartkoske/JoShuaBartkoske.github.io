---
layout: post
title: "My ICRC 2025 Proceedings"
date: 2025-07-17
---

This blog post will show everything in the current text of my ICRC 2025 Proceedings for those interested in learning more from my poster. This includes text that may only appear in either the poster or proceedings but not it both. 
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
target star (Fig. 1: Saturated 2%). See Figure 2 to see saturation at play in an observation with an
occultation.
</p>

<h2>Occultation Program Outcomes</h2>
<p>
Since 2019, VERITAS has predicted over 300 occultations with greater than 10% probability.
VERITAS successfully attempted to observe 117 of those predictions. Of the 117 observations,
20 successfully observed the occultation with 11 of the observed occultations showing at least one
diffraction peak. In total, VERITAS has observed 585 minutes of occultations, which averages to
30 minute of observation time per detected occultation.
</p>

<h2>Occultation Program Considerations</h2>
<p>
After seven seasons at VERITAS of predicting, observing, and analyzing asteroid
occultations, here are some considerations for future IACT occultation observations:
</p>
<h3>Predictions</h3>
<p>
In making occultation predictions, there are a couple of improvements worth mentioning.
First, the OW prediction software has a much higher detection rate ( 7
22 = 32%) than Occult
( 13
351 = 3.7%) while also requiring little time investment. This means that for a side program at an
IACT observatory, using OW alone will be much more effective in predicting occultations. Second,
getting accurate asteroid occultation orbital information relevant for the observer is very important
for the angular diameter analysis. Originally, we used the JPL Horizons ephemeris generator,
however the JPL Horizons "VmagOb" value we had been using was not the actual speed of the occultation shadow, but the total speed of the velocity vector (which is rarely the same value as the shadow velocity). This difference in definition means that "VmagOb" has been off by more than 7 km/s for some published
occultations. Thus, we now use the stellar occultation reduction and analysis software (SORA) [6] for generating accurate post-observation asteroid occultation
parameters such as the distance to the asteroid and the velocity of the asteroid shadow on the
ground.
</p>
<h3>Optical Bandwidth of an IACT</h3>
<p>
For an IACT, the optical bandwidth of observable wavelengths is the main limiting factor
in observing occultations, since the relative heights of the peak fringes decrease with increasing
bandwidth. VERITAS uses a Hamamatsu R10560-100-20 PMT with QE peaked in the blue/UV
[7]. The full wavelength profile of VERITAS including the measured mirror reflectivity has a
FWHM bandwidth of 146 nanometers (nm) centered at 435 nm. With VERITAS’ bandwidth, the
limiting angular resolution is 0.1 mas for occultations of asteroids at 3.2 AU [8] (See Fig. 3). At
the distance of TNOs 45 AU, the limiting angular resolution is 0.03 mas. To detect stellar angular
diameters below this threshold, both the instrument’s wavelength response function (IWRF) and
the stellar spectrum must be known with high precision. While the number of significant peaks will
always be limited due to the bandwidth, measuring the change in the visible peaks’ heights is how
we can directly measure the angular diameter of a star (see Figures 3).
</p>
<h3>Sampling Rate and Aperture</h3>
<p>
While bandwidth leads to a very large impact on observed diffraction patterns, sampling rate
has very little impact on the observed fringes at rates faster than 300 Hz. Aperture also has very
little impact on the observed diffraction pattern unless one observes close asteroid occultations (1.5
AU) with very large apertures (23.0 meters)
</p>
<h3>Timing Resolution</h3>
<p>
There are two considerations on the topic of timing. The first is our absolute timing. One
science output of asteroid occultations is the measurements of asteroid diameters. With precise
timing information, we can fit the observed shadow durations from multiple telescopes and then
calculate the length of our chord across the asteroid. However, our DACQ clock drifts seconds over
the time-scale of hours, which leaves us with a maximum accuracy on the timescale of 1 second.
To improve the timing resolution, a GPS-clock is required. 
</p>
<p>
Second, in VERITAS’ PMT backend,
the circuit had an RC time delay constant of 3 milliseconds that shows up in fast optical transients
in the ECM. To improve the system in November 2024, we changed the capacitor on the circuit and
now have a 0.3 ms time delay. However, the improvements have led to an observed time delay of
only 1.5 ms and require more study to understand. This has a minimal impact on current asteroid
occultations but may come into play for short-duration occultations.
</p>
<h3>Optics</h3>
<p>
The VERITAS optical system has a field of view of 3.5 degrees and 499 PMT pixels. Each
PMT is 0.167 degrees across and can contain many stars of similar magnitude within its field of
view causing variations on the currents observed depending on the star field. Smaller pixels would
lead to better isolation of the target star. Current IACTs are limited by their optical point spread
function which is about the same size as their pixels, but future generation IACTs like the 8-m
Schwarzschild-Couder Telescope will have much smaller pixel size.
</p>
<h3>Shape of Asteroids</h3>
<p>
One consideration that is important in the analysis of asteroid occultations is the shape of
asteroids on diffraction patterns. Because every occultation has both a covering (ingress) and
uncovering (egress), there are always two diffraction patterns per telescope with which to measure
the stellar angular diameter. However, the angular diameter measurement can be different between
the ingress and egress, even after taking into account all systematics of the instrument and the
stellar spectrum. This difference is likely due to the non-uniform shape of asteroids and can cause
a reduction of the fringes (as seen in Figure 3 where larger stars smooth out the diffraction peaks).
Thus, we always take the smaller of the two values as our measured angular diameter of the star [9].
</p>
<h3>Observing Time</h3>
<p>
The time spent observing occultations is minimal. Occultations typically range in duration from less than a second to tens of seconds and observations are usually scheduled for only 5 minutes. The 5 minute window ensures that gains can be properly set in case of saturation and timing calibration can be performed within the run. With an integrated GPS clock, observation time can be shrunk further to less than 5 minutes per occultation. In addition, longer observations are necessary to achieve further science goals, such as detecting asteroid satellites and atmospheres or rings around small solar system bodies. The length of these discovery observations is primarily due to the large range of parameters for fitting for the atmosphere and how far away satellites are discovered.
</p>

<h2>Conclusions</h2>
<p>
The main takeaways from the last seven years of running an occultation program have been: 
    1. We improved the occultation software used for making predictions (OW>Occult). 
    2. We have found a better place to obtain accurate asteroid parameters (SORA) [6]. 
    3. We learned that the main limit of our angular resolution is the bandpass of VERITAS. 
    4. We improved the time-delay by a factor of 2 for fast-optical transients. 
    5. The shape of asteroids can enlarge the angular size of the star within our analysis.
</p>
<p>
By observing asteroid occultations, IACTs have much to gain with minimal overhead to ob-
serving time and cost. IACTs can significantly contribute to the science of stellar angular diameters
at scales no current optical telescopes are capable of achieving. This is similar in scope to SII
but has a much lower cost and time consideration with similar scientific output in studying stellar
angular diameters. By equipping IACTs with a kHz current readout, IACTs can be transformed into
a premier optical telescope for measuring the smallest angular diameters of any optical observatory
[3].
</p>
<p>
There are also benefits to the broader impacts of IACTs. One of which is connection with
local astronomical communities. IOTA—the International Occultation Timing Association—is a
large multinational network of amateur astronomers who observe occultations [10]. By attempting
to observe asteroid occultations alongside IOTA observers, IACT observatories can benefit from
citizen science and public outreach simultaneously.
</p>
<h2>Future Steps</h2>
<p>
Another broader impact of looking at asteroid occultations is in the field of solar system
astronomy. Asteroid occultations and other similar stellar occultations by small bodies are used by
the planetary science community for determining sizes and shapes of objects. With large collecting
areas and precise time sampling, IACTs would be unmatched in resolving finer details of small
bodies in the solar system. Other studies of small bodies using occultations have discovered rings
around Centaurs and TNOs, satellites of asteroids, contact binaries, and binary star systems [11].
IACTs can significantly contribute to the planetary science community.
</p>
<p>
Trans-Neptunian Objects: TNOs are small bodies in the Solar System beyond Neptune. Plan-
etary scientists are interested in studying the properties of TNOs and their populations in order
to understand the formation of the Solar System [12]. Targeted observations of TNO occultations
have led to the discovery of atmospheres around TNOs as well as rings, satellites, and binary TNO
systems [11]. In the future, IACTs can contribute to these targeted observations and provide high
angular resolution to studies on the surfaces of TNOs. Additionally, by equipping IACTs with
ECM-like data acquisition systems across their entire field of view we can search for serendipi-
tous occultations of small sub-km TNOs and set constraints on the formation of the solar system
[13]. This idea for upgrading the entire field of view of an IACT is currently being developed at
VERITAS.
</p>


<h2>Bibliography</h2>
<p>
[1] A. Arnulf, <i>Sur une méthode pour la mesure des diamétres apparents des étoiles</i>, <i>Comptes
Rendus de l’Académie des Sciences</i> <b>202</b> (1936) 115.
</p>
<p>
[2] T. Hassan and M. Daniel, <i>Proving the outstanding capabilities of Imaging Atmospheric
Cherenkov Telescopes in high time resolution optical astronomy</i>, in <i>36th International
Cosmic Ray Conference (ICRC2019)</i>, vol. 36 of <i>International Cosmic Ray Conference</i>,
p. 692, July, 2019, DOI [1908.03393].
</p>
<p>
[3] W. Benbow, R. Bird, A. Brill, R. Brose, A.J. Chromey, M.K. Daniel et al., <i>Direct
measurement of stellar angular diameters by the VERITAS Cherenkov telescopes</i>, <i>Nature
Astronomy</i> 3 (2019) 511 [1904.06324].
</p>
<p>
[4] T.S. Boyajian, K. von Braun, G. van Belle, C. Farrington, G. Schaefer, J. Jones et al., <i>Stellar
Diameters and Temperatures. III. Main-sequence A, F, G, and K Stars: Additional
High-precision Measurements and Empirical Relations, 771 (2013) 40 [1306.2974].
</p>
<p>
[5] F. Spada, P. Demarque, Y.C. Kim and A. Sills, The Radius Discrepancy in Low-mass Stars:
Single versus Binaries, 776 (2013) 87 [1308.5558].
</p>
<p>
[6] A.R. Gomes-Júnior, B.E. Morgado, G. Benedetti-Rossi, R.C. Boufleur, F.L. Rommel,
M.V. Banda-Huarca et al., SORA: Stellar occultation reduction and analysis, 511 (2022)
1167 [2201.01799].
</p>
<p>
[7] N. OTTE, Upgrade of VERITAS with high efficiency photomultipliers, in International
Cosmic Ray Conference, vol. 9 of International Cosmic Ray Conference, p. 247, Jan., 2011,
DOI.
</p>
<p>
[8] S.T. Ridgway, Considerations for the application of the lunar occultation technique., 82
(1977) 511.
</p>
<p>
[9] V. Dyachenko, A. Richichi, M. Obolentseva, A. Beskakotov, A. Maksimov, A. Mitrofanova
et al., A joint occultation and speckle investigation of the binary star TYC 1947-290-1 and of
the asteroid (87) Sylvia, 508 (2021) 2730.
</p>
<p>
[10] D. Herald, D. Gault, R. Anderson, D. Dunham, E. Frappa, T. Hayamizu et al., Precise
astrometry and diameters of asteroids from occultations - a data set of observations and their
interpretation, 499 (2020) 4570 [2010.06086].
</p>
<p>
[11] R. Leiva, B. Sicardy, J.I.B. Camargo, J.L. Ortiz, J. Desmars, D. Bérard et al., Size and Shape
of Chariklo from Multi-epoch Stellar Occultations, 154 (2017) 159 [1708.08934].
</p>
<p>
[12] M.W. Buie, J.M. Keller, D. Nesvorný and S.B. Porter, Occultation constraints on solar
system formation models, Philosophical Transactions of the Royal Society of London Series
A 383 (2025) 20240194 [2502.00062].
</p>
<p>
[13] H.E. Schlichting, E.O. Ofek, R. Sari, E.P. Nelan, A. Gal-Yam, M. Wenz et al., Measuring the
Abundance of Sub-kilometer-sized Kuiper Belt Objects Using Stellar Occultations, 761
(2012) 150 [1210.8155]
</p>

