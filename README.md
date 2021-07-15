# `meltano-cicd-sample-template`

A project template for DataOps CI/CD on GitHub.

[![Open in Visual Studio Code](https://open.vscode.dev/badges/open-in-vscode.svg)](https://open.vscode.dev/meltano/meltano-cicd-lab-template)

## Testing

To test, first use the `Open in VS Code` link above to open the project in VS Code.

_Note: The only prerequisites to get started is to install **VS Code** and **Docker**. As needed, VS Code will prompt 
you to install any additional extensions needed to open the project._

### Run a simple Meltano pipeline

Once you've opened the project, test that meltano is running executing the following sample pipeline
in a new VS Code terminal:

```bash
meltano elt tap-carbon-intensity target-jsonl 
```

### Launch the web UI

```bash
meltano ui start 
```

After running the above command, you should see an option from VS Code to "Open in Browser". If not, you can manually navigate to http://localhost:5000.
