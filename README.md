<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_github"></a> [github](#requirement\_github) | 4.26.1 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_github"></a> [github](#provider\_github) | 4.26.1 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [github_membership.membership_for_another_user](https://registry.terraform.io/providers/integrations/github/4.26.1/docs/resources/membership) | resource |
| [github_repository.example](https://registry.terraform.io/providers/integrations/github/4.26.1/docs/resources/repository) | resource |
| [github_repository.repositorios](https://registry.terraform.io/providers/integrations/github/4.26.1/docs/resources/repository) | resource |
| [github_team.devops-team](https://registry.terraform.io/providers/integrations/github/4.26.1/docs/resources/team) | resource |
| [github_team_members.some_team_members](https://registry.terraform.io/providers/integrations/github/4.26.1/docs/resources/team_members) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_organizacion"></a> [organizacion](#input\_organizacion) | El nombre de la organizacion | `string` | n/a | yes |
| <a name="input_repositorio_descripcion"></a> [repositorio\_descripcion](#input\_repositorio\_descripcion) | Descipcion del repositorio | `string` | n/a | yes |
| <a name="input_repositorio_nombre"></a> [repositorio\_nombre](#input\_repositorio\_nombre) | Nombre del repositorio | `string` | n/a | yes |
| <a name="input_repositorio_visibilidad"></a> [repositorio\_visibilidad](#input\_repositorio\_visibilidad) | visibilidad del repositorio | `string` | n/a | yes |
| <a name="input_repositorios"></a> [repositorios](#input\_repositorios) | Los nombres de los repositorios | `list(string)` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_url_git_repositorio"></a> [url\_git\_repositorio](#output\_url\_git\_repositorio) | URL para clonar el repositorio |
<!-- END_TF_DOCS -->