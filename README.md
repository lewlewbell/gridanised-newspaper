# gridanised-newspaper
Using CSS grids to re-create a web unfriendly. retro newspaper, loosely based on an old Dominion Post paper.

The project is not based on any particular framework -- it is a project I have created myself from scratch. 

This project uses Node and some basic Gulp scripts to watch changes, and generate SASS and assets.

## 

## Gulp scripts

gulp sass

This script will manually generate the component SASS, clean, and export into production ready CSS.

gulp

This script will both watch for changes and automatically run 'gulp sass' if changes are detected.

## BEM

The HTML/CSS in this project is based on BEM methodology, see http://getbem.com/introduction/ if you are unfamiliar with BEM.

## Grid system

I have built a grid utility system that I am continuing to expand as the need arises (see grid-utilities.scss). The grid items use a "grid item" function to generate a SASS grid, this function accepts parameters for number of rows and columns, e.g grid__item--6x1.

You will find this grid utility system used used throughout this project.

The grid containers are still static utilities, but I am looking to do something smarter with this (see commented out lines 1 - 18 in grid-utilities.)
