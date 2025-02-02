---
title: Git 트리
shortTitle: Trees
allowTitleToDifferFromFilename: true
intro: 'REST API를 사용하여 {% data variables.product.product_name %}에서 Git 데이터베이스의 트리 개체와 상호 작용합니다.'
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - API
miniTocMaxHeadingLevel: 3
ms.openlocfilehash: ecd3781bbc78fff8b2d75f25b16d303081a7d605
ms.sourcegitcommit: 6185352bc563024d22dee0b257e2775cadd5b797
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/09/2022
ms.locfileid: '148193051'
---
## Git 트리 정보

Git 트리 개체는 Git 리포지토리의 파일 간에 계층 구조를 만듭니다. Git 트리 개체를 사용하여 디렉터리와 디렉터리에 포함된 파일 간의 관계를 만들 수 있습니다. 해당 엔드포인트를 사용하면 {% data variables.product.product_name %}에서 Git 데이터베이스에 [트리 개체](https://git-scm.com/book/en/v2/Git-Internals-Git-Objects#_tree_objects)를 읽고 쓸 수 있습니다.
