# TF code base
## Introduction
This is sample readme for terraform module
<!-- BEGIN_AUTOMATED_TF_DOCS_BLOCK -->
<!-- END_AUTOMATED_TF_DOCS_BLOCK -->
## Footer
Contributor Douce
<!-- BEGIN_TF_DOCS -->
## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | n/a |
| <a name="provider_template"></a> [template](#provider\_template) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_cloudwatch_event_rule.ebs-snap-scheduler](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/cloudwatch_event_rule) | resource |
| [aws_cloudwatch_event_target.ebs-snap-scheduler_target](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/cloudwatch_event_target) | resource |
| [aws_cloudwatch_log_group.lambda_log_group](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/cloudwatch_log_group) | resource |
| [aws_db_instance.mysql](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/db_instance) | resource |
| [aws_iam_instance_profile.iam-profile](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_instance_profile) | resource |
| [aws_iam_policy.GetParametersByPath](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.GetSecretValueAccess](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.s3_policy](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.s3_policy_migration](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.secret_rotator_lambda_policy](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_role.iam_role](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role) | resource |
| [aws_iam_role.secret_rotator_lambda_role](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role) | resource |
| [aws_iam_role_policy_attachment.GetParametersByPath2-attach](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.GetSecretValueAccess2-attach](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.aws_managed_policy-attach](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.s3-attach](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.s3_policy-attach](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.secret_rotator_lambda_role_policy_attachment](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.secret_rotator_lambda_role_policy_attachment_db_create_user](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.secret_rotator_lambda_role_policy_attachment_four](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.secret_rotator_lambda_role_policy_attachment_liquibase_user](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.secret_rotator_lambda_role_policy_attachment_super_user](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.secret_rotator_lambda_role_policy_attachment_three](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.secret_rotator_lambda_role_policy_attachment_two](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.ssm_login](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_instance.ec2_websrv_blue](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance) | resource |
| [aws_instance.ec2_websrv_green](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance) | resource |
| [aws_instance.ec2_websrv_provisioner](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance) | resource |
| [aws_instance.liquibase_instance](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance) | resource |
| [aws_kms_key.insight_db_kms_key](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/kms_key) | resource |
| [aws_lambda_function.blue_green_traffic_switch](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_function) | resource |
| [aws_lambda_function.db_create_usr_secret_rotator_lambda](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_function) | resource |
| [aws_lambda_function.ebs_snapshot](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_function) | resource |
| [aws_lambda_function.ebs_snapshot_deletion](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_function) | resource |
| [aws_lambda_function.secret_rotator_lambda](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_function) | resource |
| [aws_lambda_function.secret_rotator_lambda_four](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_function) | resource |
| [aws_lambda_function.secret_rotator_lambda_liquibase_user_rotation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_function) | resource |
| [aws_lambda_function.secret_rotator_lambda_one](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_function) | resource |
| [aws_lambda_function.secret_rotator_lambda_super_user_rotation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_function) | resource |
| [aws_lambda_function.secret_rotator_lambda_three](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_function) | resource |
| [aws_lambda_function.secret_rotator_lambda_two](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_function) | resource |
| [aws_lambda_function_url.blue_green_traffic_switch_url](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_function_url) | resource |
| [aws_lambda_permission.allow_secret_manager_call_lambda](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_permission) | resource |
| [aws_lambda_permission.allow_secret_manager_call_lambda_four](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_permission) | resource |
| [aws_lambda_permission.allow_secret_manager_call_lambda_one](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_permission) | resource |
| [aws_lambda_permission.allow_secret_manager_call_lambda_three](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_permission) | resource |
| [aws_lambda_permission.allow_secret_manager_call_lambda_two](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_permission) | resource |
| [aws_lambda_permission.db_create_user_rotation_allow_secret_manager_call_lambda](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_permission) | resource |
| [aws_lambda_permission.liquibase_user_rotation_allow_secret_manager_call_lambda](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_permission) | resource |
| [aws_lambda_permission.super_user_rotation_allow_secret_manager_call_lambda](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lambda_permission) | resource |
| [aws_lb.alb](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lb) | resource |
| [aws_lb_listener.ec2_listener](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lb_listener) | resource |
| [aws_lb_target_group.tg_blue](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lb_target_group) | resource |
| [aws_lb_target_group.tg_green](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lb_target_group) | resource |
| [aws_lb_target_group_attachment.attach_tg_blue](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lb_target_group_attachment) | resource |
| [aws_lb_target_group_attachment.attach_tg_green](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/lb_target_group_attachment) | resource |
| [aws_s3_bucket.bucket](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket) | resource |
| [aws_s3_bucket.bucket_migration](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket) | resource |
| [aws_secretsmanager_secret.Hirevue_secret](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret) | resource |
| [aws_secretsmanager_secret.Hogan_secret](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret) | resource |
| [aws_secretsmanager_secret.db1_secret](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret) | resource |
| [aws_secretsmanager_secret.db2_secret](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret) | resource |
| [aws_secretsmanager_secret.db3_secret](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret) | resource |
| [aws_secretsmanager_secret.db4_secret](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret) | resource |
| [aws_secretsmanager_secret.db_create_user_secret](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret) | resource |
| [aws_secretsmanager_secret.liquibase_user_secret](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret) | resource |
| [aws_secretsmanager_secret.mailgun_secret](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret) | resource |
| [aws_secretsmanager_secret.rds_secret](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret) | resource |
| [aws_secretsmanager_secret.saville_hs_secret](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret) | resource |
| [aws_secretsmanager_secret.super_user_secret](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret) | resource |
| [aws_secretsmanager_secret_rotation.db_create_user_rotation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_rotation) | resource |
| [aws_secretsmanager_secret_rotation.db_four_password_rotation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_rotation) | resource |
| [aws_secretsmanager_secret_rotation.db_master_password_rotation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_rotation) | resource |
| [aws_secretsmanager_secret_rotation.db_one_password_rotation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_rotation) | resource |
| [aws_secretsmanager_secret_rotation.db_three_password_rotation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_rotation) | resource |
| [aws_secretsmanager_secret_rotation.db_two_password_rotation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_rotation) | resource |
| [aws_secretsmanager_secret_rotation.liquibase_user_rotation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_rotation) | resource |
| [aws_secretsmanager_secret_rotation.super_user_rotation](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_rotation) | resource |
| [aws_secretsmanager_secret_version.db1_secret_cred](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_version) | resource |
| [aws_secretsmanager_secret_version.db2_secret_cred](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_version) | resource |
| [aws_secretsmanager_secret_version.db3_secret_cred](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_version) | resource |
| [aws_secretsmanager_secret_version.db4_secret_cred](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_version) | resource |
| [aws_secretsmanager_secret_version.db_create_user_cred](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_version) | resource |
| [aws_secretsmanager_secret_version.hirevue_cred](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_version) | resource |
| [aws_secretsmanager_secret_version.hogan_cred](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_version) | resource |
| [aws_secretsmanager_secret_version.liquibase_user_cred](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_version) | resource |
| [aws_secretsmanager_secret_version.mailgun_cred](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_version) | resource |
| [aws_secretsmanager_secret_version.rds_secret_cred](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_version) | resource |
| [aws_secretsmanager_secret_version.saville_hs_cred](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_version) | resource |
| [aws_secretsmanager_secret_version.super_user_cred](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/secretsmanager_secret_version) | resource |
| [aws_security_group.ec2_sg](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/security_group) | resource |
| [aws_security_group.lb_sg](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/security_group) | resource |
| [aws_security_group.rds](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/security_group) | resource |
| [aws_security_group.secret_rotator_lambda_sg](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/security_group) | resource |
| [aws_security_group.secrets_manager_endpoint_sg](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/security_group) | resource |
| [aws_ssm_parameter.db_user1](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter) | resource |
| [aws_ssm_parameter.db_user2](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter) | resource |
| [aws_ssm_parameter.db_user3](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter) | resource |
| [aws_ssm_parameter.rds_instance](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter) | resource |
| [aws_ssm_parameter.s3_bucket](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ssm_parameter) | resource |
| [aws_caller_identity.current](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/caller_identity) | data source |
| [template_file.user_data_blue](https://registry.terraform.io/providers/hashicorp/template/latest/docs/data-sources/file) | data source |
| [template_file.user_data_green](https://registry.terraform.io/providers/hashicorp/template/latest/docs/data-sources/file) | data source |
| [template_file.user_data_liquibase](https://registry.terraform.io/providers/hashicorp/template/latest/docs/data-sources/file) | data source |
| [template_file.user_data_provisioner](https://registry.terraform.io/providers/hashicorp/template/latest/docs/data-sources/file) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_WEIGHT_BLUE_TG_ONE"></a> [WEIGHT\_BLUE\_TG\_ONE](#input\_WEIGHT\_BLUE\_TG\_ONE) | Levels of blue traffic distribution | `string` | n/a | yes |
| <a name="input_WEIGHT_GREEN_TG_TWO"></a> [WEIGHT\_GREEN\_TG\_TWO](#input\_WEIGHT\_GREEN\_TG\_TWO) | Levels of green traffic distribution | `string` | n/a | yes |
| <a name="input_agent_pool_blue"></a> [agent\_pool\_blue](#input\_agent\_pool\_blue) | n/a | `string` | `" "` | no |
| <a name="input_agent_pool_green"></a> [agent\_pool\_green](#input\_agent\_pool\_green) | n/a | `string` | `" "` | no |
| <a name="input_agent_pool_liquibase"></a> [agent\_pool\_liquibase](#input\_agent\_pool\_liquibase) | n/a | `string` | `" "` | no |
| <a name="input_agent_token"></a> [agent\_token](#input\_agent\_token) | n/a | `string` | `" "` | no |
| <a name="input_agent_url"></a> [agent\_url](#input\_agent\_url) | n/a | `string` | `"https://dev.azure.com/tazioonline"` | no |
| <a name="input_alb-sg-tag_name"></a> [alb-sg-tag\_name](#input\_alb-sg-tag\_name) | n/a | `string` | `"hns-insight-wbsv-alb-sg"` | no |
| <a name="input_alb_name"></a> [alb\_name](#input\_alb\_name) | n/a | `string` | `"tes"` | no |
| <a name="input_alb_tag_name"></a> [alb\_tag\_name](#input\_alb\_tag\_name) | n/a | `string` | `"hns-insight-alb"` | no |
| <a name="input_ami"></a> [ami](#input\_ami) | n/a | `string` | `""` | no |
| <a name="input_application"></a> [application](#input\_application) | n/a | `string` | `"database"` | no |
| <a name="input_aws_access_key_id"></a> [aws\_access\_key\_id](#input\_aws\_access\_key\_id) | n/a | `string` | `""` | no |
| <a name="input_aws_secret_access_key"></a> [aws\_secret\_access\_key](#input\_aws\_secret\_access\_key) | n/a | `string` | `""` | no |
| <a name="input_blue_instance_count"></a> [blue\_instance\_count](#input\_blue\_instance\_count) | Number of instances in blue environment | `number` | `1` | no |
| <a name="input_blue_instance_tag_name"></a> [blue\_instance\_tag\_name](#input\_blue\_instance\_tag\_name) | n/a | `string` | `"hns-insight-wbsv-b"` | no |
| <a name="input_bucket_migration_name"></a> [bucket\_migration\_name](#input\_bucket\_migration\_name) | n/a | `list(any)` | <pre>[<br>  "hns-tazio-migration-videos",<br>  "hns-tazio-migration-audio",<br>  "hns-tazio-migration-documents",<br>  "hns-tazio-migration-keys",<br>  "hns-tazio-migration-logos",<br>  "hns-tazio-migration-thumbnails",<br>  "hns-tazio-migration-images",<br>  "hns-tazio-migration-backgrounds"<br>]</pre> | no |
| <a name="input_bucket_name"></a> [bucket\_name](#input\_bucket\_name) | n/a | `list(any)` | <pre>[<br>  "hns-test-tazio-us-east2-audio",<br>  "hns-test-tazio-us-east2-backgrounds",<br>  "hns-test-tazio-us-east2-documents",<br>  "hns-test-tazio-us-east2-images",<br>  "hns-test-tazio-us-east2-keys",<br>  "hns-test-tazio-us-east2-logos",<br>  "hns-test-tazio-us-east2-thumbnails",<br>  "hns-test-tazio-us-east2-videos"<br>]</pre> | no |
| <a name="input_bucket_param_name"></a> [bucket\_param\_name](#input\_bucket\_param\_name) | n/a | `list(any)` | <pre>[<br>  "hns-audio-bucket",<br>  "hns-backgrounds-bucket",<br>  "hns-documents-bucket",<br>  "hns-images-bucket",<br>  "hns-keys-bucket",<br>  "hns-logos-bucket",<br>  "hns-thumbnails-bucket",<br>  "hns-videos-bucket"<br>]</pre> | no |
| <a name="input_certificate_arn"></a> [certificate\_arn](#input\_certificate\_arn) | n/a | `string` | `"arn:aws:acm:us-east-2:313401190557:certificate/cc1aa7c9-297e-4721-b8e5-0e3e579a2895"` | no |
| <a name="input_clientID"></a> [clientID](#input\_clientID) | hogan credentials | `string` | `"clientID"` | no |
| <a name="input_cookie_duration"></a> [cookie\_duration](#input\_cookie\_duration) | n/a | `number` | `1800` | no |
| <a name="input_count_instance"></a> [count\_instance](#input\_count\_instance) | n/a | `number` | `2` | no |
| <a name="input_database_four"></a> [database\_four](#input\_database\_four) | n/a | `string` | `""` | no |
| <a name="input_database_one"></a> [database\_one](#input\_database\_one) | n/a | `string` | `"api_db_acc"` | no |
| <a name="input_database_three"></a> [database\_three](#input\_database\_three) | n/a | `string` | `"email_db_acc"` | no |
| <a name="input_database_two"></a> [database\_two](#input\_database\_two) | n/a | `string` | `"db_acc"` | no |
| <a name="input_db_create_user"></a> [db\_create\_user](#input\_db\_create\_user) | A user with database creation rights | `string` | `"hns_insight_db_create_usr"` | no |
| <a name="input_db_create_user_password"></a> [db\_create\_user\_password](#input\_db\_create\_user\_password) | n/a | `string` | `"pass1805"` | no |
| <a name="input_db_engine"></a> [db\_engine](#input\_db\_engine) | n/a | `string` | `"mysql"` | no |
| <a name="input_db_instance_type"></a> [db\_instance\_type](#input\_db\_instance\_type) | n/a | `string` | `"db.t3.micro"` | no |
| <a name="input_ec2-sg-tag_name"></a> [ec2-sg-tag\_name](#input\_ec2-sg-tag\_name) | n/a | `string` | `"hns-insight-wbsv-ec2-sg"` | no |
| <a name="input_ec2_iam_role"></a> [ec2\_iam\_role](#input\_ec2\_iam\_role) | n/a | `string` | `"HnS-AmazonSSMRoleForInstancesprofile"` | no |
| <a name="input_ec2_volume"></a> [ec2\_volume](#input\_ec2\_volume) | n/a | `number` | `30` | no |
| <a name="input_enable_blue_env"></a> [enable\_blue\_env](#input\_enable\_blue\_env) | Enable blue environment | `bool` | `true` | no |
| <a name="input_enable_deletion_protection"></a> [enable\_deletion\_protection](#input\_enable\_deletion\_protection) | n/a | `bool` | `false` | no |
| <a name="input_enable_green_env"></a> [enable\_green\_env](#input\_enable\_green\_env) | Enable green environment | `bool` | `true` | no |
| <a name="input_engine_version"></a> [engine\_version](#input\_engine\_version) | n/a | `number` | `5.7` | no |
| <a name="input_env_prefix"></a> [env\_prefix](#input\_env\_prefix) | n/a | `string` | `"hns"` | no |
| <a name="input_environment"></a> [environment](#input\_environment) | n/a | `string` | `"tst"` | no |
| <a name="input_green_instance_count"></a> [green\_instance\_count](#input\_green\_instance\_count) | Number of instances in green environment | `number` | `1` | no |
| <a name="input_green_instance_tag_name"></a> [green\_instance\_tag\_name](#input\_green\_instance\_tag\_name) | n/a | `string` | `"hns-insight-wbsv-g"` | no |
| <a name="input_hirevue_accountID"></a> [hirevue\_accountID](#input\_hirevue\_accountID) | Hirevue account credentials | `string` | `"1824"` | no |
| <a name="input_hirevue_apiKey"></a> [hirevue\_apiKey](#input\_hirevue\_apiKey) | Hirevue account credentials | `string` | `" "` | no |
| <a name="input_hirevue_baseInterviewURL"></a> [hirevue\_baseInterviewURL](#input\_hirevue\_baseInterviewURL) | n/a | `string` | `" "` | no |
| <a name="input_hirevue_baseURL"></a> [hirevue\_baseURL](#input\_hirevue\_baseURL) | n/a | `string` | `" "` | no |
| <a name="input_hirevue_secret_name"></a> [hirevue\_secret\_name](#input\_hirevue\_secret\_name) | Hirevue account secret credentials | `string` | `"hns-insights-hirevue"` | no |
| <a name="input_hogan_password"></a> [hogan\_password](#input\_hogan\_password) | hogan credentials | `string` | `"hogpass"` | no |
| <a name="input_hogan_secret_name"></a> [hogan\_secret\_name](#input\_hogan\_secret\_name) | hogan secret credentials | `string` | `"hns-insights-hogan"` | no |
| <a name="input_hogan_userid"></a> [hogan\_userid](#input\_hogan\_userid) | Hogan credentials | `string` | `"userID"` | no |
| <a name="input_hs-clientid"></a> [hs-clientid](#input\_hs-clientid) | Credential for H&S saville account | `string` | `"hs-clientid"` | no |
| <a name="input_hs-password"></a> [hs-password](#input\_hs-password) | Credential for H&S saville account | `string` | `"hspass"` | no |
| <a name="input_hs-url"></a> [hs-url](#input\_hs-url) | URL for H&S saville account | `string` | `" "` | no |
| <a name="input_hs-username"></a> [hs-username](#input\_hs-username) | Credential for H&S saville account | `string` | `"hs-username"` | no |
| <a name="input_iamInstanceProfile_tag_name"></a> [iamInstanceProfile\_tag\_name](#input\_iamInstanceProfile\_tag\_name) | n/a | `string` | `"HnS_iamInstanceProfile"` | no |
| <a name="input_impersonate"></a> [impersonate](#input\_impersonate) | Hirevue account credentials | `string` | `" "` | no |
| <a name="input_instance_type"></a> [instance\_type](#input\_instance\_type) | n/a | `string` | `"t2.micro"` | no |
| <a name="input_key_name"></a> [key\_name](#input\_key\_name) | n/a | `string` | n/a | yes |
| <a name="input_kms_Key_db_Name"></a> [kms\_Key\_db\_Name](#input\_kms\_Key\_db\_Name) | n/a | `string` | `"HnS-insight-db-keys"` | no |
| <a name="input_layer"></a> [layer](#input\_layer) | n/a | `string` | `"data"` | no |
| <a name="input_lgriffiths_ssh_key"></a> [lgriffiths\_ssh\_key](#input\_lgriffiths\_ssh\_key) | n/a | `string` | `""` | no |
| <a name="input_liquibase_instance_tag_name"></a> [liquibase\_instance\_tag\_name](#input\_liquibase\_instance\_tag\_name) | n/a | `string` | `"hns-insight-liquibase-srv"` | no |
| <a name="input_liquibase_server_name"></a> [liquibase\_server\_name](#input\_liquibase\_server\_name) | n/a | `string` | `"hns-tst-insight-liquibase-srv"` | no |
| <a name="input_liquibase_user"></a> [liquibase\_user](#input\_liquibase\_user) | #The user we create to login on MQSQL workbench and have rights over all databases but not root access | `string` | `"liquibase_usr"` | no |
| <a name="input_liquibase_user_password"></a> [liquibase\_user\_password](#input\_liquibase\_user\_password) | n/a | `string` | `"pass7b5"` | no |
| <a name="input_mailgun_authPassword"></a> [mailgun\_authPassword](#input\_mailgun\_authPassword) | Mailgun credentials | `string` | `"M_authpass "` | no |
| <a name="input_mailgun_authUser"></a> [mailgun\_authUser](#input\_mailgun\_authUser) | Mailgun credentials | `string` | `"api"` | no |
| <a name="input_mailgun_baseURL"></a> [mailgun\_baseURL](#input\_mailgun\_baseURL) | URL of the mailgun api | `string` | `"https://api.mailgun.net/"` | no |
| <a name="input_mailgun_default-pass"></a> [mailgun\_default-pass](#input\_mailgun\_default-pass) | Mailgun credentials | `string` | `"mailgunpass"` | no |
| <a name="input_mailgun_default-user"></a> [mailgun\_default-user](#input\_mailgun\_default-user) | Mailgun credentials | `string` | `"api"` | no |
| <a name="input_mailgun_default_domain"></a> [mailgun\_default\_domain](#input\_mailgun\_default\_domain) | mailgun api user | `string` | `"tazio24.com"` | no |
| <a name="input_mailgun_domain"></a> [mailgun\_domain](#input\_mailgun\_domain) | Default domain to be used within mailgun | `string` | `"tazio24.com"` | no |
| <a name="input_mailgun_secret_name"></a> [mailgun\_secret\_name](#input\_mailgun\_secret\_name) | Mailgun secret name | `string` | `"hns-insights-mailgun"` | no |
| <a name="input_mailgun_version"></a> [mailgun\_version](#input\_mailgun\_version) | Version of mailgun to use | `string` | `"3"` | no |
| <a name="input_mailgun_webhookKey"></a> [mailgun\_webhookKey](#input\_mailgun\_webhookKey) | Webhook to receive notifications on certain events | `string` | `" "` | no |
| <a name="input_port"></a> [port](#input\_port) | n/a | `string` | `"443"` | no |
| <a name="input_private_subnet"></a> [private\_subnet](#input\_private\_subnet) | n/a | `string` | `""` | no |
| <a name="input_product"></a> [product](#input\_product) | n/a | `string` | `"assessments"` | no |
| <a name="input_project"></a> [project](#input\_project) | n/a | `string` | `"insight"` | no |
| <a name="input_public_subnet"></a> [public\_subnet](#input\_public\_subnet) | n/a | `string` | `""` | no |
| <a name="input_rds_backup_window"></a> [rds\_backup\_window](#input\_rds\_backup\_window) | n/a | `string` | `"03:00-06:00"` | no |
| <a name="input_rds_deletion_protection"></a> [rds\_deletion\_protection](#input\_rds\_deletion\_protection) | rds\_deletion\_protection | `string` | `"false"` | no |
| <a name="input_rds_identifier"></a> [rds\_identifier](#input\_rds\_identifier) | n/a | `string` | `"insight-db"` | no |
| <a name="input_rds_maintenance_window"></a> [rds\_maintenance\_window](#input\_rds\_maintenance\_window) | n/a | `string` | `"sat:08:10-sat:08:40"` | no |
| <a name="input_rds_multizone"></a> [rds\_multizone](#input\_rds\_multizone) | n/a | `bool` | `false` | no |
| <a name="input_rds_port"></a> [rds\_port](#input\_rds\_port) | rds port | `string` | `"3306"` | no |
| <a name="input_rds_public_access"></a> [rds\_public\_access](#input\_rds\_public\_access) | rds public access | `string` | `"false"` | no |
| <a name="input_rds_secret_name"></a> [rds\_secret\_name](#input\_rds\_secret\_name) | n/a | `string` | `"insight_db"` | no |
| <a name="input_rds_skip_final_snapshot"></a> [rds\_skip\_final\_snapshot](#input\_rds\_skip\_final\_snapshot) | rds\_skip\_final\_snapshot | `string` | `"true"` | no |
| <a name="input_rds_storage_encrypted"></a> [rds\_storage\_encrypted](#input\_rds\_storage\_encrypted) | n/a | `bool` | `true` | no |
| <a name="input_rds_storage_type"></a> [rds\_storage\_type](#input\_rds\_storage\_type) | rds storage type | `string` | `"gp2"` | no |
| <a name="input_rds_username"></a> [rds\_username](#input\_rds\_username) | rds username | `string` | `"insight_db"` | no |
| <a name="input_region"></a> [region](#input\_region) | n/a | `string` | `"us-east-2"` | no |
| <a name="input_rotation_interval"></a> [rotation\_interval](#input\_rotation\_interval) | n/a | `number` | `30` | no |
| <a name="input_rotator-lambda-role_tag_name"></a> [rotator-lambda-role\_tag\_name](#input\_rotator-lambda-role\_tag\_name) | n/a | `string` | `"HnS-rotator-lambda-role"` | no |
| <a name="input_rtool-s3_policy_tag_name"></a> [rtool-s3\_policy\_tag\_name](#input\_rtool-s3\_policy\_tag\_name) | n/a | `string` | `"HnS-rclone-tool-s3-access-policy"` | no |
| <a name="input_s3_policy_tag_name"></a> [s3\_policy\_tag\_name](#input\_s3\_policy\_tag\_name) | n/a | `string` | `"HnS-EC2-S3Access-policy"` | no |
| <a name="input_saville_hs_secret_name"></a> [saville\_hs\_secret\_name](#input\_saville\_hs\_secret\_name) | Credential for H&S saville account | `string` | `"hns-insights-saville-db"` | no |
| <a name="input_secret_layer"></a> [secret\_layer](#input\_secret\_layer) | n/a | `string` | `"access"` | no |
| <a name="input_ssl_cert"></a> [ssl\_cert](#input\_ssl\_cert) | n/a | `string` | `"test-insights_heidrickdigital_com"` | no |
| <a name="input_ssl_policy"></a> [ssl\_policy](#input\_ssl\_policy) | n/a | `string` | `"ELBSecurityPolicy-FS-1-2-Res-2020-10"` | no |
| <a name="input_storage"></a> [storage](#input\_storage) | n/a | `number` | `20` | no |
| <a name="input_subnet_group"></a> [subnet\_group](#input\_subnet\_group) | subnets group for rds db HA | `string` | `"hd-insights-db-subnetgp"` | no |
| <a name="input_subnets_ids"></a> [subnets\_ids](#input\_subnets\_ids) | n/a | `list(any)` | <pre>[<br>  "subnet-",<br>  "subnet-"<br>]</pre> | no |
| <a name="input_super_user"></a> [super\_user](#input\_super\_user) | #The user we create to login on MQSQL workbench and have rights over all databases but not root access | `string` | `"hns-insights-db-super_usr"` | no |
| <a name="input_super_user_password"></a> [super\_user\_password](#input\_super\_user\_password) | n/a | `string` | `"pqassg655"` | no |
| <a name="input_tags"></a> [tags](#input\_tags) | naming eg hns-PROJECT-APPLICATION-type | `string` | `"hns-PROJECT-APPLICATION-type"` | no |
| <a name="input_target_group_name_blue"></a> [target\_group\_name\_blue](#input\_target\_group\_name\_blue) | n/a | `string` | `"test-insight-tg-blue"` | no |
| <a name="input_target_group_name_green"></a> [target\_group\_name\_green](#input\_target\_group\_name\_green) | n/a | `string` | `"test-insight-tg-green"` | no |
| <a name="input_traffic_distribution"></a> [traffic\_distribution](#input\_traffic\_distribution) | Levels of traffic distribution | `string` | `"blue"` | no |
| <a name="input_vpc_id"></a> [vpc\_id](#input\_vpc\_id) | n/a | `string` | `"vpc-0e99a5961a71f5a48"` | no |
| <a name="input_vpc_security_group_ids"></a> [vpc\_security\_group\_ids](#input\_vpc\_security\_group\_ids) | n/a | `any` | n/a | yes |
| <a name="input_vstsagentpackage"></a> [vstsagentpackage](#input\_vstsagentpackage) | n/a | `string` | `"https://vstsagentpackage.azureedge.net/agent/2.211.1/vsts-agent-linux-x64-2.211.1.tar.gz"` | no |
| <a name="input_wild_card_certs_s3_location"></a> [wild\_card\_certs\_s3\_location](#input\_wild\_card\_certs\_s3\_location) | n/a | `string` | `""` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_ec2_websrv_blue_private_ip"></a> [ec2\_websrv\_blue\_private\_ip](#output\_ec2\_websrv\_blue\_private\_ip) | ec2 instance private ip address |
| <a name="output_ec2_websrv_green_private_ip"></a> [ec2\_websrv\_green\_private\_ip](#output\_ec2\_websrv\_green\_private\_ip) | ec2 instance private ip address |
| <a name="output_key_arn"></a> [key\_arn](#output\_key\_arn) | n/a |
| <a name="output_loadbalancer_dns"></a> [loadbalancer\_dns](#output\_loadbalancer\_dns) | application load balancer dns |
| <a name="output_rds_endpoint"></a> [rds\_endpoint](#output\_rds\_endpoint) | rds endpoint |
<!-- END_TF_DOCS -->
