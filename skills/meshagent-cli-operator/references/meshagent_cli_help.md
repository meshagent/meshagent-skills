# MeshAgent CLI Help

_Packaged CLI help reference for MeshAgent CLI `0.38.4`._

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
│ setup                Perform initial login and project activation.           │
│ auth                 Authenticate to meshagent                               │
│ project              Manage or activate your meshagent projects              │
│ service-account      Manage service accounts for your project                │
│ secret               Manage user and service account secrets                 │
│ iam                  Manage IAM policies for project resources               │
│ config               Read MeshAgent deployment configuration                 │
│ doctor               Inspect a project for MeshAgent deployment gaps         │
│ create               Create a minimal deployable project                     │
│ session              Inspect recent sessions and events                      │
│ ask                  Send a one-shot prompt through the LLM router           │
│ launch               Launch CLI apps through MeshAgent                       │
│ token                Generate participant tokens (JWTs)                      │
│ service              Manage services for your project                        │
│ mcp                  Bridge MCP servers into MeshAgent rooms                 │
│ rooms                Create, list, and manage rooms in a project             │
│ agent                Create, list, and manage managed agents in a project    │
│ mailbox              Manage mailboxes for your project                       │
│ feed                 Manage feeds for your project                           │
│ subscription         Manage feed subscriptions for your project              │
│ route                Manage routes for your project                          │
│ registry             Manage registries for your project                      │
│ build                Build a container image inside a room                   │
│ deploy               Create or update a room service from an image           │
│ scheduled-task       Manage scheduled tasks for your project                 │
│ meeting-transcriber  Join a meeting transcriber to a room                    │
│ port                 Port forwarding into room containers                    │
│ voicebot             Join a voicebot to a room                               │
│ process              Join a process-backed agent to a room                   │
│ room                 Operate within a room                                   │
│ llm                  Local LLM proxy utilities                               │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent version`

```console
$ meshagent version --help

 Usage: meshagent version [OPTIONS]

 Print the version

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --help          Show this message and exit.                                  │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent setup`

```console
$ meshagent setup --help

 Usage: meshagent setup [OPTIONS]

 Perform initial login and project activation.

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --api-url        TEXT  Persist this API URL on the saved profile and use it  │
│                        for setup login.                                      │
│ --help                 Show this message and exit.                           │
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
│ switch                                                                       │
│ whoami                                                                       │
│ token                                                                        │
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
│ get       Get a MeshAgent project.                                           │
│ activate  Set the active project for subsequent CLI commands.                │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent service-account`

```console
$ meshagent service-account --help

 Usage: meshagent service-account [OPTIONS] COMMAND [ARGS]...

 Manage service accounts for your project

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ list     List service accounts for a project.                                │
│ get      Get a service account.                                              │
│ create   Create a service account for a project.                             │
│ update   Update a service account.                                           │
│ delete   Delete a service account.                                           │
│ api-key  Manage API keys                                                     │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent secret`

```console
$ meshagent secret --help

 Usage: meshagent secret [OPTIONS] COMMAND [ARGS]...

 Manage secrets

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ list                List secrets for a subject.                              │
│ search              Search secrets for a subject.                            │
│ get                 Get a secret for a subject.                              │
│ create              Create a secret for a subject.                           │
│ update              Update a secret for a subject.                           │
│ delete              Delete a secret for a subject.                           │
│ versions            List versions for a secret.                              │
│ add-version         Add a new version to a secret.                           │
│ access              List proxy access grants for one of your secrets.        │
│ grant-proxy         Grant a service account proxy access to one of your      │
│                     secrets.                                                 │
│ revoke-proxy        Revoke a service account proxy access grant from one of  │
│                     your secrets.                                            │
│ pull-secrets        List pull secrets for a service account.                 │
│ add-pull-secret     Add a pull secret to a service account.                  │
│ remove-pull-secret  Remove a pull secret from a service account.             │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent iam`

```console
$ meshagent iam --help

 Usage: meshagent iam [OPTIONS] COMMAND [ARGS]...

 Manage IAM policies for project resources

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ policy  List a resource IAM policy.                                          │
│ grant   Grant roles on a resource.                                           │
│ revoke  Revoke all direct roles for a subject.                               │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent config`

```console
$ meshagent config --help

 Usage: meshagent config [OPTIONS] COMMAND [ARGS]...

 Read MeshAgent deployment configuration

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ get  Print one deployment config value.                                      │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent doctor`

```console
$ meshagent doctor --help

 Usage: meshagent doctor [OPTIONS] [PATH]

 Inspect the current directory for MeshAgent deployment gaps.

