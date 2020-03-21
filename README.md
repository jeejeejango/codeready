# CodeReady Workspaces 

This project contains the sample [devfile.yaml](devfile.yaml) to customized the workspace. The customization includes the following:
- sample cloud-native-demo project
- codeready project
- sample maven commands

You can create a custom devfile registry image, or update the devfile before creating the workspace. 

To update maven to use the mirror maven repository setup, you will need to open a terminal and copy [settings.xml](settings.xml) file to jboss workspace:

```bash
cp codeready/settings.xml /home.jboss/.m2
```
