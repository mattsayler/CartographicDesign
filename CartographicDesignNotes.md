## Cartographic Design in GIS

Cartographic Design in GIS notes

### What is a Map?
* Argument
* Implied authority
    * i.e. people following GPS into a lake
* Communication goal

### Why cartography matters
* Maps primary role is visual communication
* Effective communication supports our work
    * Good design enhances communication
    * Poor design breaks down communication
* Cartography in GIS is about making effective maps, not pretty maps
* Quality of visuals often affects perception of work
* Missed opportunity to communicate with map effectively can nullify work you've done

### Warm up examples
* Minimize need for legend. Let map do as much of the work as possible
* Map should be able to stand on it's own
* Having a story element can be very beneficial
    * Makes more engaging.

### Questions
* What is maps purpose?
    * Purpose drives decisions
* Who is the map for?
    * Experts can handle more complex info
    * Non-experts may req simplified map
* How will the map be displayed?
    * Mediums have very different specifications
* Note: Our research maps often poor for display

### Visual Hierarchy
* Visual order
    * Somethings stand out, some fall back
* Design choices effect visual order
* Visual hierarchy follows the intellectual hierarchy
    * Must understand purpose and audience before you can build visual hierarchy
* VH derived from Figure-ground effect
    * Figures on maps are seen as separate from the rest of the map
    * Evolutionary, for picking out what's important (threats food, etc)
* Contrast emphasizes F-G relationship
    * Darker/brighter features stand out
    * Features w/less contrast appear to belong together
* Generally better to start neutral and push things back than to really pump things up in VH
* Detail: selectively remove data to emphasize other data

### Generalization and Simplification
* Fewer data are often better
* Reduce map clutter to emphasize the message
* Simplify representation

### Data Classification
* Grouping data reveals patterns

### Map Symbology
* Good symbology means small legends
* Symbolize by relationship
* Symbolize by resemblance
* Symbolize by convention
* Visual Variables
    * Shape
    * Size 
    * Color hue
    * Color value
    * Color intensity
    * Texture

### Type on maps
* Limit font-family to 1 or 2 per map
* Avoid decorative fonts
* Use styles changes to break fonts into multiple classes
    * letter spacing, size, color, bold, italics, & letter case
* 6pt - 12pt
* Geographic features: italics
* Water features: serifs
* ArcGIS: Use Maplex
* TypeBrewer website

### Colors
* single color gradient suggests changes in values
* Diverging scheme suggests diverging values or central value
* White suggests no data, avoid using as class (remember 0 is a measurement)
* [Color Brewer 2](http://colorbrewer2.org)

### Map Layout
* Descriptive title
* Distribute visual weight
* Balance does not always mean symmetry
* Align map elements to invisible grid

### ArcMap export to ai format for Illustrator
* set really high dpi to keep detail (vector, so won't blow up like a raster)
* anything below raster will be converted to raster
* Convert markers to fill
* Update labels to new ai format when opening in AI
* Arc makes a clipping mask, can't really work with map initially because of this.
    * Release all layers from clipping mask
    * Ungroup things
* Path/Symplify for smoothing blocky lines

### Resources
* Books
    * Making maps a Visual Guide... (Krygier)
    * Design Better Maps (Brewer)
* [MapBliss](http://mapbliss.com)
* davidmed@stanford.edu
