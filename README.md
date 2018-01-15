# ReverseImageLookup
A personal image Search engine used to search similiar images present in a data set by provinding an image as an input

# Description
Our goal here is to build a personal image search engine. Given our dataset of vacation photos, we want to make this dataset “search-able” by creating a “more like this” functionality — this will be a “search by example” image search engine. For instance, if I submit a photo , our image search engine should be able to find and retrieve all similiar photos.

# Installation
Extract the zip file. Open terminal in the Reverse Image Lookup Directory.

# Creating DataSet
Copy all the Pictures you want to keep in dataset and paste in dataset folder and then run the following command in terminal :
<h5>python index.py --dataset dataset --index index.csv</h5>

# Running the Search Engine
Run the following Command in Terminal
<h5>python search.py --index index.csv --query queries/(your image name) --result-path dataset</h5>

# Result	
It Will search out the best possible result and display it.
