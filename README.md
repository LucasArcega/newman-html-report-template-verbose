# newman-html-report-template-verbose
a newman html report template which contains request and response details (body plus http headers) in the report.
(similar what you could get with the newman v2 -O out option)

## How to use
* install newman
* call newman as follows:
```
newman run -e env-INTEG.json --reporters cli,json,html,junit --reporter-html-template templates/htmlreqres.hbs --reporter-html-export nice_report.html mycollection.postman.json
newman
```

