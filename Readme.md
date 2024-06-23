# Dot Image Converter

Dot Image Converterは、通常の画像をドット絵風に変換するReactベースのウェブアプリケーションです。ユーザーは画像をアップロードし、解像度とドットサイズを調整して、オリジナルのドット絵を作成できます。

## 機能

- 画像のアップロードと表示
- 解像度の調整（16x16から256x256まで）
- ドットサイズの調整
- リアルタイムプレビュー
- 変換した画像のエクスポート

## 前提条件

このプロジェクトを実行するには、以下のソフトウェアがインストールされている必要があります：

- Node.js (バージョン14.0.0以上)
- npm (通常Node.jsと一緒にインストールされます)

### Node.jsのインストール

1. [Node.jsの公式ウェブサイト](https://nodejs.org/)にアクセスします。
2. LTS（Long Term Support）バージョンをダウンロードしてインストールすることをお勧めします。
3. インストールが完了したら、ターミナルやコマンドプロンプトを開き、以下のコマンドを実行してインストールを確認します：

   ```
   node --version
   npm --version
   ```

   バージョン番号が表示されれば、インストールは成功です。

## セットアップ

Node.jsとnpmがインストールされたら、以下の手順に従ってプロジェクトをセットアップしてください：

1. リポジトリをクローンします：
   ```
   git clone https://github.com/yourusername/dot-image-converter.git
   ```

2. プロジェクトディレクトリに移動します：
   ```
   cd dot-image-converter
   ```

3. 必要な依存関係をインストールします：
   ```
   npm install
   ```

4. アプリケーションを起動します：
   ```
   npm start
   ```

これで、アプリケーションがローカルホスト（通常は http://localhost:3000）で実行されるはずです。ブラウザで自動的に開かれない場合は、手動でこのURLにアクセスしてください。

## 使用方法

1. 「ファイルを選択」ボタンをクリックして画像をアップロードします。
2. スライダーを使用して解像度を調整します（16x16から256x256まで）。
3. ドットサイズのスライダーを使用して、各ドットの大きさを調整します。
4. リアルタイムでプレビューを確認しながら、好みの設定を見つけます。
5. 「画像を出力」ボタンをクリックして、変換した画像をダウンロードします。

## 技術スタック

- React
- HTML5 Canvas
- shadcn/ui（UIコンポーネント）

## 開発

このプロジェクトをさらに開発したい場合は、以下の手順を参考にしてください：

1. 新しいブランチを作成します：
   ```
   git checkout -b feature/your-new-feature
   ```

2. 変更を加え、コミットします：
   ```
   git commit -am 'Add some feature'
   ```

3. ブランチにプッシュします：
   ```
   git push origin feature/your-new-feature
   ```

4. プルリクエストを作成します。

## 貢献

プロジェクトへの貢献を歓迎します！バグ報告、機能提案、プルリクエストなど、どんな形でも構いません。

## ライセンス

このプロジェクトはMITライセンスの下で公開されています。詳細は[LICENSE](LICENSE)ファイルをご覧ください。

## 連絡先

質問や提案がある場合は、[Issues](https://github.com/yourusername/dot-image-converter/issues)セクションを使用してください。

---

Happy dot image converting!