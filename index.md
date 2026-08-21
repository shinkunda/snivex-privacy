Snivex プライバシーポリシー

最終更新日: 2026年8月21日

1. はじめに

Snivex（以下「本拡張機能」）は、ユーザーが閲覧している Web ページのスクリーンショットを撮影し、タグとフォルダで整理し、あとから検索して見つけられるようにする Chrome 拡張機能です。
本ポリシーは、本拡張機能が扱う情報と、その取り扱い方法を説明します。

2. 本拡張機能が扱う情報

本拡張機能は、ユーザーが撮影操作を行ったときに、次の情報を扱います。

・スクリーンショット画像
・撮影したページの URL
・撮影したページのタイトル
・ユーザーが入力したタグ
・ユーザーが入力したフォルダ名
・撮影日時
・撮影方法（範囲を指定 / 表示中の画面 / ページ全体）
・画像の幅と高さ、ピン留めの有無、内部識別子
・本拡張機能の設定（保存先の有効・無効、PC 保存先のフォルダ名、確認画面の表示、連続キャプチャ、AI ショートカットの表示設定、表示テーマ）

これ以外の情報は取得しません。氏名・メールアドレス・電話番号・住所などの登録情報を求めることはなく、アカウント登録やログインも必要ありません。

3. 情報の保存場所

上記の情報はすべて、お使いのブラウザの拡張機能用ローカル領域（chrome.storage.local）に保存されます。

・Chrome の同期機能（chrome.storage.sync）は使用していません。端末間で同期されることはありません。
・IndexedDB、localStorage、sessionStorage は使用していません。
・撮影モードの一時的な状態のみ chrome.storage.session に保存され、ブラウザを終了すると消えます。
・「PC に保存」を使った場合、画像はお使いのコンピュータのダウンロードフォルダに保存されます。
・本拡張機能の開発者が運営するサーバーは存在しません。開発者がこれらの情報にアクセスすることはできません。

4. 外部への送信

本拡張機能は、扱う情報を開発者のサーバーその他いかなる外部サーバーへも送信しません。

・アクセス解析（analytics）を組み込んでいません。
・利用状況の送信（telemetry）を行いません。
・外部 API を呼び出しません。
・外部から取得したコードを実行しません。

本拡張機能のコードに含まれる fetch は、撮影した画像のデータをファイル形式へ変換するためだけに使われており、ネットワーク通信を行いません。

5. 第三者サービスについて（AI ショートカット）

本拡張機能には、ChatGPT、Claude、Gemini の各公式ページを新しいタブで開くショートカット機能があります。この機能は初期状態では無効で、設定画面で明示的に有効にした場合にのみ表示されます。

・本拡張機能がこれらのサービスへ、画像・URL・タイトルその他の情報を送信することはありません。
・開くのは各サービスの通常のページのみで、情報を含むパラメータを付けることはありません。
・クリップボードの内容をこれらのサービスへ送信することもありません。
・撮影した画像をこれらのサービスで使う場合、貼り付け操作はユーザー自身が行います。

これらのサービス上での情報の取り扱いは、各サービスのプライバシーポリシーに従います。本拡張機能は、これらのサービスの提供者と提携関係にはありません。

6. クリップボード

設定で「クリップボードへ自動コピー」を有効にした場合、撮影した画像をクリップボードへ書き込みます。
本拡張機能はクリップボードの読み取りを行いません。読み取りに必要な権限（clipboardRead）も要求していません。

7. 撮影内容に含まれる情報について

スクリーンショットは、ユーザーがそのとき画面に表示していた内容をそのまま画像にしたものです。そのため、ユーザーが撮影対象に選んだ画面によっては、氏名・メールアドレス・口座情報などの個人情報が画像に写り込むことがあります。
これらはユーザー自身の操作によって撮影され、ユーザーの端末内にのみ保存されます。本拡張機能がその内容を解析したり、外部へ送信したりすることはありません。

8. 情報の保持と削除

・保存した情報は、ユーザーが削除するまで端末内に残ります。
・ギャラリー画面から、キャプチャを 1 件ずつ、または複数選択してまとめて削除できます。
・Chrome から本拡張機能をアンインストールすると、本拡張機能のローカル保存領域は Chrome によって削除されます。
・「PC に保存」で書き出した画像は通常のファイルのため、アンインストールしても残ります。削除はユーザー自身で行ってください。

9. Limited Use への準拠

本拡張機能によるユーザーデータの取り扱いは、Chrome Web Store ユーザーデータポリシー（Limited Use requirements を含む）に準拠します。
本拡張機能は、ユーザーデータを販売しません。単一の目的と無関係な用途に使用しません。信用調査や貸付の判断を目的として使用または譲渡しません。

10. 本ポリシーの変更

本ポリシーを変更する場合は、このページを更新し、最終更新日を改めます。情報の取り扱いに実質的な変更がある場合は、拡張機能の更新時に分かる形でお知らせします。

11. お問い合わせ

iveli.official@gmail.com

English Summary

Snivex captures screenshots of web pages, lets you tag and organize them, and helps you find them later.

What it handles: screenshot images, the URL and title of the captured page, tags and folder names you enter, capture timestamps, and the extension's own settings.

Where it is stored: entirely on your own device, in the browser's local extension storage (chrome.storage.local). Chrome sync is not used. There is no server operated by the developer.

External transmission: none. Snivex does not send any of this data to the developer or to any third party. It contains no analytics, no telemetry, no external API calls, and no remotely hosted code.

AI shortcuts: Snivex can open ChatGPT, Claude, or Gemini in a new tab. This is disabled by default. Snivex does not transmit captured images, URLs, or clipboard contents to those services. Pasting is done by the user. Snivex is not affiliated with those services.

Clipboard: Snivex can write a captured image to the clipboard when you enable that setting. It never reads the clipboard.

Deletion: delete captures from the gallery at any time; uninstalling the extension removes its local storage.

Snivex's handling of user data complies with the Chrome Web Store User Data Policy, including the Limited Use requirements.
