## Implementation guidance
### I.	Import Power Automate flow:
  - Import ‘NGERFactorLibrar Generation’ Solution file from the source folder. Ref [here](https://learn.microsoft.com/en-us/power-apps/maker/data-platform/import-update-export-solutions)
  - In Powerautomate connections, [fix Dataverse connections used for the flow](https://learn.microsoft.com/en-us/power-automate/add-manage-connections#update-a-connection)
  - Open https://make.powerautomate.com/ and check the imported flow, if the flow is disabled, edit the flow. Fix connection reference errors.Save and publish the flow again.
  - This flow allows you to upload PDF when running.  Please upload one- or two-pages PDF which has the emission factor library details. The sample NGER PDFs used can be found [here](https://github.com/MS-Sustainability-Resources/msm-copilot-extensions/tree/main/setup_custom_factor_library). Please ensure the flow points to this sharepoint.