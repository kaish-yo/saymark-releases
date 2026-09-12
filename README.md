# Saymark

Windows向けの録音・文字起こし・要約アプリです。このリポジトリは配布専用です。

## ダウンロード

[Releases](https://github.com/kaish-yo/saymark-releases/releases) から Windows x64 ZIP をダウンロードし、全体を展開して `Saymark.Desktop.exe` を起動してください。

- Windows 10/11 x64
- [.NET 10 Windows Desktop Runtime x64](https://dotnet.microsoft.com/download/dotnet/10.0) が必要です。
- インターネット接続とAPIキーが必要です。API設定でBase URLと文字起こし・要約モデルIDを設定してください。
- 文字起こし時は音声を、要約時は本文を設定先APIに送信します。API利用料金は利用者負担です。
- データは `%LOCALAPPDATA%\Saymark` に保存します。
- 現在は未署名のアルファ版です。

ZIPのSHA-256は添付の `SHA256SUMS.txt` で確認できます。
GitHubが自動生成する「Source code」アーカイブはこの配布用READMEのみを含み、アプリではありません。