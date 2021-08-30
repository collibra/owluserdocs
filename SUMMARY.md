# Table of contents

* [Collibra Data Quality](README.md)
* [Release Notes](release-notes.md)
* [Our Approach](why-owl.md)
* [Our Story](our-story.md)
* [What is OwlDQ](what-is-owldq.md)
* [Get Started](assessment.md)

## Installation

* [Basic Install](installation/basic-install.md)
* [Full Standalone Install](installation/full-install.md)
* [Hadoop Integration](installation/hadoop-integration.md)
* [Agent Configuration](installation/agent-configuration.md)

## Cloud Hadoop Deployment

* [EMR / Dataproc / HDI](cloud-hadoop-deployment/emr.md)

## Cloud Native Deployment

* [AKS / EKS / GKE: Kubernetes Deployment](cloud-native-deployment/aks-eks-gke-kubernetes-deployment.md)
* [Cloud Native OwlDQ](cloud-native-deployment/cloud-native-owldq.md)
* [Preparing for Cloud Native Deployment](cloud-native-deployment/preparing-for-deployment.md)
* [Deploying Cloud Native OwlDQ](cloud-native-deployment/deploying-cloud-native-owldq.md)

## DQ JOB Examples

* [DQ Job JDBC](dq-job-examples/job-jdbc.md)
* [DQ Job Hive](dq-job-examples/job-hive.md)
* [DQ Job Files](dq-job-examples/job-files.md)
* [DQ Job JSON](dq-job-examples/job-json.md)
* [DQ Job Kafka](dq-job-examples/job-kafka.md)
* [DQ Job MySql](dq-job-examples/job-mysql.md)
* [Data Quality Pipelines](dq-job-examples/data-quality-pipelines/README.md)
  * [Simple Spark Data Pipeline](dq-job-examples/data-quality-pipelines/simple-spark-data-pipeline.md)
  * [Notebook Outlier Example](dq-job-examples/data-quality-pipelines/notebook-outlier-example.md)
  * [Notebook ColMatch Example](dq-job-examples/data-quality-pipelines/notebook-colmatch-example.md)
  * [Owl Options API](dq-job-examples/data-quality-pipelines/owl-options-api.md)
  * [Owl Rules - DQ Pipeline](dq-job-examples/data-quality-pipelines/owl-rules-dq-pipeline/README.md)
    * [Global rules](dq-job-examples/data-quality-pipelines/owl-rules-dq-pipeline/global-rules.md)
    * [SQL based rules](dq-job-examples/data-quality-pipelines/owl-rules-dq-pipeline/sql-based-rules/README.md)
      * [Simple rule](dq-job-examples/data-quality-pipelines/owl-rules-dq-pipeline/sql-based-rules/simple-rule.md)
      * [Freeform SQL](dq-job-examples/data-quality-pipelines/owl-rules-dq-pipeline/sql-based-rules/freeform-sql.md)
      * [Native SQL](dq-job-examples/data-quality-pipelines/owl-rules-dq-pipeline/sql-based-rules/native-sql.md)
      * [Function](dq-job-examples/data-quality-pipelines/owl-rules-dq-pipeline/sql-based-rules/function.md)
    * [Data type based rules](dq-job-examples/data-quality-pipelines/owl-rules-dq-pipeline/data-type-based-rules.md)
    * [FAQs](dq-job-examples/data-quality-pipelines/owl-rules-dq-pipeline/frequently-asked-questions.md)
  * [AWS DataBricks - DQ Pipeline](dq-job-examples/data-quality-pipelines/aws-databricks-dq-pipeline.md)
  * [Azure DataBricks - DQ Pipeline](dq-job-examples/data-quality-pipelines/azure-databricks-dq-pipeline.md)
  * [Spark - DQ Pipeline](dq-job-examples/data-quality-pipelines/spark-dq-pipeline.md)
