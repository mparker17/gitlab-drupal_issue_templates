# gitlab-drupal_issue_templates

[Drupal issue summary templates](https://www.drupal.org/issue-summaries) in [Gitlab](https://gitlab.com/) format.

Like these templates, but use Git**hub** instead? Check out [mparker17/github-drupal_issue_templates](https://github.com/mparker17/github-drupal_issue_templates).

I work a lot in the Drupal ecosystem, and I find Drupal's [issue summary templates](https://www.drupal.org/issue-summaries) helpful, and I'd like to be able to use them on Gitlab projects.

Gitlab supports arbitrary [issue and merge request description templates](https://git.echidna.ca/help/user/project/description_templates.md).

This project takes Drupal's issue summary templates, converts them to Markdown, and stores them in the `.gitlab` folder to make it easy for you to copy them to your own project.

## Setup

1. Clone this repository to your computer.

		git clone https://github.com/mparker17/gitlab-drupal_issue_templates.git /path/to/this/repo

## Use

1. Copy the `.gitlab` folder into your project.

		cp /path/to/this/repo/.gitlab /path/to/your/project
