# nodejs-web-api-expressjs-sqlserver-ssl

## Description
A POC project for an express api using sql server.

Sql server uses self-signed ssl.

## Tech stack
- expressjs
- mssql

## Docker stack
- alpine:edge
- node:latest
- mcr.microsoft.com/mssql/server:2017-CU17-ubuntu

## To run
`sudo ./install.sh -u`
http://localhost/dogs

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
