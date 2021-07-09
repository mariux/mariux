[<img src="https://raw.githubusercontent.com/mineiros-io/brand/3bffd30e8bdbbde32c143e2650b2faa55f1df3ea/mineiros-primary-logo.svg" width="800"/>][github]

---

[![Join Slack][badge-slack]][slack]

# The easiest way to run infrastructure on [<img src="https://upload.wikimedia.org/wikipedia/commons/9/93/Amazon_Web_Services_Logo.svg" width="50">](https://github.com/mineiros-io)
## Built on Terraform, Mineiros enables teams to deploy and manage reusable, tested and secure infrastructure on AWS in days instead of months.

***All our modules support Terraform v0.15, v0.14, v0.13 as well as v0.12.20 and above and are ready for the upcoming releases.***

**NEW** We also offer payed **PROFESSIONAL SUPPORT** for our open source library and exclusive previews on upcoming modules check out our full catalogue and pricing: [Terraform Library](https://www.mineiros.io/solutions/terraform-library#pricing).


   [![get professional support now][cta]](https://www.mineiros.io/solutions/terraform-library#pricing)


### Mineiros AWS Terraform Modules

[![Terraform Version][badge-terraform]][releases-terraform]
[![AWS Provider Version][badge-tf-aws]][releases-aws-provider]

*All Terraform AWS Modules are compatible with the Terraform AWS Provider v3 as well as v2.*

#### Compute, Containers, and Serverless
- [terraform-aws-lambda-function](https://github.com/mineiros-io/terraform-aws-lambda-function)
- terraform-aws-ec2-instance *(coming next)*
- terraform-aws-eks-cluster *(coming next)*
- terraform-aws-eks-node-group *(coming next)*
- terraform-aws-ecs *(coming next)*

#### Storage, Databases, and Cache
- [terraform-aws-s3-bucket](https://github.com/mineiros-io/terraform-aws-s3-bucket)
- [terraform-aws-dynamodb](https://github.com/mineiros-io/terraform-aws-dynamodb)
- terraform-aws-rds *(coming soon)*
- terraform-aws-elasticsearch-domain *(coming next)*

#### Identity and Access Management (IAM)
- [terraform-aws-iam-user](https://github.com/mineiros-io/terraform-aws-iam-user)
- [terraform-aws-iam-group](https://github.com/mineiros-io/terraform-aws-iam-group)
- [terraform-aws-iam-role](https://github.com/mineiros-io/terraform-aws-iam-role)
- [terraform-aws-iam-policy](https://github.com/mineiros-io/terraform-aws-policy)

#### Infratsructure and Networking
- [terraform-aws-vpc](https://github.com/mineiros-io/terraform-aws-vpc)
- [terraform-aws-route53](https://github.com/mineiros-io/terraform-aws-route53)
- terraform-aws-eip *(coming next)*
- terraform-aws-security-group *(coming next)*
- terraform-aws-cloudfront *(coming next)*
- terraform-aws-elb *(coming soon)*

#### Services
- [terraform-aws-ecr](https://github.com/mineiros-io/terraform-aws-ecr)
- [terraform-aws-cognito-user-pool](https://github.com/mineiros-io/terraform-aws-cognito-user-pool)
- terraform-aws-ses *(coming next)*
- terraform-aws-acm *(coming next)*

#### AWS Landing Zone
- terraform-aws-organizations
- terraform-aws-iam-account
- terraform-aws-kms
- terraform-aws-cloudtrail
- terraform-aws-config
- terraform-aws-guard-duty
- terraform-aws-cloudwatch
- terraform-aws-security-hub

### Mineiros Github Terraform Modules

[![Terraform Version][badge-terraform14]][releases-terraform]
[![GitHub Provider Version][badge-tf-gh]][releases-github-provider]

*All Terraform Github Modules are compatible with the Terraform GitHub Provider v3 as well as v2 and support Terraform v1*

- [terraform-github-organization](https://github.com/mineiros-io/terraform-github-organization)
- [terraform-github-repository](https://github.com/mineiros-io/terraform-github-repository)
- [terraform-github-team](https://github.com/mineiros-io/terraform-github-team)

[cta]: https://dabuttonfactory.com/button.png?t=GET+PROFESSIONAL+SUPPORT+NOW!&f=Roboto-Bold&ts=20&tc=444&hp=26&vp=17&c=9&bgt=unicolored&bgc=f90&be=1&bs=2&bc=444

[github]: https://github.com/mineiros-io
[badge-slack]: https://img.shields.io/badge/slack-@mineiros--community-f32752.svg?logo=slack
[slack]: https://join.slack.com/t/mineiros-community/shared_invite/zt-ehidestg-aLGoIENLVs6tvwJ11w9WGg

[badge-terraform]: https://img.shields.io/static/v1?label=Terraform&message=v0.13%20|%20v0.12.20%2b&color=623CE4&logo=terraform&logoColor=623CE4&labelColor=ccc
[badge-terraform14]: https://img.shields.io/static/v1?label=Terraform&message=v0.15%20|%20v0.14%20|%20v0.13%20|%20v0.12.20%2b&color=623CE4&logo=terraform&logoColor=623CE4&labelColor=ccc
[releases-terraform]: https://github.com/hashicorp/terraform/releases

[badge-tf-aws]: https://img.shields.io/static/v1?label=AWS%20Provider&message=v3%20|%20v2&color=F8991D&logo=amazon&logoColor=000&labelColor=ccc
[releases-aws-provider]: https://github.com/terraform-providers/terraform-provider-aws/releases

[badge-tf-gh]: https://img.shields.io/static/v1?label=Github%20Provider&message=v4%20|%20v3%20|%20v2&color=000&logo=github&logoColor=000&labelColor=ccc
[releases-github-provider]: https://github.com/terraform-providers/terraform-provider-github/releases
