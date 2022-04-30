# scala-cli-mill-crypto-triple-des-encrypted-scrypt-encoded

## Description
Encrypt and decrypt password with 3DES
encoded scrypt.

When storing a password it is best practice
to use a one-way hash such as bcrypt, scrypt,
or argon2.

## Tech stack
- scala
- mill
  - 3DES
  - scrypt

## Docker stack
- nightscape/scala-mill

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
