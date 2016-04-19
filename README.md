# aws-cloud-examples
collection of files for testing and developing on Amazon Web Services

# Opsworks Templates

## opsworks-minimal

## opswork-cookbook

This template will start a minimal OpsWorks stack. The instance will be configured by the recipe that you select. An example of such a Chef cookbook is https://github.com/arjenderijke/jenkins_dev This repository contains a cookbook with recipies to setup Jenkins on the OpsWorks stack. Different recipies perform different features of setting up jenkins. In the template, replace "default" with your required feature.

* default.rb: Get a default Jenkins setup
* enable_auth.rb: Enable user authentification

## opsworks-jenkins-stack
