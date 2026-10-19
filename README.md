# Chelicerate vision database (1.1.0-alpha)
##Harvester arachnids (order: Opiliones)

### Question: 
* High visual acuity is needed to achieve complex visual tasks such as active visual prey pursuit (Class IV vision: Nilsson, 2013). Given that larger eye sizes allow for greater acuity, do harvesters that actively pursue prey have larger absolute eye sizes?

### Hypothesis: 
* Harvesters with more active foraging ecologies will have more investment into their vision than those that do not.

### Prediction:
* Accounting for phylogenetic relatedness, harvesters that actively pursue prey will have larger absolute eye sizes than those that don’t actively pursue prey.

### Data search strategy:
* For now, I have decided to focus on the harvesters in the group Palpatores which is a clade of two suborders (Eupnoi and Dyspnoi) that appear to have the most variation in eye sizes. The two other suborders (Cyphophthalmi and Laniatores) appear to have much less variation in eye sizes. For this version of the dataset (1.1.0-alpha) I decided to focus on getting at least one representative from each of the currently recognized families (https://wcolite.com/) of Palpatores. I first checked Pinto-da-Rocha et al., 2007, a harvester textbook that included a compilation of known harvester diets and a reference on frugivory and herbifory in harvesters (Nyffeler et al., 2023). From there, I chose representative species from each family that generally had the most foraging information known. I then did a targeted search for each of these species to find figures with scale bars or some other scale to measure lens diameter along with other parameters described below. Some species I had to infer foraging ecologies for based on my experiences and published work on related species with similar morphologies (this is noted in the sheet). I was able to find mostly complete data for every family outside of Nipponopsalididae, an enigmatic Dyspnoan group with only 3 described species in a single genus. 

### Metadata (column name definitions):
* sex:	m = male, f = female, no value means that sex was not give and could not be determined from source
* min and max depth:	only for marine taxa - minimum and maximum number of meters that they can be found below sea level
* depth_source:	only for marine taxa - figure, paper, museum, personal
* light_environment:	photic, dysphotic, aphotic
* light_confidence:	known through literature/unpublished data or inferred by me
* foraging_ecology:	pursuit, mixed, sessile
* diet:	varied, separated by commas - ex: bacteria, hydrozoan, bryozoan, diptera, snails, etc., etc.,
* general_eating_behavior:	carnivore, herbivore, omnivore (broadest definition)
* specific_eating_behavior:	bacteriavore, detritivore, planktonivore, frugivore ,etc., etc.,
* trophic_breadth:	generalist, specialist
* diet_confidence:	known through literature or unpublished data or inferred by me
* body_length:	pycnogonid: trunk + cephalon length. opiliones: cephalothorax + abdomen length. in mm
* bl_source, th_source, ld_source:	figure (ie. photos with published scale bar or some other scale), drawing (including schematic drawings), paper (value listed in paper), photo (photo with scale found on internet), personal (measured personally)
* tubercle_height:	length of tubercle or ocularium from base of cephalon/cephalothorax to the furthest tip of eye hill/ocular tubercle/ocularium. in mm
* tubercle_shape:	shape of the tubercle or ocularium (e.g. dome, conical)
* eye_number:	0,2,4
* ant_lens_diameter:	longest axis of anterior lens diameter. this is the single eye pair in non-pycnogonids including opiliones. in mm
* post_lens_diameter:	longest axis of posterior lens diameter. in mm
* metric_conversion_yn:	did we have to convert to mm? yes or no (y/n)
* measurement_confidence:	my confidence in how accurate the measurements are (poor, moderate, good, excellent)
