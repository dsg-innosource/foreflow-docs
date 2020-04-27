# Active Directory

-   [Configuration](#configuration)
-   [Importing Users](#importing-users)

<a name="configuration"></a>

## Configuration

To integrate with active directory the following configuration variables are available:

<div markdown="1" class="table-wrap">

| Variable Name            | Required | Default         | Description                                                     |
| ------------------------ | -------- | --------------- | --------------------------------------------------------------- |
| `FOREFLOW_AD_ENABLED`    | YES      | false           | Enables Active Directory integration                            |
| `LDAP_HOSTS`             | YES      |                 | The server Hostnames or IP Addresses used separated by commas   |
| `LDAP_BASE_DN`           | YES      |                 | The distinguished name of your domain (dc=contoso,dc=local)     |
| `LDAP_USERNAME`          | YES      |                 | The username to use when querying for AD users                  |
| `LDAP_PASSWORD`          | YES      |                 | The password to use when querying for AD users                  |
| `FOREFLOW_AD_ATTRIBUTES` | NO       | name,objectguid | Comma separated list of attributes to display when adding users |
| `LDAP_ACCOUNT_PREFIX`    | NO       | _blank_         | Prefix to use for accounts                                      |
| `LDAP_ACCOUNT_SUFFIX`    | NO       | _blank_         | Suffix to use for accounts                                      |
| `LDAP_PORT`              | NO       | 389             | Port to use when connecting to the hosts                        |
| `LDAP_USE_SSL`           | NO       | false           | If SSL should be used for the connection                        |
| `LDAP_USE_TLS`           | NO       | false           | If TLS shoudl be used for the connection                        |

</div>

<a name="importing-users"></a>

## Importing Users

To import users from Active Directory, navigate to the _Users_ page and click the _Import Users_ button in the top right.

This will present the import page where you can search for and select a user to import. Once you've selected a user a modal will appear allow you to see the Active Directory attributes you've configured via the `FOREFLOW_AD_ATTRIBUTES` setting as well as allow you to change the User's name, email address and timezone.

![ad-import-add-user](/{{version}}/img/users-ad-add-modal.jpg)