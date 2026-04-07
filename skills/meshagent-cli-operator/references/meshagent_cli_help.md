# MeshAgent CLI Help

_Packaged CLI help reference for MeshAgent CLI `0.31.4`._

_Generated from the installed `meshagent` binary with recursive `--help` capture up to depth 1 and timeout 2s per command._

## `meshagent`

```console
$ meshagent --help
                                                                                
 Usage: meshagent [OPTIONS] COMMAND [ARGS]...                                   
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ version              Print the version                                       │
│ setup                Perform initial login and project/api key activation.   │
│ call                 Trigger agent/tool calls via URL                        │
│ auth                 Authenticate to meshagent                               │
│ project              Manage or activate your meshagent projects              │
│ api-key              Manage or activate api-keys for your project            │
│ session              Inspect recent sessions and events                      │
│ token                Generate participant tokens (JWTs)                      │
│ webhook              Manage project webhooks                                 │
│ service              Manage services for your project                        │
│ mcp                  Bridge MCP servers into MeshAgent rooms                 │
│ secret               Manage secrets for your project.                        │
│ rooms                Create, list, and manage rooms in a project             │
│ mailbox              Manage mailboxes for your project                       │
│ route                Manage routes for your project                          │
│ scheduled-task       Manage scheduled tasks for your project                 │
│ meeting-transcriber  Join a meeting transcriber to a room                    │
│ port                 Port forwarding into room containers                    │
│ multi                Connect agents and tools to a room                      │
│ voicebot             Join a voicebot to a room                               │
│ process              Join a process-backed agent to a room                   │
│ room                 Operate within a room                                   │
│ image                Build and pack OCI images                               │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent version`

```console
$ meshagent version --help
Usage: meshagent version [OPTIONS]

  Print the version

Options:
  --help  Show this message and exit.
```

## `meshagent setup`

```console
$ meshagent setup --help
Usage: meshagent setup [OPTIONS]

  Perform initial login and project/api key activation.

Options:
  --help  Show this message and exit.
```

## `meshagent call`

```console
$ meshagent call --help
                                                                                
 Usage: meshagent call [OPTIONS] COMMAND [ARGS]...                              
                                                                                
 Trigger agent/tool calls via URL                                               
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ tool     Send a call request to a tool webhook URL                           │
│ agent    Send a call request to an agent webhook URL                         │
│ toolkit  Send a call request to a toolkit webhook URL                        │
│ schema   Send a call request to a schema webhook URL                         │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent auth`

```console
$ meshagent auth --help
                                                                                
 Usage: meshagent auth [OPTIONS] COMMAND [ARGS]...                              
                                                                                
 Authenticate to meshagent                                                      
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ login                                                                        │
│ logout                                                                       │
│ whoami                                                                       │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent project`

```console
$ meshagent project --help
                                                                                
 Usage: meshagent project [OPTIONS] COMMAND [ARGS]...                           
                                                                                
 Manage or activate your meshagent projects                                     
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ create    Create a new MeshAgent project.                                    │
│ list      List projects and mark the currently active one.                   │
│ activate  Set the active project for subsequent CLI commands.                │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent api-key`

```console
$ meshagent api-key --help
                                                                                
 Usage: meshagent api-key [OPTIONS] COMMAND [ARGS]...                           
                                                                                
 Manage or activate api-keys for your project                                   
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ list      List API keys for a project.                                       │
│ create    Create a new API key for a project.                                │
│ show      Show the activated API key for a project.                          │
│ env       Print the activated API key as a shell export snippet.             │
│ activate  Set the default API key for a project in local CLI settings.       │
│ delete    Delete an API key from a project.                                  │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent session`

```console
$ meshagent session --help
                                                                                
 Usage: meshagent session [OPTIONS] COMMAND [ARGS]...                           
                                                                                
 Inspect recent sessions and events                                             
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ list  List recent sessions                                                   │
│ show  Show events for a session                                              │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent token`

