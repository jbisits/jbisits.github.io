---
permalink: /research/
title: "Research"
header:
  overlay_image: /assets/images/density.png
toc: true
toc_label: "Research"
toc_icon: "book-open"
---

My area of research is physical oceanography and to date I have been working on ocean mixing.
Ocean mixing is a key part of the climate system as it influences the rate and amount of heat and carbon that are taken in by the ocean.
Once such tracers have made it into the ocean, their transport is strongly influenced by (you guessed it) mixing!

Broadly speaking ocean mixing can be categorised into *lateral* (isopyncal) and *vertical* (across isopycnals) mixing.
Turbulent mixing occurs down to sub-millimetre length scales which can be simulated but the computational cost of doing so, as well as the amount of data that is produced, makes this currently impossible.
This limitation means that in global ocean circulation models many mixing processes need to be parameterised.
Continued research on mixing in the ocean is needed for improvements to how mixing is represented (i.e. parameterised) in global ocean circulation models.

For more information about any of the projects below see the relevant [publications][pubs-page] or feel free to email me.

## Numerical mixing in finite volume ocean models

The discretisation of advection schemes to transport tracers and thickness in finite volume ocean models leads to spurios *numerical* mixing.
Currently we are looking at methods to diagnose numerical mixing --- more to come soon!

## Non-linear controls on ocean circulation and mixing in the high-latitude oceans

The non-linear equation of state for the density of seawater leads to interesting phenomena, such as a gain in density when two water masses of equal density, but differing temperature and salinity, are mixed.
Understanding the effect this gain in density upon mixing and ocean circulation in the high-latitudes was the focus of my PhD.

