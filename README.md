CH4-Lutjewad-2016-2017
=====================

Description:
---------------------
Time series of x(CH4), d13C-CH4, and dD-CH4 in ambient air at Lutjewad atmospheric station (NL). 
Time period: 12/11/2016 to 31/03/2017 (DD/MM/YYYY)

Measurement methods:
---------------------
IRMS (Isotopic Ratio Mass Spectrometry) instrument: Thermo Delta Plus XP, Thermo Fisher Scientific Inc., Germany. 
Extraction system described in:
Röckmann, T., Eyer, S., van der Veen, C., Popa, M.E., Tuzson, B., Monteil, G., Houweling, S., Harris, E., Brunner, D., Fischer, H., Zazzeri, G., Lowry, D., Nisbet, E.G., Brand, W.A., Necki, J.M., Emmenegger, L., Mohn, J., 2016. In situ observations of the isotopic composition of methane at the Cabauw tall tower site. Atmos. Chem. Phys. 16, 10469–10487. https://doi.org/10.5194/acp-16-10469-2016.
Brass, M., Röckmann, T., 2010. Continuous-flow isotope ratio mass spectrometry method for carbon and hydrogen isotope measurements on atmospheric methane. Atmos. Meas. Tech. 3, 1707–1721. https://doi.org/10.5194/amt-3-1707-2010.

Modelling methods:
---------------------

_LMDz (Laboratoire de Météorologie Dynamique)_ 
(background x(CH4) only)
Hourdin, F., Musat, I., Bony, S., Braconnot, P., Codron, F., Dufresne, J.-L., Fairhead, L., Filiberti, M.-A., Friedlingstein, P., Grandpeix, J.-Y., Krinner, G., LeVan, P., Li, Z.-X., Lott, F., 2006. The LMDZ4 general circulation model: climate performance and sensitivity to parametrized physics with emphasis on tropical convection. Clim Dyn 27, 787–813. https://doi.org/10.1007/s00382-006-0158-0
Thanwerdas, J., Saunois, M., Berchet, A., Pison, I., Hauglustaine, D., Ramonet, M., Crevoisier, C., Baier, B., Sweeney, C., Bousquet, P., 2019. Impact of atomic chlorine on the modelling of total methane and its 13C:12C isotopic ratio at global scale (preprint). Gases/Atmospheric Modelling/Stratosphere/Chemistry (chemical composition and reactions). https://doi.org/10.5194/acp-2019-925

_CHIMERE_
Fortems-Cheiney, A., Pison, I., Dufour, G., Broquet, G., Berchet, A., Potier, E., Coman, A., Siour, G., Costantino, L., 2019. Variational regional inverse modeling of reactive species emissions with PYVAR-CHIMERE (preprint). Atmospheric Sciences. https://doi.org/10.5194/gmd-2019-186
Mailler, S., Menut, L., Khvorostyanov, D., Valari, M., Couvidat, F., Siour, G., Turquety, S., Briant, R., Tuccella, P., Bessagnet, B., Colette, A., Létinois, L., Markakis, K., Meleux, F., 2017. CHIMERE-2017: from urban to hemispheric chemistry-transport modeling. Geosci. Model Dev. 10, 2397–2423. https://doi.org/10.5194/gmd-10-2397-2017
Menut, L., Bessagnet, B., Khvorostyanov, D., Beekmann, M., Blond, N., Colette, A., Coll, I., Curci, G., Foret, G., Hodzic, A., Mailler, S., Meleux, F., Monge, J.-L., Pison, I., Siour, G., Turquety, S., Valari, M., Vautard, R., Vivanco, M.G., 2013. CHIMERE 2013: a model for regional atmospheric composition modelling. Geosci. Model Dev. 6, 981–1028. https://doi.org/10.5194/gmd-6-981-2013

_FLEXPART-COSMO_
Baldauf, M., Seifert, A., Förstner, J., Majewski, D., Raschendorfer, M., Reinhardt, T., 2011. Operational Convective-Scale Numerical Weather Prediction with the COSMO Model: Description and Sensitivities. Mon. Wea. Rev. 139, 3887–3905. https://doi.org/10.1175/MWR-D-10-05013.1
Henne, S., Brunner, D., Oney, B., Leuenberger, M., Eugster, W., Bamberger, I., Meinhardt, F., Steinbacher, M., Emmenegger, L., 2016. Validation of the Swiss methane emission inventory by atmospheric observations and inverse modelling. Atmos. Chem. Phys. 16, 3683–3710. https://doi.org/10.5194/acp-16-3683-2016
Pisso, I., Sollum, E., Grythe, H., Kristiansen, N., Cassiani, M., Eckhardt, S., Arnold, D., Morton, D., Thompson, R.L., Groot Zwaaftink, C.D., Evangeliou, N., Sodemann, H., Haimberger, L., Henne, S., Brunner, D., Burkhart, J.F., Fouilloux, A., Brioude, J., Philipp, A., Seibert, P., Stohl, A., 2019. The Lagrangian particle dispersion model FLEXPART version 10.3. Geosci. Model Dev. Discuss. 1–67. https://doi.org/10.5194/gmd-2018-333

Data specifications:
---------------------

Times are in __CET__

_Variables_
-__x(CH4)__ -> Methane mole fraction [ppb]
-__d13C__ -> Carbon 13 to carbon 12 isotopic ratio in methane [‰]
-__dD__ -> Deuterium to hydrogen isotopic ratio in methane [‰]

_Measurement uncertainty_
- __CRDS x(CH4)__ -> 2 ppb
- __IRMS x(CH4)__ -> 10 ppb
- __IRMS d13C VPDB__ -> 0.1 ‰
- __IRMS dD VSMOW__ -> 2 ‰

_List of abbreviations_
- __VPDB__ -> Vienna Pee Dee Belemnite
- __VSMOW__ -> Vienna Standard Mean Ocean Water
-__EDGAR__ -> EDGAR v4.3.2 emission inventory
-__TNO__ -> TNO-MACC III emission inventory
-__AGR__ -> emission sector: agriculture
-__WST__ -> emission sector: waste
-__FF__ -> emission sector: fossil fuel extraction and distribution
-__OTH__ -> emission sector: other anthropogenic
-__WETL__ -> emission sector: wetlands
-__BG__ -> background

Authors: 
---------------------
Thomas Röckmann, Carina van der Veen (Institute for Marine and Atmospheric Research Utrecht, Utrecht University), Huilin Chen, Bert Scheeren, Bert Kers and Marcel de Vries (Centre of Isotope Research, University of Groningen, The Netherlands)
_Contact_ Malika Menoud, m.menoud@uu.nl

