# api Automation Postman Collections.
This repository holds three of postman collections, that cover Functional and smoke testing by focusing on the acceptance conditions.

These examples have been created for use with the Postman utility. Postman is a testing framework for REST APIs. The tool can be downloaded from www.getpostman.com.

To import the collections.

1.First `clone` this repository.

2.Open the Postman utility and select the `Import` option. 

3.Select the `Folder tab` from the dialog and drag and drop the cloned repository folder into the target.

4.Dont forget to select `Api Automation task` Environment from the Environment Drop down at the top right of Postman window, just to declear important environment variables.

Github jobs is an api that return all jobs available in specific criteria, you can find the api documantation inside this URL https://jobs.github.com/api.

basically Github jobs api contains the following apis:

**1.GET /positions.json**

Search for jobs by term, location, full time vs part time, or any combination of the three. All parameters are optional

Parameters:

*description* — A search term, such as "ruby" or "java". This parameter is aliased to search.

*location* — A city name, zip code, or other location search term.

*lat* — A specific latitude. If used, you must also send long and must not send location.

*long* — A specific longitude. If used, you must also send lat and must not send location.

*full_time* — If you want to limit results to full time positions set this parameter to 'true'.

**2.GET /positions/ID.json**
Retrieve the JSON representation of a single job posting.

Parameters:

*markdown* — Set to 'true' to get the description and how_to_apply fields as Markdown.

