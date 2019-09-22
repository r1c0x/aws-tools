# aws-tools 
Prerequisites <br />
AWS Command Line Interface (AWS CLI) <br />
https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html <br />
Configure the AWS CLI with Your Credentials <br />
https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html

awssh - Tool to ssh login an aws instance with 'Name' tag  <br />
Example: <br />
`awssh uat-nginx-01`

instance-list - Tool to print AWS instance Name tags, id, private and public domain, AZone, instance type, launch time within a target vpc with a pretty table format
Example: <br />
`instance-list 'vpc-aaaaa,vpc-bbbbb'`

instance-list-menu - Fancy menu to ssh into instances, must be using with instance-list
Example: <br />
`instance-list-menu`
