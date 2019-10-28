# Development Workflow

This document is a high-level description of the Ronoth development flow for this project.  It is not meant to provide a detailed explanation of the git commands or exact steps required.

## Basic development process

1. Checkout master branch from Github.  For community members it is recommended that you first create a project fork.
1. Create a feature branch off of Master.
    * Give your branch a concice name related to the task you are working on.
1. Make focused, digestable changes
    * Ideally changes be reviewed by peers in 
under an hour.  If your changes are larger than that consider breaking
them down into several smaller branches.
1. Create a pull request
1. Wait for peer review
    * Review for schematic and board design elements will use
    https://cadlab.io
    * Once someone from the team has reviewed your work it's ready for merge.
1. Merge your branch
1. Delete old branch


## Release Folder Structure

Offical version releases are captured as subfolders instead of branches or release tags in order to aid users in finding documentation / schematics for their specific hardware.

* hardware/
  * hubbard_r0_alpha
  * hubbard_r1_RC0
  * hubbard_rN_\<description\>
  * ...
