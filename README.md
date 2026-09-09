## Templates

One template per organization issue type. Each template sets the issue type and contains the same "Risk assessment" section.

| File | Issue type | Use for |
|---|---|---|
| `bug.md` | Bug | an unexpected problem or behavior |
| `feature.md` | Feature | a request, an idea, or new functionality |
| `task.md` | Task | a specific piece of work that is not a bug or a feature |
| `epic.md` | Epic | a group of related issues |
| `hotfix.md` | Hotfix | a high-priority fix that goes to customers before the next release |
| `spike.md` | Spike | exploratory work with a time box |

`config.yml` disables blank issues, so each new issue starts from a template.

## How to change a template

1. Open a pull request in this repository.
2. Keep the "Risk assessment" section identical in all templates.
3. After the merge, open a new issue in a repository without its own templates and check the result.
