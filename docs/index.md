---
page_title: "GPG Provider"
subcategory: ""
description: |-
  The GPG provider provides resources to generate a private/public key pair.
---

# GPG Provider

The GPG provider provides resources to generate a private/public key pair.

## Example Usage

```terraform
terraform {
  required_providers {
    gpg = {
      source = "Olivr/gpg"
    }
  }
}
```

```terraform
resource "gpg_private_key" "key" {
  name  = "John Doe"
  email = "john@doe.com"
}
```
