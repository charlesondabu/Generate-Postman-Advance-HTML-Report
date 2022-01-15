# Generate-Postman-Advance-HTML-Report
## Generating HTML Report In Postman with Newman

1.  Install html report package for basic reporting 

	`$ npm install newman-reporter-html`
 
2. install Html Report package for advanced reporting.

	`$npm install newman-reporter-htmlextra`
3. Go to postman under collection  export postman collection to a specific location.
![]("C:\Users\v-condabu\Desktop\Untitled Project.gif")
4.		Run Collection by newman with report option for basic reports.
		`$ newman run collection.json -r html` 
5.		Run Collection by newman with report optin for advanced reports.
`$ newman run collection.json -r htmlextra` 
