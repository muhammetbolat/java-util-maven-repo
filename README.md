# Project Name

This project is utilization classes of java packages. You can create JAR file of your project and send the github maven repository.

## Requirements

To run this project, you will need the following:

- Java 17 or higher
- Maven

## Installation

To set up the project on your local machine, follow these steps:

1. Configure your Git user email:

   ```shell
   git config --global user.email "muhammetbolat@gmail.com"

2. Install the project using Maven and add a JAR file to your local Maven repository:
   Replace [group-id], [artifact-id], [new version], and [file-absolute-path.jar] with appropriate values.
   ```shell
   mvn install:install-file -DgroupId=[group-id] -DartifactId=[artifact-id] -Dversion=[new-version] -Dfile=[file-absolute-path.jar] -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=. -DcreateChecksum=true

4. Start tracking the project with Git:
   ```shell
   git add .
   git commit -m "released version for [package_name_version]"
   git push


