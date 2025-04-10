# GitHub Repository Manager Tool

A simple, client-side web tool to manage multiple GitHub repositories efficiently. This tool runs entirely in your browser and communicates directly with the GitHub API using your personal access token.

## Features

- **Browse and search** all your repositories
- **Filter repositories** by type: public, private, forks, archived, or empty
- **Sort** by recently updated, recently created, or name
- **Bulk operations**:
  - Delete multiple repositories at once
  - Toggle visibility (public/private) for multiple repositories
- **Privacy-focused**: Your GitHub token is never sent to any server other than GitHub's API

## How to Use

1. **Create a GitHub Personal Access Token**:
   - Go to [GitHub > Settings > Developer settings > Personal access tokens > Tokens (classic)](https://github.com/settings/tokens)
   - Click "Generate new token" and select "Generate new token (classic)"
   - Give it a name
   - Select the following permissions:
     - `delete_repo` (to delete repositories)
     - `repo` (to update repository visibility)
   - Click "Generate token" and copy your new token

2. **Access the Tool**:
   - Open the tool in your browser
   - Paste your GitHub personal access token
   - Click "Fetch Repository List"

3. **Use the Features**:
   - Browse, filter, and search your repositories
   - Select repositories using checkboxes
   - Use the action buttons to perform bulk operations

## Security Considerations

- Your GitHub token is stored only in your browser's memory during the session
- Never share your GitHub token with others
- Use a token with the minimum necessary permissions

## License

This project is licensed under the MIT License.

---

**Note**: This tool is not affiliated with GitHub. Use at your own risk.
