# Quick Start

1. Download the zip for your platform.
2. Extract it to a folder.
3. Run Siemserva:
   - **macOS:** `./siemserva-osx-arm64 --accept-eula --tenantids <your-tenant-id>`
   - **Windows:** `siemserva-win-x64.exe --accept-eula --tenantids <your-tenant-id>`

On macOS, run `chmod +x siemserva-*` first, or use the included `run-siemserva.sh` helper.

## Getting help

- Run with **no parameters** to launch the interactive setup guide.
- Run with `-?` for the basic parameter list.
- Run with `--full-help` for the detailed help files.

> [!IMPORTANT]
> ## Try demo mode first
>
> Not ready to point Siemserva at a live tenant? Start with **demo mode**. It ships with a rich, realistic database covering well over 1,000 users.
>
> Just run `siemserva-osx-arm64` or `siemserva-win-x64` with no parameters and follow the setup. Demo mode supports both the Siemserva dashboard and the Claude MCP server, and it is a great way to train on the tool before scanning your own environment.
>
> For a guided walkthrough of what the demo data contains and what to look for, read **`SiemservaEvaluationGuide.pdf`** included in the release zip. If you have Claude Desktop available, run with the MCP server enabled. It is the fastest way to explore the security context graph Siemserva builds.
