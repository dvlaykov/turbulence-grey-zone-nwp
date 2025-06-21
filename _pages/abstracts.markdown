---
layout: page
title: 'List of Abstracts'
exclude : true
permalink: /schedule/abstracts/
---

# List of Abstracts

**Author:** Huw Lewis, Katy Hill (UK Met Office)

**Title (Opening Talk):** Advancing prediction and projection capabilities for enhanced weather and climate services

**Abstract:** Advancing prediction and projection capabilities for enhanced weather and climate services Dr Katy Hill, Associate Director Foundation Science, Met Office Dr Huw Lewis, Head Regional Model Evaluation & Development, Met Office  Working in partnership with others across the UK and internationally, the Met Office continues to explore the costs and benefits of enhancing model resolution, physics representation, coupling between environmental components, and ensemble design to optimise our delivery of weather and climate information to help people to stay safe and thrive. At the same time, rapid advances in data-driven machine learning offers new opportunities to both exploit our physics-based simulations to underpin these developments, as well as exploiting machine learning to enhance our physics-based models. This opening talk will highlight several current strands of Met Office research, with a focus on the successes and challenges of exploiting increasing model resolution.  For example, we have long known that better resolving orography, the land surface and small-scale physical processes can lead to improved predictions with km-scale regional models forming the backbone of daily weather forecasts and the UK’s national climate projections. UK research community efforts are currently assessing these approaches applied to global model domains to understand the role of upscale feedback from small to larger scales and the impact this may have on reducing systematic model errors. This is underpinned by development of a traceable model hierarchy, enabling exploration of different model physics choices on process representation across a range of scales.  Beyond km-scale, advancement of hectometric models have demonstrated the potential benefits of 100-m scale models for representing a range of phenomena, and enabled delivery of local scale information to some users. Moving to finer resolutions can bring new challenges, as will be discussed through the workshop, and briefly introduced in this talk.  The computational cost of km-scale global Earth system models or hectometric-scale national prediction and projections is a key constraint and may be unachievable or undesirable for full climate or operational weather forecasting applications. The rapid advance in data-driven downscaling, machine learning emulators and other application of AI therefore offer exciting prospects to bridge this gap, underpinned by high quality physical model capabilities, to provide usable information for society.

---
# Session 1
**Author:** Rachel Honnert 

**Title (Featured Talk):** From grey-zone of turbulence to AROME-500m

**Abstract:** My research topics focus on the representation of atmospheric boundary layer turbulence on kilometre and hectometre scales in mesoscale numerical weather prediction (NWP) models such as AROME. Increasingly powerful supercomputers are making it possible to achieve hectometric resolutions. I am therefore looking to document the characteristics of turbulence in the atmospheric boundary layer in the resolution range where the turbulence is not yet fully resolved, but no longer fully submeshed: the grey zone of turbulence. Initially, it was necessary to define the range of resolution affected and its characteristics in terms of the various parameters, and to quantify the defects in the physical parameterisations of the mesoscale (1-10 km resolution). Initially, I concentrated on the grey zone of shallow convection, which is where the largest turbulent structures are found. At the same time, other questions about the grey zone of turbulence have emerged. In particular, at the hectometric scale, horizontal inhomogeneities become important and we need to start modelling turbulence in 3D. However, abandoning the homogeneity hypothesis poses major technical difficulties for AROME. Finally, residual turbulence is not necessarily isotropic, as is assumed at very high resolution. It was necessary to work on mixing lengths.

---
&nbsp;        
**Author:** Robert Beare (University of Exeter)

**Title:** The role of diffusion in boundary-layer turbulence simulation in the grey zone

**Abstract:** The Large Eddy Simulation (LES) regime of boundary-layer turbulence modelling is expected to be reasonably independent of sub-grid model choices. In contrast, numerical weather predictions at 1 km grid length are in the grey zone of the convective boundary layer where the sub-grid model and other sources of diffusion play a much larger role. Also, the  expectation at the limit of the grid length being the same order as the boundary-layer depth ($\Delta x \sim h$) is that turbulence should collapse due to being no longer resolved. The rate of transition from resolved to unresolved flow with increasing grid length is a key question in grey-zone research.   In this paper we investigate the role of sub-grid diffusion magnitude on the simulation of turbulence at grid lengths ranging from LES to the grey zone, focusing on three key features. For the LES, and at high wavenumbers, we look at the fall-off of the spectrum with respect to the inertial sub-range. In the grey zone, we examine the collapse of turbulence at $\Delta x \sim h$ and the ability to spin up turbulence.  Our methodology is to compare a numerical weather prediction model (the Met Office Unified Model) with an established LES model with a completely different dynamical core (MONC) but both using a Smagorinsky sub-grid model. We use an established convective boundary layer case.  Both models require an enhancement of diffusion to give a collapse of turbulence at $\Delta x \sim h$.  In contrast, the spin up of turbulence within the grey zone ideally requires a reduced diffusion. This indicates that grey-zone diffusion levels are regime dependent. 

---
&nbsp;     
**Author:** Didier Ricard (Météo-France)

**Title:** Counter-gradient structures in deep convective clouds and their representation in Numerical Weather Prediction models.

