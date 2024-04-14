## To view this data!
(i) Launch RStudio.
(ii) Change your directory to the directory containing these files.
(iii) Use the load function to load the data (e.g. file=load("TCGA_TNBC_192samplex.maf).
(iv) View files (e.g. summary (tnbc.maf/ head(tnbc.maf). 

## For additional statisitcal details, use our code!
# Install and load the psych package
install.packages("psych")
library(psych)

# Print detailed summary statistics using describe()
describe(BRCA.mut)

# Alternatively, you can use the skimr package
# Install and load the skimr package
install.packages("skimr")
library(skimr)

# Print detailed summary statistics using skim()
skim(BRCA.mut)

## For querries or troubleshooting, reach us at aamirmehmood@sjtu.edu.cn
