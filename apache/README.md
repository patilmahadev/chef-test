# apache

TODO: Enter the cookbook description here.

Upload Cookbook:
```knife cookbook upload <cookbook name>```

Bootstrap:
```knife bootstrap 10.10.1.146 --ssh-identity-file /root/chef-repo/.chef/27-aug-17-nvirginia.pem --ssh-user ec2-user --sudo --node-name rhel --run-list 'apache' -y````
