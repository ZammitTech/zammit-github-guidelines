# GitHub Guidelines

A set of guidelines to follow when working on any project/task for Zammit.

## Branches

Follow this while creating any new branch based on task type (feature, fix, etc..)

`task-type/clickup-ticket-id/meaningful-name-in-lower-case`

#### Examples
- Env. setup: `chore/ZAM-0000/mantine-setup`
- New feature: `feat/ZAM-1111/layout-setup`
- Bug fix: `fix/ZAM-2222/colors-dropdown-position`
- Urgent bug fix: `hotfix/ZAM-3333/tappy-missing-keys`
- Refactor: `refactor/ZAM-4444/separate-form-into-components`

## Branching 

There're two types of tasks & each one should follow a specific branching style

- *Single task*:  
only create a single branch with PR into whatever (dev/staging/master)
- *Parent task with multiple sub-tasks*:   
here we create a parent branch & subbranch for each sub-task & subbranches PRs to be into the parent branch

#### Examples

- Single task: `feat/ZAM-000/add-tappy-setup`
- Parent task:             

  - Parent branch: `feat/ZAM-111/layout-setup`
  - Sub-task branch: `feat/ZAM-222/header`
  - Sub-task branch: `feat/ZAM-333/sidebar`
  - Sub-task branch: `feat/ZAM-444/footer`

## Pull requests

Follow this while creating any new pull request

- Add Meaningful PR title, check [this](#commits)
- Add yourself as assignee 
- Add one or more reviewers
- Make sure build passed successfully before merge
- Don't ever merge without an approval from any reviewer
- Use `squash & merge` except for staging & master use `merge`


## Commits

Follow this for both PR titles and any commit in general

`task-type: [clickup-ticket-id] describe commits in two or more words`

#### Examples
- Env. setup: `chore: [ZAM-0000] setup mantinte`
- New feature: `feat: [ZAM-1111] layout setup including header, sidebar & footer`
- Bug fix: `fix: [ZAM-2222] change colors dropdown position`
- Urgent bug fix: `hotfix: [ZAM-3333] add tappy missing keys`
- Refactor: `refactor: [ZAM-4444] separate address form into components`

## Usful links

- Check this link for branchs, PRs and commits types: [commit type](https://mazer.dev/en/git/best-practices/git-semantic-commits/#type)



