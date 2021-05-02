<!-- Badge for License -->
<div align="right">

  [![](https://img.shields.io/github/license/TeXtw/utter-comments.svg?style=flat-square)](./LICENSE)

</div>

<!-- Logo, Title and Description -->
<div align="center">
  <img src="https://i.imgur.com/9mPRZCC.png" alt="utter-comments" height="150px">
</div>

</div>

<!-- Title and Description -->
<div align="center">

# Utter Comments

📌 _The repository to store comments for site of TWTUG, based on [Utterances](https://github.com/utterance/utterances) / [Beaudar](https://github.com/beaudar/beaudar) - use GitHub issues for comments, wiki pages and more!_

</div>

## 簡介

社群中有許多站點和手冊是透過靜態頁面生成器（Static Site Generators）所構建，為了能夠讓使用者參與討論需要加入評論系統。我們在眾多提供評論系統服務的擴充插件中，選擇使用了將資料保存於 GitHub Issue 的 [Utterances](https://github.com/utterance/utterances) 和 [Beaudar](https://github.com/beaudar/beaudar) 服務。

## 使用說明

兩者的使用方式都是透過在 HTML 檔案中加入一段 JavaScript 腳本，其中的 `repo`、`issue-term`、`theme` 需要根據自己的狀況進行設定：

<table>
<tr>
  <td>Utterances</td>
  <td>Beaudar</td>
</tr>

<tr>
  <td>

```javascript
<script src="https://utteranc.es/client.js"
        repo="[輸入倉庫名稱]"
        issue-term="pathname"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>
```

  </td>
  <td>

```javascript
<script src="https://beaudar.lipk.org/client.js"
        repo="[輸入倉庫名稱]"
        issue-term="pathname"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>
```
  </td>
</tr>
</table>

所有在個別頁面下的評論內容都會以 issue 的型態儲存在指定倉庫下。除此之外，兩者都提供了簡易的設定工具，只需要手動填入倉庫名稱並選擇需求就會產生對應的程式碼：

- [Utterances](https://utteranc.es/)
- [Beaudar](https://beaudar.lipk.org/)

## 授權許可

Licensed under the GNU General Public License v3.0, Copyright © 2020-present TWTUG (Taiwan TeX Users' Group).
