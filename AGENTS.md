# Repository guidance

Deno JSON/JSONC merge driver published as `@patdx/git-json-merge` on JSR.

- `deno task test` runs unit and Git integration tests.
- `deno fmt --check` checks formatting.
- `deno publish --dry-run` validates the package.
- Bump `version` in `deno.json` and push to main to publish through GitHub
  Actions.
- Use single quotes, no semicolons, and two-space indentation.
