# Astrophysics-Masters-Coursework
My project paper exploring how the stellar wind and magnetic field influence dust clouds in the AU Mic debris disk

## <u>Abstract</u>

In 2014, strange undulating dust clouds were observed in the southeast ansa of the debris disk orbiting the M dwarf AU Microscopii. It was proposed that these features are clouds of dust produced in 'avalanches' and subsequently expelled by the stellar wind (Chiang & Fung 2018). These avalanches would be the exponential production of sub-micron dust grains due to the violent intersection of the disk's primary ring and a secondary ring composed of planetary remnants. This avalanche model successfully reproduced many of the observed properties of the clouds such as their projected velocity, size, and mass, but the origin of the oscillating behavior of the clouds remains a mystery. We show that treating the magnetic field with a Parker spiral astrosphere current sheet produces Lorentz forces that yield the oscillating behavior, but don’t exactly match all observations. There are many loose ends left to tie up before we use our results to confidently lend support to Chiang & Fung's avalanche model. 

## <u>Introduction</u>

Debris disks are usually detected by dust's excess infrared thermal emission (Matthews 2014).  A select few disks can be resolved in images. M dwarfs are not typically good candidates for direct imaging as they are fainter, making adaptive optics wavefront correction difficult (Boccaletti et al. 2018). These low mass stars also typically have lower dust contents to detect (Boccaletti et al. 2018). To this day, there are only a handful of resolved images of debris disks around M dwarfs. 

