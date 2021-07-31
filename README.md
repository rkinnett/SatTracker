# SatTracker
_**EXPERIMENTAL!**  USE AT YOUR OWN RISK!_  
  
Automatic orbit and video-based tracking of satellites with GOTO telescopes.
  
This project derives from the brilliant work of AstronomyLiveYt at [AstronomyLiveYt/SatTraker](https://github.com/AstronomyLiveYt/SatTraker).  Original concept and algorithm are his.  See [Astronomy Live](https://www.youtube.com/messierhunter) YouTube channel for details.
  
### Updates in this fork:
* Added TLE lookup (by sat ID) to streamline switching targets on-the-fly
  * hint: use Stellarium to find satellites in view and get sat IDs
* Changed camera interface to ASCOM
* Added camera controls (gain, exposure, binning)
* Rearranged GUI button layout
