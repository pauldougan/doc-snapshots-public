![NOTE] The material in this repository is made with **PUBLIC** sources and does not depend on any internal documention or source code. 

# Docs snapshots
Some snapshots of selected public websites for:
- printing
- reading
- large language models

# How it works
The `Makefile` runs a series of commands as follows:
1. generate a list web urls for the sites in question as a csv
1. process the csv to create pdf snapshots of the pages using shot-scraper
1. combine all the generated pdf files into a single file in the [pdf](pdf) directory using ghostscript
