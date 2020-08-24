
1. `wget https://repo1.maven.org/maven2/org/openapitools/openapi-generator-cli/5.0.0-beta/openapi-generator-cli-5.0.0-beta.jar`
1. `yarn`
1. `java -jar openapi-generator-cli-5.0.0-beta.jar generate -i spec.yaml -g typescript-axios -o generated`
1. `yarn tsc -b -f`
