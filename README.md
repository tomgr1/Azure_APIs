# Azure_APIs
This is a sample project to:
1. Create a queue container if it does not exist.
2. Add a message to the queue

=========================================

Prereqs:
1. AZ Storage Account needs to be created
2. Need to save the Connection string in a App.Config VS file
3. Need to load the following modules into VS (Using VS 2019 - full addition)
    using Microsoft.Azure; // Namespace for CloudConfigurationManager 
    using Microsoft.Azure.Storage; // Namespace for CloudStorageAccount
    using Microsoft.Azure.Storage.Queue; // Namespace for Queue storage types

See: https://docs.microsoft.com/en-us/azure/storage/queues/storage-dotnet-how-to-use-queues
