# switchcase-plantuml

PlantUML Theme and other includes

This allows for a single referenced repo across documentation.

This is based on the following excellent projects

- [PlantUML](https://plantuml.com/)
- [AWS Icons for PlantUML](https://github.com/awslabs/aws-icons-for-plantuml)
- [PlantUML Themes](https://github.com/bschwarz/puml-themes)

These items can be referenced out of the `dist` directory as follows:

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
