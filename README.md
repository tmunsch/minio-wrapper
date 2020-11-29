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
`wget https://github.com/tmunsch/minio-wrapper/raw/main/mwrap && chmod +x mwrap && bash mwrap normal 9000`

## Normal Usage

./mwrap {normal/rotate} {port}

## Normal Usage Example
./mwrap normal 9000

## Rotation of Keys

./mwrap rotate 9000



