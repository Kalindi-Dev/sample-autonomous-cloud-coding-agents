[//]: # (ABCA-REVIEWED)

# AWS Service Default Quotas

This document lists selected AWS service default quotas (soft limits) as sourced
from the official AWS documentation.

---

## Amazon S3 — Maximum Buckets per Account

| Quota | Default Value |
|-------|--------------|
| General-purpose buckets per AWS account | **10,000** |

**Source:** <https://docs.aws.amazon.com/AmazonS3/latest/userguide/BucketRestrictions.html>

> By default, you can create up to 10,000 general-purpose buckets in each AWS
> account. You can increase the quota to a maximum of 1,000,000 buckets by
> submitting a service quota increase request.

---

## Amazon VPC — Maximum VPCs per Region

| Quota | Default Value |
|-------|--------------|
| VPCs per Region | **5** |

**Source:** <https://docs.aws.amazon.com/vpc/latest/userguide/amazon-vpc-limits.html>

> You can have up to 5 VPCs per Region. You can request an increase for this
> quota.

---

*Note: These are soft limits (adjustable via AWS Service Quotas console or a
support request). Hard limits cannot be increased.*
