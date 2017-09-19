# Dispersal
Simulation code for Eurasian Collared Dove dispersal

##Author: Chris Hensz##
##Date: Sept 19, 2017##

##Description##
#This function generates a matrix of coordinates of random dispersal events from a point source (start)

##Arguments##
#type: a character string indicating whether the simulation will be performed on a flat surface or a curved earth surface
#start: a numeric vector of length 2 containing x and y coordinates (for type = 'flat') or longitude and latitude (for type = 'curved')
#npoints: number of simulated points
#angle: the name of a function to be used to generate angles from source
#angleargs: a list of additional arguments to be passed to angle function
#kernel: the name of a function to be used to generate distances from source
#kernelargs: a list of additional arguments to be passed to kernel function

#NOTE: angles are asumed to be in radians (for type = 'flat') or alternatively in bearing degrees (for type = 'curved')
#NOTE: distances (for type = 'curved') are assumed to be in meters
