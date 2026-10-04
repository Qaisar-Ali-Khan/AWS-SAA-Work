S3 Object Access Control Using IAM Policies

Overview

In this lab, I created an S3 bucket containing two objects: "cats" and "dogs", using AWS CloudFormation.

Initially, access to both objects was denied by default.

Lab Procedure

1. Initial Access Denied

By default, the user was unable to access or modify either object.



![Initial Access Denied](initial-denied.png)



2. IAM Policy Through CloudFormation

I created an IAM policy using CloudFormation that allowed access to the "dogs" object while keeping access to the "cats" object restricted.



![Selective Object Access](selective-access.png)



3. Manually Attached Inline Policy

Afterward, I manually attached another inline IAM policy that granted access to both objects, allowing them to be accessed and modified.



![Inline Policy Attached](inline-policy.png)

What I Learned

- How IAM policies control access to S3 objects.
- How CloudFormation can create IAM policies.
- The difference between access granted through a CloudFormation-managed policy and a manually attached inline policy.
- How permissions can be restricted or expanded based on policy statements.
