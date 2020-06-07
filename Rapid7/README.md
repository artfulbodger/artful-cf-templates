# Rapid 7
#### CloudFormation Templates to set up IAM roles and policies
- Rapid7InsightVMSecurityConsoleSingleAccountEC2Role
  - Creates the EC2 instance role required by the Security Console EC2 instance to connect to the AWS API for AWS Asset Sync feature in the same account
- Rapid7AssetSyncMultiAccouuntEC2Role
  - Creates the EC2 instance role required by the Security Console EC2 instance to connect to the AWS API for AWS Asset Sync feature supporting cross account Asset Discovery.
- Rapid7CrossAccountAssetSyncRole
  - Creates the Role to enable Cross Account Asset Sync.  Requires the AWS Account number where the Security Console is hosted