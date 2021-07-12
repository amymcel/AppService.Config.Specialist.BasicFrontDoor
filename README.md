# AppService.Config.Specialist.BasicFrontDoor
App Service Configuration for Front Door Training

[![Deploy To Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Famymcel%2FAppService.Config.Specialist.BasicFrontDoor%2Fmain%2Fazuredeploy.json)

## This arm deployment will:

1. Crate two App Service Plans - one in East US, one in West US
2. Create two App Services - one under each app service plan
3. Create an Azure Front Door resource
4. Add Frontend, Backend and routing rule for one of the App Service's deployed
