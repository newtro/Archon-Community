# Archon Community Flows

Community-contributed agent flows for [ArchonIDE](https://github.com/newtro/ArchonIDE).

## Browse & Install

Open ArchonIDE and navigate to the **Registry** tab to browse, search, and install community flows.

## Contributing a Flow

1. Design your flow in ArchonIDE's Flow Designer
2. Click the **Share to Community** button in the toolbar
3. Fill in the metadata (name, description, tags)
4. A pull request will be created automatically

### Manual Contribution

1. Fork this repository
2. Create a folder under `flows/` with your flow slug (e.g., `flows/my-flow/`)
3. Add your `flow.json` (exported from ArchonIDE)
4. Update `flows/index.json` with your flow's metadata
5. Open a pull request

## Flow Structure

Each flow folder contains:

```
flows/my-flow/
  flow.json     # Full FlowDefinition (nodes, edges, config)
```

The catalog is maintained in `flows/index.json`.

## License

Community flows are shared under the MIT License unless otherwise specified by the author.
