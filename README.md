## dbt-health_claims
This repo is to create macros for healthcare data professionals

### Supported warehouses
>- Databricks

### 10_digit_ndc_to_hipaa_ndc
- applies to : `column`
- Converts a 10 digit NDC to a HIPAA compliant 11 digit NDC (5-4-2 configuration)
- Input has to comply with any of the following configuration
> - `6-4-2`
> - `6-4-1`
> - `6-3-2`
> - `6-3-1`
> - `5-4-2`
> - `5-4-1`
> - `5-3-2`
> - `4-4-2`
- Any other confguration is invalid and will yield a `null`
