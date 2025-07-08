# getting-data-from-the-web-api-access

Welcome! This will help you get started using an API to acquire webdata. 

There are a few elements here: the files that are numbered by level of difficulty/ease, and then additional files in `other_ex`. 

To get started: you will need API keys for OMDB and a username for geonames. 

You can save this information in your r profile using the following code:
```
usethis::edit_r_profile(scope = "project")
```

Then, you will save the following INSIDE the Rprofile:
```
options(omdb_key = "yourkey")
```

Finally, notice that we have your Rprofile in `.gitignore` so you don't commit this by mistake:

```
# History files
.Rhistory
.Rapp.history
.Rprofile
```
