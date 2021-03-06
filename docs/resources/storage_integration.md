---
page_title: "snowflake_storage_integration Resource - terraform-provider-snowflake"
subcategory: ""
description: |-
  
---

# Resource `snowflake_storage_integration`





## Schema

### Required

- **name** (String, Required)
- **storage_allowed_locations** (List of String, Required) Explicitly limits external stages that use the integration to reference one or more storage locations.
- **storage_provider** (String, Required)

### Optional

- **azure_tenant_id** (String, Optional)
- **comment** (String, Optional)
- **enabled** (Boolean, Optional)
- **id** (String, Optional) The ID of this resource.
- **storage_aws_role_arn** (String, Optional)
- **storage_blocked_locations** (List of String, Optional) Explicitly prohibits external stages that use the integration from referencing one or more storage locations.
- **type** (String, Optional)

### Read-only

- **created_on** (String, Read-only) Date and time when the storage integration was created.
- **storage_aws_external_id** (String, Read-only) The external ID that Snowflake will use when assuming the AWS role.
- **storage_aws_iam_user_arn** (String, Read-only) The Snowflake user that will attempt to assume the AWS role.


