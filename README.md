# switchcase-plantuml

PlantUML Theme and other includes

This allows for a single referenced repo across documentation.

This is based on the following excellent projects

- [PlantUML](https://plantuml.com/)
- [AWS Icons for PlantUML](https://github.com/awslabs/aws-icons-for-plantuml)
- [PlantUML Themes](https://github.com/bschwarz/puml-themes)
- [C4-PlantUML](https://github.com/plantuml-stdlib/C4-PlantUML)

## Contents

These items can be referenced out of the `dist` directory as follows:

- [Theme](#theme)
- [AWS Icons](#aws-icons)
- [C4](#c4-plantuml)

## Theme

```
!include https://raw.githubusercontent.com/SwitchCaseGroup/switchcase-plantuml/master/dist/theme/all.puml
```

## AWS Icons

```
!define AWSPuml https://raw.githubusercontent.com/SwitchCaseGroup/switchcase-plantuml/master/dist/aws-icons/
' Include main AWSCommon and then sprite files
!includeurl AWSPuml/AWSCommon.puml
' !includeurl AWSPuml/BusinessApplications/all.puml
' !includeurl AWSPuml/Storage/SimpleStorageServiceS3.puml
```

## C4-PlantUML

Pulled from https://github.com/plantuml-stdlib/C4-PlantUML/releases/tag/v2.0.0

```
' Include the appropriate file below. These files include a reference to https://raw.githubusercontent.com/SwitchCaseGroup/switchcase-plantuml/master/dist/c4/C4.puml

' Context
!include https://raw.githubusercontent.com/SwitchCaseGroup/switchcase-plantuml/master/dist/c4/C4_Context.puml

' Container
!include https://raw.githubusercontent.com/SwitchCaseGroup/switchcase-plantuml/master/dist/c4/C4_Container.puml

' Component
!include https://raw.githubusercontent.com/SwitchCaseGroup/switchcase-plantuml/master/dist/c4/C4_Component.puml

' Dynamic Diagram
!include https://raw.githubusercontent.com/SwitchCaseGroup/switchcase-plantuml/master/dist/c4/C4_Dynamic.puml

' Deployment Diagram
!include https://raw.githubusercontent.com/SwitchCaseGroup/switchcase-plantuml/master/dist/c4/C4_Deployment.puml
```
