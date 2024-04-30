# northwood-labs/tap

Homebrew tap for Northwood Labs.

```bash
brew tap northwood-labs/tap
```

## Rate limits

Unauthenticated calls to the GitHub API are rate-limited to 60/hour. Authenticated calls are rate-limited to 5,000/hour.

Create a GitHub token (no permissions), and set it to the `HOMEBREW_GITHUB_API_TOKEN` environment variable.
