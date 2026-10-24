# scoop-sill

The [Scoop](https://scoop.sh) bucket for [sill](https://github.com/lemonadesaltbagel/sill), Bash for coding agents on native Windows.

    scoop bucket add sill https://github.com/lemonadesaltbagel/scoop-sill
    scoop install sill/sill

`sill` goes on your PATH. The drop-in `bash.exe` is `~\scoop\apps\sill\current\bash.exe`:
- **Claude Code:** set `CLAUDE_CODE_GIT_BASH_PATH` to that path.
- **MCP clients** (Codex CLI, Gemini CLI, Claude Desktop): use that path with the argument `--mcp`.

The manifest follows sill's releases automatically (a daily check).
