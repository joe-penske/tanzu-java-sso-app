# Accelerator Log

## Options
```json
{
  "projectName" : "appsso-starter-java"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseFirst))
┃ ┃ ┃ engine.transformations[0].validated.merge (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(chain)
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[0].validated.chain (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Combo, Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].validated.chain.transformations[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to false
┃ ┃ ┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].validated.chain.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository == null) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug client.yaml matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew.bat matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/AuthenticationCheckFilter.java matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html matched [**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/home.html matched [**] -> excluded
┃ ┃ ┃ ┃ ┗ ┗ ┗ Debug README.md matched [**] -> excluded
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[1].include (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug build.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug client.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug gradlew matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug gradlew.bat matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/AppSSOAcceleratorApplication.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/AuthenticationCheckFilter.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/config/WebSecurityConfig.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/AuthenticatedHomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/vmware/tanzu/apps/sso/accelerator/web/HomeController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/images/tanzu-logomark.svg matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/styles/main.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/templates/authenticated-home.html matched [**] -> included
┃ ┃ ┃ ┗ ┗ Debug src/main/resources/templates/home.html matched [**] -> included
┃ ┗ ┗ ╺ engine.transformations[0].validated.merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
