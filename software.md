# Hello fruit tool

The Hello Fruit code consists on a single Jupyter Notebook. It loads a CSV file named [sample.csv](https://github.com/BioSchemas/github-markup-example/blob/main/data/sample.csv) and creates a hello message from its rows, based on the seconds corresponding to the current time.

For a description of the sample.CSV file, visit the [data page](./data.md).

## Markup

Notes about the markup: 
* We advised you to deposit your software on a software repository or archive that will provide you with a Permanent Identifier (PID) such as a Digital Object Identifer (DOI). We have not done so as we are using toy code so we use the sode URL as the software identifier rather than a proper ID.
* We provide markup for those properties defined as *minimum* and (some) *recommended* by Bioschemas ComputationalTool profile ([version Release 1.0](https://bioschemas.org/profiles/ComputationalTool/1.0-RELEASE)) but you can improve your dataset description adding more *recommended* and *optional* properties.
* Whenever you use an [EDAM](https://edamontology.org/) term to describe your software, try and find the one which describes it best. Here we use "Data management" as an example. Pay attention to the expected time, although DefinedTerm is commonly better when it comes to terms coined in a controlled vocabulay such as EDAM, that is not always compatible with the current definition in [Schema.org](https://schema.org), e.g., see [applicationSubCategory](https://schema.org/applicationSubCategory).


<script type="application/ld+json">
  { 
    "@context": "https://schema.org", 
    "@type": "softwareApplication",
    "@id": "https://github.com/BioSchemas/github-markup-example",
    "http://purl.org/dc/terms/conformsTo": "https://bioschemas.org/profiles/ComputationalTool/1.0-RELEASE", 

    "description": "Toy code used as an example on how to add Bioschemas markup to your software",
    "name": "Hello fruit tool",
    "url": "https://bioschemas.org/github-markup-example/software.html",

    "applicationCategory": [
      "Script"
    ],
    "applicationSubCategory":  [
      "Data management"
    ], 
    "author": {
      "@type": "Person",
      "@id": "https://orcid.org/0000-0003-3986-0510",
      "familyName": "Castro",
      "givenName": "Leyla Jael"
    },
    "license": "https://opensource.org/licenses/MIT",
    "softwareVersion": "0.0.1"
    
  }
</script>