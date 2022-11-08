---
title: Getting Started
weight: 1
---

{{% alert title="Prerequisites" %}}
Before beginning, you will need the following

* A Mezmo account.  You can snag one for free here.
* Docker
* An AWS account with the necessary permission to administer S3 buckets.

{{% /alert %}}

## Overview

In this workshop, we will be managing signals coming in from many simulated edge devices.

To accomplish this we will

* Create a new Pipleline
* Configure an endpoint to receive the data (ie, a Source (LINK TO DOCS))
* Filter unneccesary events
* Encrypt PII in motion
* Store required data in S3

## Final Product

In the end you are going to build a Pipeline that looks like

![Final Pipeline](../../images/final_pipeline.png)

This pipeline will drop unnecsary information from events, encrypt a filtered subset and pass data on to S3 for data engineers.