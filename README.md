# AsciiDoc custom template

This repository contains AsciiDoc custom template that I used to write report for Mini Project / Final Project at school.

# How to use

1. Install VSCode and AsciiDoc extension

2. Clone/Download this repo

3. Open a template from `template` folder (exclude the `setup.adoc` file). AsciiDoc extension provides you the Preview feature, use it to choose the ones you like and copy it to the `report` folder.

4. Now start filling some basic information and writing you report.

5. Press `Ctrl`+`Shift`+`P` and type some word to search for the command that will generate html file from asciidoc for you, ex. "asciidoc html", then press enter

# Structure

### These folders are all set, don't modifiy it

- `css` folder contains AsciiDoc css and also FontAwesome css

- `template` folder, I put all my custom template here

- `js` folder contains highlightjs javascript file

- `webfonts` folder contains FontAwesome font file

### The only two folders that you work with are

- `report` folder, put all your report file here

- `images` folder stores all the images to use in the report

There is a `setup.adoc` file in both `report` folder and `template` folder. I put all document attribute settings in it. Some attribute to setup those folders, some to turn on/off specific AsciiDoc feature that i believe will work well in most cases.

All attribute can be overwritten. So if you want to create your own template, this repo may still useful, just include `setup.adoc` and you will have a well setup structure.
