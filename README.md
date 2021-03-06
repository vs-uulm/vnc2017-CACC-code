
The code for our VNC 2017 paper is split over two repositories, just like the original Plexe distribution. It is published as a fork.
[plexe-sumo](https://github.com/vs-uulm/plexe-sumo/tree/vnc2017-cacc-attack-analysis) has minimal changes; there is only a configuration option for the CACC constant spacing that can be set in VEINS (i.e., in the omnet configuration file) -- most significant changes were made to [plexe-veins](https://github.com/vs-uulm/plexe-veins/tree/vnc2017-cacc-attack-analysis), where we implemented our attacks and document the omnetpp.ini files.

To save some time, we've also published the data set generated by this code in a separate (very large!) repository, which can be found [here](https://github.com/vs-uulm/vnc2017-CACC-data). 

The modifications to these repositories are part of a research agreement with the [BW-Stiftung](https://www.bwstiftung.de), as part of which the copyright is owned by them. In correspondence with the GPL license of the original work, the changes are available under the same license.
