# aws_trusted_advisor_leaked_creds_test

AWS MSP Audit Control 8.9

This is used as the trigger mechanism to test the requirement to respond to leaked keys in AWS.

The following leaked keys have explicit deny all policies attached, and are being used to test 
mechanisms to meet the control as per requirements.

These keys are exposed to assist in working around the Trusted Advisor checks, as per 
[This repo](https://github.com/aws/Trusted-Advisor-Tools/blob/master/ExposedAccessKeys/README.md).

## User A:

User name: `audit-8.9-cred-leaker`

Acess key ID: `AKIATAZ6CVQ55KK7LEJE`

Secret access key: `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`

