# AWS Storybook Terraform module

Terraform module which creates the resources to host a front web storybook on AWS.

## Usage

```hcl
module "main" {
  source      = "genstackio/layer-storybook/aws"

  bucket_name = "name-of-the-bucket"
  dns         = "storybook.mydomain.com"
  dns_zone    = "id-of-the-route53-zone"
}
```
