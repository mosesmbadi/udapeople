### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool


## Description
Fully Configured CI/CD Pipeline for AWS.

## Workflow
When code changes are pushed to github, it triggers a build, test and deploy process.
This process is managed in CircleCi which notifies you when the build is finished succeffully or if it failed.
The Deploy process involves setting up the infrastructure in AWS. This is done entirely by CloudFormation.
Finaly, the process ends with a configuration of monitoring system done by Prometheus.



### License

[License](LICENSE.md)
