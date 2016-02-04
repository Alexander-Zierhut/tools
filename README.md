# Docker-MySQLTuner

## Description

Provides a docker container for the MySQLtuner script. The container is based
on alpine, so it should be obnoxiously small.

## Usage

Treat this image as if it were the mysqltuner binary. So

    docker pull thekevjames/mysqltuner
    docker run --rm thekevjames/mysqltuner --buffers --cvefile /vulnerabilities.csv

For full usage information, see the [http://mysqltuner.com/](MySQLTuner homepage).