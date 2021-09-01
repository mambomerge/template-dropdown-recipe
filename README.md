# template-dropdown-recipe

This sample project is designed to be referenced by a Salesforce developer familiar with VS Code, sfdx, and Mambo Merge.  Use at your own risk.

This sample project contains the Salesforce metadata needed to configure Mambo Merge to display a drop-down menu of template options.

## Instructions

1. Upload your docx template to your Salesforce org
2. Get the salesforce Id of the file that you uploaded
3. Update the MamboMergeConfigs.json static resource located at force-app/main/default/staticresources to use the salesforce Id of the file that you uploaded
4. Make any additional changes as needed
5. Upload the static resource file to your Salesforce org
6. Edit the Lightning Page on which you put Mambo Merge and change the templateId to the key in the static resource, eg. sampleDropDown
