# Project Template Repository

This repository is designed to serve as a template for the curation and maintenance of data within a specific project. Projects may items such as a thesis chapter or a manuscript publication. 

## Minimum metadata requirements

All repositories should also contain a `README.md` file which details the following metadata, as appropriate:

1. Project title
2. Lead HQP
3. Other HQP
4. Lead PI
5. Other PI
6. Data sources
7. Funding sources

## Project structure
All project repos are named according to the associated project (e.g. _projectname'). In addition, they contain the following folders:

1. **data |** will contain separate folders for `RawData`, `CleanData`, and `ProcessedData`,
Sub-folders under ``RawData`` will usually be organized by instrument.

`CleanData`, and `ProcessedData` may contain sub-folders with merged data files derived from more than one instrument.

Do Not create swarms of unnecessary sub-folders; the YYYYMMDD is in the file name.

2. **code |** scripts and other code for processing and analyzing project information
Use sub-folder `OldR` to store outdated code.

3. **docs |** project notes, etc.
In particular, there must be a tabular `DataDictionary` in .txt or .md format.
The `DataDictionary` includes every variable name; the definition of the variable; the units; the folder (ex. **data |`RawData`|`ClarioStar`)
4. **output |** saved outputs (e.g. knit .Rmd outputs; figures and tables) from analysis
Do not save swarms of intermediate figures!


## Creating a new project for storage from the GitHub website

1. From the [template's website](https://github.com/FundyPhytoPhys/ProjectTemplate), click the _Use this template_ button.

2. Select the owner for your new repository. (This will be the `FundyPhytoPhys` organization since you want it to be integrated within the organization. It would be you as an individual user *only* if you want to use this template for something outside of the lab group.)

3. Choose a name for your new repository in the format of `PROJECTNAME`.

4. Write a brief description about the repository.

5. Set the new repository to `Public` unless you want the contents to be `Private` (usually `Public`).

6. Click the _Create repository from template_ button.

7. Clone the repo by creating a local new .Rproj under RStudio.
Do not save such local .Rproj on cloud servers or file syncing services;  GitHub is the cloud server.


## Naming and formatting conventions
All files should follow the standardized naming convention outlined below:

- Dates: YYYYMMDD
- Text: UTF-8 encoding, unless forced otherwise by instrument data file formats.
- File names: descriptive, searchable, and consistent!
PROJECT_YYYYMMDD_SampleID_OtherInfo_OtherInfo.xxx


## Repository use
Students or collaborators wishing to use data from a repo must abide by the following guidelines.

*For more information about project maintenance, please contact
**Douglas Campbell** at dcampbel@mta.ca.

With thanks to **Kateri Salk**, krsalkgu@uwaterloo.ca,  **Megan Larsen**, mlarsen@wlu.ca, **Jason Venkiteswaran**,  jvenkiteswaran@wlu.ca, who generated the template we cloned.

