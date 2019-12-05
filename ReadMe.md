# Apache NiFi InvokeHTTP processor with NTLM authentication

This project creates a copy of the standrad InvokHTTP processor but adds the ability to authenticate agains NTLM when you need to communicate with eg a SharePoint SOAP service.

To build the nar file execute the following command:
```bash
mvn clean install
```

If you need this to be created offline you can set your local maven repo and zip up that folder for distribution

```bash
mvn -Dmaven.repo.local=/your/local/mvn/repo clean install
```

This command downloads all dependencies into folder `/your/local/mvn/repo`
You can zip up this folder for distribution if you cannot work in connected mode.