╭─ Arguments ──────────────────────────────────────────────────────────────────╮
│   path      [PATH]                                                           │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --fix           Create obvious missing project files such as Dockerfile or   │
│                 pyproject.toml.                                              │
│ --help          Show this message and exit.                                  │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent create`

```console
$ meshagent create --help

 Usage: meshagent create [OPTIONS] [PATH]

 Create a minimal deployable project.

╭─ Arguments ──────────────────────────────────────────────────────────────────╮
│   path      [PATH]                                                           │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --language     -l                      TEXT  Template language for           │
│                                              non-interactive use. Supported: │
│                                              python, javascript, typescript, │
│                                              react, dotnet, dart/flutter.    │
│ --focus                                TEXT  Project focus for               │
│                                              non-interactive use. Use stable │
│                                              IDs: webserver (Web App),       │
│                                              backend-agent (Agent Toolkit),  │
│                                              chatbot (OpenAI Chatbot),       │
│                                              chatbot-anthropic (Anthropic    │
│                                              Chatbot), chatbot-ui (Agent     │
│                                              UI), room-chat (Room Chat),     │
│                                              meeting-app (Meeting App), or   │
│                                              contact-form (Contact Form).    │
│ --interactive      --no-interactive          Run or bypass the interactive   │
│                                              template picker. Defaults to    │
│                                              interactive when attached to a  │
│                                              TTY and language or focus is    │
│                                              missing.                        │
│ --help                                       Show this message and exit.     │
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
│ list    List recent sessions                                                 │
│ get     Get events for a session                                             │
│ traces  List trace spans for a session as a tree                             │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent ask`

```console
$ meshagent ask --help

 Usage: meshagent ask [OPTIONS]

 Send a one-shot LLM prompt.

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --project-id                                    TEXT  A MeshAgent project    │
│                                                       id. If empty, the      │
│                                                       activated project will │
│                                                       be used.               │
│                                                       [default: (dynamic)]   │
│ --message             -m                        TEXT  Prompt to send to the  │
│                                                       LLM                    │
│ --format                                        TEXT  Output format for      │
│                                                       non-interactive        │
│                                                       responses.             │
│                                                       [default: markdown]    │
│ --model                                         TEXT  Name of the LLM model  │
│                                                       to use                 │
│                                                       [default: gpt-5.5]     │
│ --preamble-rule           --no-preamble-rule          Include the default    │
│                                                       rule asking the model  │
│                                                       to send concise        │
│                                                       pre-tool preambles.    │
│                                                       [default:              │
│                                                       preamble-rule]         │
│ --install-completion                                  Install completion for │
│                                                       the current shell.     │
│ --show-completion                                     Show completion for    │
│                                                       the current shell, to  │
│                                                       copy it or customize   │
│                                                       the installation.      │
│ --help                                                Show this message and  │
│                                                       exit.                  │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent launch`

```console
$ meshagent launch --help

 Usage: meshagent launch [OPTIONS] COMMAND [ARGS]...

 Launch supported CLI apps through MeshAgent.

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --help          Show this message and exit.                                  │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ codex   Launch Codex through MeshAgent for the active project.               │
│ claude  Launch Claude through MeshAgent for the active project.              │
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
│                                        [default: (dynamic)]                  │
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
│ get                Get a service for the project.                            │
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
│ get     Get a single room by name or ID.                                     │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent agent`

```console
$ meshagent agent --help

 Usage: meshagent agent [OPTIONS] COMMAND [ARGS]...

 Create, list, and manage managed agents in a project

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ create  Create a managed agent in the project.                               │
│ delete  Delete a managed agent from the project.                             │
│ update  Update a managed agent configuration.                                │
│ list    List managed agents in the project.                                  │
│ get     Get a managed agent configuration.                                   │
│ use     Use a managed agent over its websocket connection.                   │
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
│ get     Get mailbox details.                                                 │
│ list    List mailboxes for the project.                                      │
│ delete  Delete a mailbox.                                                    │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent feed`

```console
$ meshagent feed --help

 Usage: meshagent feed [OPTIONS] COMMAND [ARGS]...

 Manage feeds for your project

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ create      Create a feed.                                                   │
│ update      Update a feed.                                                   │
│ get         Get feed details.                                                │
│ list        List feeds for the project.                                      │
│ delete      Delete a feed.                                                   │
│ send        Publish a single JSON message to a feed.                         │
│ send-batch  Publish a JSONL file to a feed.                                  │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent subscription`

```console
$ meshagent subscription --help

 Usage: meshagent subscription [OPTIONS] COMMAND [ARGS]...

 Manage feed subscriptions for your project

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ create  Create a feed subscription.                                          │
│ update  Update a feed subscription.                                          │
│ get     Get feed subscription details.                                       │
│ list    List subscriptions for a feed.                                       │
│ delete  Delete a feed subscription.                                          │
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
│ get     Get route details.                                                   │
│ list    List routes for the project.                                         │
│ delete  Delete a route.                                                      │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent registry`

```console
$ meshagent registry --help

 Usage: meshagent registry [OPTIONS] COMMAND [ARGS]...

 Manage registries for your project

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ create  Create a project registry repository.                                │
│ update  Update a project registry repository.                                │
│ get     Get registry details.                                                │
│ list    List registries for the project.                                     │
│ delete  Delete a project registry repository by id or name.                  │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent build`

```console
$ meshagent build --help

 Usage: meshagent build [OPTIONS] PATH

 Build a container image inside a room.

