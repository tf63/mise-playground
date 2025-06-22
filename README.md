# miseを試してみる

https://zenn.dev/tf63/scraps/0691e7c1244fba

## 使い方

`mise.toml`からインストール

```shell
mise install
```

インストール可能なパッケージを検索

```shell
mise registry
```

インストール可能なバージョンを検索

```shell
mise ls-remote <パッケージ>
```

パッケージのインストール

```
mise use # これでインタラクティブに検索できる
mise use <パッケージ>
```

パッケージのアンインストール

```
mise unuse <パッケージ>
```
