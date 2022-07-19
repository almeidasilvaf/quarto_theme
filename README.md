
## Using this theme

To use this theme, you must simply clone this repo and add a new presentation
(.qmd file) in the top-level directory.


## Inserting figures from your local machine

If you want to include figures in your presentation that are not online,
you must store them in the `figs/` subdirectory. 

It is **highly recommended**
that you create a different folder for each slide presentation inside the 
`figs/` subdirectory. 

For example, if your presentation is named
**2022_software_demo.qmd**, you should create a folder named 
`2022_software_demo/` inside `figs/` where you would store all figures used in
this presentation.

## FAQ

> How do I change the font color of the presentation's title? 

Go to `styles.scss` and change the color in *.reveal h1*.
