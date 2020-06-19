# wso2-identity-server-open-ldap-schemas
This project contains the required schemas for OpenLDAP to integrate as a userstore. 
To add schemas,
```
sudo ldapadd -Y EXTERNAL -H ldapi:// -f wso2Person.ldif
sudo ldapadd -Y EXTERNAL -H ldapi:// -f scimPerson.ldif
sudo ldapadd -Y EXTERNAL -H ldapi:// -f identityPerson.ldif
```
