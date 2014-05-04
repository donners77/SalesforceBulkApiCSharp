Salesforce Bulk Api for .Net
=======================

An SDK (i.e. light wrapper) for the Salesforce Bulk Api for use in .net, c#, vb, powershell, etc. implements Async Task pattern

Uploading data is someting that needs to be scriptable and repeatable.
When you are testing a bulk import of data into salesforce it can take quite a bit of time to setup the import just right. Once you have setup the import, you want to be able to reapeat those steps with one click.
Salesforce provides the "BulkApi" for importing data, and there are many tools that make use of this api. However none of them offer a good scripting solution.

Take a look at the unit tests to see how simple it is to upload or download csv files directly with the Bulk Api.

You can also take a look at the Powershell Script which uploads and sownloads data in a few lines of code.

The api uses the asynch/await patern so that you can run and monitor many job/batches at the same time.