**Abstract:** Deep convective clouds are associated with strong turbulence, which is often underestimated in models using resolution on kilometre or hectometre scales. In addition, as in the boundary layer, there are so-called counter-gradient structures in convective clouds linked to the presence of coherent structures.  The aim of this study is to characterise the turbulence in convective clouds using Large-Eddy Simulations (LES) carried out with the Meso-NH model.   These LES with a resolution of 50 m are used to calculate turbulent flows at different coarser horizontal resolutions (500 m, 1 km and 2 km) using a coarse-graining technique. The vertical turbulent fluxes of the ice-liquid water potential temperature and the mixing ratio of the total non-precipitating water exhibit counter-gradient structures, indicating non-local turbulence.   A diagnostic evaluation, at these coarser resolutions compared with the reference LES fields, of a traditional eddy-diffusivity type turbulence parameterisation used in the Meso-NH and AROME models shows that the turbulent kinetic energy is largely underestimated in clouds, in connection with an underestimation of thermal production. Similar results were obtained using the Smagorinsky parametrisation. The counter-gradient structures of vertical turbulent flows are not reproduced, as the local formulation of the K-gradient is not suitable. An alternative parametrisation, based on the horizontal gradients of the resolved variables (so-called Leonard terms), as proposed by Moeng (2014), gives a better representation of the thermal production of turbulence in clouds (horizontal and vertical thermodynamic fluxes).   The online evaluation using simulations with a horizontal grid spacing of 2 km, 1 km and 500 m confirms the improvement when using the modified scheme according to Moeng, with an increase in subgrid turbulence and a decrease in vertical velocities in convective clouds. This modified scheme is also evaluated using Meso-NH simulations at kilometre-scale resolutions for real cases of deep convection as well as in the operational model AROME.

--- 
&nbsp;  
**Author:** Bowen Zhou (Nanjing University)

**Title:** Variations of Subgrid-Scale Turbulent Fluxes in the Dry Convective Boundary Layer at Gray Zone Resolutions

**Abstract:** In the numerical gray zone of the convective boundary layer (CBL), the horizontal resolution is comparable to the size of organized convective circulation. As turbulence becomes partially resolved, grid-scale variations of the subgrid-scale (SGS) turbulent fluxes become significant compared to the mean. Previously, such variations have often been ignored in scale-adaptive planetary boundary layer schemes developed for the gray zone. This study investigates these variations with respect to height and resolution based on large-eddy simulations. It is found that SGS fluxes exhibit maximum variability at the center of the gray zone, where the resolved and the SGS mean fluxes are approximately equal. A simple analytical model is used to associate such characteristic variations to the nonlinear interactions of the dominant energy-containing mode of CBL turbulence. The maximum grid-scale variation is then utilized as a robust measure of the gray zone length scale, and is more advantageous than the widely-used equipartition length.

--- 
&nbsp;    
**Author:** Stephan de Roode (TU Delft)

**Title:** Momentum Transport in Turbulent Atmospheric Boundary Layers

**Abstract:** The vertical profiles of the wind speed and direction in atmospheric boundary layers are strongly controlled by turbulence. Most global weather forecast and climate models parameterize the vertical transport of horizontal momentum by turbulent eddies by means of a downgradient eddy diffusion approach, in which the same stability-dependent eddy viscosity profile is applied to both horizontal wind components. In this study we diagnose eddy viscosity profiles from large-eddy simulations of a stable, a neutral and five convective boundary layers. Each simulation was forced by the same geostrophic wind of 7.5 ms$^{-1}$, but with different surface heat fluxes. For convective cases we find that the eddy viscosity profiles for the two horizontal wind components differ significantly, in particular, we diagnose negative eddy viscosities, indicating  vertical turbulent transport that is counter the mean gradient. This suggests that a purely downgradient diffusion approach for turbulent momentum fluxes is inadequate. A modified solution of the Ekman spiral demonstrates that different eddy viscosity profiles for the two horizontal wind components lead to a different wind profile. To improve parameterizations that apply a downgradient diffusion approach for momentum,  correction terms to allow for non-local, boundary-layer scale transport should be incorporated.


--- 
&nbsp;         
**Author:** Paul Burns (Met Office)

**Title:** Filtering high-resolution UM simulations of idealised dry convective boundary layers to inform grey-zone turbulence modelling

**Abstract:** 
Comparison of UM and filtered high-resolution solutions for well-developed
dry convection using a blended subgrid turbulence scheme reveals a clear lack
of smaller-scale horizontal variability in the total heat flux at gray zone
resolutions $\geq$ 500 m. Power spectral analysis corroborates this and vertical profiles
of heat flux components indicate a lack of horizontal variation in the UM subgrid
heat flux. A lack of power at all scales was found for UM grid resolutions $\geq$ 1 km,
indicating either the subgrid scheme extracts too much energy or a need for
upscale energy transfers from the subfilter to resolved scales. Resolved flux
was found to be too large for UM effective resolutions. Analysis of Cross, Reynolds
and Leonard fluxes from the filtering are broadly similar
to those of Moeng et al at filter scales about half the size of largest turbulent features,
but that the assumption of a modified Clark model to parametrise both Leonard and
Cross terms may not be safe for finer gray zone resolutions and close to the ground.
Horizontal components of the Leonard and Cross terms were found to be as
important as the vertical fluxes close to the ground.

---
# Session 2

**Author:** Peter Clark (University of Reading)

**Title:** 3DTE: A non-downgradient turbulence parametrization for the turbulent grey-zone.

