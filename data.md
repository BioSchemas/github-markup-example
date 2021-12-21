# Hello fruit data

The [sample CSV file](https://github.com/BioSchemas/github-markup-example/blob/main/data/sample.csv) is located in the main branch of this repository and contains two rows, the first one with fruit names and the second one with their corresponding color.

## Markup

Notes about the markup: 
* We advised you to deposit your data on a data repository or archive that will provide you with a Permanent Identifier (PID) such as a Digital Object Identifer (DOI). We have not done so as we are using toy data so we use the CSV URL as the dataset identifier rather than a proper ID.
* We provide markup only for those properties defined as *minimum* by Bioschemas Dataset profile ([version Draft 0.4](https://bioschemas.org/profiles/Dataset/0.4-DRAFT)) but you can improve your dataset description adding *recommended* and *optional* properties.
* Whenever you use an [EDAM](https://edamontology.org/) term to describe your data, try and find the one which describes it best. Here we use "Data" as an example.

<script type="application/ld+json">
  { 
    "@context": "https://schema.org", 
    "@type": "Dataset",
    "@id": "https://github.com/BioSchemas/github-markup-example/blob/main/data/sample.csv",
    "http://purl.org/dc/terms/conformsTo": "https://bioschemas.org/profiles/Dataset/0.4-DRAFT", 

    "description": "Toy data used as an example on how to add Bioschemas markup to your data",
    "identifier": "https://github.com/BioSchemas/github-markup-example/blob/main/data/sample.csv",
    "keywords":  [
      {
        "@type": "DefinedTerm", 
        "@id": "http://edamontology.org/data_0006", 
        "name": "Data"
      },
      "Sample data"
    ], 
    "license": "https://creativecommons.org/licenses/by/4.0/",
    "name": "Hello fruit data",
    "url": "https://bioschemas.org/github-markup-example/data.html"

  }
</script>