# vvv-php-ldap-utility

Utility to install php-ldap as part of provisioning in [VVV](https://github.com/varying-vagrant-vagrants/vvv/).

## How To Use

Extend your `vvv-custom.yml` like this:

```yml
utilities:
  php-ldap:
    - php-ldap

utility-sources:
  php-ldap: https://github.com/michal666/vvv-php-ldap
```

For more see the [official VVV documentation on utilities](https://varyingvagrantvagrants.org/docs/en-US/utilities/).
