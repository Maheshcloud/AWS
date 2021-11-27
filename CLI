We can get the access_key_id and secret_access_key under # ~/.aws/config

If we want to configure two different profiles, then use below commands:

```sh
aws configure set profile.example.aws_access_key_id myid
aws configure set profile.example.aws_secret_access_key mysecret
aws configure set profile.example.region us-west-1
```

This results in the following.

```sh
# ~/.aws/config

[default]
region = us-west-1
output = json

[profile example]
region = us-west-1

# ~/.aws/credentials

[default]
aws_access_key_id = <YOUR_AWS_ACCESS_KEY>
aws_secret_access_key = <YOUR_AWS_SECRET_KEY>	

[example]
aws_access_key_id = myid
aws_secret_access_key = mysecret
```
