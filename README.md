# 95_override_ISLE_Drupal_Build_Tools
This `isle-docker-compose` project is, at least temporarily, specific to Digital.Grinnell!
 overrides the standard `ISLE-Drupal-Build-Tools` with an alternate configuration.

## Overview
This project overrides ISLE's default/standard `ISLE-Drupal-Build-Tools` with an alternate configuration.

## Why Do I Need This?
You probably don't unless you are the sysadmin for https://Digital.Grinnell.edu.

## The isle-docker-compose Command
See https://github.com/DigitalGrinnell/ISLE_docker_compose for details.

## How Is This Used?
It's easy, assuming the `isle-docker-compose` command is already defined, just follow these steps...

  1) Open a terminal to your ISLE host, and in that terminal...  
  2) Navigate (`cd`) your working directory to ISLE, the directory that holds your `docker-compose.yml` file. Probably `cd /opt/ISLE`.
  3) Navigate (`cd`) into your `ISLE_docker_compose` directory with: `cd ISLE_docker_compose`.
  4) `git clone` this repository to your ISLE host using `git clone https://github.com/DigitalGrinnell/95_override_ISLE_Drupal_Build_Tools.git; cd ..`.  
  5) Spin up your ISLE instance using our special form of `docker-compose up`, like so: `./isle-docker-compose`.
  6) Your ISLE instance should spin up just as if you had issued `docker-compose up -d`, but with this feature engaged.
