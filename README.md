# The Lab for Neuroimaging and Neuroinformatics (LNN) @ UCPH

This is the website for the LNN lab at UCPH. 

## Configuration

Most of the configuration is done in /config/_default. The landing page is defined in hugo.yaml, and the navigation bar is defined in menu.yaml. To link a homepage widget, specify the URL as a hash `#` followed by the filename of the desired widget in your `content/` folder. The weight parameter defines the order that the links will appear in. 

## How to add content

### New data on the main page
The content of the main page is placed in content/_index.md, and it is organized in blocks. Refer to hugo documentations for further details. 

### Authors
Members of the lab are added in content/authors. Each member gets their own directory that contains the _index.md file, and an avatar.jpg. 

### Publications
Luckily, Github Actions takes care of new publications. All you need to do is to add the bibtex entry of your latest publication to the publications.bib and push it as a new Pull Request. Github Acrions will take care automatically, and create a directory in /content/publication.

