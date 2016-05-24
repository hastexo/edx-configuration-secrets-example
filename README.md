edx-configuration-secrets
=========================

This repository contains sensitive variables and files specific to an edx
deployment.

The configuration in the master branch is just an example, and should not be
used.  When a new deployment is made, a branch should be created for that
purpose, and the playbook should be run with appropriate environment or
group vars pointing it to the location of this repository on the filesystem of
the deployment node.
