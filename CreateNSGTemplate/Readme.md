Instructions

  1. Create the deployment template - CreateNsgTemplate.json
  2. Create the Parameter file - Parameters.json
  3. Run the below Powershell cmdlet 

```powershell
New-AzResourceGroupDeployment -ResourceGroupName <rgname> -TemplateFile CreateNsgTemplate.json -TemplateParameterFile Parameters.json -Name TestDeployment2
```
