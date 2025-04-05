### Container for Kea development release

https://github.com/isc-projects/kea

Latest release

```bash
curl -s https://api.github.com/repos/isc-projects/kea/git/refs/tags | jq -r 'last(.[] | select(.ref | startswith("refs/tags/Kea-"))).ref' | tr -d "ref/tags/Kea-"
```