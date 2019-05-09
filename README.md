# script_package.xml

<h1>Script for generate package.xml</h1>

In order to generate package.xml from an unmanaged/managed package run the below command from your terminal once you cd into the project folder

./scripts/generatepkgXML.sh <org_alias> <packageName/changesetName>

<org_alias> stands for the org alias of your org that you authenticate to retrieve/deploy source

<packageName> This will be your managed package name or unmanaged package name or changeset name .

The above script command will fail if you have not authenticated to the salesforce environment via CLI or extension or you have misspelled changeset or package Name .
