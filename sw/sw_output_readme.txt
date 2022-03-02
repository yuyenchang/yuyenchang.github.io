Title: Stellar Masses and Star Formation Rates for 1M Galaxies from SDSS+WISE  
Authors: Chang Y.-Y., van der Wel A., da Cunha E., Rix H.-W. 
Table: Output Catalog
================================================================================
Byte-by-byte Description of file: datafile2.txt
--------------------------------------------------------------------------------
   Bytes Format Units        Label      Explanations
--------------------------------------------------------------------------------
   1-  7 I7     ---          ID         NYU-VAGC catalog index (1)
   9- 14 F6.2   [solMass]    lmass2.5   log stellar mass; 2.5th percentile
  16- 21 F6.2   [solMass]    lmass16    log stellar mass; 16th percentile
  23- 28 F6.2   [solMass]    lmass50    log stellar mass; 50th percentile
  30- 35 F6.2   [solMass]    lmass84    log stellar mass; 84th percentile
  37- 42 F6.2   [solMass]    lmass97.5  log stellar mass; 97.5th percentile
  44- 50 F7.3   [solMass/yr] lsfr2.5    log SFR; 2.5th percentile
  52- 58 F7.3   [solMass/yr] lsfr16     log SFR; 16th percentile
  60- 66 F7.3   [solMass/yr] lsfr50     log SFR; 50th percentile
  68- 74 F7.3   [solMass/yr] lsfr84     log SFR; 84th percentile
  76- 82 F7.3   [solMass/yr] lsfr97.5   log SFR; 97.5th percentile
  84- 89 F6.2   [1/yr]       lssfr2.5   log specific SFR; 2.5th percentile
  91- 96 F6.2   [1/yr]       lssfr16    log specific SFR; 16th percentile
  98-103 F6.2   [1/yr]       lssfr50    log specific SFR; 50th percentile
 105-110 F6.2   [1/yr]       lssfr84    log specific SFR; 84th percentile
 112-117 F6.2   [1/yr]       lssfr97.5  log specific SFR; 97.5th percentile
 119-125 F7.3   [solLum]     lDust2.5   log Dust luminosity; 2.5th percentile
 127-133 F7.3   [solLum]     lDust16    log Dust luminosity; 16th percentile
 135-141 F7.3   [solLum]     lDust50    log Dust luminosity; 50th percentile
 143-149 F7.3   [solLum]     lDust84    log Dust luminosity; 84th percentile
 151-157 F7.3   [solLum]     lDust97.5  log Dust luminosity; 97.5th percentile
 159-165 F7.3   ---          mu2.5      Dust attenuation parameter; 2.5th
                                         percentile (2)
 167-173 F7.3   ---          mu16       Dust attenuation parameter; 16th
                                         percentile (2)
 175-181 F7.3   ---          mu50       Dust attenuation parameter; 50th
                                         percentile (2)
 183-189 F7.3   ---          mu84       Dust attenuation parameter; 84th
                                         percentile (2)
 191-197 F7.3   ---          mu97.5     Dust attenuation parameter; 97.5th
                                         percentile (2)
 199-205 F7.3   ---          tauv2.5    Dust attenuation parameter; 2.5th
                                         percentile (2)
 207-213 F7.3   ---          tauv16     Dust attenuation parameter; 16th
                                         percentile (2)
 215-221 F7.3   ---          tauv50     Dust attenuation parameter; 50th
                                         percentile (2)
 223-229 F7.3   ---          tauv84     Dust attenuation parameter; 84th
                                         percentile (2)
 231-237 F7.3   ---          tauv97.5   Dust attenuation parameter; 97.5th
                                         percentile (2)
 239-249 A11    Mpc+3        vmax       Maximum volume for LMASS_50
 251-264 F14.10 [solLum]     lrest-u    Rest-frame u-band Luminosity
 266-279 F14.10 [solLum]     lrest-g    Rest-frame g-band Luminosity
 281-294 F14.10 [solLum]     lrest-r    Rest-frame r-band Luminosity
 296-309 F14.10 [solLum]     lrest-i    Rest-frame i-band Luminosity
 311-324 F14.10 [solLum]     lrest-z    Rest-frame z-band Luminosity
 326-339 F14.10 [solLum]     lrest-w1   Rest-frame W1-band Luminosity
 341-354 F14.10 [solLum]     lrest-w2   Rest-frame W2-band Luminosity
 356-369 F14.10 [solLum]     lrest-w3   Rest-frame W3-band Luminosity
 371-384 F14.10 [solLum]     lrest-w4   Rest-frame W4-band Luminosity
     386 I1     ---          flag-r     Radius flag (3)
     388 I1     ---          flag-w     WISE flag (4)
     390 I1     ---          flag-w1    WISE W1 filter detection flag (5)
     392 I1     ---          flag-w2    WISE W2 filter detection flag (5)
     394 I1     ---          flag-w3    WISE W3 filter detection flag (5)
     396 I1     ---          flag-w4    WISE W4 filter detection flag (5)
     398 I1     ---          flag-chi2  Best-fit model flag (6)
     400 I1     ---          flag       Flag (7)
--------------------------------------------------------------------------------
Note (1): There are all 858,365 galaxies from the SDSS spectroscopic galaxy 
          sample with good redshift measurements (NYU-VAGC catalog: 
          OBJTYPE=GALAXY, Zwarning=0). A -99.99 in any column indicates a Null
          value.
Note (2): In da Cunha et al. (2008) [2008MNRAS.388.1595D].
Note (3): 
    1 = Simard radius; 
    2 = deVaucouleurs radius; 
    3 = exponential radius; 
    0 = no radius
Note (4):
    1 = single optical matched in WISE; 
    2 = > 1 counterparts within 6"; 
    0 = not matched.
Note (5):
    1 = detected (SNR>2); 
    2 = upper limit on filter detection; 
    0 = no data in this filter.
Note (6):
    1 = chi^2^ < 3 for best-fit model; 
    0 = chi^2^ > 3 for best-fit model.
Note (7): We recommend to use the MAGPHYS modeling results for objects with 
          flag=1 (633,205 out of 858,365). These are all z < 0.2 galaxies with 
          reliable aperture corrections based on size measurements from 
          Simard et al. (2011) [2011ApJS..196...11S], good WISE photometry
          (FLAG_W?=1 or 2), and good-quality SED fits (FLAG_CHI2=1).
    1 = good fit (flag-r=1; flag-w?=1 or 2; flag-chi2=1; z < 0:2); 
    0 = others.
--------------------------------------------------------------------------------
