### Contributing

This is an example of a PR process for contributing changes from your forked `iceberg-mcp-server` repo's `develop` branch back to the main repo.

#### Suggested Contribution

**Item/Adjustment**: Add more local-install instructions support to the README.  Add a CONTRIBUTING page.

**Why this is valuable**:

- The current upstream README (`cloudera/iceberg-mcp-server`) only has minimal Option 2 instructions.
- CONTRIBUTING.MD is preffered place to document PR process.

#### How to Contribute (Step-by-Step)

1. In **your fork** (`cldr-steven-matison/iceberg-mcp-server`):
   ```bash
   git checkout -b develop
   git push -u origin develop
   ```

2. Make the changes to your local repo:

   - Update `README.md`
   - Create `CONTRIBUTING.MD`

3. Commit and push:
   ```bash
   git add README.md CONTRIBUTING.MD
   git commit -m "feat: update readme local install + CONTRIBUTING"
   git push
   ```

4. Open a **Pull Request**:
   - Go to your fork on GitHub → Compare & pull request → Base repository: `cloudera/iceberg-mcp-server` → Base branch: `main`
   - Title: "Update Readme for Local Install + CONTRIBUTING"