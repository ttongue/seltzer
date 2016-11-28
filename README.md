# Seltzer CRM customized for TVCOG and Tonic

This distribution of Seltzer CRM is a fork of the original Seltzer CRM by Edwin Platt hosted at 

	https://github.com/elplatt/seltzer

This version has been lightly customized to match the TVCOG business model, and provides the core management tools to maintain the membership database. This version compatible with the Tonic extensions (separate project written in Python).

INSTALLATION
------------
The original instructions from Seltzer CRM will still work to install this package, but it won't 
be the complete solution for Seltzer &amp; Tonic development. Instead, follow the instructions at

	https://github.com/ttongue/seltzer-tonic-vagrant

to set up a complete  environment for development. The vagrant-based installation will load tonic and seltzer as submodules and will insure that all of the peices will stay in sync during the development process.