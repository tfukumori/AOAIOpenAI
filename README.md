# Azure OpenAIとOpenAIの違い

https://note.com/pharmax/n/n56fbcfa51e48

> 本家OpenAIとの違いは、api_baseやdeployment_idを与えなければいけないところでしょうか。
> api_base（エンドポイントのbase URL）は、赤枠で囲んだリソース名ごとに異なります

利用する側のインタフェースとしては次が異なる

## Azure OpenAI

- URLを指定する（api_baseやdeployment_idにより異なるURL）
- API KEYを指定する

## OpenAI

- API KEYを指定する
