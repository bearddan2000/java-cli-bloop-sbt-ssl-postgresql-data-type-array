# java-cli-bloop-sbt-ssl-postgresql-data-type-array

## Description
Creates a small table `dog` that uses
a text array data type. Arrays can also be
numeric.

A java bloop-sbt build, that connects to postgresql database.

Uses self-sign ssl.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- java
- bloop-sbt
  - log4j
  - postgresql drivers

## Docker stack
- alpine:edge
- postgresql:alpine
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
