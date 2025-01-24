### kea development release container

Latest release

```bash
curl -s https://api.github.com/repos/isc-projects/kea/tags | jq -r 'first(.[] | select(.name | startswith("Kea-"))).name' | tr -d 'Kea-'
```