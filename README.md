# LSDnD

*Text repo for tabletop rpg references*

***

#### Introduction

This system is built off of principles outlined in several existing Tabletop RPG systems, Such as Dungeons & Dragons 3.5e and 5e, Pathfinder, GURPS, Spelljammer, and draws heavy influence from the Steelshod system by MostlyWrites. 

It is designed as a rules-lite system, giving much more freedom to GMs to craft their world, however it is focused on a low magic environment, so GMs looking to include High Magic in their worlds will have to make major changes to the rules balance. 

Functionally LSDnD is designed around the use of as standard set of tabletop dice; d4, d6, d8, d10, d12, d20. there are also options for more esoteric die, such as backgammon doubleing dice and hi-lo split dice. 

***

#### About build.sh and toc.sh

in the root directory of this repo is a build.sh shell script. As you can see by browsing this guide is broken into many smaller text files and snippits of text detailing important features. As many smaller files are difficult to reference at the table this can cause a problem.

This is where build.sh comes into play. when executing the script with ./build.sh it will walk through the repo calling all of the toc.sh scripts to generate section based tables of contents, wich will then be comprised into a master document for ease of use and distrobution. this file, called *Guide.md* will be ready to print.