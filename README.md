# hocs-ukvi-complaint-schema
The JSON schema for the UKVI Complaints Management complaint schema.
Contains the schemas, examples and validation tests.

## Generating test data
This is a [useful site for generating JSON from JSON schema](https://json-schema-faker.js.org)

## Publishing

When the repository is tagged this schema is currently published to both Artifactory and GitHub Packages.

View the `.drone.yml` file for more information on the commands used in the pipeline and when this is triggered.

### Maven Local
For local development, the module can be published to the 
[Maven local repository](https://docs.gradle.org/current/userguide/publishing_maven.html#publishing_maven:install).

Example command for publishing to Maven local:
```
./gradlew publishToMavenLocal -PartifactVersion=1.0.0
```

## Versioning

For versioning this project uses [SemVer](https://semver.org/).

## Authors

This project is authored by the Home Office.

## License

This project is licensed under the MIT license. For details please see [License](LICENSE) 
