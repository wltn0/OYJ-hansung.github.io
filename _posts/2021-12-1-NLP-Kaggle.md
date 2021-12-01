---
layout: post
title:  "Kaggle NLP with Disaster Tweets"
author: YoungJoo
categories: [ challenge ]
tags: [ kaggle ]
image: assets/images/kaggle.png
rating: 4.5
---

자연어처리(NLP)를 활용해서 서비스를 개발해보고 싶다는 생각에 무작정 말뭉치 데이터셋을 접해봤습니다.

말뭉치 데이터가 어떤것임을 사전에 알고는 있었지만, 이것을 전처리하고 직접활용할 생각을 하니까 너무 막막해서 

어디서부터 시작해야할까? 라는 고민을 하게 되었습니다. 그래서 찾은게 Kaggle의 NLP를 주제로한 경연(competition)입니다.

주재는 'Natural Language Processing with Disaster Tweets'인데요,
특별히 이것을 선택한 이유는, 저와 같이 NLP를 처음 접하는 개발자들에게 좋은 데이터셋이라고 소개 되었기 때문입니다.

> ![image](/assets/images/kaggle_.png)

경연의 내용을 간단하게 설명해드리면, 사람들 사이에 오가는 트윗을 통해서 이상기후와 같은 비상상황(emergency)에 대한 내용을 색출해 내는 것입니다. 

하지만 여기서 중요한것은, 비유적인 표현을 잘 걸러낼 수 있게 해야한다는 것이죠. 

예를 들어서 아래와 같은 상황에서, 글쓴이는 '하늘이 불타고 있다'라고 트윗을 했습니다. 여기서 무엇인가 '불타고' 있으니까 기계가 비상상황을 선포하면 안되겠죠?

> ![image](/assets/images/twitter_ablaze.png)