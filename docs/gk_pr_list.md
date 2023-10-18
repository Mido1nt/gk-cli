## gk pr list

Display every open pull request from the repositories within a workspace

```
gk pr list [flags]
```

### Examples

```
  # Perform a 'gk workspace prs' command without any filters
  $ gk pr list

  # Filter by the title of the PRs
  $ gk pr list --title pr_Title

  # Filter by title, author, and created date (DD-MM-YY, DD/MM/YY or DD.MM.YY)
  $ gk pr list origin --title pr_Title --opened-by userName --created-after 20-01-2022
```

### Options

```
  -i, --assigned-to strings       Filter pull requests by assigned users
  -a, --created-after string      Filter pull requests created after a certain date (DD-MM-YY, DD/MM/YY or DD.MM.YY)
  -b, --created-before string     Filter pull requests created before a certain date (DD-MM-YY, DD/MM/YY or DD.MM.YY)
  -h, --help                      help for list
  -d, --is-draft                  Filter pull requests whether they are drafts or not
  -m, --mention-to string         Filter pull requests by mentioned user
  -o, --opened-by string          Filter pull requests by who has opened them
  -r, --review-requested string   Filter pull requests by reviewers
  -s, --select-ws                 Skip the default workspace for this action and force a workspace selection
  -t, --title string              Filter pull requests by title
  -u, --updated-before string     Filter pull requests updated before a certain date (DD-MM-YY, DD/MM/YY or DD.MM.YY)
```

### SEE ALSO

* [gk pr](gk_pr.md)	 - List and view pull requests

###### Auto generated by spf13/cobra on 18-Oct-2023