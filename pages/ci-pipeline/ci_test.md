---
title: testing
keywords: CI pipeline
sidebar: product1_sidebar
toc: true
permalink: ci_test.html
summary: "Use the CI pipeline to automatically test and verify your TACO file."
folder: ci-pipeline
---

To test your connector, you must tag a commit with a version and then commit the tag to the repo.
## Create a release
When you [create a tag](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/managing-commits/managing-tags) for your connector, you start the CI pipeline. The results of the pipeline are emailed to the address you [configured earlier](./ci_configuration.html).

## Monitor the job

<!-- Include email, attachments (possibly show example of each), and also add section for Tuning/Fixing problems. -->


## Verify the results

To verify your results, you can do either of the following:

* Use the validation result email to get the submission ID.
<img src="images/connectivity_ci_pipeline_email.jpg" alt="" />
* Use the Tableau workbook.
<img src="images/connectivity_ci_workbook.png" alt="" />