╭─ Arguments ──────────────────────────────────────────────────────────────────╮
│ *    pack      PATH  Local directory to stream as the build context. Format  │
│                      '<path>[:<mount>]'. Defaults mount to /context.         │
│                      [required]                                              │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Options ────────────────────────────────────────────────────────────────────╮
│    --project-id                          TEXT  A MeshAgent project id. If    │
│                                                empty, the activated project  │
│                                                will be used.                 │
│    --room                                TEXT  Existing room name.           │
│ *  --tag                                 TEXT  Image tag to build. Supports  │
│                                                <repository>:<tag>,           │
│                                                <project-key>/<repository>:<… │
│                                                or                            │
│                                                <registry>/<project-key>/<re… │
│                                                Shorthand forms resolve       │
│                                                against the configured        │
│                                                MeshAgent registry.           │
│                                                [required]                    │
│    --context-path                        TEXT  Build context path inside the │
│                                                streamed build context        │
│                                                (absolute path). Defaults to  │
│                                                the PATH mount path.          │
│    --dockerfile-path                     TEXT  Optional Dockerfile path      │
│                                                inside the streamed build     │
│                                                context (absolute path).      │
│    --builder-name                        TEXT  Optional reusable builder     │
│                                                name for streamed local       │
│                                                builds.                       │
│    --private            --public               Whether the build container   │
│                                                is private to the participant │
│                                                [default: public]             │
│    --optimize           --no-optimize          Whether to optimize room      │
│                                                image outputs to eStargz      │
│                                                before publishing. Enabled by │
│                                                default.                      │
│                                                [default: optimize]           │
│    --cred                                TEXT  Docker creds                  │
│                                                (username,password) or        │
│                                                (registry,username,password)  │
│    --latest                                    Also publish the built image  │
│                                                as :latest in the same        │
│                                                repository.                   │
│    --help                                      Show this message and exit.   │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent deploy`

```console
$ meshagent deploy --help

 Usage: meshagent deploy [OPTIONS] [PATH]

 Create or update a room service from an image, optionally building it first.
 The target room must already exist. If .meshagent/deploy.yaml exists, deploy
 prompts for template values in TUI mode and saves them to
 .meshagent/values.yaml. Use `meshagent deploy describe` to inspect the local
 deploy spec. Happy path for a Dockerfile app: run 'meshagent deploy PATH
 --room <room> --tag <tag> --public --domain <domain>'. Use 'meshagent config
 get domains.pages' to find the pages domain for --domain. If PATH does not
 include a Dockerfile yet, create a minimal Dockerfile in the app directory
 first or create one elsewhere in PATH and pass it with --dockerfile-path.

