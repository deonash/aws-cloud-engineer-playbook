```

mvn -B archetype:generate \
 -DarchetypeGroupId=software.amazon.awssdk \
 -DarchetypeArtifactId=archetype-lambda -Dservice=s3 -Dregion=AP_SOUTH_1 \
 -DarchetypeVersion=2.21.29 \
 -DgroupId=com.techoral.myapp \
 -DartifactId=myapp

```