* [OwlCheck Spark](dq-job-examples/owlcheck-spark.md)
* [OwlCheck Databricks](dq-job-examples/owlcheck-databricks.md)
* [OwlCheck Cron](dq-job-examples/owlcheck-cron.md)
* [OwlCheck Snowflake](dq-job-examples/owlcheck-snowflake.md)
* [OwlCheck BigQuery](dq-job-examples/owlcheck-bigquery.md)
* [OwlCheck S3](dq-job-examples/owlcheck-s3.md)
* [OwlCheck HDFS](dq-job-examples/owlcheck-hdfs.md)
* [OwlCheck MongoDB](dq-job-examples/owlcheck-mongodb.md)
* [OwlCheck Zeppelin](dq-job-examples/owlcheck-zeppelin.md)
* [OwlCheck LinkId](dq-job-examples/owlcheck-linkid.md)
* [OwlCheck Back Run](dq-job-examples/owlcheck-backrun.md)
* [OwlCheck Validate Source](dq-job-examples/owlcheck-validate-source.md)
* [OwlCheck 43M rows](dq-job-examples/owlcheck-43m-rows.md)
* [OwlCheck Transform](dq-job-examples/owlcheck-transform.md)
* [More...](dq-job-examples/owlcheck/README.md)
  * [OwlCheck JSON](dq-job-examples/owlcheck/owlcheck-json.md)

## How OwlDQ <a id="projects"></a>

* [Builds a Better DQ Dashboard](projects/builds-a-better-dq-dashboard.md)
* [Ensures CCPA & GDPR](projects/ccpa-and-gdpr.md)
* [Makes your Data Lake better.](projects/data-quality-monitoring.md)
* [Speeds Migrations/Enables Replications](projects/migrations.md)
* [Assists Data Aggregation](projects/assists-data-aggregation.md)

## Security

* [Owl Security](security/owl-security/README.md)
  * [Authentication With Active Directory LDAP](security/owl-security/authentication-with-active-directory-ldap/README.md)
    * [AD Group to Owl Role Mapping](security/owl-security/authentication-with-active-directory-ldap/ad-group-to-owl-role-mapping.md)
  * [Authentication with SAML IDP](security/owl-security/authentication-with-saml-idp.md)
  * [Authentication With Local User Store](security/owl-security/authentication-with-local-user-store/README.md)
    * [Adding Local Users](security/owl-security/authentication-with-local-user-store/adding-local-users.md)
  * [Role Based Access Control \(RBAC\)](security/owl-security/role-based-access-control-rbac.md)
  * [Connection Security](security/owl-security/connection-security.md)
  * [Dataset Security](security/owl-security/dataset-security.md)
  * [Dataset Masking](security/owl-security/dataset-masking.md)

## Scorecards

* [Dataset Scorecard](scorecards/dataset-scorecard.md)
* [Group Scorecard](scorecards/group-scorecard.md)
* [List View](scorecards/list-view.md)

## Connecting to DBs in Owl Web

* [Supported Drivers](connecting-to-dbs-in-owl-web/supported-drivers.md)
* [Owl DB Connection](connecting-to-dbs-in-owl-web/owl-db-connection/README.md)
  * [Connecting to CDH 5.16 Hive SSL/TLS/Kerberos Setup](connecting-to-dbs-in-owl-web/owl-db-connection/connecting-to-cdh-5.16-hive-ssl-tls-kerberos-setup.md)

## Core Components <a id="dq-visuals"></a>

* [Overview](dq-visuals/overview.md)
* [Profile](dq-visuals/profile/README.md)
  * [AutoProfile](dq-visuals/profile/autoprofile.md)