**Abstract:** It is well-known the down-gradient parametrization of turbulent fluxes represented by commonly-used schemes such as Smagorinsky and ‘1.5-order closure’, or ‘TKE’ schemes are only adequate for model filter-scales deep within the inertial subrange, where isotropy and steady-state assumptions may apply. Even here there is no obvious justification to ignore the tilting of sub-filter fluxes. We present the formulation and testing of a scheme that seeks to retain both buoyancy-related counter-gradient terms and tilting/shear-production terms. Mellor-Yamada-related scaling arguments are used to obtain an approximate solution of closed, filtered second-order equations.  The resulting scheme can be related to existing results, including both the so-called non-local or counter-gradient terms and the ‘Leonard terms’ included in the mixed model. The scheme has been implemented in the Met Office’s current Numerical Weather Prediction and Climate model (the MetUM). Results will be presented to evaluate performance within the turbulence grey zone in idealised case studies


--- 
&nbsp;    
**Author:** Junshi Ito (Tohoku University)

**Title:** Greyzone parameterization developed by idealized large eddy simulations of back-building meso-scale convective systems

**Abstract:** Predictions of extreme precipitation caused by back-building mesoscale convective systems (MCSs) is major issue in Japan. Research and development are underway, assuming the operation of high-resolution (dx ~ 1 km) mesoscale meteorological models. This study presents idealized experiments on mesoscale convective systems using large-eddy simulation (LES) and introduces an example of parameterization development based on scale similarity laws derived from these experiments.


--- 
&nbsp;   
**Author:** Yuqi Bai (University of Reading)

**Title:** Implementation of dynamic filtering with grey-zone turbulent closures in a Numerical Weather Prediction Model: Evaluation in idealised cases

**Abstract:** As model resolution decreases into the turbulence grey-zone the conventional Smagorinsky sub-filter model inadequately represents turbulent fluxes. Errors of sub-grid turbulent fluxes and turbulent kinetic energy (TKE) budget is partly because of down-gradient only fluxes and local equilibrium hypothesis TKE only respectively in Smagorinsky parametrization. In addition, the fixed length scale approximation in Smagorinsky parametrization also limits the liability for more heterogeneous and anisotropic formation of grey-zone turbulence. Dynamic filtering has offered one potential improvement over grey-zone turbulence parametrization by using the Germano identity from runtime analogy of coarser-grained spatial filters. The HiFi project aims to implement generalised dynamic filtering to estimate length-scales within a 3D turbulence closure (the 3DTE scheme, inspired by the 1-D Mellor-Yamada-Nakanishi-Niino boundary layer scheme), featuring inclusion of counter-gradient and Tilting/Leonard fluxes. One of the final objectives of HiFi is to be implemented in operational NWP model. In the current work, an implementation of dynamic filtering on sub-grid turbulence parametrization has been evaluated by using idealised runs in Met-Office Unified Model. Both the Smagorinsky parametrization and the 3DTE scheme has been combine with dynamic filtering, using different dynamic options on filter scales and Prandtl number approximations.  Results of these idealised runs are then compared against each other and evaluated quantitatively.


--- 
&nbsp;   
**Author:** Bob Plant (University of Reading)

**Title:** Dynamic diagnoses of turbulent mixing lengths in shallow convection

**Abstract:** The dynamic method, based on the Germano identity, is a popular approach for setting flow-dependent  parameters within turbulence parameterizations. Here we apply the method as a diagnostic tool for studying the variation of mixing lengths with shallow convective flows.   In particular, the MONC large-eddy model was used to produce high-resolution fields for three archetypal case studies: an  idealised dry convective boundary layer, the BOMEX case of subtropical oceanic convection, and the ARM  case of a deepening cloud layer over land. MONC employs the Smagorinsky subgrid scheme, whose filter shape in Fourier space was analysed and found analogous to a Gaussian filter. This facilitated the application of the dynamic method, to calculate flow and filter-dependent mixing lengths, by Gaussian-filtering data to multiple scales.  Distinctive characteristics of turbulent mixing have been identified within the well-mixed boundary layer, the cloud-free environment aloft, and areas within-cloud. Mixing lengths  for momentum, heat, and moisture are significantly influenced by both the flow regime and filter scale. Notably, not all scalars are equivalent, and the consideration of cloud-conserved variables is found to be important.  The variations in the diagnosed mixing length with filter scale are considered within the grey-zone regime  and reveal key dependencies against which grey-zone parameterization methods could be tested. 


--- 
&nbsp;  
**Author:** Jian Zhong (University of Greenwich)

**Title:** Implementation of a synthetic inflow turbulence generator in idealised WRF large eddy simulations under neutral atmospheric conditions

**Abstract:** A synthetic inflow turbulence generator was implemented in the idealised Weather Research and Forecasting large eddy simulation (WRF-LES v3.6.1) model under neutral atmospheric conditions. This method is based on an exponential correlation function and generates a series of two-dimensional slices of data which are correlated both in space and in time. A WRF-LES simulation with periodic boundary conditions was conducted to provide prior mean profiles of first and second moments of turbulence for the synthetic turbulence generation method, and the results of the periodic case were also used to evaluate the inflow case. The inflow case generated similar turbulence structures to those of the periodic case after a short adjustment distance. The inflow case yielded a mean velocity profile and second-moment profiles that agreed well with those generated using periodic boundary conditions, after a short adjustment distance. For the range of the integral length scales of the inflow turbulence (±40 %), its effect on the mean velocity profiles is negligible, whereas its influence on the second-moment profiles is more visible. This implementation enables a WRF-LES simulation of a horizontally inhomogeneous case with non-repeated surface land-use patterns and can be extended so as to conduct a multi-scale seamless nesting simulation from a meso-scale domain with a kilometre-scale resolution down to LES domains with metre-scale resolutions.

