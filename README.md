# minio-wrapper


### Bash wrapper for minio functions in linux


# Requirements
wget


## Ubuntu/Debian
apt-get install wget -y


## Centos/RHEL
yum -y install wget

# Usage

## One liner
`wget https://github.com/tmunsch/minio-wrapper/raw/main/mwrapper.sh && chmod +x mwrap && bash mwrap normal 9000`

## Normal Usage

mwrapper.sh {normal/rotate} {port}

## Example
mwrapper.sh normal 9000