* [Behaviors](dq-visuals/behaviors.md)
* [Schema Evolution](dq-visuals/schema-evolution.md)
* [Outliers](dq-visuals/outliers.md)
* [Shapes](dq-visuals/shapes.md)
* [Validate Source](dq-visuals/validate-source.md)
* [Rules](dq-visuals/rules/README.md)
  * [Easier Rule Examples](dq-visuals/rules/easier-rule-examples.md)
  * [The best DQ rule, is the one you don't have to write](dq-visuals/rules/dq-rule-automation.md)
  * [Creating a Business Rule](dq-visuals/rules/creating-a-business-rule.md)
* [Duplicates](dq-visuals/duplicates.md)
* [Explorer](dq-visuals/explorer.md)
* [Explorer 2](dq-visuals/explorer-2.md)
* [Pattern Mining](dq-visuals/pattern-mining/README.md)
  * [Bloomberg Data](dq-visuals/pattern-mining/bloomberg-data.md)
* [Missing Records](dq-visuals/missing-records.md)

## Integration

* [Collibra Native DQ Connector](integration/dq-connector.md)

## Labeling / Training

* [Item Labeling](labeling-training/item-labeling.md)
* [Peak vs Off Peak](labeling-training/peak-vs-off-peak.md)

## Graph

* [Process Dependency](graph/process-dependency.md)
* [Dataset Dependency](graph/dataset-dependency.md)

## ARTICLES <a id="creating-a-data-quality-pipeline"></a>

* [Creating a Data Quality Pipeline](creating-a-data-quality-pipeline/creating-a-data-quality-pipeline.md)

## APIs

* [Swagger](apis/swagger.md)
* [Job Server](apis/job-server.md)
* [Custom Configurations](apis/custom-configurations.md)
* [Notebook API](apis/notebook-api/README.md)
  * [OwlOptions \(base\)](apis/notebook-api/owloptions-base.md)

## Catalog

* [Catalog](catalog/catalog.md)
* [Catalog Bulk Actions](catalog/catalog-bulk-actions.md)
* [Cluster Health Report](catalog/cluster-health-report.md)

## Use-Cases

* [Bank Loans](use-cases/bank-loans.md)
* [Financial FxRate Data](use-cases/financial-fxrate-data.md)
* [Intraday Positions](use-cases/intraday-positions.md)
* [Security Reference Data](use-cases/security-reference-data.md)
* [Copying or Moving data](use-cases/copying-or-moving-data.md)
* [Cyber Anomalies in Real-Time](use-cases/cyber-anomalies-in-real-time.md)

## Owl Time

* [Owl Time Zone API](owl-time/owl-time-zone-api.md)

## Alerts

* [Email Alerts](alerts/email-alerts.md)

## Troubleshooting

* [Cloudera CLASSPATH](troubleshooting/cloudera-classpath.md)
* [Performance Tuning](troubleshooting/performance-tuning.md)
* [Deploy Mode](troubleshooting/deploy-mode.md)

## Advanced

* [Add Date Column](advanced/add-date-column.md)
* [File Look Back](advanced/file-lookback.md)
* [Filter & Filter Not](advanced/filter.md)
* [Multiple Pattern Relationships](advanced/multiple-pattern-combinations.md)
* [Nulls in Datasets](advanced/zero-if-null.md)
* [Transform Expressions](advanced/transform.md)
* [Prescriptive Personas](advanced/prescriptive-personas.md)

## Multi-Tenant

* [Multi-Tenancy](multi-tenant/multi-tenancy.md)

## Reports

* [Completeness Report](reports/completeness-report.md)
* [Owl Summary Reports](reports/owl-summary-reports.md)
* [Dataset Report](reports/profile.md)
* [Coverage Report](reports/coverage-report.md)

## Scheduler

* [Schedule Management](scheduler/schedule-management.md)
* [Schedule Owlchecks](scheduler/schedule-owlchecks.md)
* [View/Re-Run Scheduled Jobs](scheduler/view-re-run-scheduled-jobs.md)

## API-Core <a id="api"></a>

* [Notebook/Spark](api/notebook/README.md)
  * [Spark-shell Sample](api/notebook/spark-shell-sample.md)
  * [Dupe](api/notebook/dupe.md)
  * [Load](api/notebook/load.md)
  * [Source](api/notebook/source.md)
  * [Profile](api/notebook/profile.md)
* [JWT](api/jwt.md)
* [Cookie](api/cookie.md)

---

* [DQ is the difference](data-quality.md)
* [Owl's Scorecard and 9 Dimensions of DQ](owl-dq-screen-shots.md)
* [Best Practices](best-practices.md)
* [Healthcare  Data Quality](healthcare-dq-in-2-minutes.md)
* [Smart Meter Data](smart-meter-data.md)
* [Health Insurance Claims Data](insurance-data.md)

## OBSERVATION ASSIGNMENTS

* [Assignment Queue\(s\)](observation-assignments/assignment-queue-s.md)
* [Internal Assignment](observation-assignments/internal-assignment.md)
* [External Assignment](observation-assignments/external-assignment.md)
* [Business Units](observation-assignments/business-units.md)
* [Assignment API](observation-assignments/assignmentapi.md)
* [ERD](observation-assignments/erd.md)
* [FAQ](observation-assignments/faq.md)

## Benchmarks

* [Performance Tests](benchmarks/performance-tests.md)
* [FAQ](benchmarks/benchmark-faq.md)

## Migration and Promoting

* [Export and Import API](migration-and-promoting/export-and-import-api.md)
* [Rules Import Export](migration-and-promoting/rules-import-export.md)

## Data Retention

* [Time Based Data Retention](data-retention/time-based-data-retention.md)

## REST API

* [APIs](rest-api/apis.md)

