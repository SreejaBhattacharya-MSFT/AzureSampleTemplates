Instructions:

1. Create a user assigned managed identity
2. Assign Global Reader role in Azure AD to this managed identity using the object id of the managed identity
3. Run the below Powershell cmdlet
```powershell
New-AzResourceGroupDeployment -ResourceGroupName lab -TemplateFile RoleAssignmentCreate.json -TemplateParameterFile Parameters.json -Name TestDeployment1
```
