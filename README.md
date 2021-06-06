# Marconi Society Machine Learning Laboratory
This repository contains the source files for the Marconi Society Machine Learning Laboratory website.

[ml.netlabsug.org](https://ml.netlabsug.org/)

## Structure
The website structure is built upon folders which create different components of the rendered website.

_**_data**_ folder contains `.yml` files containing data for the different components in yaml format including:
  1. `agriculture.yml`: Contains the profiles for the projects in the agriculture domain, this is similar to the
      health.yml and the nlp.yml files.
  2. `news.yml`: Contains the news items with a date and a headline, a headline containing a snippet of the news
      item.
  3. `publist.yml`: Contains a list of publications that have come out of MSMLL.
  4. `seniors.yml`: Contains the profiles of the senior researchers of the laboratory, `researchers.yml` contains the
      profiles of junior researchers while `students.yml` has the student profiles.
      
 _**_includes**_ folder contains `.html` files defining the generally static components of the website i.e 
 header, body and footer of the website.
 
 _**_layouts**_ folder contains the `html` code for the dynamic parts of the websiste.
 
 _**_pages**_ folder contains `.md` files that define how the different dynamic data items of the website are displayed.
 
 _**_images**_ folder contains all the image files used for the website including the project thumbnails, team profile pictures,
 logos etc.
 
 _**CNAME**_ file that links this repository to the [ml.netlabsug.org](ml.netlabsug.org) URL.
