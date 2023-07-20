# template-nf

This is a Nextflow workflow template generator. This template is under development, with further features and improved documentation to be added. 

## **Why use this template?** 

[Nextflow](https://www.nextflow.io/) is open source and scalable workflow management software, developed for bioinformatics. It enables the development and execution of integrated, reproducible workflows consisting of multiple processes, various environment management systems, scripting languages, and software packages. 

Given Nextflow's extensive capabilities, there are many ways to structure your workflows. We developed this template to aid beginners in learning how to develop best practice Nextflow workflows. Here, we've prioritised modularity, portability, and flexibility.  

## **Who is this template for?** 

The DSL2 workflow template is suitable for:

* Nextflow newcomers looking for a low barrier to entry, structured starting point, and guidance.
* Custom workflow developers looking for a simple scaffold which can be extended and modified as needed.
* Collaborative teams looking for a standard and consistent workflow code base structure.
* Scalable workflow developers looking for a scalable and reproducible solution for their data analysis and processing needs.

It is not suitable for:

* Those wishing to create and contribute to public nf-core workflows, as it is not nf-core compatible.
* Those creating simple or single-task workflows with only a few tasks and minimal complexity.
* Those with no previous command-line and bash experience.

## **How to create a template?** 

Once you create a new repository using this template, a GitHub Action workflow will automatically be deployed. This workflow will populate your new repository with the skeleton template directory. To create a new repository: 

### [User guide](https://sydney-informatics-hub.github.io/Nextflow_DSL2_template_guide/) 

Please see our [documentation](https://sydney-informatics-hub.github.io/Nextflow_DSL2_template_guide/) for instructions on how to use the template code base to build your workflow.

### Install Nextflow

Depending on the system you're working on there are a few options for installing and running Nextflow including software management tools like bioconda and Singularity. See [here](https://www.nextflow.io/docs/latest/getstarted.html#installation) for installation instructions. Once you have installed Nextflow, you can configure it to run on your system if needed. 


## **Acknowledgements** 

The work presented here was developed by the Sydney Informatics Hub, a Core Research Facility of the University of Sydney and the Australian BioCommons 'Bring Your Own Data' Platforms Project which is enabled by NCRIS via ARDC and Bioplatforms Australia. 