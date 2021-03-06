## glab issue create

Create an issue

### Synopsis

Create an issue

```
glab issue create [flags]
```

### Options

```
  -a, --assignee string      Assign issue to people by their ID. Multiple values should be comma separated 
  -c, --confidential         Set an issue to be confidential. Default is false
  -d, --description string   Supply a description for issue
  -h, --help                 help for create
  -l, --label string         Add label by name. Multiple labels should be comma separated
      --linked-mr int        The IID of a merge request in which to resolve all issues (default -1)
  -m, --milestone int        The global ID of a milestone to assign issue (default -1)
      --no-editor            Don't open editor to enter description. If set to true, uses prompt. Default is false
  -t, --title string         Supply a title for issue
  -w, --weight int           The weight of the issue. Valid values are greater than or equal to 0. (default -1)
```

### Options inherited from parent commands

```
  -R, --repo string   Select another repository using the OWNER/REPO format or the project ID. Supports group namespaces
```

### SEE ALSO

* [glab issue](glab_issue.md)	 - Create, view and manage remote issues

###### Auto generated by spf13/cobra on 31-Aug-2020
