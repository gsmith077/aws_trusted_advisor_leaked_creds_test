# aws_trusted_advisor_leaked_creds_test

AWS MSP Audit Control 8.9

This is used as the trigger mechanism to test the requirement to respond to leaked keys in AWS.

The following leaked keys have explicit deny all policies attached, and are being used to test 
mechanisms to meet the control as per requirements.

These keys are exposed to assist in working around the Trusted Advisor checks, as per 
[This repo](https://github.com/aws/Trusted-Advisor-Tools/blob/master/ExposedAccessKeys/README.md).

It appears that changes to the secret scanning may have changed the detection. Enabled on repo, this push is to trigger detection.

https://github.blog/2022-12-15-leaked-a-secret-check-your-github-alerts-for-free/

## User A:

User name: `leaked_key_test`

Acess key ID: AKIATAZ6CVQ5YAQGXOUR

Secret access key: t6Y9WjL2cNp1PQgkx77m2Mtk4r2pl

