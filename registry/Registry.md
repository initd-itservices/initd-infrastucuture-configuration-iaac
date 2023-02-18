# Install Container Registry on Control Plane

### Run following playbook

```bash
ansible-playbook -i hosts registry/install-docker-registry.yaml -e "username=johndlamini@mailinator.com" -e "hostname=registry.cluster.net" -e "user=johndlamini@mailinator.com" -e "password=qwerty1234"
```

The project is currently developed and maintained by [DeveloperPrince](https://developerprince.co.zw) any additional support is appreciated.
