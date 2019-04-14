# role-apticron
role to setup apticron to inform the user about updates via email on a debian server. The role only installs apticron on debian and ubuntu, since it´s not avaible on other distributions. However the role will not throw errors on other distributions.

Variables
---------
* `apticron_email`: email adress apticron sends update information to

+ `server_name`: Name of the server that gets mentioned in the update informations

Example config:
```bash
apticron_email: "example@examplemail.de"
server_name: "example_server"
```
