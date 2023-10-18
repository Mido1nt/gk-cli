## gk issue list

Display every issue from the repositories within a workspace.
The limit of displayed issues is affected by the setting "Max display items"

```
gk issue list [flags]
```

### Options

```
  -i, --assigned-to strings     Filter issues by assigned users
  -a, --created-after string    Filter issues created after a certain date (DD-MM-YY, DD/MM/YY or DD.MM.YY)
  -b, --created-before string   Filter issues created before a certain date (DD-MM-YY, DD/MM/YY or DD.MM.YY)
  -h, --help                    help for list
      --jira-org string         If you have multiple Jira organizations connected, specify which one to use for authenticating
  -m, --mention-to string       Filter issues by mentioned user
  -o, --opened-by string        Filter issues by who has opened them
  -s, --select-ws               Skip the default workspace for this action and force a workspace selection
  -t, --title string            Filter issues by title
  -u, --updated-before string   Filter issues updated before a certain date (DD-MM-YY, DD/MM/YY or DD.MM.YY)
```

### SEE ALSO

* [gk issue](gk_issue.md)	 - List and view issues

###### Auto generated by spf13/cobra on 18-Oct-2023