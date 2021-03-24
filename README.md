# Unity Generate UML

[![Generate UML](https://github.com/Delt06/unity-generate-uml/actions/workflows/unity-generate-uml.yml/badge.svg)](https://github.com/Delt06/unity-generate-uml/actions/workflows/unity-generate-uml.yml)

A GitHub action that generates UML diagrams for Unity C# code automatically.

## Workflow file
Can be found [here](.github/workflows/unity-generate-uml.yml).

### Parameters
- `CODE_PATH`: location of C# code to generate diagrams from
- `UML_OUTPUT_PATH`: a folder to put the UML diagrams to
- `UMP_GENERATION_PARAMETERS`: parameters of the UML generator (refer to the [documentation](https://github.com/pierre3/PlantUmlClassDiagramGenerator#usage))

## Example of output
![Example Output](UML/include.svg)

## References
- [PlantUmlClassDiagramGenerator](https://github.com/pierre3/PlantUmlClassDiagramGenerator) - a .NET cli tool to generate `.puml` files from C# code.
- [PlantUML GitHub action](https://github.com/cloudbees/plantuml-github-action) - a GitHub action to generate images from `.puml` files.
- [Add & Commit](https://github.com/EndBug/add-and-commit) - a GitHub action to commit changes from workflows.
