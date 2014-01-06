simple-website
==============

This is a simple example cloudlet that demonstrates using vagrant or AWS to deploy the same (very simple) website. It uses the minimal needed configuration required to execute the same BASH script -- which sets up a single page website -- on an instance started in either vagrant, or Amazon Web Service (AWS).

It's primarily intended to be illustrative of the bootstrap process (via vagrant provisioning and Amazon's cloud-init and CloudFormation), of how a configuration "payload" could be deployed and run in different cloud environments, and of how one might generalize this. It's not meant to be used in "real" work.

This cloudlet is for the [nepho](http://github.com/huit/nepho) deployment tool.