```console
$ meshagent token --help
                                                                                
 Usage: meshagent token [OPTIONS]                                               
                                                                                
 Generate a participant token (JWT) from a spec                                 
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│    --project-id                  TEXT  A MeshAgent project id. If empty, the │
│                                        activated project will be used.       │
│                                        [default:                             │
│                                        203b1bf9-72c9-4022-bfaa-55d6f656dfeb] │
│    --output              -o      TEXT  File path to a file                   │
│ *  --input               -i      TEXT  File path to a token spec [required]  │
│    --key                         TEXT  an api key to sign the token with     │
│    --install-completion                Install completion for the current    │
│                                        shell.                                │
│    --show-completion                   Show completion for the current       │
│                                        shell, to copy it or customize the    │
│                                        installation.                         │
│    --help                              Show this message and exit.           │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent webhook`

```console
$ meshagent webhook --help
                                                                                
 Usage: meshagent webhook [OPTIONS] COMMAND [ARGS]...                           
                                                                                
 Manage project webhooks                                                        
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ create  Create a webhook                                                     │
│ list    List webhooks                                                        │
│ delete  Delete a webhook                                                     │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent service`

```console
$ meshagent service --help
                                                                                
 Usage: meshagent service [OPTIONS] COMMAND [ARGS]...                           
                                                                                
 Manage services for your project                                               
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ spec               Render a service or template YAML spec without creating a │
│                    service.                                                  │
│ create             Create a service attached to the project.                 │
│ update             Create a service attached to the project.                 │
│ validate           Validate a service spec from a YAML file.                 │
│ create-template    Create a service from a ServiceTemplate spec.             │
│ update-template    Update a service using a ServiceTemplate spec.            │
│ validate-template  Validate a service template from a YAML file.             │
│ render-template    Render a service template with variables and print the    │
│                    rendered YAML.                                            │
│ run                Run a local command and register it as a temporary room   │
│                    service.                                                  │
│ show               Show a services for the project.                          │
│ list               List all services for the project.                        │
│ delete             Delete a service.                                         │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent mcp`

```console
$ meshagent mcp --help
                                                                                
 Usage: meshagent mcp [OPTIONS] COMMAND [ARGS]...                               
                                                                                
 Bridge MCP servers into MeshAgent rooms                                        
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ sse            Connect an MCP server over SSE and register it as a toolkit   │
│ http           Connect an MCP server over streamable HTTP and register it as │
│                a toolkit                                                     │
│ stdio          Run an MCP server over stdio and register it as a toolkit     │
│ http-proxy     Expose a stdio MCP server over streamable HTTP                │
│ sse-proxy      Expose a stdio MCP server over SSE                            │
│ stdio-service  Run a stdio MCP server as an HTTP service                     │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent secret`

```console
$ meshagent secret --help
                                                                                
 Usage: meshagent secret [OPTIONS] COMMAND [ARGS]...                            
                                                                                
 Manage secrets for your project.                                               
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ list    List all secrets in the project (typed as Docker/ACR/GAR or Keys     │
│         secrets).                                                            │
│ delete  Delete a secret.                                                     │
│ key     Create or update environment-based key-value secrets.                │
│ docker  Create or update docker registry pull secrets.                       │
│ acr     Create or update Azure Container Registry pull secrets.              │
│ gar     Create or update Google Artifact Registry pull secrets.              │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent rooms`

```console
$ meshagent rooms --help
                                                                                
 Usage: meshagent rooms [OPTIONS] COMMAND [ARGS]...                             
                                                                                
 Create, list, and manage rooms in a project                                    
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ create  Create a room in the project.                                        │
│ delete  Delete a room by ID (or by name if --name is supplied).              │
│ update  Update a room's name (ID is preferred; name will be resolved to ID   │
│         if needed).                                                          │
│ list    List rooms in the project.                                           │
│ get     Get a single room by name (handy for resolving the ID).              │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent mailbox`

```console
$ meshagent mailbox --help
                                                                                
 Usage: meshagent mailbox [OPTIONS] COMMAND [ARGS]...                           
                                                                                
 Manage mailboxes for your project                                              
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ create  Create a mailbox attached to the project.                            │
│ update  Update a mailbox routing configuration.                              │
│ show    Show mailbox details.                                                │
│ list    List mailboxes for the project.                                      │
│ delete  Delete a mailbox.                                                    │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent route`

```console
$ meshagent route --help
                                                                                
 Usage: meshagent route [OPTIONS] COMMAND [ARGS]...                             
                                                                                
 Manage routes for your project                                                 
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ create  Create a route attached to the project.                              │
│ update  Update a route configuration.                                        │
│ show    Show route details.                                                  │
│ list    List routes for the project.                                         │
│ delete  Delete a route.                                                      │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent scheduled-task`

