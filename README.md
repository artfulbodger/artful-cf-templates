# CloudFormation Templates
AWS CloudFormation provides a common language for you to model and provision AWS and third party application resources in your cloud environment.  CloudFormation Templates help you to define your Cloud Infrastructure as code.

#### AWS
- SecurityHubXRAggregator
-- Creates a cross-Region aggregator in the current Region
#### Rapid7
- Rapid7AssetSyncEC2Role
-- Creates the EC2 instance role required by the Security Console EC2 instance to connect to the AWS API for AWS Asset Sync feature
- Rapid7CrossAccountAssetSyncRole
-- Creates the Role to enable Cross Account Asset Sync.  Requires the AWS Account number where the Security Console is hosted