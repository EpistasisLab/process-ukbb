# template-repository
This is a template repository for EpistasisLab members. Click the "Use this template" button in the [project page](https://github.com/EpistasisLab/template-repository) to start your own project! 

* Make your project private, and name it “[Your_Selected_Project_Name]-DEV”, e.g. TPOT-DEV. After getting permission to make it public, you can eaisly duplicate the DEV project and remove the "DEV" in the project name.
* Please document important project information (paper, data, code etc.) in your project repository so other lab members can easily reproduce your work.
* Do NOT record credentials! All public/private repositories are visible to lab members. 
* Large data and licensed data (e.g. UK biobank) should ONLY be saved under directory /project/moore on LPC.

## File Structure
```
.
├── docs                # Docs related to this project, e.g. paper, emails...
├── data                # Data related to this project, e.g. raw data info, results... NOTE: large data goes on LPC
├── code                # Code for data Analysis, app development
└── tmp                 # Temporary data ignored by git. See ".gitignore"
```
