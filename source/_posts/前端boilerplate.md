---
layout: post
title: "前端Boilerplate"
date:       2022-07-06
author:     "Gavin"
header-img: ""
categories:
	-Frontend
tags:

---

1. 使用 create-next-app 脚手架
   npx create-next-app@latest --ts or yarn create next-app --typescript

Following: https://nextjs.org/docs/getting-started
yarn create next-app --typescript
cd my-project

此脚手架配置了 git ts，并初始化了 index 页面
yarn dev 就可以启动项目

自我定制：
mkdir src
mv pages stypes public src
mkdir src/components
