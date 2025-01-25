### Container for Kea development release

https://github.com/isc-projects/kea

Latest release

```bash
curl -s https://api.github.com/repos/isc-projects/kea/tags | jq -r 'first(.[] | select(.name | startswith("Kea-"))).name' | tr -d 'Kea-'
```
