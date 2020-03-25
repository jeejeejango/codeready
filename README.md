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

## First Administrator
To enable first administrator on CodeReady Workspaces/CHE, you will need to add the following environment variable for deployment/codeready:

- name: CHE_SYSTEM_ADMIN__NAME
- value: \<userid\>

Ensure the changes are rollout to new version.
