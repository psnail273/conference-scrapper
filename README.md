# Conference Scrapper

This project is to create a tool that can update a Google sheet with a list of upcoming conferences
and the associated information for those conferences.

# Running

Just run all steps in the jupyter notebook `scrapper.ipynb`. This will create a file called 'conferences.xlsx'
that can be imported into Google Drive.

## Issues

- Will make multiple items for the same conference if different websites name them slightly different
- Does not add dates for getting tickets/submitting papers
- Each website uses a different scrapping method
  - If one fails, just try again and it will probably work...
- `scrapper2.ipynb` was an attempt at cleaning up the inital notebook, but it's not completed