# Unity Generate UML

[![Generate UML](https://github.com/Delt06/unity-generate-uml/actions/workflows/unity-generate-uml.yml/badge.svg)](https://github.com/Delt06/unity-generate-uml/actions/workflows/unity-generate-uml.yml)

A GitHub action that generates UML diagrams for Unity C# code automatically.

## Workflow file
Can be found [here](.github/workflows/unity-generate-uml.yml).

### Parameters
- `CODE_PATH`: location of C# code to generate diagrams from
- `UML_OUTPUT_PATH`: a folder to put the UML diagrams to
- `UMP_GENERATION_PARAMETERS`: parameters of UML generator

## Example of output
![Example Output](UML/include.svg)
