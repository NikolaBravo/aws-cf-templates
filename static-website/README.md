# aws-cf-templates

## Static website

Use the `static-website.json` template to create the infrastructure for hosting a static website. 

### Architecture

![Architecture](./static-website.png?raw=true "Architecture")

### Components

#### AWS services

* S3: object storage
* CloudFront: CDN
* Route53: DNS names

### Installation Guide

1. Download the template [static-website.json](https://raw.githubusercontent.com/widdix/aws-cf-templates/master/static-website/static-website.json)
1. Open AWS CloudFormation within the Management Console: [https://console.aws.amazon.com/cloudformation](https://console.aws.amazon.com/cloudformation).
1. Create a new stack by clicking on the **Create Stack** button.
1. Select **Upload a template to Amazon S3** and upload the template `static-website.json`.
1. Click **Next** to proceed with the next step of the wizard.
1. Specify a name and all parameters for the stack.
1. Click **Next** to proceed with the next step of the wizard.
1. Click **Next** to skip the **Options** step of the wizard.
1. Check the **I acknowledge that this template might cause AWS CloudFormation to create IAM resources.** checkbox.
1. Click **Create** to start the creation of the stack.
1. Wait until the stack reaches the state **CREATE_COMPLETE**

## Support needed?

Do you need help?

[![Contact Andreas on Codementor](https://cdn.codementor.io/badges/contact_me_github.svg)](https://www.codementor.io/andreaswittig) Andreas Wittig or [![Contact Michael on Codementor](https://cdn.codementor.io/badges/contact_me_github.svg)](https://www.codementor.io/michaelwittig) Michael Wittig
