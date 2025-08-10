# ttem_in_p223

A tTEM configuration for P223

Notes:
- Beowulf and Leroi are interchangeable for the layered earth part and given beowulf has no forward only mode it is easier to use leroi
- The P223F software suite (Raiche et al.2007) is an extensive collection of tools for EM forward modelling and inversion, that in the past has been made available on a website maintained by AMIRA. While the original site no longer exists, it and the related files have been captured by the wayback machine and are available [here](https://web.archive.org/web/20160313045828/http://amirainternational.com/web/site.asp?page=projectpages/p223f_software&section=news)
- Leroi can be be built by running buid.sh in leroi
- The sirotem example can be run by running run.sh in test_01
- A sirotem setup as used by wiglaf and leroi is in background/sirotem_in_wiglaf
- A tTEM specification is in backgorund/tTEM_Details.txt
  - tTEM as per specs file appears to be mdoelle with transmitter loop and a dipole receiver

Next steps:
- Migrate the current setup in test_01 from one for a Sirotem system to a tTEM system
