{{indexmenu_n>1}}

====== list ======

## ucloud firewall list

List extranet firewall

### Synopsis

List extranet firewall

```
ucloud firewall list [flags]
```

### Options

```
  --region     string                Optional. Region, see 'ucloud region' (default "cn-bj2") 

  --project-id     string            Optional. Project-id, see 'ucloud project list' (default
                                     "org-ryrmms") 

  --firewall-id     string           Optional. The Rsource ID of firewall. Return all
                                     firewalls by default. 

  --bound-resource-type     string   Optional. The type of resource bound on the firewall 

  --bound-resource-id     string     Optional. The resource ID of resource bound on the firewall 

  --offset     string                Optional. Offset (default "0") 

  --limit     string                 Optional. Limit (default "50") 

  --help, -h                         help for list 

```

### Options inherited from parent commands

```
  --debug, -d   Running in debug mode 

  --json, -j    Print result in JSON format whenever possible 

```

### SEE ALSO

* [ucloud firewall](software/cli/cmd/ucloud/firewall)	 - List and manipulate extranet firewall
