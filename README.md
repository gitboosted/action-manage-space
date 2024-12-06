# Manage GitBoosted Space

A GitHub action to manage the upsertion of spaces on GitBoosted.

## How to use

```yaml
- name: Manage space definition in GitBoosted
  uses: gitboosted/action-manage-space
  with:
    apiKey: ${{ secrets.GITBOOSTED_SPACE_API_KEY }}
```
