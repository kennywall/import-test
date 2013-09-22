---
layout: post
title: "New Billing Structure for Amazon Web Services (AWS)"
url: 'http://kinlane.com/2010/02/12/new-billing-structure-for-amazon-web-services-aws/'
image: ''
---

[Amazon Web Services][1] has added a new and more flexible way to manage an account. They have added the ability for:

  * Consolidated billing across multiple AWS accounts
  * Volume pricing across more than one AWS account
  * Way to track the cost of a project across an organization.
The new billing feature lets you designate one AWS account as a _paying_ account and a set of other accounts as _linked_ accounts to form a simple one-level hierarchy. The AWS usage within the linked accounts is rolled up into the paying account for volume pricing and billing purposes, so there's just one AWS bill per month.

The account relationship is solely for accounting purposes and normal AWS permissions still apply. You can set up AWS accounts for projects, departments, dev/test/staging/production, or even by employee. You can add up to twenty linked accounts to a single paying account.

These features will do a lot to address the needs of larger customers.. Later this year [Amazon Web Services][1] is planning to provide additional functionality to allow linking of accounts and user permissions.

   [1]: http://aws.amazon.com/
