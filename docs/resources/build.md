---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "packer_build Resource - terraform-provider-packer"
subcategory: ""
description: |-
  
---

# packer_build (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **file** (String) Packer file to use for building

### Optional

- **additional_params** (Set of String) Additional parameters to pass to Packer
- **directory** (String) Working directory to run Packer inside. Default is cwd.
- **environment** (Map of String) Environment variables
- **force** (Boolean) Force overwriting existing images
- **triggers** (Map of String) Values that, when changed, trigger an update of this resource
- **variables** (Map of String) Variables to pass to Packer

### Read-Only

- **build_uuid** (String) UUID that is updated whenever the build has finished. This allows detecting changes.
- **id** (String) The ID of this resource.