---
# Session 3

**Author:** Florian Menter (ANSYS)

**Title (Featured Talk):** Hybrid RANS-LES Turbulence Models in Industrial Use

**Abstract:** The presentation is intended as a cross-disciplinary contribution to showcase hybrid RANS-LES turbulence models as used in today’s industrial CFD codes. The focus will be on the simulation of wall-bounded flow where at least the outer part of the boundary layer grid is sufficiently refined to allow the application of Large-Eddy Simulation strategies.  The models considered are  •	Wall-Function LES (WFLES) •	Wall-Modelled LES (WMLES) o	Alg. WMLES o	Transport equation based WMLES (SBES) Furthermore, the interaction between turbulence model details and numerical settings will be highlighted.  Several industry-relevant cases will be presented, ranging from simple diffuser and airfoil flows to complex technical applications.


---
&nbsp;  
**Author:** Zheng-Tong Xie (University of Southampton)

**Title:** Challenges in coupling between meso-scale and micro-scale simulations

**Abstract:** Coupling between the meso-scale simulations (e.g. UM, WRF codes) and the micro-scale simulations (e.g. large-eddy simulations in CFD codes) has recently attracted a greater attention (e.g. in CWE2014 conference, Hamburg).  Very High Resolution Numerical Weather Prediction (VHR NWP) models can have a grid size of 100m using nesting domains now. Since such a resolution falls into scales in which turbulence is dominant, the unphysical ‘spin-up’ phenomena occurs which pollutes the local flow field.  An appropriate treatment must be imposed at the interface to avoid the problem.  One solution is to insert synthetic turbulence at an appreciate level at the interface. Such techniques have been investigated in engineering communities.  While similar techniques are to be used for meso- and micro-scales coupling, it is not easy to decide how much turbulence intensity (TKE) is to add at the interface.   The talk will also discuss other two key issues in this application. The first one is how to deal with small terrain features (<100 m) which are missing in the current meso-scale models.  The second one is how to deal with clusters of tall buildings of which the wake can last several kilometres. 


--- 
&nbsp;   
**Author:** Georgios Efstathiou (University of Exeter)

**Title:** Dynamic Turbulence Modelling in the ‘Terra-Incognita’ of turbulence.

**Abstract:** TBA


--- 
&nbsp;  
**Author:** John T Bruun (University of Exeter)

**Title:** Universal properties of turbulence cascades and opportunities to improve LES/RANS computations

**Abstract:** The properties of turbulent cascades has been a topic of interest for some time. When large scale computation became available from the 1970’s onwards we have had the capability to examine scale-invariant and universal features of these cascades. Feigenbaum formulated a universal theory and understanding of the features that the period doubling cascade to turbulence exhibit. With modern fine spatial scale Computation Fluid Dynamics methods – one of the challenges we find is that finite grid computations can lead to the Eddy Convection scale not been physically resolved across all its relevant orders of magnitude. In this talk I’ll discuss the Universal features of the period doubling cascade to turbulence with a mix of background (Feigenbaum, 1980, Bruun et al, 2017) and latest related fluid dynamics research papers. The aim here is to debate how these Universal features could further help to identify features of the grey zone turbulence issues that are of interest in LES/RANS settings.     

Feigenbaum, M. J. (1980), The metric universal properties of period doubling bifurcations and the spectrum for a route to turbulence, Ann. N. Y. Acad. Sci., 357, 330–336. 

Bruun, J. T., J. Icarus Allen, and T. J. Smyth (2017), Heartbeat of the Southern Oscillation explains ENSO climatic resonances, J. Geophys. Res. Oceans, 122, 6746–6772, doi:10.1002/2017JC012892.


--- 
&nbsp;   
**Author:** John Thuburn (University of Exeter)

**Title:** Diagnosing numerical dissipation in Implicit Large-Eddy Simulation

**Abstract:** Numerical models designed primarily for global weather and climate prediction are increasingly being used at km-scale resolution, and even convection permitting and LES resolutions. The numerical methods used in such models, such as semi-implicit, semi-Lagrangian schemes, are very different from those typically used in LES, and it is important to understand how they perform in km-scale flow regimes, especially at grey-zone resolutions.  This study will present attempts to quantify the numerical dissipation, both globally and locally, in a semi-implicit, semi-Lagrangian model applied to implicit LES of typical boundary-layer flows. Global dissipation rates of kinetic energy are typical of those seen in LES. Because the model numerics conserve entropy rather than energy, there is also a net global dissipation of internal energy due to numerical mixing that is comparable in magnitude to the global kinetic energy dissipation. Three-dimensional fields of numerical kinetic energy dissipation have plausible distributions and can be related to the structures of the turbulent eddies. It has proved very difficult to obtain believable three-dimensional distributions of numerical internal energy dissipation. Reasons include the inherent ambiguity in the fluxes in any conservation law, the difficulty of accounting for the gauge invariance -- the ability to add a constant to the internal energy without affecting any physical result, and the use in the model of the vertically staggered Charney-Phillips grid.


