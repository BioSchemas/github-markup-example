---
layout: tutorial
bioschemas:
  "@context": https://schema.org
  "@type": LearningResource
  "@id": https://bioschemas.org/github-markup-example/tutorial.html
  http://purl.org/dc/terms/conformsTo: https://bioschemas.org/profiles/TrainingMaterial/0.9-DRAFT-2020_12_08
  description: Toy tutorial used as an example on how to add Bioschemas markup to your
    tutorials
  keywords: Sample tutorial, Jupyter Notebook, Bioschemas, markup
  name: Hello fruit tutorial
  audience:
    "@type": Audience
    audienceType: Python learners
  author:
    "@type": Person
    "@id": https://orcid.org/0000-0003-3986-0510
    familyName: Castro
    givenName: Leyla Jael
  competencyRequired: Jupyter notebooks
  educationalLevel: Beginner
  identifier: https://bioschemas.org/github-markup-example/tutorial.html
  inLanguage:
  - en-US
  learningResourceType:
  - guideline
  license: https://creativecommons.org/licenses/by/4.0/
  mentions:
  - "@type": SoftwareApplication
    "@id": https://github.com/BioSchemas/github-markup-example
  - "@type": Dataset
    "@id": https://github.com/BioSchemas/github-markup-example/blob/main/data/sample.csv
  teaches:
  - The student will be able to run a Jupyter Notebook
  url: https://bioschemas.org/github-markup-example/tutorial.html

---

## Getting started

In this tutorial, you will learn how to use the Hello Fruit code and get a warm fruty and colorful greeting. We use Jupyter Notebooks so it is an advantage if you are familiar with it.
If you have not installed yet Jupyter Notebooks, please do so. 

To run the code, follow these instructions:
* Clone the repository at https://github.com/BioSchemas/github-markup-example, we will use the main branch
* Init Jupyter Notebooks and make sure you can access the folder where you cloned de repo
* Open the notebook named "hello_fruit" under folder *code*
* Run the cells one by one to get a fuity colorful greeting

## Markup

Notes about the markup: 
* We advised you to deposit your tutorial on a training repository or archive that will provide you with a Permanent Identifier (PID) such as a Digital Object Identifer (DOI). We have not done so as we are using a toy tutorial so we use the tutorial page URL as the tutorial identifier rather than a proper ID.
* We provide markup for those properties defined as *minimum* and (some) *recommended* by Bioschemas TrainingMaterial profile ([version Draft 0.9](https://bioschemas.org/profiles/TrainingMaterial/0.9-DRAFT-2020_12_08)) but you can improve your dataset description adding more *recommended* and *optional* properties.
* Whenever you use an [EDAM](https://edamontology.org/) term to describe your tutorial, try and find the one which describes it best. We do not use EDAM terms in this example.


<script type="application/ld+json">
  {{ page.bioschemas | jsonify }}
</script>