╭─ Arguments ──────────────────────────────────────────────────────────────────╮
│   pack      [PATH]  Local directory to stream as the build context before    │
│                     deploy. Format '<path>[:<mount>]'. Defaults mount to     │
│                     /context. PATH is typically the app directory you want   │
│                     to deploy.                                               │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Options ────────────────────────────────────────────────────────────────────╮
│    --project-id                            TEXT  A MeshAgent project id. If  │
│                                                  empty, the activated        │
│                                                  project will be used.       │
│    --room                                  TEXT  Existing room name.         │
│ *  --tag                                   TEXT  Image tag to deploy, e.g.   │
│                                                  repo/name:tag. When used    │
│                                                  with PATH, shorthand        │
│                                                  <repository>:<tag> and      │
│                                                  <project-key>/<repository>… │
│                                                  resolve against the         │
│                                                  configured MeshAgent        │
│                                                  registry.                   │
│                                                  [required]                  │
│    --context-path                          TEXT  Build context path inside   │
│                                                  the packed build context    │
│                                                  (absolute path). Only used  │
│                                                  with PATH.                  │
│    --dockerfile-path                       TEXT  Optional Dockerfile path    │
│                                                  inside the packed build     │
│                                                  context (absolute path).    │
│                                                  Only used with PATH. Use    │
│                                                  this when the app directory │
│                                                  has no top-level Dockerfile │
│                                                  or when you create the      │
│                                                  Dockerfile under a          │
│                                                  different path.             │
│    --optimize             --no-optimize          Whether to optimize room    │
│                                                  image outputs to eStargz    │
│                                                  during the build stage.     │
│                                                  Enabled by default. Only    │
│                                                  used with PATH.             │
│                                                  [default: optimize]         │
│    --cred                                  TEXT  Docker creds                │
│                                                  (username,password) or      │
│                                                  (registry,username,passwor… │
│    --builder-name                          TEXT  Optional reusable builder   │
│                                                  name for streamed local     │
│                                                  pack builds.                │
│    --latest                                      Also publish the built PATH │
│                                                  image as :latest in the     │
│                                                  same repository. Only used  │
│                                                  with PATH.                  │
│    --domain                                TEXT  Create or update a room     │
│                                                  route for the deployed      │
│                                                  service and return a public │
│                                                  URL. Use this with --public │
│                                                  when you need an external   │
│                                                  URL from deploy. Use        │
│                                                  'meshagent config get       │
│                                                  domains.pages' to find the  │
│                                                  pages domain for --domain.  │
│                                                  Requires exactly one        │
│                                                  published service port.     │
│    --email                                 TEXT  Create or update a public   │
│                                                  mailbox for the deployed    │
│                                                  service. When a local       │
│                                                  deploy template has an      │
│                                                  email variable, that value  │
│                                                  is used unless --email is   │
│                                                  passed.                     │
│    --values           -f                   TEXT  YAML file containing deploy │
│                                                  template values. Can be     │
│                                                  passed multiple times;      │
│                                                  later files override        │
│                                                  earlier files.              │
│    --set                                   TEXT  Set a deploy template value │
│                                                  as KEY=VALUE. Can be passed │
│                                                  multiple times.             │
│    --extra-port                            TEXT  Add an extra route path to  │
│                                                  DOMAIN as TARGET:/path.     │
│                                                  TARGET can be PORT,         │
│                                                  SERVICE, or SERVICE:PORT.   │
│                                                  Can be passed multiple      │
│                                                  times. The target must      │
│                                                  already be published by a   │
│                                                  room service.               │
│    --validation-mode                       TEXT  Request validation          │
│                                                  annotation mode for private │
│                                                  published service ports:    │
│                                                  default, cookie, or none.   │
│                                                  [default: default]          │
│    --template                              TEXT  Allowed values: agent,      │
│                                                  none. agent: MeshAgent      │
│                                                  mounts room storage at      │
│                                                  /data, sets                 │
│                                                  MESHAGENT_TOKEN,            │
│                                                  OPENAI_API_KEY, and         │
│                                                  ANTHROPIC_API_KEY to a      │
│                                                  container-scoped MeshAgent  │
│                                                  token. agent also sets      │
│                                                  SMTP_PASSWORD to that       │
│                                                  token, SMTP_USERNAME to the │
│                                                  container name, SMTP_PORT   │
│                                                  to 587, SMTP_HOSTNAME from  │
│                                                  MESHAGENT_MAIL_DOMAIN when  │
│                                                  available, plus             │
│                                                  OPENAI_BASE_URL,            │
│                                                  ANTHROPIC_BASE_URL,         │
│                                                  MESHAGENT_API_URL,          │
│                                                  MESHAGENT_ROOM_URL,         │
│                                                  MESHAGENT_ROOM,             │
│                                                  MESHAGENT_PROJECT_ID,       │
│                                                  MESHAGENT_SESSION_ID,       │
│                                                  OTEL_ENDPOINT,              │
│                                                  OTEL_PYTHON_LOG_LEVEL, and  │
│                                                  MESHAGENT_MAIL_DOMAIN from  │
│                                                  the room runtime when       │
│                                                  available. Manual env       │
│                                                  values win. none: MeshAgent │
│                                                  applies no template         │
│                                                  defaults.                   │
│                                                  [default: agent]            │
│    --liveness                              TEXT  HTTP path to use for        │
│                                                  service liveness checks.    │
│                                                  Defaults to / for new or    │
│                                                  missing HTTP liveness       │
│                                                  paths.                      │
│    --room-mount                            TEXT  Mount room storage as       │
│                                                  <source>:<mount>[:ro|rw]    │
│    --project-mount                         TEXT  Mount project storage as    │
│                                                  <source>:<mount>[:ro|rw]    │
│    --empty-dir-mount                       TEXT  Mount empty dir at          │
│                                                  <mount>[:ro|rw]             │
│    --image-mount                           TEXT  Mount image as              │
│                                                  <image>=<mount>[:ro|rw]     │
│    --env              -e                   TEXT  Set environment variable as │
│                                                  KEY=VALUE                   │
│    --env-secret                            TEXT  Set environment variable    │
│                                                  from a service account      │
│                                                  secret as NAME=SECRET_ID    │
│    --identity                              TEXT  Identity name to use for    │
│                                                  --meshagent-token. Defaults │
│                                                  to the current token        │
│                                                  identity or the derived     │
│                                                  service name.               │
│    --run-as                                TEXT  Service account email the   │
│                                                  deployed container runs as. │
│                                                  Required when using         │
│                                                  --env-secret.               │
│    --meshagent-token                       TEXT  Inject MESHAGENT_TOKEN      │
│                                                  using userDefault,          │
│                                                  agentDefault, full, or a    │
│                                                  JSON ApiScope object.       │
│    --private              --public               Whether published service   │
│                                                  ports should stay private   │
│                                                  or be public when they are  │
│                                                  created or updated.         │
│                                                  Defaults to private.        │
│                                                  [default: private]          │
│    --wait                 --no-wait              Wait for the deployed       │
│                                                  service to start, stream    │
│                                                  container logs, and verify  │
│                                                  the route liveness URL when │
│                                                  --domain is provided.       │
│                                                  [default: wait]             │
│    --help                                        Show this message and exit. │
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
│ runs    List runs for a scheduled task.                                      │
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
│                                        [default: (dynamic)]                  │
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

 Run process-backed agents

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ join      Join a room and run a process-backed agent.                        │
│ service   Add a process-backed agent service to the host.                    │
│ spec      Generate a service spec for deploying a process-backed agent.      │
│ deploy    Deploy a process-backed agent service.                             │
│ run       Run a process-backed agent and wait for messages.                  │
│ threads   List threads for a process-backed agent.                           │
│ messages  List messages in a process-backed agent thread.                    │
│ grep      Search coalesced messages in a process-backed agent thread.        │
│ use       Send a one-shot or interactive message to a running process-backed │
│           agent.                                                             │
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
│ agents     Interact with agents and toolkits                                 │
│ queue      Use queues in a room                                              │
│ messaging  Send and receive messages                                         │
│ storage    Manage storage for a room                                         │
│ service    Manage services in a room                                         │
│ developer  Developer utilities for a room                                    │
│ dataset    Manage dataset tables in a room                                   │
│ memory     Manage memories in a room                                         │
│ container  Manage containers and images in a room                            │
│ sync       Inspect and update mesh documents in a room                       │
│ connect    Connect to a room and run a local command with room auth env      │
╰──────────────────────────────────────────────────────────────────────────────╯
```

## `meshagent llm`

```console
$ meshagent llm --help

 Usage: meshagent llm [OPTIONS] COMMAND [ARGS]...

 Local LLM proxy utilities

╭─ Options ────────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.      │
│ --show-completion             Show completion for the current shell, to copy │
│                               it or customize the installation.              │
│ --help                        Show this message and exit.                    │
╰──────────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────────╮
│ proxy   Expose a local MeshAgent-authenticated LLM proxy.                    │
│ logger  Manage project LLM loggers                                           │
╰──────────────────────────────────────────────────────────────────────────────╯
```
