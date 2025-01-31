---
title: クエリ
miniTocMaxHeadingLevel: 3
redirect_from:
  - /v4/query
  - /v4/reference/query
versions:
  fpt: '*'
  ghec: '*'
  ghes: '*'
  ghae: '*'
topics:
  - API
---

## クエリについて

すべてのGraphQLスキーマは、クエリとミューテーションの両方についてルート型を持っています。 [クエリ型](https://graphql.github.io/graphql-spec/June2018/#sec-Type-System)は、サーバーからデータを取り出すGraphQLの操作を定義します。

詳しい情報については「[クエリについて](/graphql/guides/forming-calls-with-graphql#about-queries)」を参照してください。

{% note %}

**注釈:** For [user-to-server](/developers/apps/identifying-and-authorizing-users-for-github-apps#user-to-server-requests) {% data variables.product.prodname_github_app %}リクエストの場合は、Issueとプルリクエストに別々のクエリを使用する必要があります。 たとえば、`is:issue`または`is:pull-request`フィルタと、それと同等のフィルタを使用します。 `search`接続を使用してIssueとプルリクエストの組み合わせを1つのクエリで返すと、ノードのセットが空になります。

{% endnote %}

<!-- Content after this section is automatically generated -->
