How to Import SAS XPORT files into R with the foreign package?
Ans. 
setwd()
library(foreign)
read.xport()
How to Import SAS Files into R with the Haven package?
Ans.
        setwd()
        library(haven)
        read_sas(data_file, catalog_file = NULL, encoding = NULL,
        cols_only = NULL)
       
       3. How to read Weka Attribute-Relation File Format (ARFF) files in R?
        Ans. 
        setwd()
        library(foreign)
        read.arff(file)
      
How to read a heavy csv/tsv file using readr package?
        Ans.
         library(readr)

         read_csv(file, col_names = TRUE, col_types = NULL,
         
         locale = default_locale(), na = c("", "NA"), quoted_na = TRUE,
         
         quote = "\"", comment = "", trim_ws = TRUE, skip = 0, n_max = Inf,
         
         guess_max = min(1000, n_max), progress = show_progress())



       read_tsv(file, col_names = TRUE, col_types = NULL,
         
         locale = default_locale(), na = c("", "NA"), quoted_na = TRUE,
         
         quote = "\"", comment = "", trim_ws = TRUE, skip = 0, n_max = Inf,
         
         guess_max = min(1000, n_max), progress = show_progress())
