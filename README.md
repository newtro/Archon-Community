# Archon Community Flows

Community-contributed agent flows for [ArchonIDE](https://github.com/newtro/Archon).

## Browse & Install

Open ArchonIDE and navigate to the **Registry** tab to browse, search, and install community flows.

## How It Works

1. **Build** your flow in ArchonIDE's Flow Designer
2. **Share** it by clicking the **Share to Community** button in the toolbar (auto-creates a PR)
3. **Community reviews** the PR, tests the flow, and votes with thumbs up reactions
4. **3+ votes** triggers the `community-approved` label and notifies the maintainer
5. **Maintainer merges** the PR into main, making it available in the Registry

## Contributing a Flow

### Via the App (Recommended)
1. Design your flow in ArchonIDE's Flow Designer
2. Click **Share to Community** in the toolbar
3. Fill in the metadata (name, description, tags)
4. A pull request is created automatically

### Manual Contribution
1. Fork this repository
2. Create a folder under `flows/` with your flow slug (e.g., `flows/my-flow/`)
3. Add your `flow.json` (exported from ArchonIDE)
4. Update `flows/index.json` with your flow's metadata
5. Open a pull request

## Reviewing Flows

Community input matters. When you see a PR:

1. Pull the branch and install the flow in ArchonIDE
2. Test it with a real use case
3. Leave feedback in the comments
4. **Thumbs up the PR** if the flow works well

PRs with 3+ thumbs up are flagged for maintainer review and merge.

## Flow Structure

Each flow folder contains:

```
flows/my-flow/
  flow.json     # Full FlowDefinition (nodes, edges, config)
```

The catalog is maintained in `flows/index.json`.

## Guidelines

- Flows must export and run successfully in ArchonIDE
- No hardcoded API keys or secrets
- Include a clear description of what the flow does and when to use it
- One flow per PR

## License

Community flows are shared under the MIT License unless otherwise specified by the author.
