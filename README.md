# provisioning-drive
used to hold all script and source to provision the Drive demo
1. Update installed modules with the latest release
1. Launch provisioning script
```shell
curl --request POST \
--url [host]/modules/api/provisioning \
--header 'Authorization: Basic [base64]' \
--header 'Content-Type: application/yaml' \
--data '- include: https://raw.githubusercontent.com/Jahia/provisioning-drive/main/script/modules.yaml'
```
1. update the credential for widen from tools -> OSGI -> configuration -> 
2. launch the modules **quiz-electric-vehicule-1.0.0-SNAPSHOT.jar** stored in the directory `modules`
3. Optional : before the official release install kibana-dashboards-provider-0.3.0-SNAPSHOT.jar
and jexperience-dashboards-0.2.0-SNAPSHOT.jar
4. Launch provisioning script
```shell
curl --request POST \
--url [host]/modules/api/provisioning \
--header 'Authorization: Basic [base64]' \
--header 'Content-Type: application/yaml' \
--data '- include: https://raw.githubusercontent.com/Jahia/provisioning-drive/main/script/templateSet.yml'
```
