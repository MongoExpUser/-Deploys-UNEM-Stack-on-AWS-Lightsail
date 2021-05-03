# Deploys-UNEM-Stack-on-AWS-Lightsail

Deploys Ubuntu, NodeJS, Express and MySQL (UNEM) Stack on AWS Lightsail with Python Terraform CDK.


This repo can be used to create the following resources with Terrform Python CDK:


1) AWS Lightsail ssh key pair, assigned to instance(s) in Item 2 below.
                                                                                                                                                 
2) AWS Lightsail instance(s) with Ubuntu 20.04 LTS OS
                                                                                                                                                 
3) AWS Lightsail static ip(s) for the instance(s).
                                                                                                                                               
4) AWS Lightsail static ip attachhment(s) to the instance(s).

5) Bash launch or start-up script (user data) for the installation of software, on the instance(s), including:

  a) Additional Ubuntu OS Packages.
  b) NodeJS
  c) ExpressJS Web Server Framework
  d) Other Node.js Packages and
  d) MySQL
