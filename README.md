# Docker with Ansible

Role installing and configuring docker CE

## Optional Parameters

 * `docker_users` - List of users that can use docker

## Testing

Credit: Tested with vagrant image from [@geerlingguy's Ansible for Devops](https://github.com/geerlingguy/ansible-for-devops)

Run the following from the test directory:

### Initial Install
```
ansible-galaxy install -r requirements.yml
vagrant up
```

### Reapply provisioning
```
vagrant provision
```