--- 
&nbsp;  
**Author:** Dimitar Vlaykov (University of Exeter)

**Title:** Dynamic Anisotropic Eddy-Diffusivity for multiscale simulations.

**Abstract:** TBA

---
# Session 4

**Author:** Kirsty Hanley (Met Office)

**Title:** Hectometric modelling for the Paris 2024 Olympic and Paralympic summer

**Abstract:** The Paris 2024 Olympics Research Demonstration Project, endorsed by the World Weather Research Programme of WMO, aimed to make progress on future weather forecasting systems at O(100 m) grid length for urban areas. The project brought together more than 20 national meteorological centres and laboratories from 10 countries. During summer 2024 (the Olympic and Paralympic summer), simulations from seven hectometric numerical models, with grid lengths ranging from 100-500 m, were conducted daily by several of the partner institutes. As part of this, the Met Office contributed a variable resolution 300 m Paris Model (the “PMV”), which was run as an 18-member ensemble nested inside a 2.2km ensemble. The PMV was the only hectometric model run as an ensemble. Overall, the hectometric models look promising for high-impact small-scale convective events such as squall lines and thunderstorms, as they are better able to represent the organisation of convection into lines or larger storms whereas kilometre-scale models tend to simulate isolated, circular storms. However, there is an issue with the hectometric models producing too many small precipitating showers in situations where there should only be shallow clouds. This is thought to be a result of shallow clouds getting too deep in the model and precipitating erroneously. The benefit of hectometric models for larger synoptic-scale features such as MCSs and fronts is less obvious as these are often well represented by the kilometre-scale models (assuming the large-scale conditions are correctly captured by the driving model). In many situations, the PMV ensemble encompassed the solutions of the other hectometric models, highlighting the importance of ensembles for forecasting convection as it is hard to draw conclusions from a single deterministic simulation.


--- 
&nbsp;  
**Author:** Branko Kosovic (Johns Hopkins University)

**Title:** Multiscale simulations of flows in atmospheric boundary layers from mesoscale to microscale: challenges and opportunities

**Abstract:** An accurate characterization of the full complexity of atmospheric boundary layer structure and evolution is needed for a range of applications including wind engineering, renewable energy, transport and dispersion of pollutants, wildland fire prediction, urban climate, etc. High performance computing capabilities now enable detailed studies of heterogeneous boundary layers using multiscale simulations. Nevertheless, the coupling of large-scale simulations with turbulence resolving, microscale simulations presents a number of challenges. To address some of these challenges we have developed a three-dimensional planetary boundary layer parameterization to better represent turbulence in the so called “gray zone,” at grid scales between 100 m and a couple of kilometers. We have also developed and demonstrated a cell perturbation methodology that provides an effective way to develop turbulence when transitioning from a mesoscale to a microscale simulation. Finally, the development of a graphical processing unit (GPU) based large-eddy simulation model, FastEddy, enables addressing uncertainty through an ensemble LES approach. These developments will be demonstrated on idealized as well as multiscale simulations based on the Perdigão field study in complex and heterogenous terrain.


--- 
&nbsp;  
**Author:** Isabelle Gorst (University of Reading)

**Title:** An evaluation of horizontal convective roll characteristics and occurrence in sub-km simulations during the 2023 WesCon - WOEST campaign

**Abstract:** Horizontal convective rolls (HCRs) are counter-rotating vortices in the boundary layer with a typical vertical extent of 1-2 km and a downstream extent of up to 100 km. There are updraft regions that transport moist surface air upwards into the boundary layer and downdraft regions that force dry air down. HCRs are oriented approximately parallel to the mean wind. Formation of cloud streets can occur above the updraft regions as the moist air is cooled as it is carried aloft. Many studies have shown the importance of HCRs in convective initiation as they are critical in determining the spacing between consecutive clouds. In this study, observations from a number of ground based instruments deployed during the WesCon field campaign in summer 2023, including 2 X-band radars, are used to investigate the occurrence and characteristics of HCRs in the UK in relation to boundary layer characteristics. We find that HCRs occur at lower wind speeds than reported in the literature and are associated with a greater convective boundary layer (CBL) stability parameter. The findings from the observations are used to evaluate HCR occurrence in the Met Office Unified Model (UM), which was run at a grid length of 300 m throughout the campaign. When HCRs are present in the model they tend to occur later in the day than observed and are present across the domain, in contrast to the observations which are more limited in occurrence. In comparison to the observations HCRs tend to occur at lower wind speeds but similar CBL stability parameters in the model. The UM was also run at grid lengths of 200 and 100 m for specific dates during the field campaign. For specific cases the importance of model resolution will be explored to gain a better understanding of whether resolution affects the time occurrence of HCRs and their characteristics.


--- 
&nbsp;   
**Author:** Emanuele Silvio Gentile (Princeton University)

**Title:** Enhanced simulations of low-level jets and moisture transport over the US great plains by directly prognosing momentum flux and using a generalised turbulence length-scale  

