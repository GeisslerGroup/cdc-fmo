#  cdc-fmo
Implements the cdc method for the FMO pigment protein complex.

## AUTHOR

2015-11-05
John Haberstroh
Geissler Group, UC Berkeley
jhaberstroh@berkeley.edu

## INSTRUCTIONS

No need to install! Just execute the code from this folder. If you want to
install, you should make sure that all sources are in the same folder;
cdctraj.sh will assume all other source shares its own directory.

## SIMPLE USAGE

Execute the following

```bash
TOP=/path/to/fmo_gromacs_top_preprocessed.top    \
ATOMS=(number of atoms per frame)                \
TRJLEN=(number of frames to use from trajectory) \
./cdctraj.sh /path/to/trajectory.gro             \
    > /path/to/output.txt
```

## MORE INFORMATION

Browse the headers and help files of the executables for more information 
about usage. Good luck and happy hacking!
