# Rapid 7
#### CloudFormation Templates to set up IAM roles and policies
- Rapid7AssetSyncEC2Role
  - Creates the EC2 instance role required by the Security Console EC2 instance to connect to the AWS API for AWS Asset Sync feature
- Rapid7CrossAccountAssetSyncRole
  - Creates the Role to enable Cross Account Asset Sync.  Requires the AWS Account number where the Security Console is hosted