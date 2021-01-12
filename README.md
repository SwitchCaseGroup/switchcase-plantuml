# switchcase-plantuml

PlantUML Theme and other includes

This allows for a single referenced repo across documentation.

This is based on the following excellent projects

- [PlantUML](https://plantuml.com/)
- [AWS Icons for PlantUML](https://github.com/awslabs/aws-icons-for-plantuml)
- [PlantUML Themes](https://github.com/bschwarz/puml-themes)

These items can be referenced out of the `dist` directory as follows:

## Theme

```puml
!include https://raw.githubusercontent.com/SwitchCaseGroup/switchcase-plantuml/master/dist/theme/all.puml
```

## AWS Icons

```puml
!define AWSPuml https://raw.githubusercontent.com/SwitchCaseGroup/switchcase-plantuml/master/dist/aws-icons/
' Include main AWSCommon and then sprite files
!include AWSPuml/AWSCommon.puml
' !include AWSPuml/BusinessApplications/all.puml
' !include AWSPuml/Storage/SimpleStorageServiceS3.puml
```
