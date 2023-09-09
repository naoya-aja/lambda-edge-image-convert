# lambda-edge-image-convert
AWS Lambda@Edgeで画像をリアルタイムにリサイズする

以下を参考に構築
> [AWS Lambda@Edge で画像をリアルタイムにリサイズ＆WebP形式へ変換する
](https://techlife.cookpad.com/entry/2018-05-25-lambda-edge)

変更点
---
### Sharp(画像処理モジール)の使用方法変更
max や他の多くの操作は v0.21.0 で非推奨になり、v0.22.0 で削除されたようです。
- http://sharp.pixelplumbing.com/en/stable/changelog/#v0210-4th-october-2018
- http://sharp.pixelplumbing.com/en/stable/changelog/#v0220-18th-march-2019

参考
---
- [AWS Lambda@Edge で画像をリアルタイムにリサイズ＆WebP形式へ変換する
](https://techlife.cookpad.com/entry/2018-05-25-lambda-edge)
- [Amazon CloudFront & Lambda@Edge で画像をリサイズする](https://aws.amazon.com/jp/blogs/news/resizing-images-with-amazon-cloudfront-lambdaedge-aws-cdn-blog/)
- [Lambda@Edgeを使って画像をリサイズしてみた](https://dev.classmethod.jp/articles/lambda-edge-image-resize/)
