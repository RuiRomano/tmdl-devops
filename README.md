# What is TMDL?

A human readable Tabular Model Definition Language using a YAML-like syntax. Each tabular metadata object has a textual representation with minimal delimiters. Indentation is used to indicate parent-child relationships between objects.

Learn more here:
https://powerbi.microsoft.com/en-us/blog/announcing-public-preview-of-the-tabular-model-definition-language-tmdl/


# Convert PBIX into TMDL using Tabular Editor

Install latest version of [Tabular Editor](https://github.com/TabularEditor/TabularEditor)

Enable TMDL Serialization mode in Tabular Editor Preferences:

![image](./.images/TabularEditorTMDL.png)

Open PBIX in Power BI Desktop and open Tabular Editor External tool:

![image](./.images/OpenTE.png)

Save as Folder to save the model definition into TMDL Format:

![image](./.images/SaveTMDL.png)

Navigate to the folder and your model should be serialized using TMDL format:

![image](./.images/TMDLFolder.png)

# Deploy to Workspace using pbi-tools

This repo uses [pbi-tools](https://pbi.tools/) to deploy the dataset using TMDL to a Power BI Premium workspace

