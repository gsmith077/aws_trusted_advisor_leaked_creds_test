# aws_trusted_advisor_leaked_creds_tes

Re: AWS Audit Control 8.2.4 - Create solution for AWS Trusted Advisor Check: Exposed Access Key

The following leaked keys have explicit deny all policies attached, and are being used to test mechanisms to meet the control as per requirements.

## User A:

Don't worry, the below keys have an explicit deny * * policy attached. This is exposed to assist in working around the Trusted Advisor checks, as per [This repo](https://github.com/aws/Trusted-Advisor-Tools/blob/master/ExposedAccessKeys/README.md).

- AKIA3EJ2KHUUIKDS4ICZ
- medeaXbupJgpnbDXhokk6ftcL4FSKHYDaIDuRytt


It looks like the autoataed quartine action only occurs once on a given key-pair, regardless of whether it's been deactivated and reactived, or the quarantine policy has been removed.

- AKIA3EJ2KHUUFBYWFAPP
- i1ZKdu6DoBnOBRdPCk1GcUvzmv2HV5GDAWg+ncDR

## User B:

- AKIAXXGJ2GM2WF3MVLNC
- ih+qFgU29oNkIkaPIK9kDi+a2xbvQQRlLwRHt6Qd



