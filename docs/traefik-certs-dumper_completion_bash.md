## traefik-certs-dumper completion bash

Generate the autocompletion script for bash

### Synopsis

Generate the autocompletion script for the bash shell.

This script depends on the 'bash-completion' package.
If it is not installed already, you can install it via your OS's package manager.

To load completions in your current shell session:

	source <(traefik-certs-dumper completion bash)

To load completions for every new session, execute once:

#### Linux:

	traefik-certs-dumper completion bash > /etc/bash_completion.d/traefik-certs-dumper

#### macOS:

	traefik-certs-dumper completion bash > $(brew --prefix)/etc/bash_completion.d/traefik-certs-dumper

You will need to start a new shell for this setup to take effect.


```
traefik-certs-dumper completion bash
```

### Options

```
  -h, --help              help for bash
      --no-descriptions   disable completion descriptions
```

### Options inherited from parent commands

```
      --clean              Clean destination folder before dumping content. (default true)
      --config string      config file (default is $HOME/.traefik-certs-dumper.yaml)
      --crt-ext string     The file extension of the generated certificates. (default ".crt")
      --crt-name string    The file name (without extension) of the generated certificates. (default "certificate")
      --dest string        Path to store the dump content. (default "./dump")
      --domain-subdir      Use domain as sub-directory.
      --key-ext string     The file extension of the generated private keys. (default ".key")
      --key-name string    The file name (without extension) of the generated private keys. (default "privatekey")
      --post-hook string   Execute a command only if changes occurs on the data source. (works only with the watch mode)
      --watch              Enable watching changes.
```

### SEE ALSO

* [traefik-certs-dumper completion](traefik-certs-dumper_completion.md)	 - Generate the autocompletion script for the specified shell

###### Auto generated by spf13/cobra on 21-Feb-2025
