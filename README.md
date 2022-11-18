# Policy-Analysis-TK
Framework that will allow me to scafold text analysis projects, designed to work totally in Google Drive and Google Colab

## Setup

1. Copy as template, and rename according
1. Create folder that will be where you project is stored
1. Copy the [settings.yaml](settings.yaml) file into this Google Drive Folder
1. Provide `$FOLDER` as path to your Google Drive folder into `settings.yaml`
1. Provide `$SPEADSHEET` URLto Google spreadsheet that has the list of files you want to harvest into `settings.yaml`
1. Deploy the notebook you need by opening in Colab using `link` below.
1. Modify `YAML_LOCATION` in first line of notebook to be the 'Shared' URL of your YAML file

## Notebooks

|Notebook|Description|Link|
|---|---|---|
|Harvest|Grabs the contents of the files in the `$SPREADSHEET` and creates Text documents of them in `$FOLDER`|link|
|PreProcess_LDA|Preprocesses text to create BOW, Corpus, etc and saves to `$FOLDER\preprocess`|link|
|Contruct_LDA|Builds actual model and gives some exploratory parameters and saves to `$FOLDER\model`|link|
