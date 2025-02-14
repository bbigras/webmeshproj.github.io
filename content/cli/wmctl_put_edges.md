## wmctl put edges

Create or update an edge in the mesh

```
wmctl put edges [NAME] [flags]
```

### Options

```
      --from string    node to add the edge from
  -h, --help           help for edges
      --ice            whether the edge is negotiated over ICE
      --to string      node to add the edge to
      --weight int32   weight of the edge (default 1)
```

### Options inherited from parent commands

```
      --basic-auth-password func     The password for basic authentication
      --basic-auth-username func     The username for basic authentication
      --certificate-authority func   The path to the CA certificate for the cluster connection
      --client-certificate func      The path to the client certificate for the user
      --client-key func              The path to the client key for the user
  -c, --config string                Path to the CLI configuration file
      --context string               The name of the context to use (default "flags")
      --insecure                     Whether TLS should be disabled for the cluster connection
      --ldap-password func           The password for LDAP authentication
      --ldap-username func           The username for LDAP authentication
      --prefer-leader                Whether to prefer the leader node for the cluster connection
      --server string                The URL of the node to connect to
      --tls-skip-verify              Whether TLS verification should be skipped for the cluster connection
```

### SEE ALSO

* [wmctl put](wmctl_put.md)	 - Create or update resources in the mesh

###### Auto generated by spf13/cobra on 5-Aug-2023
