# Jenkins pipelines on AWS

This project is intended to deploy and run an instance on AWS, configure Jenkins, and run some pipelines that are able to deploy a static website on S3.

## Table of Contents

* [Project Overview](#project-overview)
* [Getting Started](#getting-started)
* [Contributing](#contributing)

## Project Overview

As already mentioned, this projet deploys and runs an instance on AWS, configures Jenkins, and finally runs some pipelines to deploy a static website on S3. The steps taken are as follows:

* A number of steps on AWS, including the creation of a group attaching policies, creation of a user, creation of a new key pair, launching of an instance, creation of a security group, and connection to the instance.
* Installation of Jenkins on Ubuntu.
* Setting up Jenkins.
* Installation of required plugins.
* Setting up GitHub.
* Setting up AWS credentials in Jenkins.
* Setting up an S3 bucket.
* Setting up a pipeline for AWS.
* Adding another stage to the pipeline.

## Getting Started

In this section, it can be seen how the aforementioned steps have been accomplished.

* Firstly, a screenshot is provided which shows the AWS console with the permissions being created.

![screenshot-01.png](/ScreenShots/screenshot-01.png)

* Secondly, the following screenshot shows the unique AWS URL of the EC2 instance.

![screenshot-02.png](/ScreenShots/screenshot-02.png)

* Thirdly, the screenshot below shows the "Unlock Jenkins" screen, at the unique AWS URL of the EC2 instance.

![screenshot-03.png](/ScreenShots/screenshot-03.png)

* In the fourth place, an screenshot is provided that shows the Jenkins sidebar with the Blue Ocean link.

![screenshot-04.png](/ScreenShots/screenshot-04.png)

* In the fifth place, the following screenshot shows the GitHub project as a pipeline.

![screenshot-05.png](/ScreenShots/screenshot-05.png)

* In the sixth place, yet another screenshot is added that shows "index.html" rendered.

![screenshot-06.png](/ScreenShots/screenshot-06.png)

* In the seventh place, the screenshot below shows the failure when linting.

![screenshot-07.png](/ScreenShots/screenshot-07.png)

* Finally, the last screenshot shows passing the linting stage and deploys to S3.

![screenshot-08.png](/ScreenShots/screenshot-08.png)

## Contributing

This repository contains all the work that makes up the project. Individuals and I myself are encouraged to further improve this project. As a result, I will be more than happy to consider any pull requests.
