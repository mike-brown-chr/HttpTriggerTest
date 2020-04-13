Nuget adds:
* Microsoft.Azure.WebJobs.Extensions.Storage --version 3.0.4 
* Microsoft.Azure.WebJobs.Extensions.CosmosDB --version 3.0.5

if doing dotnet core with vscode:
```
$ func init HttpTriggerTest --dotnet 
$ cd HttpTriggerTest/ 
$ ls $ func new --name HttpTrigger1 --template "HTTP trigger" 
$ dotnet add package Microsoft.Azure.WebJobs.Extensions.Storage --version 3.0.4 
$ dotnet add package Microsoft.Azure.WebJobs.Extensions.CosmosDB --version 3.0.5 
$ dotnet add package Microsoft.Azure.WebJobs.Extensions.ServiceBus --version 4.1.1

$ func azure functionapp publish mdb-func-test-httptrigger1 --force 
```
