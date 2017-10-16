# newman-html-report-template-verbose
a newman html report template which contains request and response details (body) in the report

## How to use
* install newman
* call newman as follows:
```
newman run -e env-INTEG.json --reporters cli,json,html,junit --reporter-html-template templates/htmlreqres.hbs --reporter-html-export nice_report.html mycollection.postman.json
newman
```

