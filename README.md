# Digital Ocean Devstack

## HOW TO

Initialize Terraform. These will be install terraform digitalocean provider plugin.

```bash
terraform init
```

Validate the terraform files.

```bash
terraform validate
```

Build Terraform. Deploy digitalocean droplet and install devstack

```
terraform apply
```

*Logging devstack installation*

login into your droplet

```bash
ssh root@1.2.3.4
```

logging devstack installation

```bash
tail -f /var/log/cloud-init-output.log
```