The M dwarf AU Microscopii is auspiciously close to the solar system at an approximate distance of 9.8 pc, and as a member of the ![](https://latex.codecogs.com/svg.latex?%5Cbeta) Pic moving group, it has been an object of interest to observers (Boccaletti et al. 2018). In 2004, Kalas et al. directly imaged the edge-on debris disk around AU Mic with the University of Hawaii's 2.2-m telescope and its optical stellar coronograph (Kalas et al. 2004). 

Follow-up observations with the Hubble Space Telescope (HST) and the Keck telescope found a break in the surface brightness profile at a stellocentric distance around ~25 to ~40 AU (Strubbe & Chiang 2006). This suggested the presence of a concentrated primary or 'birth ring' containing most of the mass in the disk (Chiang & Fung 2018). The inner disk region relative to this birth ring is devoid of small dust grains (Strubbe & Chiag 2006). There was also a significant brightness asymmetry with the southeast side dimmer than the northwest side (Boccaletti et al. 2018). 

This motivated further observations of AU Mic's debris disk. In 2014, it was observed with the Spectro-Polarimetric High-contrast Exoplanet REsearch instrument (SPHERE) at the Very Large Telescope (VLT). The high angular resolution and contrast revealed the structures above the disk midplane in the southeast ansa of the disk. These arched intensity variations are depicted in Figures 1 and 2. 

<img src="disk doop.png" alt="drawing" style="width:420px;"/>

__Figure 1:__ _Various direct images of AU Microscopii's debris disk with strong enough resolution to see structures above the midplane in the southeast ansa of the disk. (Figure 1 of Boccaletti et al. 2015)_




<img src="observed.png" alt="drawing" style="width:420px;"/>

__Figure 2:__ _A closer look at the five main features: undulating intensity variations. (Figure 2 of Boccaletti et al. 2015)_ 





Typically leftover gas, resonances, or outflows from planets can explain structures in debris disks, but these hypotheses cannot account for the features' radial speeds exceeding the escape velocity, the increased speed with increased stellocentric distance, nor the isolation of the structures to one side of the disk (Chiang & Fung 2018). These anomalies, in addition to the knowledge that most of the disk mass is concentrated in the birth ring with a radius of approximately 35 AU, compelled Chiang & Fung to postulate that the features are sub-micron dust clouds being accelerated by the stellar wind. These sub-micron grains are produced at an exponential rate due to an 'avalanche' or a series of violent collisions at the intersection of the birth ring and a secondary ring composed of debris from a destroyed planetesimal (Chiang & Fung 2018). The geometry of this avalanche theory is shown in Figure 3 and more details on the mechanics of this model can be found in Chiang & Fung 2018. 

<img src="rings.png" alt="drawing" style="width:420px;"/>
__Figure 3:__ _Illustration of Chiang & Fung's avalanche theory (Figure 1 in Chiang & Fung 2018)._





The avalanche model successfully reproduces various observable characteristics of the system such as the projected velocities, sizes, and masses of the five features (Chiang & Fung 2018). A key shortcoming of the analysis, however, involves reproducing the undulating shape of the clouds and explaining how the clouds maintain an approximate vertical displacement of 2 AU above the disk instead of being launched far above or below the disk. 

The issue (that Chiang has acknowledged since publishing) lies in the treatment of the magnetic field. Stellar rotation, the stellar wind, and misalignment of the rotation and magnetic axes have a strong effect on the interplanetary magnetic field. In this work, we reevaluate the Lorentz force's contribution to a dust grain's motion through the disk by accounting for these complications. We aim to reproduce the wave-like shape of the dust clouds while remaining consistent with the other successes of Chiang & Fung's avalanche model. Such a result would yield further support to this theoretical explanation of AU Mic's strange debris disk behavior as well as lend insight into the complexities of a star's interplanetary magnetic field. 

## <u>Model Methods</u>
### Current Sheet 

AU Mic is a strongly convective, active young M dwarf with a short rotation period of 4.847 days (Hebb et al. 2007). These qualities suggest that AU Mic has a strong magnetic field, and the star's high mass-loss rate indicates a strong stellar wind (Chiang & Fung 2018). The stellar wind is a highly electrically conductive plasma, and from Alfven's theorem of magnetohydrodynamics, it follows that the magnetic field lines are frozen into the plasma. Subsequently, the stellar wind drags the magnetic field lines deep into the astrosphere. 

The stellar magnetic field is like that of a dipole whose magnetic poles flip according to the star's magnetic cycle. The astrospheric current sheet (ACS) delineates a boundary between the negative and positive field lines extending toward and away from the star, respectively. The magnetic field does not go to zero at the ACS; the field discontinuously changes sign, and we model the magnitude of the field as symmetric about the current sheet. An oversimplified treatment of the stellar magnetic field assumes the ACS is flat and coplanar with the disk, and the magnetic field is radial (Smith 2018). This assumption breaks down when the magnetic and rotation axes are misaligned--a common occurrence and a safe assumption for AU Mic (Smith 2001). This paper seeks to analyze the magnetic field more completely and account for these complexities. 

The rotation of the star bends the magnetic field lines into Archimedean spirals, and the tilt of the magnetic axis and the stellar wind collectively warp the ACS into a Parker spiral, creating a series of peaks and troughs as shown in Figure 4 (Smith 2018). This is significant, as now charged particles lying above the disk midplane may cross the ACS multiple times and encounter both positive and negative magnetic forces depending on their radial stellocentric distance and latitude position (Smith 2018). The locations where the ACS is crossed and the field sign flips are called sector boundaries (Smith 2018). 





![a](FSU.gif)
__Figure 4:__
_The stellar rotation, misalignment between the rotation and magnetic axes, and the stellar wind collectively warp the current sheet into the Parker spiral shown here in blue. This astrospheric current sheet serves as a boundary between opposite polarities of the magnetic field. The magnetic field lines shown in yellow follow Archimedean spirals._



While the radial positions of sector boundaries are approximately stationary for most of the magnetic cycle, the inclination of the entire ACS varies dramatically (Smith 2018). At stellar minimum, the ACS can be considered parallel to the equatorial plane, but at stellar maximum it is highly inclined, and the Parker spiral model breaks down (Landgraf 2000). The current sheet may extend from pole to pole at stellar maximum, and there may even be multiple isolated current sheets, further complicating the structure (Hoeksema et al. 1983). We ignore some of these magnetic cycle effects and focus on the radial locations of sector boundaries and the strength and sign of the magnetic field throughout the magnetic cycle. We would like to incorporate the tilt of the current sheet in our later work, but justify our current simplified model by noting that the field is weakest nearest stellar maximum, and thus the equatorial Parker spiral is an acceptable model for the periods of strongest magnetic forces.

Currently, astronomers don't have detailed models of the structure of the ACS, but the interplanetary magnetic field is known to large-scale approximation. This so-called Parker field is a function of astrographic coordinates which can be expressed in terms of spherical coordinates <img src="https://render.githubusercontent.com/render/math?math=r">, <img src="https://render.githubusercontent.com/render/math?math=\xi = \frac{\pi}{2} - \theta">, <img src="https://render.githubusercontent.com/render/math?math=\phi">. The components of the field equations are given in Equation 1 (Landgraf 2000).  

![equation](https://latex.codecogs.com/gif.latex?B_r%20%3D%20%5Cpm%5C%20B_%7Br%2C0%7D%5C%20%5Cleft%28%5Cfrac%7Br_0%7D%7Br%7D%5Cright%29%5E2%20%5C%5C%20B_%5Ctheta%20%3D%200%20%5C%5C%20B_%5Cphi%20%3D%20%5Cpm%5C%20B_%7B%5Cphi%2C0%7D%5C%20%5Cfrac%7Br_0%7D%7Br%7D%5Ccos%5Cxi)


![](https://latex.codecogs.com/svg.latex?B_%7Br%2C0%7D) and ![](https://latex.codecogs.com/svg.latex?B_%7B%5Cphi%2C0%7D) are the magnitudes of the magnetic field components at ![](https://latex.codecogs.com/svg.latex?r_0%20%3D%2035%5C%20%5Ctextrm%7BAU%7D). At the large stellocentric distances of interest here (> 35 AU), the magnetic field lines are almost entirely azimuthal and it is therefore appropriate to approximate that ![](https://latex.codecogs.com/svg.latex?B_%7Br%2C0%7D%20%3D%200) (Chiang 2018). To determine the strength of the azimuthal component of the field, we compare AU Mic's field to the Sun's. The mean field strength of AU Mic is 4.2 kG, or approximately 2.8 times stronger than the solar 1.5 kG (Linsky 1994). The solar system's interplanetary magnetic field has been shown to follow ![](https://latex.codecogs.com/svg.latex?B_%7B%5Cphi%7D%20%5Csim%2040%5C%20%5Cmu%20G%5C%20%5Cleft%28%5Cfrac%7Ba%7D%7B%5Ctextrm%7BAU%7D%7D%5Cright%29%5E%7B-1%7D), and thus a field 2.8 times larger would yield ![](https://latex.codecogs.com/svg.latex?B_%7B%5Cphi%2C0%7D%20%3D%203.2%20%5C%20%5Cmu%20G%5C%20%24%20@%20%24r_0%20%3D%2035%5C%20%5Ctextrm%7BAU%7D)

For ease of calculation, it is customary to determine the signs of ![](https://latex.codecogs.com/svg.latex?B_r) and ![](https://latex.codecogs.com/svg.latex?B_%5Cphi) with an average polarity (Landgraf 2000). Moving radially outward, a dust grain would encounter alternating sectors of positive and negative polarity. The average polarity of the sectors the dust grain encounters depends on its latitude ![](https://latex.codecogs.com/svg.latex?%5Cxi) (Landgraf 2000). Typically, this is an appropriate simplification to make for dust grains with radii between ![](https://latex.codecogs.com/svg.latex?0.1%5C%20%5Cmu%20%5Ctextrm%7Bm%7D) and ![](https://latex.codecogs.com/svg.latex?0.7%5C%20%5Cmu%20%5Ctextrm%7Bm%7D) i.e. the grains we are most interested in (Landgraf 2000). But in order to reproduce the alternating upward and downward Lorentz force necessary to produce the observed undulations of the dust clouds, we must look at instantaneous polarity as a function of position. This requires implementing the assumptions made above--the sign of the magnetic field flips both spatially (we look only at the radial not latitudinal change) and temporally (throughout the magnetic cycle). 

To account for the radial changes in magnetic polarity, we simply place sector boundaries every distance ![](https://latex.codecogs.com/svg.latex?D_%7B%5Ctextrm%7BACS%7D%7D) [AU]. The location of the first sector boundary is a distance ![](https://latex.codecogs.com/svg.latex?D_%7B%5Ctextrm%7Bstart%7D%7D%20%3C%20D_%7B%5Ctextrm%7BACS%7D%7D) from the star. In essence, these two free parameters allow us to adjust the geometry of the Parker spiral and define the spatial polarity ![](https://latex.codecogs.com/svg.latex?p_%7B%5Ctextrm%7Bspace%7D%7D). In addition, the temporal changes to the magnetic field throughout the magnetic cycle period ![](https://latex.codecogs.com/svg.latex?t_%7B%5Ctextrm%7Bmag%7D%7D) can be expressed with the cosine term in Equation 2. The parameter ![](https://latex.codecogs.com/svg.latex?%5Cdelta_%7B%5Ctextrm%7Bhigh%7D%7D) has units of years and determines when the high phase starts (Note that ![](https://latex.codecogs.com/svg.latex?%5Cdelta_%7B%5Ctextrm%7Bhigh%7D%7D) may be negative). 


![](https://latex.codecogs.com/svg.latex?B_%7Br%2C%5Cphi%7D%20%3D%20p_%7B%5Ctextrm%7Bspace%7D%7D%20%5Ctimes%5C%20%5Ccos%5Cleft%28%5Cfrac%7B2%5Cpi%7D%7Bt_%7B%5Ctextrm%7Bmag%7D%7D%7D%5C%20%5Cleft%5Bt%20-%20%5Cdelta_%5Ctextrm%7Bmag%7D%5Cright%5D%20%5Cright%29%5C%20%5Ctimes%5C%20%5Cleft%7CB_%7Br%2C%5Cphi%7D%5Cright%7C)

We find that we can best reproduce the observations of Boccaletti et al. when ![](https://latex.codecogs.com/svg.latex?D_%7B%5Ctextrm%7BACS%7D%7D%20%5Csim%2020%5C%20%5Ctextrm%7BAU%7D) and ![](https://latex.codecogs.com/svg.latex?D_%7B%5Ctextrm%7Bstart%7D%7D%20%5Csim%2010%5C%20%5Ctextrm%7BAU%7D). 

### Equation of Motion
Dust grains in the disk are photoionized by AU Mic's UV emission (Chiang & Fung 2018). They move through the disk azimuthally at sub-Keplerian speeds and have a large velocity relative to the radial stellar wind (Chiang & Fung 2018). Subsequently, the Lorentz force acts on these grains in addition to gravity and radiation pressure. The three-dimensional equation of motion is expressed in Equation 3 where ![](https://latex.codecogs.com/svg.latex?%5Cvec%7Bx%7D) is a three-dimensional position vector, ![](https://latex.codecogs.com/svg.latex?%5Cbeta) is the ratio of the magnitudes of radiation pressure force and gravitational force, ![](https://latex.codecogs.com/svg.latex?%5Ctextrm%7BG%7D) is the gravitational constant, ![](https://latex.codecogs.com/svg.latex?M_*) is the stellar mass, ![](https://latex.codecogs.com/svg.latex?q) is the charge of the dust grain, ![](https://latex.codecogs.com/svg.latex?m) is the mass of the dust grain, and ![](https://latex.codecogs.com/svg.latex?%5Cvec%7Bv%7D_%7B%5Ctextrm%7Bwind%7D%7D) is the stellar wind speed (Landgraf 2000). Note that the cross products may be performed in spherical coordinates without requiring a transformation to Cartesian for the calculation. Spherical coordinates require extra care as the unit vectors themselves change with position. But here, the velocity and magnetic field are evaluated at the same point in space, and thus both vectors have identical sets of mutually orthogonal unit vectors. 

![](https://latex.codecogs.com/svg.latex?%5Cddot%7B%5Cvec%7Bx%7D%7D%20&plus;%20%5Cleft%281-%5Cbeta%5Cright%29%5Cfrac%7B%5Ctextrm%7BGM%7D_*%7D%7B%5Cleft%7C%5Cvec%7Bx%7D%5Cright%7C%5E3%7D%5Cvec%7Bx%7D%20-%20%5Cfrac%7Bq%7D%7Bm%7D%5Cleft%5B%5Cleft%28%5Cfrac%7B%5Cdot%7B%5Cvec%7Bx%7D%7D%20-%20%5Cvec%7Bv%7D_%7B%5Ctextrm%7Bwind%7D%7D%7D%7Bc%7D%5Cright%29%5C%20%5Ctimes%5C%20%5Cvec%7BB%7D%5Cright%5D%20%3D%200)

In spherical coordinates, this equation of motion may be divided into the radial, polar, and azimuthal components as expressed in Equation 4. 

![](https://latex.codecogs.com/svg.latex?%5Cddot%7Br%7D%20%3D%20r%5Cdot%7B%5Ctheta%7D%5E2%20&plus;%20r%5Cdot%7B%5Cphi%7D%5E2%20%5Csin%5E2%5Ctheta%20-%20%5Cleft%281-%5Cbeta%5Cright%29%5Cfrac%7BGM_*%7D%7Br%5E2%7D%20%5C%5C%20%5Chspace%7B-1.5cm%7D&plus;%5C%20%5Cfrac%7Bq%7D%7Bm%7D%20%5Cleft%5B%5Cfrac%7B1%7D%7Bc%7D%5Cleft%28%5Cleft%28%5Cdot%7Br%7D%5Chat%7Br%7D%20&plus;%20r%5Cdot%7B%5Ctheta%7D%5Chat%7B%5Ctheta%7D%20&plus;%20r%5Cdot%7B%5Cphi%7D%5Csin%7B%5Ctheta%7D%5Chat%7B%5Cphi%7D%5Cright%29%20-%20v_%7B%5Ctextrm%7Bwind%7D%7D%5Chat%7Br%7D%5Cright%29%5C%20%5Ctimes%5C%20%5Cleft%28p_%7B%5Ctextrm%7Bspace%7D%7D%20%5Ctimes%5C%20%5Ccos%5Cleft%28%5Cfrac%7B2%5Cpi%7D%7Bt_%7B%5Ctextrm%7Bmag%7D%7D%7D%5C%20t%5C%20&plus;%20%5Cfrac%7B%5Cfrac%7Bt_%7B%5Ctextrm%7Bmag%7D%7D%7D%7B4%7D%20-%5C%20%5Cdelta_%7B%5Ctextrm%7Bhigh%7D%7D%7D%7B%5Cpi%7D%5Cright%29%5Cleft%5BB_%7Br_0%7D%5Cleft%28%5Cfrac%7Br_0%7D%7Br%7D%5Cright%29%5E2%5Chat%7Br%7D%20&plus;%20B_%7B%5Cphi_0%7D%5Cfrac%7Br_0%7D%7Br%7D%5Cleft%7C%5Ccos%7B%5Cxi%7D%5Cright%7C%5Chat%7B%5Cphi%7D%5Cright%5D%5Cright%29%20%5Cright%5D%20%5Ccdot%20%5Chat%7Br%7D%20%5C%5C)


![](https://latex.codecogs.com/svg.latex?%5Cddot%7B%5Ctheta%7D%20%3D%20r%5E%7B-1%7D%5Cleft%5Br%5Cdot%7B%5Cphi%7D%5E2%5Csin%5Ctheta%5Ccos%5Ctheta%20-%202%5Cdot%7Br%7D%5Cdot%7B%5Ctheta%7D%20%5C%5C%20%5Chspace%7B-1.5cm%7D&plus;%20%5Cfrac%7Bq%7D%7Bm%7D%5Cleft%5B%5Cfrac%7B1%7D%7Bc%7D%5Cleft%28%5Cleft%28%5Cdot%7Br%7D%5Chat%7Br%7D%20&plus;%20r%5Cdot%7B%5Ctheta%7D%5Chat%7B%5Ctheta%7D%20&plus;%20r%5Cdot%7B%5Cphi%7D%5Csin%7B%5Ctheta%7D%5Chat%7B%5Cphi%7D%5Cright%29%20-%20v_%7B%5Ctextrm%7Bwind%7D%7D%5Chat%7Br%7D%5Cright%29%5C%20%5Ctimes%5C%20%5Cleft%28p_%7B%5Ctextrm%7Bspace%7D%7D%20%5Ctimes%5C%20%5Ccos%5Cleft%28%5Cfrac%7B2%5Cpi%7D%7Bt_%7B%5Ctextrm%7Bmag%7D%7D%7D%5C%20t%5C%20&plus;%20%5Cfrac%7B%5Cfrac%7Bt_%7B%5Ctextrm%7Bmag%7D%7D%7D%7B4%7D%20-%5C%20%5Cdelta_%7B%5Ctextrm%7Bhigh%7D%7D%7D%7B%5Cpi%7D%5Cright%29%5Cleft%5BB_%7Br_0%7D%5Cleft%28%5Cfrac%7Br_0%7D%7Br%7D%5Cright%29%5E2%5Chat%7Br%7D%20&plus;%20B_%7B%5Cphi_0%7D%5Cfrac%7Br_0%7D%7Br%7D%5Cleft%7C%5Ccos%7B%5Cxi%7D%5Cright%7C%5Chat%7B%5Cphi%7D%5Cright%5D%5Cright%29%20%5Cright%5D%20%5Ccdot%20%5Chat%7B%5Ctheta%7D%5C%20%5Cright%5D)


![](https://latex.codecogs.com/svg.latex?%5Cddot%7B%5Cphi%7D%20%3D%20%5Cleft%28r%5Csin%5Ctheta%5Cright%29%5E%7B-1%7D%5Cleft%5B-2%5Cdot%7Br%7D%5Cdot%7B%5Cphi%7D%5Csin%5Ctheta%20-%202r%5Cdot%7B%5Ctheta%7D%5Cdot%7B%5Cphi%7D%5Ccos%5Ctheta%20%5C%5C%20%5Chspace%7B-1.5cm%7D&plus;%5C%20%5Cfrac%7Bq%7D%7Bm%7D%5Cleft%5B%5Cfrac%7B1%7D%7Bc%7D%5Cleft%28%5Cleft%28%5Cdot%7Br%7D%5Chat%7Br%7D%20&plus;%20r%5Cdot%7B%5Ctheta%7D%5Chat%7B%5Ctheta%7D%20&plus;%20r%5Cdot%7B%5Cphi%7D%5Csin%7B%5Ctheta%7D%5Chat%7B%5Cphi%7D%5Cright%29-v_%7B%5Ctextrm%7Bwind%7D%7D%5Chat%7Br%7D%5Cright%29%20%5Ctimes%20%5Cleft%28p_%7B%5Ctextrm%7Bspace%7D%7D%20%5Ctimes%5C%20%5Ccos%5Cleft%28%5Cfrac%7B2%5Cpi%7D%7Bt_%7B%5Ctextrm%7Bmag%7D%7D%7D%5C%20t%5C%20&plus;%20%5Cfrac%7B%5Cfrac%7Bt_%7B%5Ctextrm%7Bmag%7D%7D%7D%7B4%7D%20-%5C%20%5Cdelta_%7B%5Ctextrm%7Bhigh%7D%7D%7D%7B%5Cpi%7D%5Cright%29%5Cleft%5BB_%7Br_0%7D%5Cleft%28%5Cfrac%7Br_0%7D%7Br%7D%5Cright%29%5E2%5Chat%7Br%7D%20&plus;%20B_%7B%5Cphi_0%7D%5Cfrac%7Br_0%7D%7Br%7D%5Cleft%7C%5Ccos%7B%5Cxi%7D%5Cright%7C%5Chat%7B%5Cphi%7D%5Cright%5D%5Cright%29%20%5Cright%5D%20%5Ccdot%20%5Chat%7B%5Cphi%7D%5Cright%5D)


To assign parameter values of a reasonable order of magnitude and to be consistent with the projected distances and velocities Chiang & Fung simulated, we follow the numerical approximations given in their 2018 work. The charge-to-mass ratio ![](https://latex.codecogs.com/svg.latex?%5Ctiny%20%5Cfrac%7Bq%7D%7Bm%7D) is expressed as a scaling relation with that of a proton as shown in Equation 5. Chiang & Fung note that a first-principles calculation of the charge-to-mass ratio is a goal of future work.

![](https://latex.codecogs.com/png.latex?%5Ctiny%20%5Cfrac%7Bq%7D%7Bm%7D%20%3D%20%5Cfrac%7Bs%5C%20%5CPhi%7D%7B4%5Cpi%20%5Crho_%7B%5Ctextrm%7Bp%7D%7D%20s%5E3%20/%203%7D%20%5Csim%205%5C%20%5Ctimes%5C%2010%5E%7B-8%7D%5C%20%5Cfrac%7Be%7D%7Bm_%7B%5Ctextrm%7Bp%7D%7D%7D%20%5Cleft%28%5Cfrac%7B%5CPhi%7D%7B2%5C%20%5Ctextrm%7Bvolts%7D%7D%5Cright%29%20%5Cleft%28%5Cfrac%7B0.1%5C%20%5Cmu%5Ctextrm%7Bm%7D%7D%7Bs%7D%5Cright%29%5E2)

The wind strength relative to gravity is given by the dimensionless parameter ![](https://latex.codecogs.com/svg.latex?%5Cbeta) expressed below in Equation 6 (Chiang & Fung 2018). Chiang & Fung note that AU Mic has a mass-loss rate much greater than the Sun, and flares can drive ![](https://latex.codecogs.com/svg.latex?%5Cbeta) up to 40. It is also likely that the dust grains we are interested in (![](https://latex.codecogs.com/svg.latex?0.1%5C%20%5Cmu%20m)) are about 90% porous which can double the wind strength parameter (Graham). 


![](https://latex.codecogs.com/png.latex?%5Cbeta_%7B%5Ctextrm%7Bw%7D%7D%20%5Cequiv%20%5Cfrac%7B3%5Cdot%7BM%7D_*v_%7B%5Ctextrm%7Bwind%7D%7D%7D%7B16%5Cpi%20GM_*%20%5Crho_%7B%5Ctextrm%7Bp%7D%7Ds%7D%20%5Csim%204%5Cleft%28%5Cfrac%7B%5Cdot%7BM%7D_*%7D%7B10%5E3%5Cdot%7BM%7D_%7B%5Codot%7D%7D%5Cright%29%20%5Cleft%28%5Cfrac%7Bv_%7B%5Ctextrm%7Bwind%7D%7D%7D%7B400%5C%20%5Ctextrm%7Bkm/s%7D%7D%5Cright%29%20%5Cleft%28%5Cfrac%7B0.1%5C%20%5Cmu%20m%7D%7Bs%7D%5Cright%29)

To simulate the variable strength of the stellar wind due to gusts, Chiang & Fung model ![](https://latex.codecogs.com/svg.latex?%5Cbeta) as the piece-wise function in Equation 7 to account for the wind's high and low phases. They try two cases (![](https://latex.codecogs.com/svg.latex?%5Cbeta_%7B%5Ctextrm%7Bhigh%7D%7D%20%3D%2020) or ![](https://latex.codecogs.com/svg.latex?40)) with ![](https://latex.codecogs.com/svg.latex?%5Cbeta_%7B%5Ctextrm%7Blow%7D%7D%20%3D%20%5Cfrac%7B%5Cbeta_%7B%5Ctextrm%7Bhigh%7D%7D%7D%7B10%7D). The low phase lasts three times as long as the high phase. In this work, we explore ![](https://latex.codecogs.com/svg.latex?%5Cbeta_%7B%5Ctextrm%7Bhigh%7D%7D) values beyond 20 and 40, and allow ![](https://latex.codecogs.com/svg.latex?%5Cbeta_%7B%5Ctextrm%7Blow%7D%7D) to be ![](https://latex.codecogs.com/svg.latex?%5Capprox%20%5Cfrac%7B%5Cbeta_%7B%5Ctextrm%7Bhigh%7D%7D%7D%7B10%7D) but not exact. 

Lastly, we erroneously used Chiang & Fung's specific ![](https://latex.codecogs.com/svg.latex?t_%7B%5Ctextrm%7Bhigh%7D%7D) value of ![](https://latex.codecogs.com/svg.latex?t_%7B%5Ctextrm%7Bhigh%7D%7D%20%3D%20%5Cfrac%7Bt_%7B%5Ctextrm%7Bcycle%7D%7D%7D%7B4%7D%20%3D%20%5Cfrac%7Bt_%7B%5Ctextrm%7Bmag%7D%7D%7D%7B8%7D%20%3D%202.5%5C%20%5Ctextrm%7Byr%7D) based on their estimated magnetic cycle period of 20 years. Instead we should change the piecewise function conditions as we change ![](https://latex.codecogs.com/svg.latex?t_%7B%5Ctextrm%7Bmag%7D%7D). In our current analysis, changing the period of the magnetic cycle only changes the periodicity of the magnetic field polarity sign change as discussed above, but does not change the frequency of AU Mic's flaring activity. We expect that this will negatively affect the accuracy of our model to reproduce the observations made by Boccaletti et al., but will not affect our ability to produce the general undulating shape of the dust clouds. We hope to address this oversight in future work. 

![](https://latex.codecogs.com/png.latex?%5Cbeta%20%3D%20%5Cbegin%7BBmatrix%7D%202%5C%20%284%29%20%26%20%5Ctextrm%7Blow%20phase%7D%20%26%20t_%7B%5Ctextrm%7Blow%7D%7D%20%3D%20%5Cfrac%7B3%5C%20t_%7B%5Ctextrm%7Bcycle%7D%7D%7D%7B4%7D%20%3D%20%5Cfrac%7B3%5C%20t_%7B%5Ctextrm%7Bmag%7D%7D%7D%7B8%7D%5C%5C%2020%5C%20%2840%29%20%26%20%5Ctextrm%7Bhigh%20phase%7D%20%26%20t_%7B%5Ctextrm%7Bhigh%7D%7D%20%3D%20%5Cfrac%7Bt_%7B%5Ctextrm%7Bcycle%7D%7D%7D%7B4%7D%20%3D%20%5Cfrac%7Bt_%7B%5Ctextrm%7Bmag%7D%7D%7D%7B8%7D%20%5Cend%7BBmatrix%7D)

As in Chiang & Fung 2018, we assume that the stellar wind speed is comparable to the solar wind's speed of ![](https://latex.codecogs.com/png.latex?v_%7B%5Ctextrm%7Bwind%7D%7D%20%3D%20400%5C%20%5Ctextrm%7Bkm%7D%5C%20%5Ctextrm%7Bs%7D%5E%7B-1%7D). The accepted mass of AU Mic is ![](https://latex.codecogs.com/png.latex?M_*%20%3D%200.6%5C%20M_%5Codot) (Boccaletti et al. 2015). 

### Numerical Integration
To track the position of a charged dust particle, we perform a three-dimensional, seventh order Runge-Kutta integration over 40 years using the three ordinary differential equations shown above in Equation 4. The seven input parameters are ![](https://latex.codecogs.com/png.latex?%5Cleft%5B%5Cdot%7Br%7D%2C%20%5Cdot%7B%5Ctheta%7D%2C%20%5Cdot%7B%5Cphi%7D%2C%20r%2C%20%5Ctheta%2C%20%5Cphi%2C%20t%5Cright%5D). To be consistent with the geometry used in Boccaletti et al. 2015 and Chiang & Fung 2018, the initial position of a dust grain in the avalanche zone in spherical coordinates is ![](https://latex.codecogs.com/png.latex?%5Cleft%28r%3D35%5C%20%5Ctextrm%7BAU%7D%2C%20%5Ctheta%20%3D%20%5Cfrac%7B%5Cpi%7D%7B2%7D%2C%20%5Cphi%20%3D%20%5Cfrac%7B3%5Cpi%7D%7B2%7D%5Cright%29). We approximate that dust particles through the disk at Keplerian speeds and thus ![](https://latex.codecogs.com/png.latex?%5Cdot%5Cphi_0%20%3D%20%5Csqrt%7B%5Cfrac%7BGM%7D%7Br_0%5E3%7D%7D), but we keep ![](https://latex.codecogs.com/png.latex?%5Cdot%7Br%7D_0%2C%20%5Cdot%5Ctheta_0%20%5Capprox%200). 

## <u>Results and Discussion</u>
As shown in Figure 4 below, a charged dust particle originating from the avalanche zone can trace out an undulating path resembling the one Boccaletti et al. observed as it is exerted on by gravity, radiation pressure, and the magnetic Lorentz force. In Figure 4 the x-axis shows the projected distances of the particle as it travels from right to left away from the star from the perspective of the observer looking at the disk edge-on. The disk lies in the x-y plane, and AU Mic lies at (0,0,0) in cartesian coordinates. This geometry allows us to directly compare the simulated path to that observed by Boccaletti et al. 

The vertical lines and corresponding shaded error bars indicate the observed locations of the five features A, B, C, D, and E from Boccaletti et al. 2015. Encouragingly, the locations of the peaks for A, B, and C match the observed locations well. We are also able to reproduce cloud B's higher amplitude than the others as seen in Figure 4. Nevertheless, the amplitudes of the peaks in the particle's simulated path are larger than those observed. Though the observed dust clouds peak at approximately 2 AU, we are optimistic that further work with fitting models will enable us to adjust this scale. Table 1 contains the values of the free parameters used for simulating this path, and they are compared to those implemented by Chiang & Fung. 
$$ $$


|Source|![](https://latex.codecogs.com/png.latex?%5Cdot%5Ctheta_0) | ![](https://latex.codecogs.com/png.latex?%5Cbeta_%7B%5Ctextrm%7Bhigh%7D%7D) | ![](https://latex.codecogs.com/png.latex?%5Cbeta_%7B%5Ctextrm%7Blow%7D%7D) |![](https://latex.codecogs.com/png.latex?%5Cdelta_%7B%5Ctextrm%7Bhigh%7D%7D) | ![](https://latex.codecogs.com/png.latex?v_%7B%5Ctextrm%7Bwind%7D%7D)| ![](https://latex.codecogs.com/png.latex?D_%7B%5Ctextrm%7BACS%7D%7D) | ![](https://latex.codecogs.com/png.latex?D_%7B%5Ctextrm%7Bstart%7D%7D) | ![](https://latex.codecogs.com/png.latex?t_%7B%5Ctextrm%7Bmag%7D%7D) |
|------|------|------|------|------|------|------|------|------|
|Fleming 18|-0.078| 20.9 | 2 | 3 yrs | 350 km/s | 20 AU | 10 AU | 5.1 yrs|
| C&F 18 | 0 | 20 (40) | 2 (4) | 7.5 yrs | 400 km/s | na | na | 20 yrs |

__Table 1:__ _A comparison of the free parameter values used in Chiang & Fung's and our analysis._
$$ $$

$$ $$

Most notably, we find that the period of the magnetic cycle must be much shorter than 20 years in order for the magnetic field to switch signs more frequently and create the oscillating behavior. This shorter period may actually be an improvement on the model for AU Mic since a criticism of the avalanche theory is the long duration of the flaring high phase. There is great agreement between our two wind strengths $\beta_{\textrm{high}}$ and $\beta_{\textrm{low}}$.  

$$ $$

$$ $$
<img src="z vs x shaded.png" alt="drawing" style="width:500px;"/>

__Figure 4:__
A charged dust grain follows this blue path from right to left as it is expelled by the stellar wind and the lorentz force. The observed projected stellocentric distance of the five features are shown with vertical lines and corresponding shaded error bars. The simulated trajectory reproduces the five features A-E, the first three of which match closely with the observed peak locations.

During our analysis, there was concern that adjusting the free parameters would cause us to stray away from the progress Chiang & Fung made in reproducing the projected velocities of the clouds. We determine the projected velocities of the five clouds by tracking the distance a particle of that particular cloud travels in one year (a short enough time scale to be similar to an instantaneous velocity). In Figure 5 below we compare our estimated projected velocities with those observed by Boccaletti et al. As is shown in Figure 4, there is great agreement among the projected distances of clouds A, B, and C, but the projected velocities are too large. Conversely, for clouds D and E, the simulated projected velocities agree well with the observed ones, but the projected distances are too large. 

<img src="projected velocity.png" alt="drawing" style="width:500px;"/>

__Figure 5:__ _A comparison of observed and our simulated projected velocities and distances of the five features._
$$ $$

$$ $$

This particular trajectory in the above 2 figures was simulated with very specific parameter values found by essentially trial-and-error. We hope to perform a Monte Carlo simulation in future work to determine the form of a typical trajectory, and to find the best fit for the multiple free parameters listed in __Table 1__. Something we discovered early on is the high sensitivity to small changes in the free parameter values. This is somewhat disheartening as it seems likely that many of the dust grains in the cloud will not follow this particular path and will be launched far above or below the disk. In the future we hope to look at the distribution of $\left|\dot\theta_0\right|$ for instance among the grains created from avalanches to see how the clouds would move.  


In the figures below, we plot the path of the dust grain in physical space for various parameter values. In these plots, if a parameter is not being varied, its value is given in Table 1. It is evident that a charged particle will be launched into one direction if $\left|\dot\theta_0\right|$, $t_{\textrm{mag}}$, or $v_{\textrm{wind}}$ are too large. Keeping the particle oscillating above the midplane at a steady vertical displacement requires fine-tuning the variables that we would like to continue studying in future work.

<img src="thetaDot.png" alt="drawing" style="width:420px;"/>

<img src="tMag.png" alt="drawing" style="width:420px;"/>

<img src="vwind.png" alt="drawing" style="width:420px;"/>

<img src="WindStrength.png" alt="drawing" style="width:480px;"/>

<img src="highPhase.png" alt="drawing" style="width:420px;"/>

<img src="spacePeriod.png" alt="drawing" style="width:420px;"/>

<img src="startSector.png" alt="drawing" style="width:420px;"/>

## <u>Conclusion</u>
Modeling the astrophysical current sheet as a Parker spiral instead of a flat plane results in a dust grain trajectory that resembles the strange observations, at least to general shape. We would like to continue improving this work and take the following steps. We hope to construct a more detailed model of the ACS. We will likely not be able to model its detailed substructure such as small waves on the undulating surface itself due to velocity shears (Smith 2001), but we aim to at least incorporate the time-dependent tilt of the ACS. In addition, although we compared the projected positions and velocities of the clouds with observations and Chiang & Fung's work, we would like to more rigorously verify that this new model is still consistent with the other findings such as the mass-loss rate of AU Mic and the cloud sizes. We have not yet investigated the relationship between M dwarf rotation rates and magnetic field activity, but we think this would be a fruitful exercise. And lastly, we eagerly await further observations and calculations of AU Mic's stellar wind strength, magnetic cycle period, etc. in order to better constrain our model. 

## <u>References</u>
Boccaletti A., Sezestre E., Lagrange A. M. et al 2018 A&A 614 A52

Boccaletti, A., Thalmann, C., Lagrange, A.-M., et al. 2015, Nature, 526, 230

Chiang, E., & Fung, J. 2018 ApJ, 848, 4

Graham, J. R., Kalas, P. G., & Matthews, B. C. 2007, ApJ, 654, 595

Hebb, L., Petro, L., Ford, H. C., et al. 2007, MNRAS, 379, 63

Hoeksema, J. T., Wilcox, J. M., & Scherrer, P. H. 1983, Journal of Geophysical Research, 88, 
A12

Kalas, P., Liu, M. C., & Matthews, B. C. 2004, Science, 303, 1990

Landgraf, M. 2000, Journal of Geophysical Research: Space Physics, 105, A5

Linsky, J. L., & Wood, B. E. 1994, ApJ, 430, 342

Matthews, B. C., Krivov, A. V., Wyatt, M. C., Bryden, G., & Eiroa, C. 2014, in Protostars and 
Planets VI, ed. H. Beuther (Tucson, AZ: Univ. Arizona Press), 521

Smith, E. J. 2001, Journal of Geophysical Research, 106, A8

Strubbe, L. E., & Chiang, E. I. 2006, ApJ, 648, 652



```javascript
%%javascript
MathJax.Hub.Config({
    TeX: { equationNumbers: { autoNumber: "AMS" } }
});
```


    <IPython.core.display.Javascript object>

