# UtilityOld

## Description
General-purpose utility library.

## This Repository
https://github.com/mlbrock/UtilityOld

## Related Repositories
None.

## External Dependencies
### Git
* Any recent version of git.
### GNU C++ Compiler
* GNU g++ 4.1.2 through gcc 16.1.1 are supported.
### Boost
* Boost 1.32 through Boost 1.90 are supported.

## How-to Build
### Install external dependencies:
* Install git
* Install GNU g++
* Install Boost
### Get the current source distribution:
    git clone https://github.com/mlbrock/UtilityOld
### Change to the cloned top-level directory:
    cd UtilityOld
### Clean an existing build (if necessary):
    ./SimpleBuildDriver.sh clean
### Run the build script:
    ./SimpleBuildDriver.sh
### Check for build warnings or errors:
    grep -P '((warning)|(error)):' `ls -1 BuildResults.*|sort -r|head -n 1`

