# Conda deployment on Cheyenne
Documented script example of Miniconda deployment on [Cheyenne Supercomputer](https://www2.cisl.ucar.edu/resources/computational-systems/cheyenne)


# Installing using [HPCinstall](https://github.com/andersy005/HPCinstall)

- Get source code
```bash
$ git clone git@github.com:andersy005/conda-deploy-cheyenne.git
$ cd conda-deploy-cheyenne
```

- Load HPCinstall module
```bash
$ module use $MODULEPATH_ROOT/system
$ module load hpcinstall
```

- Install using HPCinstall
```bash
$ hpcinstall build_conda
```

# Use

To load this module:

```bash
$ ml use /glade/scratch/abanihi/ch/test_installs/modulefiles/idep/
$ ml conda
```