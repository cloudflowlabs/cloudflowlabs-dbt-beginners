### Welcome to cloudflowlabs dbt project! 

This repository is used in CloudFlow Lab's multi-part series: [DBT for Data Engineering: A Beginner's Guide ](https://www.youtube.com/watch?v=5B4FhKVEvYg)

### Prerequisites

- Access to a terminal or command prompt.
- Have Python installed on your machine. You can check if Python is installed by running `python --version` or `python3 --version` in your terminal or command prompt.
- Have pip installed. You can check if pip is installed by running `pip --version` or `pip3 --version`.
- Have the necessary permissions to create directories and install packages on your machine.
- Clone this repository locally
- Once you've met the prerequisites, follow the steps [in Part 1](https://www.youtube.com/watch?v=5B4FhKVEvYg&list=PLrVIpYK81ITHalkgmzGJzMGexY56xfnPO) to set up your virtual environment.


### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [dbt community](https://getdbt.com/community) to learn from other analytics engineers
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices

# Welcome to zero to dbt from dbt Labs!
The purpose of this project is to demonstrate common patterns and use cases for dbt!!

We're going to get hands on, do some rapid learning, and get you soaring on your dbt journey!

Quick Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](http://slack.getdbt.com/) on Slack for live discussions and best practices
- Find [dbt events](https://events.getdbt.com) near you

Would you rather just get started with dbt Cloud and skip the lab? [Just say hello and we'll take it from there.](https://getdbt.com/contact)


**TASK** - please do this one little thing:
- in your project, create a file called `packages.yml`. Place this file in the same folder as your `dbt_project.yml`, aka - in the root of the project.
- if you're not able to add or edit files, make sure you're not on the `main` branch of your project - check the big green button in the editor at the top left under `Version Control`. If it prompts you to create a branch, go ahead and do that now and try again.
- Paste in the following yaml and then save the file. Don't forget to save!!

```yaml
packages:
  - git: https://github.com/dbt-labs/2023-04-18---zero-to-dbt.git
```
- When you save `packages.yml` (do NOT forget to save this file hahaha), you'll see an error in the editor. That is NORMAL - all part of the process 🤘
- An alert should pop up asking you to run `dbt deps`. Please click it. Deps = dependencies. It'll install the base project for today's session.
- If you don't see a form pop up, don't panic. In the dbt command line at the bottom of the IDE, go ahead and run `dbt deps`.
- If you have any issues, we'll help you - just let us know in the chat.

From here, it's smooth sailing ⛵ - we'll work through everything together LIVE.

And just like before, we'll send recordings for this portion

## Section 3 - free play!
Let's do something fun with the new tools you have. Take a look at the dbt Docs we just built and see if you can find something interesting to build.

Here are the ground rules:
- build for your curiosity - not for your job
- start small. Preview data, ask a question, get an answer, ask a new question, repeat 🔄
- Starving for inspiration? Check out kaggle.com for CSV data sets - download, drop in your `seeds` directory, and run `dbt seed` to get started

We'll spend some time letting folks work and doing open Q&A. 