================================================================================
--------------------------------------------------------------------------------
Column Name Format Unit Column Description
--------------------------------------------------------------------------------
NUMBER LONG - COSMOS2015 index 
ALPHA_J2000 DOUBLE deg J2000 R.A. [deg] from COSMOS2015
DELTA_J2000 DOUBLE deg J2000 Dec. [deg] from COSMOS2015
PHOTO_Z DOUBLE - photometric redshift from COSMOS2015 
TEMPLATE INT - AGN template; 1: low lum type-2; 2:high lum type-2; 4: QSO type-1 5: Seyfert type-1
MSTAR_2_5_AGN FLOAT log Msun log stellar mass (2.5th percentile) [MAGPHYS+AGN]
MSTAR_16_AGN FLOAT log Msun log stellar mass (16th percentile) [MAGPHYS+AGN]
MSTAR_50_AGN FLOAT log Msun log stellar mass (50th percentile) [MAGPHYS+AGN]
MSTAR_84_AGN FLOAT log Msun log stellar mass (84th percentile) [MAGPHYS+AGN]
MSTAR_97_5_AGN FLOAT log Msun log stellar mass (97.5th percentile) [MAGPHYS+AGN]
SFR_2_5_AGN FLOAT log Msun/yr log SFR (2.5th percentile) [MAGPHYS+AGN]
SFR_16_AGN FLOAT log Msun/yr log SFR (16th percentile) [MAGPHYS+AGN]
SFR_50_AGN FLOAT log Msun/yr log SFR (50th percentile) [MAGPHYS+AGN]
SFR_84_AGN FLOAT log Msun/yr log SFR (84th percentile) [MAGPHYS+AGN]
SFR_97_5_AGN FLOAT log Msun/yr log SFR (97.5th percentile) [MAGPHYS+AGN]
AV_2_5_AGN FLOAT - dust attenuation parameter (2.5th percentile) [MAGPHYS+AGN]
AV_16_AGN FLOAT - dust attenuation parameter (16th percentile) [MAGPHYS+AGN]
AV_50_AGN FLOAT - dust attenuation parameter (50th percentile) [MAGPHYS+AGN]
AV_84_AGN FLOAT - dust attenuation parameter (84th percentile) [MAGPHYS+AGN]
AV_97_5_AGN FLOAT - dust attenuation parameter (97.5th percentile) [MAGPHYS+AGN]
AGNF_2_5_AGN FLOAT - AGN IR fraction (2.5th percentile) [MAGPHYS+AGN]
AGNF_16_AGN FLOAT - AGN IR fraction (16th percentile) [MAGPHYS+AGN]
AGNF_50_AGN FLOAT - AGN IR fraction (50th percentile) [MAGPHYS+AGN]
AGNF_84_AGN FLOAT - AGN IR fraction (84th percentile) [MAGPHYS+AGN]
AGNF_97_5_AGN FLOAT - AGN IR fraction (97.5th percentile) [MAGPHYS+AGN]
LDUST_2_5_AGN FLOAT log Lsun log dust luminosity (2.5th percentile) [MAGPHYS+AGN]
LDUST_16_AGN FLOAT log Lsun log dust luminosity (16th percentile) [MAGPHYS+AGN]
LDUST_50_AGN FLOAT log Lsun log dust luminosity (50th percentile) [MAGPHYS+AGN]
LDUST_84_AGN FLOAT log Lsun log dust luminosity (84th percentile) [MAGPHYS+AGN]
LDUST_97_5_AGN FLOAT log Lsun log dust luminosity (97.5th percentile [MAGPHYS+AGN]
LDUSTAGN_2_5_AGN FLOAT log Lsun log dust AGN luminosity (2.5th percentile) [MAGPHYS+AGN]
LDUSTAGN_16_AGN FLOAT log Lsun log dust AGN luminosity (16th percentile) [MAGPHYS+AGN]
LDUSTAGN_50_AGN FLOAT log Lsun log dust AGN luminosity (50th percentile) [MAGPHYS+AGN]
LDUSTAGN_84_AGN FLOAT log Lsun log dust AGN luminosity (84th percentile) [MAGPHYS+AGN]
LDUSTAGN_97_5_AGN FLOAT log Lsun log dust AGN luminosity (97.5th percentile) [MAGPHYS+AGN]
MSTAR_2_5_0 FLOAT log Msun log stellar mass (2.5th percentile) [MAGPHYS]
MSTAR_16_0 FLOAT log Msun log stellar mass (16th percentile) [MAGPHYS]
MSTAR_50_0 FLOAT log Msun log stellar mass (50th percentile) [MAGPHYS]
MSTAR_84_0 FLOAT log Msun log stellar mass (84th percentile) [MAGPHYS]
MSTAR_97_5_0 FLOAT log Msun log stellar mass (97.5th percentile) [MAGPHYS]
SFR_2_5_0 FLOAT log Msun/yr log SFR (2.5th percentile) [MAGPHYS]
SFR_16_0 FLOAT log Msun/yr log SFR (16th percentile) [MAGPHYS]
SFR_50_0 FLOAT log Msun/yr log SFR (50th percentile) [MAGPHYS]
SFR_84_0 FLOAT log Msun/yr log SFR (84th percentile) [MAGPHYS]
SFR_97_5_0 FLOAT log Msun/yr log SFR (97.5th percentile) [MAGPHYS]
AV_2_5_0 FLOAT - dust attenuation parameter (2.5th percentile) [MAGPHYS]
AV_16_0 FLOAT - dust attenuation parameter (16th percentile) [MAGPHYS]
AV_50_0 FLOAT - dust attenuation parameter (50th percentile) [MAGPHYS]
AV_84_0 FLOAT - dust attenuation parameter (84th percentile) [MAGPHYS]
AV_97_5_0 FLOAT - dust attenuation parameter (97.5th percentile) [MAGPHYS]
LDUST_2_5_0 FLOAT log Lsun log dust luminosity (2.5th percentile) [MAGPHYS]
LDUST_16_0 FLOAT log Lsun log dust luminosity (16th percentile) [MAGPHYS]
LDUST_50_0 FLOAT log Lsun log dust luminosity (50th percentile) [MAGPHYS]
LDUST_84_0 FLOAT log Lsun log dust luminosity (84th percentile) [MAGPHYS]
LDUST_97_5_0 FLOAT log Lsun log dust luminosity (97.5th percentile) [MAGPHYS]
FLAG INT - Flag (1=good fits; 0=others) (1)
--------------------------------------------------------------------------------
Note (1): We recommend to use the MAGPHYS modeling results for objects with 
          flag=1 (223,999 out of 1,182,108).  These are all 0 <= z <= 2.5 galaxies 
          with good-quality SED fits (0 <= chi^2(AGN) <= 3).
--------------------------------------------------------------------------------
