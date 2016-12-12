**Integrating proteomics and selected reaction monitoring to develop a non-invasive assay for geoduck reproductive maturation.**
Supporting Information


**File names** and their contents.


**S1-Pgenerosa-gonad-protein-v3.fasta**  
Deduced protein sequences derived from gonad transcriptome sequencing.


**S2-comet.params** 
Parameter file used in Comet searches for the DDA data.


**S3-technical-reps.pdf**
NMDS of  the whole proteomic profiles (DDA data) for the three biological replicates and corresponding three technical replicates for each sex and maturation stage. Blue points represent female proteomes and orange represent male. Shapes and shade (light to dark) represent the different stages: circles for early-stage, squares for mid-stage, and triangles for late-stage.


**S4-technical-reps-box-plots.pdf**
Box plot of the coefficients of variation for protein spectral counts from DDA data A) across technical replicates for each geoduck biological replicate and B) across biological replicates for each sex-maturation stage. CVs were calculated in R using the raster package. X-axis labels correspond to the geoduck sex and maturation stage, indicated by e.g. “EF3” represents early-stage female sample 3. The boxes represent the upper and lower quartiles of the data distribution; horizontal black line represents median value; “whiskers” extend to the greatest and least values, excluding outliers; open circles represent outliers (more or less than 3/2 times the upper or lower quartiles.


**S5-NMDS-SRM-tech-reps.pdf**
NMDS of gonad SRM data for the 3 biological replicates and corresponding three technical replicates for each sex and maturation stage. Blue points represent female proteomes and orange represent male. Shapes and shade (light to dark) represent the different stages: circles for early-stage, squares for mid-stage, and triangles for late-stage.


**S6-spc-nsaf-prot-names.txt**
All identified proteins from the DDA experiment with Uniprot annotations (e-value cut-off of 1E-10), total spectral counts for each technical replicate, calculated normalized spectral abundance factor (NSAF) for combined technical replicates, and indication of significantly differentially abundant proteins by pairwise comparison. Columns containing spectral count data have headers “SpC” followed by the biological replicate number, sex, maturation stage, and technical replicate (for example, “SpC 3FE” is technical replicate 1 from early-stage female 3). Notation for NSAF is similar to SpC. The 9 columns in the sheet have headers such as “EFvLF” (comparison between early- and late-stage females) have asterisks in the cells that correspond to proteins that were differentially abundant for each given comparison. The last two columns (“NMDS Gonad” and “NMDS Hemolymph”) have asterisks in cells that correspond to the proteins with peptide transitions that contribute significantly to the SRM NMDS plot distributions.


**S7-DAGs.pdf**
Enrichment plots for early- and mid-maturation stage geoduck (EM, EF, MM, MF). Processes colored in blue were enriched from the set of all proteins detected in the given sex-stage, while red processes are from the protein set that was uniquely detected in a sex-stage. Darker colors represent higher significance of enrichment.


**S8-SRM-data.xlsx**
Raw Skyline output (in the tab “Skyline output) and peak intensities normalized by QC peptide abundance (“Normalized Intensities”) for the gonad and hemolymph SRM data. 


**S9-SRM-cv-boxplots.pdf**
Integrated peak area coefficient of variation values across all gonad peptide transitions (n=212) and hemolymph peptide transitions (n=171) A) across technical replicates for each geoduck biological replicate in gonad tissue, B) across biological replicates for each sex-maturation stage in gonad tissue, C) across technical replicates for each geoduck biological replicate in hemolymph, and D) across biological replicates for each sex-maturation stage in hemolymph. CVs were calculated in R using the raster package. X-axis labels correspond to the geoduck sex and maturation stage, indicated by e.g. “EF3” represents early-stage female sample 3. The boxes represent the upper and lower quartiles of the data distribution;horizontal black line represents median value;“whiskers” extend to the greatest and least values, excluding outliers; open circles represent outliers (more or less than 3/2 times the upper or lower quartiles).


**_Enrichment-input.xlsx**
Input files for running the enrichment analysis. Each tab in the spreadsheet has a list of geoduck protein IDs for each sex and stage. The tabs labeled e.g. “LM” are all the proteins detected in the late-stage male gonad proteome whereas the tabs labeled e.g. “LM only” are the proteins that were detected exclusively in the late-stage male proteome.


**_egg-sperm.txt**
Identifying information for the three proteins used for phylogenetic comparison of egg-sperm interacting proteins. The geoduck protein ID is provided, along with additional geoduck protein IDs that had the same Uniprot annotation. The Uniprot ID and protein annotation are provided, along with the NCBI accession numbers of the proteins used for the comparison from the other species.


