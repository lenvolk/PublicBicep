# PublicBicep

Public repo for Azure Bicep projects

List of Storage Account SKU's used for Parameter video:  
 'Standard_LRS'  
 'Standard_GRS'  
 'Standard_RAGRS'  
 'Standard_ZRS'  
 'Premium_LRS'  
 'Premium_ZRS'  
 'Standard_GZRS'

storageV2.bicep Used for the Variables and Functions Video

New-AzResourceGroupDeployment -Name Test -ResourceGroupName biceptstRG -TemplateFile .\storage.bicep