**Abstract:** We investigate the effects of directly prognosing turbulent momentum flux and implementing a generalized turbulence length scale in the CLUBB (Cloud Layers Unified by Binormals) turbulence scheme within the GFDL-AM4 climate model. The goal is to evaluate improvements in the representation of the low-level jet (LLJ) and associated moisture transport and precipitation patterns over the US Great Plains during summer. Results show that combining prognostic momentum flux with the generalized turbulence length scale yields the most realistic simulations of LLJ structure and precipitation phase and amplitude, outperforming both diagnostic CLUBB configurations and ERA5 reanalysis. The enhancements appear to be driven by increased buoyancy production of upgradient momentum fluxes and improved representation of boundary-layer processes.  Impacts of directly prognosing momentum flux and implementing a generalised turbulent length-scale are further studied by disaggregating the diurnal and nocturnal boundary-layer contributions and the integration of moisture budgets and CAPE fields. Overall, these findings highlight the promise of physical and data-driven strategies to improve boundary-layer turbulence representation in climate models.


--- 
&nbsp;   
**Author:** Adrian Lock (Met Office)

**Title:** Experiences and challenges for operational NWP in the turbulent grey zone.

**Abstract:** TBA


---
&nbsp;   
**Author:** Paolo Giani (Massachusetts Institute of Technology)

**Title:** Impact of Gray Zone Parameterizations on Realistic LES for Numerical Weather Prediction

**Abstract:** Advances in computational power have enabled the use of fine-scale Large Eddy Simulations (LES) in numerical weather prediction, primarily in research settings. LES calculations are often nested within mesoscale models, with large-scale forcing provided by lateral boundaries at coarser resolutions and realistic topography and land use. However, the gray zone of turbulence challenge — where the intermediate domains necessary to couple LES and mesoscale models are too coarse for subgrid LES closures but too fine for traditional boundary layer parameterizations — has emerged as a significant bottleneck in achieving the mesoscale-to-LES coupling. LES solutions are notably sensitive to how turbulence is modeled in the parent gray zone domains. This study examines these sensitivities within the broader context of modeling decisions required for operational regional weather models. We focus on a dry case from 2017 over the Perdigão field site, using an ensemble of 36 configurations of the WRF model with five nested domains ranging from 11.25 km to 30 m resolution. Each configuration represents a unique combination of four key input factors: (i) large-scale initial and boundary conditions, (ii) subgrid turbulence parameterizations in the gray zone, (iii) subgrid-scale (SGS) models in LES, and (iv) topography and land-cover datasets. We probe the relative importance of these four factors for LES calculations of velocity, temperature, and moisture fields. Results indicate that topography and land use datasets are the primary sources of variability in time-averaged quantities across the ensemble. However, local sensitivities can be strongly influenced by gray zone parameterizations. We illustrate this with a case study, exploring the physical mechanisms by which different gray zone schemes produce markedly different wind estimates. We finally discuss the relative importance between gray zone parameterizations and other modeling choices in high-resolution numerical weather prediction.

---
# Session 5

**Author:** Roel Neggers (University of Cologne)

**Title:** Exploring the turbulent/convective grey zone with a binomial thermal population model

**Abstract:** Spatial organization is a defining feature of most forms of turbulence and convection. Numerical models as used in weather prediction and climate simulation struggle to properly represent this behavior. One problem is that organization is typically situated in the "grey zone" of resolutions at which this process is only partially resolved. Another complicating factor is that the exact causes for the emergence of organization in a turbulent field are still not fully understood. In this study we explore to what extent a binomial population model for turbulent/convective thermals can address some of these questions. Thermals are here considered the smallest building block of convection. Being situated on a horizontal microgrid, all aspects of their life cycle are represented through Bernoulli processes, making the model system computationally efficient. Thermals can interact through simple rules, representing processes like pulsating growth and deformation of their environment. Thermal birth rates are calibrated against Large-Eddy Simulations of diurnal cycles of atmospheric convection. The model is then tested across the convective grey zone as implemented in a simple circulation model, coupled to an EDMF transport scheme. The emergence of spatial organization is investigated, including its dependence on the discretization of the host model. Robust forms of organization are identified, matching structures typically detected in subtropical marine Trade Wind cumulus cloud fields. Additional rules of thermal behavior representing impacts of precipitation are explored.


--- 
&nbsp;  
**Author:** Samantha Smith (Met Office)

**Title:** An investigation into length scales for the Comorph convection scheme

**Abstract:** Idealised simulations of the TWPICE case study have been performed at various horizontal resolutions across the convective grey zone using the new Comorph convection scheme.  The performance of the scheme is being assessed against 100m resolution "truth" simulations, with the aim of improving its scale awareness. 


--- 
&nbsp;   
**Author:** Dan Shipley (University of Reading)

**Title:** Examining EDMF-type approaches in the grey zone via conditional filtering

**Abstract:** Mass flux and eddy diffusivity-mass flux-type approaches to convection parametrization generally model the problem as 1D. This is a reasonable assumption at resolutions much coarser than the outer scale of the modelled coherent overturning structures (i.e. the inter-cloud spacing). However, this assumption becomes inappropriate in the grey zone, where the model resolution is similar to the key length scales of the structures being parametrized. To inform mass flux-type approaches to grey zone convection parametrization, we investigate how the 1D assumption is violated as resolution increases using conditional filtering of LES. Using an exact decomposition into ``coherent'' and ``incoherent'' parts, we examine how the 1D -> 3D transition manifests in scalar and momentum fluxes, as well as the constraints placed on the turbulence kinetic energy and vertical velocity variance budgets. These lead to consistency requirements for a mass flux-type parametrization in the grey zone.


