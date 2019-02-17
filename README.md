﻿# vueCliPractice

### 安裝vue-cli
打開命令提示自元(cmd)<br>
輸入npm install --global vue-cli<br>
mac or linux 輸入 sudo npm install --global vue-cli<br>
如果你還沒裝npm，那就先裝node.js裝了之後就可以使用npm了<br>
裝完輸入vue就可以看到可用指令<br>
<br>

### 建立專案資料夾<br>
在windows環境底下 在你的專案資料夾下按shift+右鍵 然後選擇開啟命令視窗<br>
也可以直接搜尋cmd然後再把路徑指到你的專案資料夾<br>
總之就是要打開命令提示字元視窗然後把路徑指到你的專案資料夾<br>
<br>

### 建立模板<br>
再來在cmd輸入vue list<br>
就會看到vue-cli可以幫我們建立的模板有幾種<br>
這裡我先建立webpack-simple<br>
所以我需要輸入 vue init webpack-simple vue-lesson<br>
就下來他就會幫我建立一個資料夾叫做vue-lesson<br>
這裡我試過如果我的Project name名稱跟專案資料夾一樣<br>
那就會直接在資料夾建立檔案 而不會多建一個資料夾然後再把資料丟進去<br>
<br>
接著將路徑變換到你新建立的資料夾底下(像我這邊就是輸入cd vue-lesson)<br>
再來在vue-lesson資料夾下安裝npm (輸入npm install)<br>
最後再輸入npm run dev 就可以看到網頁了

### main.js<br>
先看到main.js<br>
new Vue({<br>
  el: '#app',<br>
  render: h => h(App)<br>
})<br>
<br>
render其實是長這樣<br>
new Vue({<br>
  el: '#app',<br>
  render: function(creatElement){<br>
    return creatElement(App);<br>
  }<br>
})<br>


