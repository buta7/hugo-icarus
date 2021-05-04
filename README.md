# README

## セットアップ

サイト作成

```shell
hugo new site hugo-icarus
```

レポジトリ初期化

```shell
cd hugo-icarus
git init
echo '*~' >> .gitignore
echo '*.bak' >> .gitignore
echo '*.orig' >> .gitignore
echo '.env' >> .gitignore
echo 'public' >> .gitignore
echo 'resources' >> .gitignore
```

テーマ設定(submoduleはhttpsプロトコルで追加)

```shell
git submodule add https://gitlab.com/toryanderson/hugo-icarus.git themes/icarus
```

(参考)submoduleの削除

```shell
git submodule deinit -f themes/icarus
git rm themes/icarus
rm -fr .git/modules/icarus
```

サイト設定

```shell
cp -p themes/icarus/exampleSite/config.toml .
cp -pr themes/icarus/exampleSite/{content,static} .
```

## Link

* [Hugo Icarus \| Hugo Themes](https://themes.gohugo.io/hugo-icarus/)