For a real riot you can find my [thesis here](https://unsworks.unsw.edu.au/entities/publication/31923b90-a5fa-4c58-8202-d59c7434ef72) or just view the <button class="btn btnId btnPub--abstract" id="thesis-abstract" style="outline:none; color:var(--info-color); border-color:var(--info-color);">abstract</button>
<div class="dropDownThesisAbstract" id="thesis-abstract" style="display:none; font-size: 0.75rem;">
    "The uptake and vertical redistribution of heat and carbon is a crucial component of the ocean’s role in regulating Earth’s climate. Turbulent mixing, triggered by gravitational instability, enhances vertical transport of heat and carbon between the sea surface and deep ocean. Non-linearities in the equation of state for seawater density result in processes that can alter local gravitational stability, possibly leading to enhanced mixing. In this thesis I explore the impact of these non-linearities on the thermohaline structure and mixing in the high-latitude oceans. In chapter 2, I seek to establish if the gain in density upon mixing, known as cabbeling, is having an impact in high-latitude oceans. A hypothesis from a 1957 study by N. Fofonoff is extended to investigate if a gravitationally stable profile can become unstable after mixing due to cabbeling creating denser waters i.e. if a profile is unstable to cabbeling. In both observational data and output from a data constrained global circulation model, profiles are rarely unstable to cabbeling suggesting cabbeling sets a limiting threshold for vertical profile stability. Cabbeling’s effect on small-scale mixing is explored using Direct Numerical Simulation (DNS) in chapter 3. The simulations show that a cabbeling instability can trigger and drive convection from an initially gravitationally stable state. Further, cabbeling driven convection is the same order of magnitude as convection driven by static instability indicating parametrisations of convection in global ocean models may need updates to take into account cabbeling instability, particularly at the high-latitudes. In chapter 4, the interaction between cabbeling and double diffusion is investigated using DNS. At high-latitudes, when turbulent mixing is weak and salinity and temperature increase with depth, conditions are favourable for "diffusive" convection. With a linear equation of state, this double diffusive instability forms equal density anomalies within layers either side of a "diffusive" interface. With a non-linear equation of state, our DNS results show a larger density anomaly forms in the lower layer, and the interface migrates upward, consistent with previous laboratory experiments. The temperature difference is found to be the main driver of the asymmetric density anomalies."
</div>

Broadly speaking, when turbulent mixing is the dominant background mixing process in the high-latitude oceans, cabbeling will influence the thermohaline structure of the upper ocean by setting a limiting stability criteria.
When the dominant background mixing process is *diffusive convection*, cabbeling's effect is subtle untile there is a temperature difference of 0.5$\circ$C between layers meaning cabbeling is more prominent in the thermohaline staircases in the Southern Ocean.

![image-right](/assets/images/unsw-crest.png){: .align-right style="width: 20%;"} I was based in the [school of mathematics and statistics](https://www.unsw.edu.au/science/our-schools/maths) under the supervision of [Associate Professor Jan Zika](https://sites.google.com/view/janzika/home), [University of New South Wales](https://www.unsw.edu.au/) Sydney, Australia.

![image-left](/assets/images/ACEAS_logo_1.png){: .align-left style="width: 50%;"} I was also part of the the [Antarctic Centre for Excellence in Antarctic Science](https://antarctic.org.au/) for the duration of my PhD.

### Does cabbeling shape the thermohaline structure of the high-latitude oceans?

In the first project of my PhD, we investigated whether a non-linear process called [*cabbeling*](https://en.wikipedia.org/wiki/Cabbeling) is influencing the thermohaline structure of temperature inverted profiles in the global ocean.
The Antarctic winter causes the surface water to approach its freezing point.
If brine rejection occurs due to sea ice formation, then the density of the winter surface water increases.
Once the salinity of the surface water reaches a critical value, relatively warm and salty deep water that is upwelled to the surface can mix with this winter surface water resulting in a more dense water mass forming (as a result of cabbeling) that can trigger a gravitational instability and convective mixing.
The salintiy-temperature region where the profile becomes unstable to cabbeling is the violet shaded region in the schematic show below.
We developed a criteria to diagnose when a water column will be unstable to cabbeling, but still statically stable, using model output and in-situ observations.

![image](/assets/images/cab_schematic.png)

### Cabbeling as a catalyst and driver of turbulent mixing

The first project of my PhD demonstrated the influence cabbeling is having in the high-latitude oceans but was unable to address whether cabbeling is able to trigger and drive turbulent mixing.
To investigate this we used Direct Numerical Simulations which simulate all length scales of motion to determine how cabbeling impacts mixing and the energetics of mixing - see the figure below with snapshots of the onset of cabbeling triggered convection from a statically stable initial state.
To our knowledge this was the first turbulence resolving simulation to simulate cabbeling which we found can trigger and drive rapid turbulent mixing as well as create a source of available potential energy.

![image](/assets/images/dns_schematic_ts_horizontal.png)

### Interplay between cabbeling and double diffusion

Another small scale process that is prominent in the high-latitude oceans, and drives enhanced mixing, is *doubele diffusion*.
Double diffusion arises because of the differing molecular diffusivities of salinity and temperature; molecular temperature diffusivity is two orders of magnitude larger than molecular salinity diffusivity.
When conditions are favourable, i.e. when there is an *unstable vertical temperature gradient and a *stable* vertical salinity gradient, the differing diffusivities of salinity drive a type of enhanced mixing known as *diffusive convection.*
We investigated how the non-linear nature of the equation of state and double diffusion interact in the high-latitude oceans.
Using Direct Numerical Simulations we found that the non-linearities in the equation of state drive an upward migration of *diffusive interfaces* agreeing with previous laboratory work.

![image](/assets/images/interface_height.png)

## Estimating isopycnal mixing

Isopycnal (i.e. lateral) mixing in the Southern Ocean is important for the global climate as it influences the uptake and transport of heat and carbon.
During my honours year I worked on methods to estimate lateral mixing from simulated tracer release experiments.
The goal was to assess how accurate an estimate of lateral mixing is if there is only data available from a single tracer release experiment (as is the case in observational campaigns such as [DIMES](https://dimes.ucsd.edu/)).
Using a two layer quasi-geostrophic model of turbulent flow we were able to show that data from a single tracer release does yield an accurate estimate when compared to the ensemble average of many tracer release experiments.
An example of the tracer release experiment, built using the [PassiveTracerFlows.jl](https://github.com/FourierFlows/PassiveTracerFlows.jl) package, is below.

{% include video id="17REV8J_tm2WguqOlU6ZD6gC4UBaiiMTK" provider="google-drive" %}

## Water quality modelling and prediction

As a research assistant I worked with [Associate Lecturer Simon Llyod](https://www.unsw.edu.au/staff/simon-lloyd) on processing and analysing data that was used to develop the [RiverWatch model](https://urbanplunge.sydneywater.com.au/content/dam/sydneywater/urban-plunge/documents/Riverwatch%20Predictive%20Model%20fact%20sheet_online.pdf).
This model is a predictive water quality model used to predict the amount of pollution, and consequently whether water is safe, to swim in.

[pubs-page]: https://jbisits.github.io/publications/
