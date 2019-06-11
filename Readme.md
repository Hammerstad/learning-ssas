# SSAS basic example

Just files after following the [Analysis Services Fundamentals course on Pluralsight](https://app.pluralsight.com/library/courses/ssas-basic/table-of-contents).

In order to use this, spin up a local MSSQL db, e.g using docker:

```
docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=@wesomePassw0rd' -p 1433:1433 -d mcr.microsoft.com/mssql/server:2017-latest
```

Connect to the datasource, and generate the relational schema (`Visual studio -> Extensions -> Database -> Generate Relational Schema`). You will need the [Microsoft Analysis Services Projects extension](https://marketplace.visualstudio.com/items?itemName=ProBITools.MicrosoftAnalysisServicesModelingProjects) installed.