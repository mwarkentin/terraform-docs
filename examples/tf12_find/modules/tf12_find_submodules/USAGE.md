# Usage
<!--- BEGIN_TF_DOCS --->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:-----:|
| subnet\_ids | A list of subnet ids to use | `list(string)` | n/a | yes |
| vpc\_id | The id of the vpc | `string` | n/a | yes |
| extra\_environment | List of additional environment variables | <code><pre>list(object({<br>    name  = string<br>    value = string<br>  }))<br></pre></code> | `[]` | no |
| extra\_tags | Additional tags | `map(string)` | `{}` | no |
| instance\_count | Number of instances to create | `number` | `1` | no |
| instance\_name | Instance name prefix | `string` | `"test-"` | no |

## Outputs

| Name | Description |
|------|-------------|
| vpc\_id | The Id of the VPC |
<!--- END_TF_DOCS --->
