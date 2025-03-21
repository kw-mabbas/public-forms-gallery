# Public forms templates gallery
These templates are part of the KWIZ Forms public-forms product feature.

More info on KWIZ Forms:
https://kwizcom.com/kwiz-forms/

More info on public forms:
https://docs.kwizcom.com/link/535/documentation-forms-features-public-forms

This project and license covers the free use rights for the templates.
Using these templates within KWIZ Forms / Public Forms requires a license for KWIZ Forms.

Customers may fork this repo and create their own gellery following the instructions below:

## Template Creation Process:

-   Create the form in form designer 

-   Export as a JSON file 

-   Fork & Clone the repository 

-   Add the file into the gallery/templates folder 

-   Clean up internal names (make sure all names are logical, use lower camel case when naming e.g.  firstName) 

-   Add your new template to the manifest file 

    -   Make sure that you include the fileName property. You must set it to the name of the JSON file you uploaded for the template. For example, if you uploaded a template called workSite.json, then you must have the property "fileName" : "workSite.json" 

    -   You also have the option of including a category property. This would allow you to either add it to a larger group or make a new category. Then when you filter the templates on the site, it will appear with its group. 
  
-   Switch to the KWizCom environment picker to "development" and test your new templates

-   Give the URL of your forked repo to the URL popup on the site

-   If you do see some errors when trying to load the templates , here is what they might mean:  

    -   "Template file not found" - The fileName did not match a file stored in the templates folder 

    -   "Template JSON structure is invalid, check documentation for details" - The template you uploaded is not of a valid public forms template type.

- If your templates work to your satisfaction, create a new PR and copy your changes into the dev branch
