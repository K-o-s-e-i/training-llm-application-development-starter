# AWS Cloud9 を使用する場合の補足

AWS Cloud9 (Amazon Linux 2023) を想定した補足です。

## Jupyter のセットアップ

以下のコマンドで Jupyter を起動することができます。

```console
make cloud9_jupyter
```

Cloud9 上部の「Preview」>「Preview Running Application」をクリックしてください。

![](./images/aws_cloud9/cloud9_preview_running_application.png)

Cloud9 の画面内のプレビューではうまく表示されないのは想定通りです。

![](./images/aws_cloud9/cloud9_pop_out_into_new_window.png)

プレビューの右上のアイコン (Pop Out Into New Window) をクリックすると、ブラウザの別のタブでアクセスできます。

![](./images/jupyter_auth.png)

Jupyter のトークンを入力するよう求められた場合、ターミナル上に表示されているトークンをコピーしてログインしてください。

![](./images/jupyter_home.png)

「notebooks」というフォルダの「hello.ipynb」を開いてください。

「hello.ipynb」の内容が想定通り動作するか確認してください。

![](./images/jupyter_hello_world.png)