---
&nbsp;    
**Author:** Gabriel Rooney (Met Office)

**Title:** Rain and shape effects on idealised downdraughts

**Abstract:** This presentation discusses simulations of idealised, rain-laden downdraughts using the MONC large-eddy model. Each downdraught begins as a “cold, wet bubble” i.e. a spheroidal region of the lower atmosphere with a negative temperature perturbation and a non-zero liquid water content. The bubbles are statically unstable and evolve into downdraughts. The initial buoyancy split between liquid water and temperature reduction affects the downdraught structure, with a larger rain contribution suppressing horizontal downdraught expansion. A drier environment increases cooling in the downdraught, but reduces the peak in downdraught speed. Both these effects stem from increased rain evaporation. Most bubbles are initialised as spherical, but for spheroidal bubbles it is found that downdraughts intensify for an increased bubble height-to-width ratio, being greatest for vertically stretched bubbles and vice versa. The results indicate the effects that rain microphysics may have on km-scale downdraught structures in convective environments.

---
# Poster Session 

**Author:** Alison Stirling (Met Office)

**Title:** The ParaChute programme: An overview

**Abstract:** The ParaChute programme is a UK collaboration between the Met Office and NERC, aiming to improve the representation of turbulence in km and sub-km scale models. A central programme was an observational campaign in Summer 2023 called WesCon.  Here I will present an overview of the wide range of activities, and how we plan to bring these together to improve NWP models.


---
&nbsp;   
**Author:** Bob Plant (University of Reading)

**Title:** A dynamic extension of the pragmatic blending scheme for scale-dependent sub-grid mixing

**Abstract:** Pragmatic blending approaches are used for grey-zone simulations at some operational centres, in which the sub-grid turbulent mixing is estimated using a simple weighted average of the predictions from a 1D mesoscale formulation and a 3D Smagorinsky formulation. Here the approach is modified and extended to incorporate a scale-dependent dynamic Smagorinsky scheme instead of a static Smagorinsky scheme. Results from simulating an evolving convective boundary layer show that the dynamic aspect is able to improve the representation of turbulence statistics and potential temperature profiles at grey-zone resolutions during the transition from the shallow morning to the deep afternoon boundary layer. This is achieved mainly because the dynamic aspect facilitates and controls an earlier spin-up of resolved turbulence. The dynamic blending scheme is also shown to be more adaptive to the evolving flow and somewhat less sensitive to the blending parameters.


--- 
&nbsp;     
**Author:** CHEUNG, Chi-Chiu (Chris) (ClusterTech)

**Title:** Numerical weather prediction at 200 m local resolution based on the unstructured grid CPAS model

**Abstract:** The ClusterTech Platform for Atmospheric Simulation (CPAS) model is derived from the Model for Prediction Across Scales - Atmosphere (MPAS-A), with additional features Customizable Unstructured Mesh Generation and Hierarchical Time-Stepping. CPAS can be used with global meshes with large resolution ratio, steep transition and high-resolution patches in demand or regional meshes in a flexible way because mesh generation is very fast. For high-fidelity hectometric modeling, CPAS implemented multi-resolution geographical data processing using down to 3 arc-second terrain and up-to-date street map coastline. For resolution greyzones CPAS integrated the Shinhong Planetary Boundary Layer and other scale-aware parameterization schemes. Use cases for extreme weather modeling will be shown.


--- 
&nbsp;   
**Author:** Daniela-Christin Littmann (German Weather Service - DWD)

**Title:** The Study of Near-Surface Interaction over Complex Terrain using Subhectrometric Simulations

**Abstract:** Higher resolution models have the potential to be more accurate in capturing the key boundary layer exchange processes. Recently, the use of sub-hectometric grid spacing for operational forecasting has been actively explored by a growing number of meteorological services. However, numerical weather prediction faces increasing difficulties in accurately representing the partially resolved and unresolved processes, as some of the commonly used parametrisations may not be appropriate. Predicting mountainous regions is particularly challenging due to their complex topography and the associated meteorological events that occur at different temporal and spatial scales.  The GLObal to Regional ICON Digital Twin (GLORI-DT) project aims to improve the quality of high-resolution forecasts for the entire Alpine region. The ICOsahedral Non-hydrostatic model is used in Limited Area Mode (ICON-LAM) to perform simulations over complex terrain. The model is run in one-way nesting mode, with an outer domain covering the entire Alps at 2 km horizontal grid spacings with nested configurations at higher resolutions.  Experiments were conducted to investigate the overall model performance for resolutions of 2 km, 1 km, and 500 m when compared observations. The performance of the model at all resolutions is rather similar for a month with strong convection, but higher resolutions show some advantage for winter time (mainly for surface winds). We have tried to adjust the turbulence parametrisation for higher resolutions, which should be less active as more turbulence is being resolved, but found, however, that the model is mostly insensitive to most changes. Only adaptations in the minimum diffusion coefficient have a small positive effect on the results. To further understand this behaviour, we now focus on case studies from campaigns where more observations are available. We have first investigated a cold-air pool observed in the Inn valley during the PIANO campaign on the night of 15-16 October 2017. Simulations in the nested domain were performed down to 250 m. The higher resolution simulations show a cold pool similar to the observed one, although not exactly at the same time and position. This cold pool appears at 1 km resolution and its intensity increases with resolution. This case illustrates one aspect of why higher-resolution simulations do not produce much better scores. Although the higher-resolution simulations can reproduce realistic small-scale winds, they may be in the wrong place in time and space, thus worsening the scores.


