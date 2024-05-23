# test-renovate-customization

```bash
docker run -e LOG_LEVEL=debug -v $(pwd)/renovate.json:/usr/src/app/renovate.json -v $(pwd)/base-os.yaml:/usr/src/app/base-os.yaml --rm renovate/renovate --platform=local > output.txt
```