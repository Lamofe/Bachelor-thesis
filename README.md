# Bachelor-thesis
The result of piepline

The result of the photometry pipeline：
a) gband_result.7z     a compressed PDF file containing 225 pages
                       each page contains the g band result plots of one galaxy including original image, mask, clean data, curve of growth, background fluctuation and model flux fitting
b) rband_result.7z     a compressed PDF file containing 225 pages
                       each page contains the r band result plots of one galaxy including original image, mask, clean data, curve of growth, background fluctuation and model flux fitting

The catalog of sample galaxies：
low_mass_galaxy&rgflux_photometry&extinction&stellar_mass.fits         contain the information of 365 sample galaxies
columun names (80) and discription
1)_RAJ2000            RA from Cosmicflow-3 (Tully et al. 2016) with units in deg
2)_DEJ2000            DEC from Cosmicflow-3 (Tully et al. 2016) with units in deg
3)PGC                 Principal Galaxies Catalog ID (Makarovet al. 2014)
4)LEDA                
5)Dist                Luminosity distance measurement for individual galaxy. Weighted average of the distance moduli if more than one source. [Mpc]
6)r_Dist
7)DM
8)e_DM
9)RAJ2000             RA from Cosmicflow-3 (Tully et al. 2016) with units in ‘h:m:s’
10)DEJ2000            DEC from Cosmicflow-3 (Tully et al. 2016) with units in ‘d:m:s’
11)Ab                 Reddening at B band
12)Bmag               Total B magnitude from LEDA
13)Ksmag              2MASS Ks magnitude with corrections from Lavaux&Hudson
14)HV                 Heliocentric velocity from Cosmicflow-3
15)Vgsr               Velocity in Galactic standard of rest; circular velocity at Sun of 239 km/s; total velocity 251 km/s toward ℓ = 90, b = 0 (van der Marelet al. 2012).[km/s]
16)Vls                Velocity in Local Sheet standard of rest (Tully et al. 2008).[km/s]
17)Vcmb               Velocity in CMB standard of rest (Fixsenet al. 1996).[km/s]
18)Vcmba
19)Nest               2MASS “nest” group identification (Tully 2015b).
20)_Vcmba_
21)S14
22)_6dfgs
23)RC3
24)CF1                Luminosity selection function correction factor.
25)CF2
26)_2M
27)SimbadName
28)PGC1                Principal Galaxies Catalog ID of brightest groupmember.
29)_RAJ2000_kara       RA from Uperdated Nearby Galaxy Catalog in units deg
30)_DEJ2000_kara       DEC from Uperdated Nearby Galaxy Catalog in units deg
31)HRV_kara            Heliocentric velocity from Uperdated Nearby Galaxy Catalog
32)Dist_kara           Distance from Uperdated Nearby Galaxy Catalog
33)MHI_kara            Logarithm of hydrogen mass from Uperdated Nearby Galaxy Catalog
34)l_MHI_kara          Mark whether the hydrogen mass is accurate value or upper limit
35)_RAJ2000_leda       RA from Hyperleda_HI in units deg
36)_DEJ2000_leda       DEC from Hyperleda_HI in units deg
37)VHI_leda            Mean homogenized HI heliocentric radial velocity from Hyperleda_HI
38)m21_leda            Mean homogenized 21-cm magnitude from Hyperleda_HI
39)lgMHI_kara_2        Logarithm of hydrogen mass from Uperdated Nearby Galaxy Catalog recalibrated using the distance from cosmicflow-3
40)lgMHI_leda_2        Logarithm of hydrogen mass from Hyperleda_HI recalibrated using the distance from cosmicflow-3
41)F3.6_LVL            3.6-μm flux from LVL_Spitzer (Cook, David O. et al. 2014)
42)F4.5_LVL            4.5-μm flux from LVL_Spitzer (Cook, David O. et al. 2014)
43)F24_LVL             24-μm flux from LVL_Spitzer (Cook, David O. et al. 2014)
44)Est_stellarmass     The extimated logarithm of stellar mass using single band magnitude
45)lgMHI               Logarithm of hydrogen mass combining the result from Uperdated Nearby Galaxy Catalog and Hyperleda_HI
46)ra_phot_rband       The RA of the rband photometry center [deg]
47)dec_phot_rband      The DEC of the rband photometry center [deg]
48)r_final_flux        The rband final flux [nanomaggie]
49)r_final_radius      The rband final radius [pixel]
50)r_final_error       The rband final error [nanomaggie]
51)r_model_flux_add    The flux need to be added after the model fitting [nanomaggie]
52)r_8*scale_length    8 times of scale length [pixel]
53)r_total_flux        Total flux of rband (combining the 48 & 51) [nanomaggie]
54)flag                Label of the galaxy image (0: no data; 1: normal; 2: too big; 3: overexplored star on the galaxy surface; 4: multiple galaxies exists in one image)
55)ra_phot_gband       The RA of the gband photometry center [deg]
56)dec_phot_gband      The DEC of the gband photometry center [deg]
57)g_fianl_flux        The gband final flux [nanomaggie]
58)g_final_radius      The gband final radius [pixel]
59)g_final_error       The gband final error [nanomaggie]
60)g_model_flux_add    The flux need to be added after the model fitting [nanomaggie]
61)g_8*scale_length    8 times of scale length [pixel]
62)g_total_flux        Total flux of gband (combining the 48 & 51) [nanomaggie]
63)r_mag_final         Rband final magnitude [mag]
64)r_mag_total         Rband total magnitude [mag]
65)r_mag_error         Rband magnitude error[mag]
66)g_mag_final         Gband final magnitude [mag]
67)g_mag_total         Gband total magnitude [mag]
68)g_mag_error         Gband magnitude error[mag]
69)r_ext_SandF         Rband extinction from Schlafly, Edward F. et al. 2011 [mag]
70)g_ext_SandF         Gband extinction from Schlafly, Edward F. et al. 2011 [mag]
71)r_mag_extfinal      Rband final magnitude after extinction correction [mag]
72)r_mag_exttotal      Rband total magnitude after extinction correction [mag]
73)g_mag_extfinal      Gband final magnitude after extinction correction [mag]
74)g_mag_exttotal      Gband total magnitude after extinction correction [mag]
75)r_Abmag_extfinal    Rband final absolute magnitude after extinction correction [mag]
76)r_Abmag_exttotal    Rband total absolute magnitude after extinction correction [mag]
77)g_Abmag_extfinal    Gband final absolute magnitude after extinction correction [mag]
78)g_Abmag_exttotal    Gband total absolute magnitude after extinction correction [mag]
79)log_M_star_final    The logarithm of stellar mass calculated using 75&77
80)log_M_star_total    The logarithm of stellar mass calculated using 76&78





