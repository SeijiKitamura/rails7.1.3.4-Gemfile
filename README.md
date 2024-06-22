# rails7.1.3.4-Gemfile

## セットアップ手順
```bash
mkdir app_dir
cd app_dir
rbenv local 3.2.2
rails _7.1.3.4_ new . -c bootstrap -d postgresql
curl -o Gemfile https://gist.github.com/SeijiKitamura/a4dafefd6e9e44b7e16e2d737b51090c
bundle
```
