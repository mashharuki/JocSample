# JocSample

Japan Open Chain 上でスマコン開発するためのテンプレートプロジェクトです。

## 動かし方

`backend`ディレクトリ配下で実行してください。

- インストール

  ```bash
  yarn
  ```

- セットアップ

  ```bash
  yarn setUp --network jocTestnet
  ```

- コンパイル

  ```bash
  yarn compile
  ```

- テスト

  ```bash
  yarn test
  ```

- デプロイ

  ```bash
  yarn deploy --network jocTestnet
  ```

  実際にデプロイしたコントラクト

  [0xAa363921A48Eac63F802C57658CdEde768B3DAe1](https://explorer.testnet.japanopenchain.org/address/0xAa363921A48Eac63F802C57658CdEde768B3DAe1/transactions#address-tabs)

- 試しにコントラクトの機能を呼び出す方法

  ```bash
  yarn getOwner --network jocTestnet
  ```

  ```bash
  ========================================== [START] ==========================================
  owner address: 0x51908F598A5e0d8F1A3bAbFa6DF76F9704daD072
  ========================================== [END] ==========================================
  ✨  Done in 0.94s.
  ```
