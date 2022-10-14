# provisioning-drive
used to hold all script and source to provision the Drive demo

1. Launch provisioning script
```shell
curl --request POST \
--url [host]/modules/api/provisioning \
--header 'Authorization: Basic [base64]' \
--header 'Content-Type: application/yaml' \
--data '- include: https://raw.githubusercontent.com/Jahia/provisioning-playground/main/scripts/playground-modules.yml'
```
2. 
