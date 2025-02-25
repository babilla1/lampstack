# this repo contains
main.tf which contains th provider bog, ec2 instance, vpc, subnets
install.sh which contains lamp stack installation files for appache, msql, php
output.tf containin the list of outputs to be declare after terraform apply
keypair.tf to generate the keypair and download automatically to the directory where we are
var.tf to declare all the variables in the other terraform files(anything subjected to change or that varies)
