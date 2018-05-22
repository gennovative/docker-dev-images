# Docker images for developers
Docker images pre-installed with some debug tools.

## Base Images

### Alpine
- Version: 3.7
- Pre-installed: 
  * `vim`: Turned on syntax highlight and line numbering.
  * `curl`
  * `wget`


### NodeJS
- Node version: 8.11.2
- Yarn version: 1.6.0
- Pre-installed: 
    * `nodemon`

## How To Build Docker Image
- `cd` to a folder that contains two files `build.sh` and `Dockerfile`.
- Execute file `build.sh`:
    * `./build.sh`, or
    * `sudo sh ./build.sh`