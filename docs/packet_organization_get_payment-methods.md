## packet organization get payment-methods

Retrieves a list of payment methods for the organization

### Synopsis

Example:

packet organization get payment-methods --id [organization_UUID]



```
packet organization get payment-methods [flags]
```

### Options

```
  -h, --help        help for payment-methods
  -i, --id string   UUID of the organization
```

### Options inherited from parent commands

```
      --config string     Path to JSON or YAML configuration file
      --exclude strings   Comma seperated Href references to collapse in results, may be dotted three levels deep
      --include strings   Comma seperated Href references to expand in results, may be dotted three levels deep
  -j, --json              JSON output
      --search string     Search keyword for use in 'get' actions. Search is not supported by all resources.
  -y, --yaml              YAML output
```

### SEE ALSO

* [packet organization get](packet_organization_get.md)	 - Retrieves an organization or list of organizations

