# Get GitHub PAM token

## Usage example

```
-   name: Get Github Token
    id: github_token
    uses: gismart/github-action-public@main
-   name: Checkout Gismart GitHub Action Repository
    uses: actions/checkout@v3
    with:
        repository: gismart/github-action
        token: ${{ steps.github_token.outputs.token }}
        path: github-actions    
```
