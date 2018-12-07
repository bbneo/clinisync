
# 
# Clinisync Scan
# 
# The plan will be to scan clinisyc HIE pdf file text to extract:
# 
#   - summary of patient identifying information
#   - a summary of episodes of medical care and dates captured
#       - along with locations
#   - a summary of HCC suggestive information or documentation (risk adjusting diagnoses:  diabetes, COPD, CHF, ...)
#   - a summary of CMS Stars measures suggestive information or documentation (mammograms, colonoscopy, immunizations)
# 
# An initial pass will implement arrays of search terms to process with associated labels and do simple searches on
# the text extracted from clinisync pdf ("CCD") files using the pdftools package
# )
# 
#   Brad Banko, MD  
#   12/7/2018
#

setwd('C:/Users/bradley.banko/Documents/Analytics/Clinisync HCC extraction/clinisync')

install.packages('pdftools');
library(pdftools);

# using a configuration file with search terms and labels will be the goal rather than hardcoding search terms
# in this script

# Read search terms arrays and labels from file

search_terms_df <- read.csv("Clinisync Search Terms.csv")

# Syntax will be something like:
#  $ clinisync_scan CCD_<ptname>_<MRN>_<date>
#  read and concatenate text of clinisync file

clinisync_text <- pdf_text('CCd')

# Output will be as described above

# for each labels()
#   for each search term in labels()
#     if search term in clinisync text then
#       add label and search term to results data.frame()
      
# Output Results

# de-duplicate labels and search terms()
# display results dataframe:
#   Suspected HCC due to search term found in clinisync recordGraphics()



      
      )