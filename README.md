# Policy-Analysis-TK
Framework that will allow me to scafold text analysis projects, designed to work totally in Google Drive and Google Colab

## Setup

1. Copy as template, and rename according 
2. Copy the [settings.yaml](settings.yaml) file into the Google Drive Folder where you want all of you documents to live
3. Provide `$FOLDER` as path to your Google Drive folder into `settings.yaml`
4. Provide `$SPEADSHEET` URLto Google spreadsheet that has the list of files you want to harvest into `settings.yaml`
5. Deploy the notebook you need by opening in Colab and start running your cells


## Notebooks

|Notebook|Description|Link|
|---|---|---|
|Harvest|Grabs the contents of the files in the `$SPREADSHEET` and creates Text documents of them in `$FOLDER`|link|
|PreProcess_LDA|Preprocesses text to create BOW, Corpus, etc and saves to `$FOLDER\preprocess`|link|
|Contruct_LDA|Builds actual model and gives some exploratory parameters and saves to `$FOLDER\model`|link|
