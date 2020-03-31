## Sneha's pagedown rendered Resume

This repo contains the source-code and results of my resume built with the [pagedown package](https://pagedown.rbind.io) and a modified version of the 'resume' template. 

The main files are:

  - `index.Rmd`: Source template for the resume, contains a variable `PDF_EXPORT` in the header that changes styles for pdf vs html. 
  - `index.html`: The final output of the template when the header variable `PDF_EXPORT` is set to `FALSE`. 
  - `skannan_resume.pdf`: The final exported pdf as rendered by Chrome on my computer. 
  - `parsing_functions.R`: A series of small functions for parsing a position entry into the proper HTML format. Includes logic for removing links if needed etc..
  - `gather_data.R`: Loads the data that makes up the body of the resume.
  - `csvs/positions.csv`: 
  - `css/`: Directory containing the custom CSS files used to tweak the default 'resume' format from pagedown. 
  - `cv_strayer`: Folder containing the [original repo's](https://github.com/nstrayer/cv) files 


## Acknowledgement

Thanks to [Nick Strayer](http://nickstrayer.me/) for simplifying the process of using pagedown for creating a resume. There are parts of code which are modified from the original repo to customize my resume.

