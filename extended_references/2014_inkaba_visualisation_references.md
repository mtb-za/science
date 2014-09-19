# Extended references for visualisation poster presented at Matjiesfontein, September 2014.

## General information on colour in visualisations
There is a huge amount of work that has been done on colour in visualisations, and even this extended list is barely scratching the surface.

An excellent starting point are the two blog series by Matteo Niccoli and Rob Simmon:

Niccoli, M., 2012. The rainbow is dead...long live the rainbow! [WWW Document]. MyCarta. URL http://mycarta.wordpress.com/2012/05/29/the-rainbow-is-dead-long-live-the-rainbow-series-outline/ (accessed 9.15.14).

Simmon, R., 2014a. Subtleties of Color 1/6 [WWW Document]. URL http://earthobservatory.nasa.gov/blogs/elegantfigures/2013/08/05/subtleties-of-color-part-1-of-6/ (accessed 8.4.14).

Simmon, R., 2014b. Subtleties of Color 2/6 [WWW Document]. URL http://earthobservatory.nasa.gov/blogs/elegantfigures/2013/08/06/subtleties-of-color-part-2-of-6/ (accessed 8.4.14).

Simmon, R., 2014c. Subtleties of Color 3/6 [WWW Document]. URL http://earthobservatory.nasa.gov/blogs/elegantfigures/2013/08/12/subtleties-of-color-part-3-of-6/ (accessed 8.4.14).

Simmon, R., 2014d. Subtleties of Color 4/6 [WWW Document]. URL http://earthobservatory.nasa.gov/blogs/elegantfigures/2013/08/19/subtleties-of-color-connecting-color-to-meaning/ (accessed 8.4.14).

Simmon, R., 2014e. Subtleties of Color 5/6 [WWW Document]. URL http://earthobservatory.nasa.gov/blogs/elegantfigures/2013/08/28/subtleties-of-color-part-5-of-6/ (accessed 8.4.14).

In addition, the discussion about matplotlib colour maps ( http://matplotlib.org/users/colormaps.html ) covers some of the same ground along with some good additional resources about different types of colour maps.

Once this has whetted your appetite, there are a few classic papers and books that are worth a look:
Borland, D., Taylor II, R.M., 2007. Rainbow color map (still) considered harmful. IEEE Computer Graphics and Applications 27, 14–17.

Rogowitz, B.E., Treinish, L.A., 1996a. How Not to Lie with Visualization. Computers in Physics 10, 268. doi:10.1063/1.4822401

Rogowitz, B.E., Treinish, L.A., 1996b. Why Should Engineers and Scientists Be Worried About Color? [WWW Document]. URL http://www.research.ibm.com/people/l/lloydt/color/color.HTM (accessed 9.18.14).

Tufte, E.R., 1983. The Visual Display of Quantitative Information. Graphics Press, Cheshire, Conneticut.

Ware, C., 2000. Information Visualization: Perception for Design, Interactive Technologies. Morgan Kaufmann, San Francisco, USA.

Two presentations from SciPy2014 were also extremely helpful:

McDougall, D., 2014. How to choose a good colour map. Presented at the SciPy 2014, Austin, Texas. http://pyvideo.org/video/2768/how-to-choose-a-good-colour-map

Thyng, K.M., 2014. Perceptions of Matplotlib Colormaps. Presented at the SciPy 2014, Austin, Texas. http://pyvideo.org/video/2769/perceptions-of-matplotlib-colormaps

## General Comments
Research in the field is ongoing, but there seems to be general consensus about many things. Essentially, for smoothly varying data, use a colour map that increases or decreases monotonically in lightness. For diverging data from a midpoint, choose a colour map that smoothly varies from a neutral centre. For nominal data, smooth lightness variation is less important, but care must be paid to choosing colours that will be distinguished by people with colour-blindness.

## Colourblindness
Some good general references on colourblindness can be found with a quick search of your favourite internet search engine. I found the following to be quite helpful:

http://www.iamcal.com/toys/colors/

http://safecolours.rigdenage.com/palettefiles.html

http://colororacle.org/design.html

## Conclusion and some useful tools
The use of colour can make or break a visualisations, so it pays to spend some time on deciding what colours you will use.

In order to get a feel for what good colour maps can look like, I strongly recommend looking at the ColorBrewer tool. The references above (in particular Simmons' blog series) mention a number of other ones that can be used as well.

Brewer, Cynthia A., Geoffrey W. Hatchard and Mark A. Harrower, 2003, ColorBrewer in Print: A Catalog of Color Schemes for Maps, Cartography and Geographic Information Science 30(1): 5-32. http://colorbrewer2.org/

This is also worth a look: http://geog.uoregon.edu/datagraphics/color_scales.htm but might need to be tweaked somewhat to get smooth gradients rather than discrete steps.

A useful tool for testing colourblindness safety is http://colororacle.org/