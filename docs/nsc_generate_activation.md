## nsc generate activation

Generate an export activation jwt token

### Synopsis

Generate an export activation jwt token

```
nsc generate activation [flags]
```

### Options

```
  -a, --account string          account name
      --expiry string           valid until ('0' is always, '2M' is two months) - yyyy-mm-dd, #m(inutes), #h(ours), #d(ays), #w(eeks), #M(onths), #y(ears) (default "0")
  -h, --help                    help for activation
  -o, --output-file string      output file '--' is stdout (default "--")
      --push                    push activation token to operator's account server (exclusive of output-file
      --start string            valid from ('0' is always, '3d' is three days) - yyyy-mm-dd, #m(inutes), #h(ours), #d(ays), #w(eeks), #M(onths), #y(ears) (default "0")
  -s, --subject string          export subject
  -t, --target-account string   target-account
```

### Options inherited from parent commands

```
  -i, --interactive          ask questions for various settings
  -K, --private-key string   private key
```

### SEE ALSO

* [nsc generate](nsc_generate.md)	 - Generate activations, creds, configs or nkeys

###### Auto generated by spf13/cobra on 26-Nov-2019
