# Test2::FHEM
Repository for [Test2](https://metacpan.org/pod/Test2) Helper Modules used in FHEM environment


# Files included in this repository:


## Files and folders

### lib/Test2/FHEM/SIGNALduino/RDmsg.pm

Tool that helps testing dispatch (via dmsg messages), loaded from a json file which defines settings and expected tests


### lib/Test2/FHEM/Command.pm

Tool that helps testing Results of FHEM commands (set, get and attr), provided via a pure perl hash.


### .perlcritc

Settings for perlcritc commandline tool

### cpanfile

Cpan modules needed for running your module and your tests, they will be installed after perl is set up and running 


# Installation of tools

Update from this repository
`update force https://raw.githubusercontent.com/fhem/Test2-FHEM/main/controls_Test2-FHEM.txt`
