# ModifiedOpenLabelling
A modified version of https://github.com/Cartucho/OpenLabeling OpenLabelling tool and https://github.com/ivangrov/ModifiedOpenLabelling for labeling yolo.

This repo is used to migrate Custom Vision Label (using GetTaggedImages from CustomVisionAPI) into yolov5 format.

Prerequisite :

    1. Azure Custom Vision Resource and its project with labeled images
    2. Installed Anaconda in The computer 

How to run (First Time):

    1. Open Your Anaconda Prompt / Shell that has been installed with anaconda
    2. Run `conda env create -f environment.yml` to create new conda environment
    3. Activate environment with `conda activate customvisionmigration` 
    4. Set .env-example variable with change \<anything in here> content like with Custom Vision configuration, and then rename it into .env
    5. Run DataLabelMigration.ipynb
    6. to check the images, run `python run.py` (make sure you running it using correct conda environment)

How to run (Next time to run):

    Just follow *How to run (First Time)* from step 3 to 6

