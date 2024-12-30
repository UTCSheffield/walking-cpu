# walking-cpu

Turn your building into indiviual CPU's for your students to explore and discover "Fetch Decode Execute".

This software takes the room list for your school and produces easily printable html files for a 20 minute exercise where the students walk around being a CPU, executing individual differentiated programs.

This Glitch site is used for our version of the exrcise but feel free to fork it or go to git to get it to use yourself

![UTC Sheffield Olympic Legacy Park Horizontal](https://www.utcsheffield.org.uk/olp/assets/sites/3/2021/07/UTC-Sheffield-Olympic-Legacy-Park-Horizontal.svg)

## Main Project

[https://github.com/UTCSheffield/walking-cpu](https://github.com/UTCSheffield/walking-cpu)

Running ```node schoolcpu.js``` will create an output folder with the html files in. --help will tell you how to change things.


## Glitch Version

The *package.json* file build line allows you to change the numbers of each of the 4 levels of the worksheets using the -n parameter

When you change any of the configs or the settings in package,json the project will rebuild

Our version is available to veiw [here](https://utc-olp-walking-cpu.glitch.me/) or [remix it](https://glitch.com/edit/#!/remix/utc-olp-walking-cpu)


## Both 

The room config list allows you to change the names to fit your school. You can edit the default or copy it to another file 
and change the -r parameter from "default" (which points at default.json )

The same can be done for the level config, this is set to what I think in appriate for the OCR Level 1-9 GCSE in Computer Science. But it could be changed to reflect you local courses.


## Doing the activity

- Decide on how many students you want doing each level and the names of rooms you are going to use for your physical RAM locations.
Adust the parameters and config files for this.
- Print out the 3 resulting HTML files 
  - The worksheets are 2 pages per student and can be printed double sided
  - The Posters must be printed single sided
  - The teachers sheets have the answers on, so print how you think best.
- All students will need a clipboard and pen / pencil
- On the day stick up the posters around school in the places indicated on the posters
- The different level worksheets have different things to do for the Fetch Decode and Execute stages so go through them with the students as much as you think needed.



