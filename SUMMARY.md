# FOSSEE Summer Fellowship 2021
## TASK 9:Import and export project
Currently, an authenticated user can save the circuit on the cloud. However, there should be a facility for a user to export the circuit in some format (say json) and import the circuit into the system as and when needed.
### How did you approach the problem?
I started by reading the problem statement. The moment i read it, i understood what things i may require to implement it, which turned out be json object which may have whole information about the user's progress on website, and then to read the json while importing i might require some kind of flow which will load everything present in json format. After this i started understanding a little bit about the major functions used, Angular Route i might work majorly on and data structure i might need. I ended up determining all these things through little bit of research on documentation of project and then searched in project itself.
After searching a bit i found that we are already saving a JSON object in indexedDB of browser, and then fetching it to load project from there. This helped me to better understand the flow by revisiting those functions used in there. So all this gave me fine idea about how to solve the problem. So solution i came up was i will generate an object containing all data about the Schematic on website, then save its blob into a file and download it. And if we want to import a json, then function will read the file's blob and process it in a function after converting into an object again from file blob.

### What steps you took to solve?
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
![Process Flow Chart](assets/images/process.png)

### Any new package/technology that you used?
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

### Indicate which files were changed heavily
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## Recorded Demo
### Project Export Functionality
![Screen Recording Exporting](assets/Export.gif)
### Project Import Functionality
![Screen Recording Importing](assets/Import.gif)

## GITHUB LINK:
[GITHUB BRANCH](https://github.com/ikartikgautam/eSim-Cloud/tree/add-import-export)
