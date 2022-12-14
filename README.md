# GitHub Actions and Terraform to provision AWS EC2 instance, with Slack notification

## Repository Overview
This repository was set up as part of a demonstration for a Devops course presentation.

## Project Details
* Goal: Use GitHub Actions and Terraform to provision AWS EC2 instance, with Slack notification.
  * Only provisions (EC2 and Slack notification) when .tf files are pushed (e.g. doesn't when .txt file is pushed) from a specified directory
  * EC2 is named via the yaml file
* Referred to the following two tutorials:
  * For Slack integration: https://blog.searce.com/automating-terraform-with-github-actions-5b3aac5abea7
  * For EC2 instance provisioning: https://medium.com/everything-full-stack/use-github-actions-and-terraform-to-provision-ec2-instance-5b51636e4e54
  * Both links helped with GitHub Actions and Terraform provisioning
