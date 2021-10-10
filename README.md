# HansonHauntedTest2
Test of Visual Essay Format

<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Girl with a Pearl Earring"
       author="JSTOR Labs team"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

This is a story of an earring. 
            
An ugly earring.
           
Cheaply made and cheaply bought, it is meant to resemble a queenly diamond in glass and brass. A large, 3 lobed brown jewel sits beneath a crown of small, round, apricot-colored gems in a color palette that now seems a stereotype of the 1970s. These faux diamonds have been haphazardly set into a thin, metal clip that pinches and weighs the ear unpleasantly. It was presumably once part of a pair, but its twin has long ago been lost in the back of a drawer of a relative or the case of a second-hand shop or (most likely) underneath 200ft of West Seattle landfill. It is, without doubt, an object out of place. I keep it in my jewelry drawer, but I have no intention of wearing it. It has no functionalist, aesthetic, or rational role in my life and there is really no reason that I should keep it.
            
Yet, I cling to it: not for what it is, or what it was, or what it could be; not for its value, not for its beauty, not for the hope that I may someday wear it. I cling to it because it was hers: the property of a great aunt, Bea, now dead. I keep it because it is full of memories: the memory of childhood visits and the smell of old perfume and hospital disinfectant. The memory of a sombre distribution that I did not understand, and a jewellery box that I was too small to carry. The memory of a quiet presence, felt on the back of the neck in the superstitious hours. The memory of death and life and loss and obligation and the first thing I ever owned that glittered. 
            
In my archaeological education, I have spent a great deal of time exploring the properties of materials. I have tried to make sense of object materiality through measurement, weight, form, wear, illustration, reconstruction, sound, smell, heft, and feel. Yet in this lump of ugly brown glass, none of these really matter. Instead, I cannot relinquish it (though I might wish to) because it is imbued with a secret materiality that exists in my mind alone. I understand and interact with this object because it is haunted: by memory, by superstition, and by a link that still connects me to a woman decades dead. 
            
Bea, somehow, has made this object different. 

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Girl with a Pearl Earring_ (Dutch: Meisje met de parel) is an oil painting by Dutch Golden Age painter Johannes Vermeer, 
dated c. 1665. Going by various names over the centuries, it became known by its present title towards the end of the 
20th century after the earring worn by the girl portrayed there.[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
