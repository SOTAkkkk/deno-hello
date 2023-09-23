# deno-hello

## 実行

```shell
deno run hello.ts
```

- cli.js
```shell
deno run --allow-read cli.js 
```

## コンパイル

- ホストPCでコンパイル
    ```shell
    deno compile --output target/ hello.ts
    ```
- windows
    ```shell
    deno compile --output target/ --target x86_64-pc-windows-msvc hello.ts
    ```

## deno公式
- [compiler](https://docs.deno.com/runtime/manual/tools/compiler)

## ライブラリ
- [commander](https://deno.land/x/cmd@v1.2.0)