```console
$ meshagent scheduled-task --help
                                                                                
 Usage: meshagent scheduled-task [OPTIONS] COMMAND [ARGS]...                    
                                                                                
 Manage scheduled tasks for your project                                        
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ add     Add a scheduled task.                                                │
│ list    List scheduled tasks.                                                │
│ update  Update a scheduled task.                                             │
│ delete  Delete a scheduled task.                                             │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent meeting-transcriber`

```console
$ meshagent meeting-transcriber --help
                                                                                
 Usage: meshagent meeting-transcriber [OPTIONS] COMMAND [ARGS]...               
                                                                                
 Join a meeting transcriber to a room                                           
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ join     Join a room and run the meeting transcriber agent.                  │
│ service                                                                      │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent port`

```console
$ meshagent port --help
                                                                                
 Usage: meshagent port [OPTIONS]                                                
                                                                                
 Forward a container port to localhost                                          
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│    --project-id                  TEXT  A MeshAgent project id. If empty, the │
│                                        activated project will be used.       │
│                                        [default:                             │
│                                        203b1bf9-72c9-4022-bfaa-55d6f656dfeb] │
│ *  --room                -r      TEXT  Room name containing the target       │
│                                        container                             │
│                                        [required]                            │
│    --name                -n      TEXT  Container name to port-forward into   │
│    --container-id        -c      TEXT  Container ID to port-forward into     │
│ *  --port                -p      TEXT  Port mapping in the form LOCAL:REMOTE │
│                                        [required]                            │
│    --install-completion                Install completion for the current    │
│                                        shell.                                │
│    --show-completion                   Show completion for the current       │
│                                        shell, to copy it or customize the    │
│                                        installation.                         │
│    --help                              Show this message and exit.           │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent multi`

```console
$ meshagent multi --help
                                                                                
 Usage: meshagent multi [OPTIONS] COMMAND [ARGS]...                             
                                                                                
 Connect agents and tools to a room                                             
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ spec     Generate a combined service spec from multiple subcommands.         │
│ deploy   Deploy a combined service from multiple subcommands.                │
│ service                                                                      │
│ join     Run multiple join commands together in one process.                 │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent voicebot`

```console
$ meshagent voicebot --help
                                                                                
 Usage: meshagent voicebot [OPTIONS] COMMAND [ARGS]...                          
                                                                                
 Join a voicebot to a room                                                      
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ join     Join a room and run a voicebot agent.                               │
│ service                                                                      │
│ spec     Generate a service spec for deploying a voicebot.                   │
│ deploy   Deploy a voicebot service to a project or room.                     │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent process`

```console
$ meshagent process --help
                                                                                
 Usage: meshagent process [OPTIONS] COMMAND [ARGS]...                           
                                                                                
 Join a process-backed agent to a room                                          
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ join     Join a room and run a process-backed agent.                         │
│ service  Add a process-backed agent service to the host.                     │
│ spec     Generate a service spec for deploying a process-backed agent.       │
│ deploy   Deploy a process-backed agent service.                              │
│ run      Join a room, run a process-backed agent, and wait for messages.     │
│ use      Send a one-shot or interactive message to a running process-backed  │
│          agent.                                                              │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent room`

```console
$ meshagent room --help
                                                                                
 Usage: meshagent room [OPTIONS] COMMAND [ARGS]...                              
                                                                                
 Operate within a room                                                          
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ agent      Interact with agents and toolkits                                 │
│ secret     Manage secrets in a room                                          │
│ queue      Use queues in a room                                              │
│ messaging  Send and receive messages                                         │
│ storage    Manage storage for a room                                         │
│ service    Manage services in a room                                         │
│ developer  Developer utilities for a room                                    │
│ database   Manage database tables in a room                                  │
│ memory     Manage memories in a room                                         │
│ container  Manage containers and images in a room                            │
│ sync       Inspect and update mesh documents in a room                       │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent image`

```console
$ meshagent image --help
                                                                                
 Usage: meshagent image [OPTIONS] COMMAND [ARGS]...                             
                                                                                
 Build and pack OCI images                                                      
                                                                                
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ build   Build a container image inside a room.                               │
│ deploy  Create or update a room service from an image, optionally building   │
│         it first.                                                            │
│ pack    Pack a local directory into an OCI image archive.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
```
