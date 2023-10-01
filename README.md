git config --global user.email "muhammetbolat@gmail.com"

mvn install:install-file -DgroupId=[group-id] -DartifactId=[artifact-id] -Dversion=[bew version] -Dfile=[file-absoulute-path.jar] -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=. -DcreateChecksum=true

git add .


git commit -m "released version for [package_name_version]"

git push
