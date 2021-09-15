# aws_trusted_advisor_leaked_creds_tes

Re: AWS Audit Control 8.2.4 - Create solution for AWS Trusted Advisor Check: Exposed Access Key

The following leaked keys have explicit deny all policies attached, and are being used to test mechanisms to meet the control as per requirements.

## User A:

Don't worry, the below keys have an explicit deny * * policy attached. This is exposed to assist in working around the Trusted Advisor checks, as per [This repo](https://github.com/aws/Trusted-Advisor-Tools/blob/master/ExposedAccessKeys/README.md).

Keys removed.


It looks like the autoataed quartine action only occurs once on a given key-pair, regardless of whether it's been deactivated and reactived, or the quarantine policy has been removed.

## User B:

Keys removed.
