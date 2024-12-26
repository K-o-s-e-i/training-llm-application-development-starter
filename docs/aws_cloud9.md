# AWS Cloud9 を使用する場合の補足

AWS Cloud9 (Amazon Linux 2023) を使用する場合、Jupyter には以下の手順でアクセスできます。

### コマンドでの Jupyter の起動

以下のコマンドで Jupyter を起動することができます。

```console
make cloud9_jupyter
```

Cloud9 上部の「Preview」>「Preview Running Application」をクリックしてください。

![](./images/aws_cloud9/cloud9_preview_running_application.png)

Cloud9 の画面内のプレビューではうまく表示されないのは想定通りです。

![](./images/aws_cloud9/cloud9_pop_out_into_new_window.png)

プレビューの右上のアイコン (Pop Out Into New Window) をクリックすると、ブラウザの別のタブでアクセスできます。
