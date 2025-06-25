## TODO

1) Make sure this builds as-is from git pull and runs on pytorch nightly
2) Set up ci/cd to push it to pypi
3) See if we can prebuild wheels

## MAYBE
1) See if we can add a backward pass, although it's not clear that we want to do this in cuda as opposed to pytorch
2) See if we can have it self-pad to powers of two, although same concern
3) Figure out what's going on with dtypes in here
