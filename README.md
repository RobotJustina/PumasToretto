# PumasToretto
Repo for autonmous car software

##model_car
Contains catkin workspace and some scripts to copy to the model car

##scripts
Some codes written to simplify connection and configuration of the car in different situations

##Docker
Car runs on Indigo. To be able to cross compile we need to emulate ubnuntu Trusty and indigo using Docker
Copy  sdk and compiler from https://github.com/AutoModelCar/AutoModelCarWiki/wiki and rename to compilerOdroid.tar.bz2
and sdkOdroid.tar.bz2  then you can build the container.

##Todo
Write tutorial on cross compilation with docker.
