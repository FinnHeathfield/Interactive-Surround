# Interactive Surround
 Interactive Sound exibit Combining VCV rack, Max, and IRCAM's CoMote app to control audio in an 8-channel array.

Each phone connects on a private network via OSC and the comote app to the max patch wich handles spatialisation and OSC processing before scaled messages are sent on to VCV rack. The VCV rack patch required a number of specialist modules which can be found within. 

## Dependancies
The max patch requires the use of IRCAM's Spat.5 package for spatialisation which is avaliable from [IRCAM's Website](https://forum.ircam.fr/projects/detail/spat/)
