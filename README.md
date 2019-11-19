# Templates

This repo contains some common templates to make team communication clear and more effecient. It includes,

- commit templates
- pull request templates
- code review replies

## Commit Templates

The git commit template (.gitmessage) is set in your git configuration.
```
[commit]
  template = ~/path/to/.gitmessage
```

## Pull Request Templates

GitHub uses a [template](https://help.github.com/en/github/building-a-strong-community/creating-a-pull-request-template-for-your-repository) when they exist in your repository. You can place the pull_request_template.md in a .github folder in the root of your repository.

## Code Review Replies

The replies folder contains some categorization for common issues in pull requests. The categories are based on Google's best [practices](https://google.github.io/eng-practices/review/). You can configure them as [replies in github](https://help.github.com/en/github/writing-on-github/using-saved-replies).


### Other Useful Configuration

The following is a list of other useful configuration for teams.

#### Stories
```
As a <personas>, I want <a goal> so that <benefit>.
```

#### Labels
Labels in github work best if they are categoriezed by color.

| **Theme**   | Label                | Color   |
| ----------- | -------------------- | ------- |
| Status      | Development          | #0075ca |
| Status      | Design               | #0075ca |
| Status      | Requirements         | #0075ca |
| Blocker     | Blocked: Product     | #d73a4a |
| Blocker     | Blocked: Development | #d73a4a |
| Blocker     | Blocked: Test        | #d73a4a |
| Defect      | Bug                  | #CCCC4E |
| Defect      | Security             | #CCCC4E |
| Type        | Feature              | #7057ff |
| Type        | Chore                | #7057ff |
| Type        | Bug                  | #7057ff |
| Improvement | Refactor             | #cfd3d7 |
| Improvement | Usability            | #cfd3d7 |
| Improvement | Optimization         | #cfd3d7 |
| Filler      | < 15                 | #f9bdd4 |
| Filler      | < 30                 | #f9bdd4 |
| Filler      | < 45                 | #f9bdd4 |


#### Slack

In slack, it is often difficult to determine who has ownership of a group message. A good way to handle this is by making a [triage channel](https://slack.com/help/articles/360000384726-prioritize-tasks-quickly-with-triage-channels).

There are a few rules of a triage channel. 

1. All messages in the root are categorized.
2. Each day a 👩‍✈️ is assigned to categorize and respond to issues. 
3. People agree to use some common emojis to indicate the status of an item. 

##### Categories

A team can agree to the categories that work best for them. Here are some suggestions. 

- ❓{ General question }
- 🐛 { Bug report }
- 😂 { Fun }
- 🛑 { Blocker }
- 📘 { Today I learned }
- 🔥 { Emergency }

The channel captain is responsible for adding 👀 when they are looking at an issue and a ✅ when it is resolved. The channel captain will thread all responses and can reach out for additional help.