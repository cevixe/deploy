# Cevixe Deploy GitHub Actions

Cevixe Deploy GitHub Actions allows you to deploy cevixe projects

## Example usage

```yaml
on: [push]

jobs:
  aws_cdk:
    runs-on: ubuntu-latest
    steps:
      - name: Build
        uses: cevixe/deploy@v1
```

## License

[MIT](LICENSE)

## Authors

[Ronnie Ayala](https://github.com/ronnieacs)