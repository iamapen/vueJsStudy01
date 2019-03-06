DirectoryIndex 付きのwebサーバに乗せて動かすこと。
indexは静的HTMLで作った方がポータビリティがいいかもしれない、いずれ。

- フレームワークというより、ビューライブラリである
- Vue インスタンスは MVVMパターンでいうViewModelであり、ViewとModelの仲介をするためのもの。
  - 状態を持っている。


# vue-cli
これはグローバルの方がいいのかもしれない。少なくともプロジェクト内にいれるものではない。
```bash
$ yarn add vue-cli

$ node_modules/vue-cli/bin/vue --version
2.8.1
```

## プロジェクト作成
```bash
$ ./npm/node_modules/vue-cli/bin/vue init webpack 06

$ cd 06
$ yarn install
$ npm run dev
```

