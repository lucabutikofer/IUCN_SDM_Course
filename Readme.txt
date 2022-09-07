# Transdisciplinary Nature Conservation: the IUCN Red List of Threatened Species from evaluation to practice

# Program:

## Morning (9:00 - 12:30)
- Theoretical introduction
- Step by step SDM workflow tutorial with Wallace


### Introduction (9:00 - 9:30)
*Antoine*
- What are SDMs?
- What are SDMs used for?


### SDM workflow (9:30 - 10:30)
*Fede*
- Occurrence Data (Wallace component)
	- Data types (5 min)
		- Presence only; Presence/absence; Detection/non-detection https://onlinelibrary.wiley.com/doi/10.1111/ecog.02445
		- Biases (5 min)
		- Sampling
		- Detectability FR: is detectability « bias » ? Perhaps we should also give a second of info on bias and how we define it
		- Taxonomic biases
- Process Occurrence Data (Wallace component) (5 min)
	- Dealing with biases
		- Data filtering FR: isn’t « data filtering » the same as « spatial thinning » ?
		- Replicating bias in background locations
		- Model bias
		- Spatial Thinning (Wallace component)


## Morning break (10:30 11:00)

 
### SDM workflow (11:00 - 12:30)
*Luca*
- Environmental Data (Wallace component) (10 min)
	- Matching our rationale
		- Typical kinds of layers
			- Climate
			- Geology
			- Podology
			- Hydrology
			- Land use/cover
			- Distance to … proxies of a process
			- Moving windows landscape moderation of local ecological processes
			- WorldClim (Wallace component)
				- Alternatives: CHELSA, ESA-CCI-LC,...
- Process Environmental Data (Wallace component) (5 min)
	- Niche truncation
	- Variables correlation

*Fede*
- Partition Occurrence Data (Wallace component) (5 min)
        - Model validation
        - Spatial partition (Wallace component) (10 min)
    - Modelling algorithms
	    - MaxEnt (Wallace component)
		    - Feature classes (Wallace component)
        - Regularisation multipliers (Wallace component)
		    - Classification performance (Wallace component)
          - ROC (Receiver Operating Characteristic)
          - AUC (Area Under the ROC Curve)
          - OR (Omission Rates)
          - AIC (Akaike Information Criterion)
          - TSS
          - Specificity and sensitivity

*Luca*
- Visualise (Wallace component) (10 min)
    - Response curves
    - Map predictions
        - Raw and Logistic outputs (Wallace component)
        - Binary output (Wallace component)
- Project (Wallace component) (10 min)
    - New locations
    - Future environmental variables
    - Multivariate Environmental Similarity Surface (MESS) (Wallace component)
- Extracting R code (Wallace component) (5 min)

*Fede*
- Defining our rationale (10 min)
    - What are you modeling, and why?
        - Predicting distribution (maps for present or future), inferring species-environment relationships
        - “Where are potential breeding sites?”
        - “Where are potential sighting locations?”
            - Mobile/sessile species
            - Home range sizes
    - “How will distribution change in the future?”
        - Examples of all of the above 
- Theory (10 min)
    - Niche theory https://onlinelibrary.wiley.com/doi/10.1111/j.1461-0248.2007.01107.x 
    - BAM diagram https://www.researchgate.net/publication/255722125_Variation_in_niche_and_distribution_model_performance_The_need_for_a_priori_assessment_of_key_causal_factors 
    - Implications of theory
    - Choosing appropriate resolution (10 min)
        - Temporal
        - Spatial
        - Thematic (https://ace-lab.ca/assets_b/Riva-Nielsen2020_Article_SixKeyStepsForFunctionalLandsc.pdf)

## Lunch break(12:30 - 14:00)

## Afternoon
- Theory on SDMs as Red List assessments tools
- Students to produce SDM for threatened species


## SDMs for Red List assessments (14:00 15:30)

### Theory
- Extent Of Occurrence (EOO)
- Area Of Occurrence (AOO, 2x2 km grid)
- SDMs as AOO

### Exercises
1. Redo SDM with one new species With R
2. EOO, AOO in R, compare with IUCN online
4. Area Of Habitat (AOH) for mountain tree (e.g. *Larix decidua*)
5. Compare SDM with IUCN AOO and EOO (and AOH if for *Larix decidua*)