--- 
&nbsp;   
**Author:** Lokahith Narendra Agasthya (Institute of Science and Technology, Austria)

**Title:** Moist Convective Scaling: Insights from DNS and CRM simulations

**Abstract:** The scaling of moist convection with changes in the large-scale forcing is crucial to understanding the dynamics of deep convective clouds, both locally and in an average sense across the tropics. While it is expected that increased radiative cooling should lead to a commensurate increase in cumulus mass flux, observations and simulations suggest that this increase comes from an increase in the areal coverage of convection rather than the intensity of convection. In this study, we show that this scaling behaviour is robust across moist convection simulations using cloud resolving models as well as idealised direct numerical simulations, suggesting that it is a fundamental property of moist convective instabilities.Using theory and simulations, we further study the scaling of extreme vertical velocities, buoyancies, CAPE, entrainment and precipitation to draw insights into moist convection and compare its behaviour with dry convection. We strive to bridge the gap between studies of idealised models of convection in fluid dynamics to realistic atmospheric simulations.


--- 
&nbsp;   
**Author:** Matthew Coburn (University of Southampton)

**Title:** Increasing high-fidelity modelling efficiency with automated setup and validation of methodologies

**Abstract:** CFD requires a significant time investment to get accurate, realistic results. The task of the work undertaken here is to reduce the time taken to conduct high-fidelity modelling of chemical plumes through the use of automation. In order to correctly model downstream dispersion, in particular near field dispersion, a good prediction of the flow field is extremely important. Both convection and diffusion processes of the pollutants should be simulated accurately. Convection and diffusion are driven, in urban areas, by large and small turbulent eddies, respectively. Computational Fluid Dynamics (CFD), in the form of Large Eddy Simulation (LES) will be used to resolve the energetic eddies generated within the urban boundary layer. This will make use of Palm4U, an unsteady LES code designed for simulation of urban boundary layers. It is possible to run simulations at near real time with small grids and suitable computing power. To drastically reduce the time required an automation tool will be created. This will include the entire setup process, which includes downloading terrain and building data, creating the mesh file, setting up boundary conditions and generating the required input files.   To demonstrate this capability and the capability of palm overall, a case study will be used. In Dec 2019, a collection of vintage film reels caught alight and started a large fire in the back garden of residential housing in Southampton. The University of Southampton happened to have a sensor network deployed at the time and one sensor was downstream near the plume centre. A study by Clements et. Al. (2024) reviewed different modelling strategies, comparing the Gaussian plume method in ADMS to the LES method embedded in OpenFOAM to estimate the emission rate of pollutants. The sensor data and the OpenFOAM data will be compared to the data produced by Palm4U, as a validation.


--- 
&nbsp;    
**Author:** Stephan de Roode (TU Delft)

**Title:** Dependency of mesoscale organization on grid anisotropy in  large-eddy simulations of convective boundary layers at Gray Zone resolutions

**Abstract:** A new generation of operational atmospheric models operating at horizontal resolutions in the range  $\qty{200}{\metre} \sim$ \qty{2}{\kilo \metre}$ is becoming increasingly popular for operational use in numerical weather prediction and climate applications. Such grid spacings are becoming sufficiently fine to resolve a fraction of the turbulent transports. Here we analyze LES results of a convective boundary layer obtained by coarsening horizontal grid spacings up to 800 m. The aim is to explore the dependency of the mean state and turbulent fluxes on the grid resolution.  Both  isotropic  and anisotropic eddy diffusion approaches are evaluated, where in the latter case  the horizontal and vertical eddy diffusivities differ in accord with their horizontal and vertical grid spacings.   For coarsening horizontal grid  sizes entrainment at the top of the boundary layer tends to get slightly enhanced for isotropic diffusion, whereas for the anisotropic diffusion approach the vertically well-mixed boundary-layer structure becomes severely degraded. An analysis of the energy spectrum shows that anisotropic diffusion causes relatively more dissipation of variance at smaller length scales. This leads, in turn, to a shift of spectral energy towards larger length scales that also becomes apparent from a rather different kind of spatial organization of convection. The present study therefore suggests that details with regards to the representation of processes at small scales might impact the organization at length scales much larger than the smallest scales that can be resolved by the model. 


        
--- 
&nbsp;    
**Author:** Yuhang Tong (University of Exeter)

**Title:** A Surface Layer Scheme for an Implicit Large Eddy Simulation Model

**Abstract:** This research focuses on improving the near-surface performance of an Implicit Large Eddy Simulation (ILES) model. The ILES model uses the Semi-implicit semi-Lagrangian numerical method for simulating the atmospheric boundary layer. Moreover, the model is called an "implicit" model because it includes no explicit scheme to represent subgrid-scale fluxes but makes use of the numerical dissipation. One of the problems we've met so far is that: some simulations indicate the weakness of this model in solving the eddies near the bottom boundary, which can be reflected by, for example, failure to reproduce a log wind profile for the neutral case.  We hope that this type of issue can be solved by spreading the effect of surface flux convergence into several model layers using a surface model. The purpose of this surface model is to minimize the inability of our ILES model to resolve the near-surface eddies.



    
