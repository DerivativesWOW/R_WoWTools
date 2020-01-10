# R_WowTools

These are just some derpy utility scripts written in R to...
+ Draw cute plots about WOW classic statistics
+ Create information diagrams

**Dependencies**
+ [R](https://www.r-project.org/)
+ [ggplot](https://ggplot2.tidyverse.org/index.html)

## raid_png.R
The idea here is to cocerce an 8 panel plot to actually function as a raid roster, 
displaying character names and classes via color, thus displaying what positions 
are currently filled/scheduled, and what spots are available. By taking a simple 
text <.csv>, the script generates a png as out. Check the sample data folder for 
roster.csv for an example of the in-data; just four columns of character name, class,
group, position. It can only handle at present the 8 horde classes in basic classic wow.

**Usage**
```
Rscript raid_png.R roster.csv out.png
```

**Output**
<img src='sample_data/out.png' align='center' width='600px'/>