---
id: approve
title: 承認
keywords:
- 'pos client, erc721, approve, polygon, sdk'
description: 'ルートトークンで必要な量を承認します。'
---

`approve`メソッドは、ルートトークンで必要な量を承認するために使用できます。

```
const erc721RootToken = posClient.erc721(<root token address>,true);

const approveResult = await erc721RootToken.approve(<token id>);

const txHash = await approveResult.getTransactionHash();

const txReceipt = await approveResult.getReceipt();

```
