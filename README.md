# HabitatAnnotation
Habitat annotation of horizontally facing benthic imagery from baited and unbaited remote stereo-video deployments and diver swum stereo-video transects.

We have developed an simple approach to characterise the composition and complexity of habitats, using horizontally facing benthic imagery adapting existing standardised schema for benthic composition (CATAMI classification scheme<sup>1</sup>) and benthic complexity<sup>2</sup>, with the addition of a class to quantify the % of benthos within the horizontally facing imagery. The annotation approach is rapid and produces % composition and mean and standard deviation estimates of complexity which enable flexible modeling of habitat occurrence and habitat-fish relationships.

This annotation schema is described and included in a published paper<sup>3</sup>, please cite if you use it.
However, please refer to this GitHub repository for uptodate versions of the annotation schema.

Parts of this annotation scheme have also been trailed in two further published papers so far<sup>4,5</sup>.

<HR>
</HR>

To simplify the annotation process and give the charateristic changing depth of field of view of horizontaly facing imagery we have gridded the images in 5 x 4 cells.

Each of the cells should be annotated for dominant Benthic Composition, Field of View and Relief.

![alt text](tm.png "Application of annotation approach to characterise benthic composition and benthic complexity from horizontally facing remote video or from diver swum transects. Using TransectMeasure software")

<HR>
</HR>

Tht annotation schema is made up of nested Benthic Composition classes taken direclty from the CATAMI schema and a Field of View and Relief class that are useful for characterising horizonatlly facing imagery.
BROAD>MORPHOLOGY>TYPE/FieldOfView/Relief

To the BROAD class we have added additional levels of "Open Water", to calculate the % of benthos within each image, and "Unknown", to account for the frequent issues of limited visibility typical for forward facing imagery.

The FieldOfView class allows the qualification of the image quality within each cell and the "Limited" class is used where benthos or substrate obscurs the cell within ~1m of the camera (typically the length of the diode arm of stereo-video systems)

The Relief class uses a 0-5 quatification of releif

<HR>
</HR>


<HR>
</HR>
Bibliography

1. Hill, N., Althaus, F., Rees, T., et al., 2014. CATAMI Classification Scheme for Scoring Marine Biota and Substrata in Underwater Imagery Version 1.4: December 2014

2. Wilson, S. K., N. A. J. Graham, and N. V. C. Polunin. 2006. “Appraisal of Visual Assessments of Habitat Complexity and Benthic Composition on Coral Reefs.” Marine Biology 151 (3). Springer-Verlag: 1069–76.

3. McLean, Dianne L., Tim J. Langlois, Stephen J. Newman, Thomas H. Holmes, Matthew J. Birt, Katrina R. Bornt, Todd Bond, et al. 2016. “Distribution, Abundance, Diversity and Habitat Associations of Fishes across a Bioregion Experiencing Rapid Coastal Development.” Estuarine, Coastal and Shelf Science 178 (September): 36–47.

4. Collins, Danielle, Tim J. Langlois, Todd Bond, Thomas H. Holmes, Euan S. Harvey, Rebecca Fisher Dianne L. McLean. In press. “A novel stereo-video method to investigate fish-habitat relationships.” Methods in Ecology and Evolution.

5. Katherine Bennett, Timothy Langlois , George Shedrawi , Shaun Wilson, Dianne McLean. In press. “Can Diver Operated Stereo-Video Surveys for Fish Be Used to Collect Meaningful Data on Benthic Coral Reef Communities?” Limnology and Oceanography, Methods / ASLO.
