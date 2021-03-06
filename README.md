## Ansible Missing Collection 
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/116davinder/ansible.missing_collection/CI%20Testing)
![Lines of code](https://img.shields.io/tokei/lines/github/116davinder/ansible.missing_collection)
![GitHub contributors](https://img.shields.io/github/contributors/116davinder/ansible.missing_collection)
![GitHub all releases](https://img.shields.io/github/downloads/116davinder/ansible.missing_collection/total)

It will host all new modules which doesn't exists in Official Ansible Collections and takes years to publish something new. Anyone who wan't to contribute, please feel free to create PR / Bug Report / Feature Request.

## Why this repository exists ?
Ansible Community reviewers takes too much time and have too hard restrictions.
So I decided to host modules on my repository instead of ansible.

**Examples:**
* [Official Ansible PR: 1](https://github.com/ansible/ansible/pull/40029)
* [Official Ansible PR: 2](https://github.com/ansible-collections/community.general/pull/876)
* [Official Ansible PR: 3](https://github.com/ansible-collections/community.general/pull/1501)
* [Official Ansible PR: 4](https://github.com/ansible-collections/community.aws/pull/305)

**Articles**
* https://116davinder.medium.com/story-of-unsuccessful-pr-to-open-source-project-da78db20613

## Notes
* **master** branch is always under-development, please tags for production use.
* [easy_dev.sh](https://github.com/116davinder/ansible.missing_collection/blob/master/easy_dev.sh)
  It is being used for local basic testing.

<!--start requires_ansible-->
## Ansible version compatibility

This collection has been tested against following Ansible versions: **>=2.9.10**.

Plugins and modules within a collection may be tested with only specific Ansible versions.
A collection may contain metadata that identifies these versions.
PEP440 is the schema used to describe the versions of Ansible.
<!--end requires_ansible-->

## How to Install Ansible Missing Collection
```bash
$ ansible-galaxy collection install git+https://github.com/116davinder/ansible.missing_collection.git
Starting galaxy collection install process
Process install dependency map
Starting collection install process
Installing 'community.missing_collection:0.0.7' to '/home/dpal/.ansible/collections/ansible_collections/community/missing_collection'
Created collection for community.missing_collection at /home/dpal/.ansible/collections/ansible_collections/community/missing_collection
community.missing_collection (0.0.7) was installed successfully

$ ansible-galaxy collection list
Collection                   Version
---------------------------- -------
community.missing_collection 0.0.7

```

<!--start collection content-->
### Modules
Name | Description
--- | ---
[community.missing_collection.aws_amp](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_amp_module.rst)|Create / Update AWS Prometheus Service.
[community.missing_collection.aws_amp_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_amp_info_module.rst)|Get details about AWS Prometheus Service.
[community.missing_collection.aws_api_gateway_management_api](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_api_gateway_management_api_module.rst)|Manage Resources of Amazon API Gateway Management API.
[community.missing_collection.aws_api_gateway_management_api_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_api_gateway_management_api_info_module.rst)|Get details about Amazon API Gateway Management API.
[community.missing_collection.aws_api_gateway_v2_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_api_gateway_v2_info_module.rst)|Get details about AWS API Gateway V2 Service.
[community.missing_collection.aws_app_integrations_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_app_integrations_info_module.rst)|Get details about Amazon AppIntegrations Service.
[community.missing_collection.aws_appflow_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_appflow_info_module.rst)|Get details about AWS AppFlow Service.
[community.missing_collection.aws_application_auto_scaling_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_application_auto_scaling_info_module.rst)|Get details about AWS Application Auto Scaling.
[community.missing_collection.aws_application_insights_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_application_insights_info_module.rst)|Get details about Amazon CloudWatch Application Insights.
[community.missing_collection.aws_appmesh_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_appmesh_info_module.rst)|Get details about AWS App Mesh Service.
[community.missing_collection.aws_appstream_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_appstream_info_module.rst)|Get details about Amazon AppStream 2.0.
[community.missing_collection.aws_athena_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_athena_info_module.rst)|Get Information about AWS Athena.
[community.missing_collection.aws_auditmanager_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_auditmanager_info_module.rst)|Get details about AWS Audit Manager.
[community.missing_collection.aws_autoscaling_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_autoscaling_info_module.rst)|Get details about Amazon EC2 Auto Scaling.
[community.missing_collection.aws_autoscaling_plans_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_autoscaling_plans_info_module.rst)|Get details about AWS Auto Scaling Plans.
[community.missing_collection.aws_backup_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_backup_info_module.rst)|Get Information about AWS Backup.
[community.missing_collection.aws_batch_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_batch_info_module.rst)|Get details about AWS Batch.
[community.missing_collection.aws_cloud9_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_cloud9_info_module.rst)|Get details about AWS Cloud9 Environments.
[community.missing_collection.aws_cloudfront_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_cloudfront_info_module.rst)|Get details about Amazon CloudFront.
[community.missing_collection.aws_cloudhsm_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_cloudhsm_info_module.rst)|Get details about Amazon CloudHSM.
[community.missing_collection.aws_cloudhsm_v2_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_cloudhsm_v2_info_module.rst)|Get details about Amazon CloudHSM V2.
[community.missing_collection.aws_cloudsearch_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_cloudsearch_info_module.rst)|Get details about Amazon CloudSearch.
[community.missing_collection.aws_cloudtrail_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_cloudtrail_info_module.rst)|Get Information about AWS Cloudtrail.
[community.missing_collection.aws_cloudwatch_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_cloudwatch_info_module.rst)|Get Information about AWS CloudWatch.
[community.missing_collection.aws_codeartifact_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_codeartifact_info_module.rst)|Get Information about AWS Code Artifact.
[community.missing_collection.aws_codebuild_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_codebuild_info_module.rst)|Get Information about AWS Code Build.
[community.missing_collection.aws_codecommit_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_codecommit_info_module.rst)|Get Information about AWS Code Commit.
[community.missing_collection.aws_codeguru_reviewer_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_codeguru_reviewer_info_module.rst)|Get Information about AWS Codeguru Reviewer.
[community.missing_collection.aws_codeguruprofiler_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_codeguruprofiler_info_module.rst)|Get Information about Amazon CodeGuru Profiler.
[community.missing_collection.aws_codepipeline_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_codepipeline_info_module.rst)|Get Information about AWS CodePipeline.
[community.missing_collection.aws_codestar_connections_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_codestar_connections_info_module.rst)|Get Information about AWS CodeStar Connections.
[community.missing_collection.aws_codestar_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_codestar_info_module.rst)|Get Information about AWS CodeStar.
[community.missing_collection.aws_codestar_notifications_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_codestar_notifications_info_module.rst)|Get Information about AWS CodeStar Notifications.
[community.missing_collection.aws_cognito_identity_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_cognito_identity_info_module.rst)|Get Information about Amazon Cognito Identity.
[community.missing_collection.aws_cognito_idp_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_cognito_idp_info_module.rst)|Get Information about Amazon Cognito Identity Provider.
[community.missing_collection.aws_cognito_sync_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_cognito_sync_info_module.rst)|Get Information about Amazon Cognito Sync.
[community.missing_collection.aws_comprehend_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_comprehend_info_module.rst)|Get Information about Amazon Comprehend.
[community.missing_collection.aws_comprehendmedical_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_comprehendmedical_info_module.rst)|Get Information about Amazon Comprehend Medical.
[community.missing_collection.aws_compute_optimizer_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_compute_optimizer_info_module.rst)|Get Information about AWS Compute Optimizer.
[community.missing_collection.aws_config_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_config_info_module.rst)|Get Information about AWS Config.
[community.missing_collection.aws_connect_contact_lens_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_connect_contact_lens_info_module.rst)|Get Information about Amazon Connect Contact Lens.
[community.missing_collection.aws_connect_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_connect_info_module.rst)|Get Information about Amazon Connect.
[community.missing_collection.aws_connectparticipant_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_connectparticipant_info_module.rst)|Get Information about Amazon Connect Participant Service.
[community.missing_collection.aws_cur_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_cur_info_module.rst)|Get Information about AWS Cost and Usage Report Service.
[community.missing_collection.aws_customer_profiles_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_customer_profiles_info_module.rst)|Get Information about Amazon Connect Customer Profiles.
[community.missing_collection.aws_databrew_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_databrew_info_module.rst)|Get Information about AWS Glue DataBrew.
[community.missing_collection.aws_dataexchange_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_dataexchange_info_module.rst)|Get Information about AWS Data Exchange.
[community.missing_collection.aws_datapipeline_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_datapipeline_info_module.rst)|Get Information about AWS Data Pipeline.
[community.missing_collection.aws_datasync_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_datasync_info_module.rst)|Get Information about AWS DataSync.
[community.missing_collection.aws_dax_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_dax_info_module.rst)|Get Information about AWS Dax.
[community.missing_collection.aws_detective_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_detective_info_module.rst)|Get Information about AWS detective.
[community.missing_collection.aws_devicefarm_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_devicefarm_info_module.rst)|(WIP) Get Information about AWS Device Farm.
[community.missing_collection.aws_devops_guru_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_devops_guru_info_module.rst)|Get Information about AWS Device Guru.
[community.missing_collection.aws_directconnect_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_directconnect_info_module.rst)|Get Information about AWS Direct Connect.
[community.missing_collection.aws_discovery_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_discovery_info_module.rst)|Get Information about AWS Application Discovery Service.
[community.missing_collection.aws_dlm_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_dlm_info_module.rst)|Get Information about Amazon Data Lifecycle Manager.
[community.missing_collection.aws_dms_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_dms_info_module.rst)|Get Information about AWS Database Migration Service.
[community.missing_collection.aws_docdb_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_docdb_info_module.rst)|Get Information about Amazon DocumentDB.
[community.missing_collection.aws_ds_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_ds_info_module.rst)|Get Information about AWS Directory Service.
[community.missing_collection.aws_dynamodb_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_dynamodb_info_module.rst)|Get Information about Amazon DynamoDB.
[community.missing_collection.aws_dynamodbstreams_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_dynamodbstreams_info_module.rst)|Get Information about Amazon DynamoDB Streams.
[community.missing_collection.aws_ebs_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_ebs_info_module.rst)|Get Information about Amazon Elastic Block Store (EBS).
[community.missing_collection.aws_ecr_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_ecr_info_module.rst)|Get Information about Amazon EC2 Container Registry (ECR).
[community.missing_collection.aws_ecr_public_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_ecr_public_info_module.rst)|Get Information about Amazon Elastic Container Registry Public (ECR Public).
[community.missing_collection.aws_ecs_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_ecs_info_module.rst)|Get Information about Amazon EC2 Container Service (ECS).
[community.missing_collection.aws_eks_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_eks_info_module.rst)|Get Information about AWS EKS.
[community.missing_collection.aws_elastic_inference_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_elastic_inference_info_module.rst)|Get Information about Amazon Elastic Inference (Elastic Inference).
[community.missing_collection.aws_elasticbeanstalk_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_elasticbeanstalk_info_module.rst)|Get Information about AWS Elastic Beanstalk.
[community.missing_collection.aws_elastictranscoder_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_elastictranscoder_info_module.rst)|Get Information about Amazon Elastic Transcoder.
[community.missing_collection.aws_elbv2_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_elbv2_info_module.rst)|Get Information about Amazon Elastic Load Balancing (Elastic Load Balancing v2).
[community.missing_collection.aws_emr_containers_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_emr_containers_info_module.rst)|Get Information about Amazon EMR Containers.
[community.missing_collection.aws_emr_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_emr_info_module.rst)|Get Information about Amazon Elastic MapReduce (EMR).
[community.missing_collection.aws_es_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_es_info_module.rst)|Get Information about Amazon Elasticsearch Service.
[community.missing_collection.aws_events_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_events_info_module.rst)|Get Information about Amazon EventBridge.
[community.missing_collection.aws_firehose_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_firehose_info_module.rst)|Get Information about Amazon Firehose.
[community.missing_collection.aws_fms_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_fms_info_module.rst)|Get Information about Firewall Management Service (FMS).
[community.missing_collection.aws_forecast_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_forecast_info_module.rst)|Get Information about Amazon Forecast Service.
[community.missing_collection.aws_frauddetector_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_frauddetector_info_module.rst)|Get Information about Amazon Fraud Detector.
[community.missing_collection.aws_fsx_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_fsx_info_module.rst)|Get Information about Amazon FSx.
[community.missing_collection.aws_gamelift_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_gamelift_info_module.rst)|Get Information about Amazon Gamelift.
[community.missing_collection.aws_glacier_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_glacier_info_module.rst)|Get Information about Amazon Glacier.
[community.missing_collection.aws_globalaccelerator_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_globalaccelerator_info_module.rst)|Get Information about Amazon Global Accelerator.
[community.missing_collection.aws_glue_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_glue_info_module.rst)|Get Information about Amazon Glue.
[community.missing_collection.aws_greengrassv2_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_greengrassv2_info_module.rst)|Get Information about Amazon Green Grass V2.
[community.missing_collection.aws_groundstation_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_groundstation_info_module.rst)|Get Information about AWS Ground Station.
[community.missing_collection.aws_guardduty_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_guardduty_info_module.rst)|Get Information about Amazon GuardDuty.
[community.missing_collection.aws_health_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_health_info_module.rst)|Get Information about Amazon Health.
[community.missing_collection.aws_healthlake_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_healthlake_info_module.rst)|Get Information about Amazon Health Lake.
[community.missing_collection.aws_honeycode_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_honeycode_info_module.rst)|Get Information about Amazon Honey Code.
[community.missing_collection.aws_iam_access_analyzer_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_iam_access_analyzer_info_module.rst)|Get Information about AWS IAM Access Analyzer.
[community.missing_collection.aws_identitystore_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_identitystore_info_module.rst)|Get Information about AWS SSO Identity Store (IdentityStore).
[community.missing_collection.aws_imagebuilder_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_imagebuilder_info_module.rst)|Get Information about EC2 Image Builder (imagebuilder).
[community.missing_collection.aws_importexport_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_importexport_info_module.rst)|Get Information about AWS Import/Export.
[community.missing_collection.aws_inspector_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_inspector_info_module.rst)|Get Information about Amazon Inspector.
[community.missing_collection.aws_ivs_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_ivs_info_module.rst)|Get Information about Amazon Interactive Video Service (IVS).
[community.missing_collection.aws_kafka_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_kafka_info_module.rst)|Get Information about Amazon MSK cluster.
[community.missing_collection.aws_kendra_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_kendra_info_module.rst)|Get Information about AWS KendraFrontendService.
[community.missing_collection.aws_kinesis_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_kinesis_info_module.rst)|Get Information about Amazon Kinesis.
[community.missing_collection.aws_kinesis_video_archived_media_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_kinesis_video_archived_media_info_module.rst)|Get Information about Amazon Kinesis Video Streams Archived Media.
[community.missing_collection.aws_kinesis_video_signaling_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_kinesis_video_signaling_info_module.rst)|Get Information about Amazon Kinesis Video Signaling Channels.
[community.missing_collection.aws_kinesisanalytics_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_kinesisanalytics_info_module.rst)|Get Information about Amazon Kinesis Analytics.
[community.missing_collection.aws_kinesisanalyticsv2_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_kinesisanalyticsv2_info_module.rst)|Get Information about Amazon Kinesis Analytics V2.
[community.missing_collection.aws_kinesisvideo_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_kinesisvideo_info_module.rst)|Get Information about Amazon Kinesis Video Streams.
[community.missing_collection.aws_kms_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_kms_info_module.rst)|Get Information about AWS KMS.
[community.missing_collection.aws_lakeformation_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_lakeformation_info_module.rst)|Get Information about AWS Lake Formation.
[community.missing_collection.aws_lex_runtime_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_lex_runtime_info_module.rst)|Get Information about Amazon Lex Runtime Service.
[community.missing_collection.aws_lexv2_runtime_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_lexv2_runtime_info_module.rst)|Get Information about Amazon Lex Runtime Service (V2).
[community.missing_collection.aws_license_manager_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_license_manager_info_module.rst)|Get Information about AWS License Manager.
[community.missing_collection.aws_lightsail_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_lightsail_info_module.rst)|Get Information about Amazon Lightsail.
[community.missing_collection.aws_location_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_location_info_module.rst)|Get Information about Amazon Location Service.
[community.missing_collection.aws_logs_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_logs_info_module.rst)|Get Information about Amazon CloudWatch Logs.
[community.missing_collection.aws_lookoutvision_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_lookoutvision_info_module.rst)|Get Information about Amazon Lookout for Vision.
[community.missing_collection.aws_machinelearning_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_machinelearning_info_module.rst)|Get Information about Amazon Machine Learning.
[community.missing_collection.aws_macie2_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_macie2_info_module.rst)|Get Information about Amazon Macie 2.
[community.missing_collection.aws_macie_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_macie_info_module.rst)|Get Information about Amazon Macie.
[community.missing_collection.aws_managedblockchain_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_managedblockchain_info_module.rst)|Get Information about Amazon Managed Blockchain.
[community.missing_collection.aws_marketplace_catalog_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_marketplace_catalog_info_module.rst)|Get Information about AWS Marketplace Catalog Service.
[community.missing_collection.aws_marketplace_entitlement_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_marketplace_entitlement_info_module.rst)|Get Information about AWS Marketplace Entitlement Service.
[community.missing_collection.aws_mediaconnect_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_mediaconnect_info_module.rst)|Get Information about AWS Elemental MediaConnect.
[community.missing_collection.aws_mediaconvert_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_mediaconvert_info_module.rst)|Get Information about AWS Elemental MediaConvert.
[community.missing_collection.aws_medialive_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_medialive_info_module.rst)|Get Information about AWS Elemental MediaLive.
[community.missing_collection.aws_mediapackage_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_mediapackage_info_module.rst)|Get Information about AWS Elemental MediaPackage.
[community.missing_collection.aws_mediapackage_vod_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_mediapackage_vod_info_module.rst)|Get Information about AWS Elemental Mediapackage Vod.
[community.missing_collection.aws_mediastore_data_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_mediastore_data_info_module.rst)|Get Information about AWS Elemental Mediastore Data.
[community.missing_collection.aws_mediastore_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_mediastore_info_module.rst)|Get Information about AWS Elemental MediaStore.
[community.missing_collection.aws_sns_platform_endpoint_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_sns_platform_endpoint_info_module.rst)|Get Information about AWS SNS Platforms.
[community.missing_collection.aws_sns_platform_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_sns_platform_info_module.rst)|Get Information about AWS SNS Platforms.
[community.missing_collection.aws_sns_subscriptions_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_sns_subscriptions_info_module.rst)|Get Information about AWS SNS Subscriptions.
[community.missing_collection.aws_sqs_queue_info](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_sqs_queue_info_module.rst)|Get information about AWS SQS queues.
[community.missing_collection.aws_ssm_parameter_store](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.aws_ssm_parameter_store_module.rst)|Manage key-value pairs in aws parameter store.
[community.missing_collection.mapr_service](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.mapr_service_module.rst)|Manage MapR Services by rest api.
[community.missing_collection.newrelic_deployment](https://github.com/116davinder/ansible.missing_collection/blob/master/docs/community.missing_collection.newrelic_deployment_module.rst)|Notify newrelic about app deployments via v2 api.

<!--end collection content-->

### Install ansible automatic doc creation tool ?
```bash
$ pip3 install git+https://github.com/ansible-network/collection_prep.git
```

### Generate docs from ansible tool ?
```bash
$ collection_prep_add_docs -p . -b master
INFO      Setting collection name to community.missing_collection
INFO      Setting GitHub repository url to https://github.com/116davinder/ansible.missing_collection
INFO      Purging content from directory /home/dpal/python-projects/ansible.missing_collection/docs
INFO      Making docs directory /home/dpal/python-projects/ansible.missing_collection/docs
INFO      Process content in /home/dpal/python-projects/ansible.missing_collection/plugins/modules
INFO      Processing /home/dpal/python-projects/ansible.missing_collection/plugins/modules/aws_amp_info.py
..............
INFO      Processing 'modules' for README
ERROR     README.md not found in ./ansible.missing_collection
ERROR     README.md not updated
```
