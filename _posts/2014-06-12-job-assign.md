---
layout: post
category :
tagline : "Project 01"
tags : [job assign]
---
{% include JB/setup %}

## Project

預計6/17(二)展示各模組成果

* 做法
  0.  為了不要重連socket，因此不跳頁
  1.  各模組先用假資料方式建構
  2.  先各位建branch，6/17再視情況合併

* 大廳＆聊天室(Tang&Charles)
	0. 輸入名字並隨機給顏色
	1. 進入大廳聊天
	2. 產生玩家佇列
	3. player 1按開始鍵後，顯示遊戲的DIV

* 遊戲(Eddie&David)
  0.  以假資料模擬多位玩家
  1.  遊戲方式以棋盤式
  2.  每個三角型旁邊顯示各玩家id
  3.  當只剩下一人則顯示勝利畫面
  
* 勝利畫面(Jane&Yuyu)
  0.  依照遊戲結果顯示勝利者
  1.  顯示完再用javascript關閉勝利畫面，顯示聊天室
  
* 畫面(Yvonne)
  0.  完成50%畫面
