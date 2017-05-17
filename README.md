初期:
一.基本算法:

    枚舉. (POJ 1753,POJ 2965)
    貪心(POJ 1328,POJ 2109,POJ 2586)
    遞歸和分治法.
    遞推.
    構造法.(POJ 3295)
    模擬法.(POJ 1068,POJ 2632,POJ 1573,POJ 2993,POJ 2996)

二.圖算法:

    圖的深度優先遍歷和廣度優先遍歷.
    最短路徑算法(dijkstra,bellman-ford,floyd,heap+dijkstra) (POJ 1860,POJ 3259,POJ 1062,POJ 2253,POJ 1125,POJ 2240)
    最小生成樹算法(prim,kruskal) (POJ 1789,POJ 2485,POJ 1258,POJ 3026)
    拓撲排序 (POJ 1094)
    二分圖的最大匹配 (匈牙利算法) (POJ 3041,POJ 3020)
    最大流的增廣路算法(KM算法). (POJ 1459,POJ 3436)

三.數據結構.

    串 (POJ 1035,POJ 3080,POJ 1936)
    排序(快排、歸併排(與逆序數有關)、堆排) (POJ 2388,POJ 2299)
    簡單並查集的應用.
    哈希表和二分查找等高效查找法(數的Hash,串的Hash) (POJ 3349,POJ 3274,POJ 2151,POJ 1840,POJ 2002,POJ 2503)
    哈夫曼樹(POJ 3253)
    堆
    trie樹(靜態建樹、動態建樹) (POJ 2513)

四.簡單搜索

    深度優先搜索 (POJ 2488,POJ 3083,POJ 3009,POJ 1321,POJ 2251)
    廣度優先搜索(POJ 3278,POJ 1426,POJ 3126,POJ 3087.POJ 3414)
    簡單搜索技巧和剪枝(POJ 2531,POJ 1416,POJ 2676,POJ 1129)

五.動態規劃

    背包問題. (POJ 1837,POJ 1276)
    型如下表的簡單DP(可參考lrj的書 page149):
        E[j]=opt{D+w(i,j)} (POJ 3267,POJ 1836,POJ 1260,POJ 2533)
        E[i,j]=opt{D[i-1,j]+xi,D[i,j-1]+yj,D[i-1][j-1]+zij} (最長公共子序列) (POJ 3176,POJ 1080,POJ 1159)
        C[i,j]=w[i,j]+opt{C[i,k-1]+C[k,j]}.(最優二分檢索樹問題) 

六.數學

    組合數學:
        加法原理和乘法原理.
        排列組合.
        遞推關係.
        (POJ 3252,POJ 1850,POJ 1019,POJ 1942) 

    數論.
        素數與整除問題
        進制位.
        同余模運算.
        (POJ 2635, POJ 3292,POJ 1845,POJ 2115) 
    計算方法.
        二分法求解單調函數相關知識.(POJ 3273,POJ 3258,POJ 1905,POJ 3122) 

七.計算幾何學.

    幾何公式.
    叉積和點積的運用(如線段相交的判定,點到線段的距離等). (POJ 2031,POJ 1039)
    多邊型的簡單算法(求面積)和相關判定(點在多邊型內,多邊型是否相交) (POJ 1408,POJ 1584)
    凸包. (POJ 2187,POJ 1113)

中級:
一.基本算法:

    C++的標準模版庫的應用. (POJ 3096,POJ 3007)
    較為複雜的模擬題的訓練(POJ 3393,POJ 1472,POJ 3371,POJ 1027,POJ 2706)

二.圖算法:

    差分約束系統的建立和求解. (POJ 1201,POJ 2983)
    最小費用最大流(POJ 2516,POJ 2195)
    雙連通份量(POJ 2942)
    強連通分支及其縮點.(POJ 2186)
    圖的割邊和割點(POJ 3352)
    最小割模型、網絡流規約(POJ 3308)

三.數據結構.

    線段樹. (POJ 2528,POJ 2828,POJ 2777,POJ 2886,POJ 2750)
    靜態二叉檢索樹. (POJ 2482,POJ 2352)
    樹狀樹組(POJ 1195,POJ 3321)
    RMQ. (POJ 3264,POJ 3368)
    並查集的高級應用. (POJ 1703,POJ 2492)
    KMP算法. (POJ 1961,POJ 2406)

四.搜索

    最優化剪枝和可行性剪枝
    搜索的技巧和優化 (POJ 3411,POJ 1724)
    記憶化搜索(POJ 3373,POJ 1691)

五.動態規劃

    較為複雜的動態規劃(如動態規劃解特別的施行商問題等) (POJ 1191,POJ 1054,POJ 3280,POJ 2029,POJ 2948,POJ 1925,POJ 3034)
    記錄狀態的動態規劃. (POJ 3254,POJ 2411,POJ 1185)
    樹型動態規劃(POJ 2057,POJ 1947,POJ 2486,POJ 3140)

六.數學

    組合數學:
        容斥原理.
        抽屜原理.
        置換群與Polya定理(POJ 1286,POJ 2409,POJ 3270,POJ 1026).
        遞推關係和母函數. 

    數學.
        高斯消元法(POJ 2947,POJ 1487,POJ 2065,POJ 1166,POJ 1222)
        概率問題. (POJ 3071,POJ 3440)
        GCD、擴展的歐幾里德(中國剩餘定理) (POJ 3101) 

    計算方法.
        0/1分數規劃. (POJ 2976)
        三分法求解單峰(單谷)的極值.
        矩陣法(POJ 3150,POJ 3422,POJ 3070)
        迭代逼近(POJ 3301) 

    隨機化算法(POJ 3318,POJ 2454)

    雜題. (POJ 1870,POJ 3296,POJ 3286,POJ 1095)

七.計算幾何學.

    坐標離散化.
    掃瞄線算法(例如求矩形的面積和周長並,常和線段樹或堆一起使用). (POJ 1765,POJ 1177,POJ 1151,POJ 3277,POJ 2280,POJ 3004)
    多邊形的內核(半平面交)(POJ 3130,POJ 3335)
    幾何工具的綜合應用.(POJ 1819,POJ 1066,POJ 2043,POJ 3227,POJ 2165,POJ 3429)

高級:
一.基本算法要求:

    代碼快速寫成,精簡但不失風格 (POJ 2525,POJ 1684,POJ 1421,POJ 1048,POJ 2050,POJ 3306)
    保證正確性和高效性. POJ 3434

二.圖算法:

    度限制最小生成樹和第K最短路. (POJ 1639)
    最短路,最小生成樹,二分圖,最大流問題的相關理論(主要是模型建立和求解) (POJ 3155, POJ 2112,POJ 1966,POJ 3281,POJ 1087,POJ 2289,POJ 3216,POJ 2446 )
    最優比率生成樹. (POJ 2728)
    最小樹形圖(POJ 3164)
    次小生成樹.
    無向圖、有向圖的最小環

三.數據結構.

    trie圖的建立和應用. (POJ 2778)
    LCA和RMQ問題(LCA(最近公共祖先問題) 有離線算法(並查集+dfs) 和 在線算法
    (RMQ+dfs)).(POJ 1330)
    雙端隊列和它的應用(維護一個單調的隊列,常常在動態規劃中起到優化狀態轉移
    的目的). (POJ 2823)
    左偏樹(可合併堆).
    後綴樹(非常有用的數據結構,也是賽區考題的熱點). (POJ 3415,POJ 3294)

四.搜索

    較麻煩的搜索題目訓練(POJ 1069,POJ 3322,POJ 1475,POJ 1924,POJ 2049,POJ 3426)
    廣搜的狀態優化:利用M進制數存儲狀態、轉化為串用hash表判重、按位壓縮存儲
    狀態、雙向廣搜、A*算法. (POJ 1768,POJ 1184,POJ 1872,POJ 1324,POJ 2046,POJ 1482)
    深搜的優化:儘量用位運算、一定要加剪枝、函數參數儘可能少、層數不易過大
    、可以考慮雙向搜索或者是輪換搜索、IDA*算法. (POJ 3131,POJ 2870,POJ 2286)

五.動態規劃

    需要用數據結構優化的動態規劃. (POJ 2754,POJ 3378,POJ 3017)
    四邊形不等式理論.
    較難的狀態DP(POJ 3133)

六.數學

    組合數學.
        MoBius反演(POJ 2888,POJ 2154)
        偏序關係理論. 
    博奕論.
        極大極小過程(POJ 3317,POJ 1085)
        Nim問題. 

七.計算幾何學.

    半平面求交(POJ 3384,POJ 2540)
    可視圖的建立(POJ 2966)
    點集最小圓覆蓋.
    對踵點(POJ 2079)

八.綜合題.

(POJ 3109,POJ 1478,POJ 1462,POJ 2729,POJ 2048,POJ 3336,POJ 3315,POJ 2148,POJ 1263)

========
ACM大量習題題庫 

ACM大量習題題庫 
現在網上有許多題庫，大多是可以在線評測，所以叫做Online Judge。除了USACO是為IOI準備外，其餘幾乎全部是大學的ACM競賽題庫。

USACO

http://ace.delos.com/usacogate

美國著名在線題庫，專門為信息學競賽選手準備


TJU

http://acm.tongji.edu.cn/

同濟大學在線題庫，唯一的中文題庫，適合NOIP選手


ZJU

http://acm.zju.edu.cn/

浙江大學在線題庫


JLU

http://acm.jlu.edu.cn/

吉林大學在線題庫（一直上不去）


PKU

http://acm.pku.edu.cn

北京大學在線題庫


URAL

http://acm.timus.ru

俄羅斯烏拉爾大學在線題庫


SGU

http://acm.sgu.ru/

俄羅斯聖薩拉托夫州大學在線題庫


ELJ

http://acm.mipt.ru/judge/bin/problems.pl?lang=en

俄羅斯莫斯科物理技術學院


SPOJ

https://spoj.sphere.pl/

波蘭格但斯克理工大學


UVA

http://acm.uva.es/

西班牙的Universidad de Valladolid在線題


ACM聯繫建議

一位高手對我的建議：

一般要做到50行以內的程序不用調試、100行以內的二分鐘內調試成功.acm主要是考算法的
，主要時間是花在思考算法上，不是花在寫程序與debug上。 
下面給個計劃你練練：

第一階段：
練經典常用算法，下面的每個算法給我打上十到二十遍，同時自己精簡代碼，
因為太常用，所以要練到寫時不用想，10-15分鐘內打完，甚至關掉顯示器都可以把程序打
出來. 
1.最短路(Floyd、Dijstra,BellmanFord) 
2.最小生成樹(先寫個prim,kruscal要用並查集，不好寫) 
3.大數（高精度）加減乘除 
4.二分查找. (代碼可在五行以內) 
5.叉乘、判線段相交、然後寫個凸包. 
6.BFS、DFS,同時熟練hash表(要熟，要靈活,代碼要簡) 
7.數學上的有：輾轉相除（兩行內），線段交點、多角形面積公式. 
8. 調用系統的qsort, 技巧很多，慢慢掌握. 
9. 任意進制間的轉換


第二階段：
練習複雜一點，但也較常用的算法。 
如： 
1. 二分圖匹配（匈牙利），最小路徑覆蓋 
2. 網絡流，最小費用流。 
3. 線段樹. 
4. 並查集。 
5. 熟悉動態規劃的各個典型：LCS、最長遞增子串、三角剖分、記憶化dp 
6.博弈類算法。博弈樹，二進製法等。 
7.最大團，最大獨立集。 
8.判斷點在多邊形內。 
9. 差分約束系統. 
10. 雙向廣度搜索、A*算法，最小耗散優先.


第三階段：
前兩個階段是打基礎，第三階段是鍛鍊在比賽中可以快速建立模型、想新算法
。這就要平時多做做綜合的題型了。 
1. 把oibh上的論文看看（大概幾百篇的，我只看了一點點，呵呵）。 
2. 平時掃掃zoj上的難題啦，別老做那些不用想的題.(中大acm的版主經常說我挑簡單的來
做:-P ) 
3. 多參加網上的比賽，感受一下比賽的氣氛，評估自己的實力. 
4. 一道題不要過了就算，問一下人，有更好的算法也打一下。 
5. 做過的題要記好 :-) 


ACM ICPC學習計劃

大牛給的計劃——
一般要做到50行以內的程序不用調試、100行以內的二分鐘內調試成功.acm主要是考算法的,主要時間是花在思考算法上，不是花在寫程序與debug上。 
下面給個計劃你練練： 
第一階段：練經典常用算法，下面的每個算法給我打上十到二十遍，同時自己精簡代碼，
因為太常用，所以要練到寫時不用想，10-15分鐘內打完，甚至關掉顯示器都可以把程序打
出來. 
1.最短路(Floyd、Dijstra,BellmanFord) 
2.最小生成樹(先寫個prim,kruscal要用並查集，不好寫) 
3.大數（高精度）加減乘除 
4.二分查找. (代碼可在五行以內) 
5.叉乘、判線段相交、然後寫個凸包. 
6.BFS、DFS,同時熟練hash表(要熟，要靈活,代碼要簡) 
7.數學上的有：輾轉相除（兩行內），線段交點、多角形面積公式. 
8. 調用系統的qsort, 技巧很多，慢慢掌握. 
9. 任意進制間的轉換
第二階段：練習複雜一點，但也較常用的算法。 
如： 
1. 二分圖匹配（匈牙利），最小路徑覆蓋 
2. 網絡流，最小費用流。 
3. 線段樹. 
4. 並查集。 
5. 熟悉動態規劃的各個典型：LCS、最長遞增子串、三角剖分、記憶化dp 
6.博弈類算法。博弈樹，二進製法等。 
7.最大團，最大獨立集。 
8.判斷點在多邊形內。 
9. 差分約束系統. 
10. 雙向廣度搜索、A*算法，最小耗散優先.
&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&
ACMer必備知識（這麼多呀，慢慢學了……

圖論



路徑問題

0/1邊權最短路徑

BFS

非負邊權最短路徑（Dijkstra）

可以用Dijkstra解決問題的特徵

負邊權最短路徑

Bellman-Ford

Bellman-Ford的Yen-氏優化

差分約束系統

Floyd

廣義路徑問題

傳遞閉包

極小極大距離 / 極大極小距離

Euler Path / Tour

圈套圈算法

混合圖的 Euler Path / Tour

Hamilton Path / Tour

特殊圖的Hamilton Path / Tour 構造



生成樹問題

最小生成樹

第k小生成樹

最優比率生成樹

0/1分數規劃

度限制生成樹



連通性問題

強大的DFS算法

無向圖連通性

割點

割邊

二連通分支

有向圖連通性

強連通分支

2-SAT

最小點基



有向無環圖

拓撲排序

有向無環圖與動態規劃的關係



二分圖匹配問題

一般圖問題與二分圖問題的轉換思路

最大匹配

有向圖的最小路徑覆蓋

0 / 1矩陣的最小覆蓋

完備匹配

最優匹配

穩定婚姻



網絡流問題

網絡流模型的簡單特徵和與線性規劃的關係

最大流最小割定理

最大流問題

有上下界的最大流問題

循環流

最小費用最大流 / 最大費用最大流



弦圖的性質和判定





組合數學



解決組合數學問題時常用的思想

逼近

遞推 / 動態規劃

概率問題

Polya定理





計算幾何 / 解析幾何



計算幾何的核心：叉積 / 面積

解析幾何的主力：複數



基本形

點

直線，線段

多邊形



凸多邊形 / 凸包

凸包算法的引進，卷包裹法



Graham掃瞄法

水平序的引進，共線凸包的補丁



完美凸包算法



相關判定

兩直線相交

兩線段相交

點在任意多邊形內的判定

點在凸多邊形內的判定



經典問題

最小外接圓

近似O(n)的最小外接圓算法

點集直徑

旋轉卡殼，對踵點

多邊形的三角剖分





數學 / 數論



最大公約數

Euclid算法

擴展的Euclid算法

同余方程 / 二元一次不定方程

同余方程組



線性方程組

高斯消元法

解mod 2域上的線性方程組

整係數方程組的精確解法



矩陣

行列式的計算

利用矩陣乘法快速計算遞推關係



分數

分數樹

連分數逼近



數論計算

求N的約數個數

求phi(N)

求約數和

快速數論變換

……



素數問題

概率判素算法

概率因子分解





數據結構



組織結構

二叉堆

左偏樹

二項樹

勝者樹

跳躍表

樣式圖標

斜堆

reap



統計結構

樹狀數組

虛二叉樹

線段樹

矩形面積並

圓形面積並



關係結構

Hash表

並查集

路徑壓縮思想的應用



STL中的數據結構

vector

deque

set / map





動態規劃 / 記憶化搜索



動態規劃和記憶化搜索在思考方式上的區別



最長子序列系列問題

最長不下降子序列

最長公共子序列

最長公共不下降子序列



一類NP問題的動態規劃解法



樹型動態規劃



背包問題



動態規劃的優化

四邊形不等式

函數的凸凹性

狀態設計

規劃方向





線性規劃



常用思想



二分

最小表示法



串



KMP

Trie結構

後綴樹/後綴數組

LCA/RMQ

有限狀態自動機理論



排序

選擇/冒泡

快速排序

堆排序

歸併排序

基數排序

拓撲排序

排序網絡


熟練掌握數據結構、常用算法匯聚



（一）

不可能都完全記住那麼多的算法. 
常用算法,拿過來就可以寫出來 
不常用的,拿起書來,看10分鐘,就能理解算法(因為以前記過). 
對以前沒有記過的算法,就不好說了,難的可能要研究好幾天. 
這樣就可以了. 

應該熟練掌握的常用的算法應該有: 
各種排序算法（插入排序、冒泡排序、選擇排序，快速排序，堆排序，歸併排序） 
線性表(一般的線性表,棧,隊列)的插入和刪除 
二叉樹的遍歷（前序，中序，後序） 
圖的遍歷（深度優先，廣度優先） 
二分法查找，排序二叉樹，Hash查找（處理衝突的方法）。 


（二）

分析一個東西,你可以用不同的眼光去看待,有很多時候,就跟自己生活一樣,覺得小時候看待問題很幼稚,現在看問題全面了,而且方式不一樣了,為什麼,就是成長吧,就跟這個一樣的,你對算法,比如寫一個程序,可能直接寫很簡單,可是可以有一些有趣的方式,比如通過什麼樣來表達,怎麼樣更高效..等等吧



（三）



於大學裡把基本的專業課學紮實就ok，如：數據結構，離散，操作系統等。碰到一些基本的數據結構和算法，如查找排序要根據原理馬上能寫出相應的代碼就行了，我個人是這樣理解的，對於更深層次的東西，也是建立在自己熟練的基礎之上的吧



（四）

算法與數據結構考驗試題精析》第2版 機械工業出版社 
如果你想練習的話，這裡有N多的題可以來練習，但實際中能用到的比較少，除非搞一些高端的玩意，不過平時也可以在自己的項目中結合使用



（五）



數據結構在平時可能用不上，但數據結構可以培養你程序時如果注意效率的意識，一個學過數據結構的人和一個沒有學過數結構的人寫出來的程序可能在效率上有差別。



（六）

搞ACM需要的掌握的算法. 
要注意,ACM的競賽性強,因此自己應該和自己的實際應用聯繫起來. 
適合自己的才是好的,有的人不適合搞算法,喜歡系統架構,因此不要看到別人什麼就眼紅, 
發揮自己的長處,這才是重要的. 


第一階段：練經典常用算法，下面的每個算法給我打上十到二十遍，同時自己精簡代碼， 
因為太常用，所以要練到寫時不用想，10-15分鐘內打完，甚至關掉顯示器都可以把程序打 
出來. 
1.最短路(Floyd、Dijstra,BellmanFord) 
2.最小生成樹(先寫個prim,kruscal要用並查集，不好寫) 
3.大數（高精度）加減乘除 
4.二分查找. (代碼可在五行以內) 
5.叉乘、判線段相交、然後寫個凸包. 
6.BFS、DFS,同時熟練hash表(要熟，要靈活,代碼要簡) 
7.數學上的有：輾轉相除（兩行內），線段交點、多角形面積公式. 
8. 調用系統的qsort, 技巧很多，慢慢掌握. 
9. 任意進制間的轉換 

第二階段：練習複雜一點，但也較常用的算法。 
如： 
1. 二分圖匹配（匈牙利），最小路徑覆蓋 
2. 網絡流，最小費用流。 
3. 線段樹. 
4. 並查集。 
5. 熟悉動態規劃的各個典型：LCS、最長遞增子串、三角剖分、記憶化dp 
6.博弈類算法。博弈樹，二進製法等。 
7.最大團，最大獨立集。 
8.判斷點在多邊形內。 
9. 差分約束系統. 
10. 雙向廣度搜索、A*算法，最小耗散優先. 



相關的知識 

圖論 

路徑問題 
0/1邊權最短路徑 
BFS 
非負邊權最短路徑（Dijkstra） 
可以用Dijkstra解決問題的特徵 
負邊權最短路徑 
Bellman-Ford 
Bellman-Ford的Yen-氏優化 
差分約束系統 
Floyd 
廣義路徑問題 
傳遞閉包 
極小極大距離 / 極大極小距離 
Euler Path / Tour 
圈套圈算法 
混合圖的 Euler Path / Tour 
Hamilton Path / Tour 
特殊圖的Hamilton Path / Tour 構造 

生成樹問題 
最小生成樹 
第k小生成樹 
最優比率生成樹 
0/1分數規劃 
度限制生成樹 

連通性問題 
強大的DFS算法 
無向圖連通性 
割點 
割邊 
二連通分支 
有向圖連通性 
強連通分支 
2-SAT 
最小點基 

有向無環圖 
拓撲排序 
有向無環圖與動態規劃的關係 

二分圖匹配問題 
一般圖問題與二分圖問題的轉換思路 
最大匹配 
有向圖的最小路徑覆蓋 
0 / 1矩陣的最小覆蓋 
完備匹配 
最優匹配 
穩定婚姻 

網絡流問題 
網絡流模型的簡單特徵和與線性規劃的關係 
最大流最小割定理 
最大流問題 
有上下界的最大流問題 
循環流 
最小費用最大流 / 最大費用最大流 

弦圖的性質和判定 


組合數學 

解決組合數學問題時常用的思想 
逼近 
遞推 / 動態規劃 
概率問題 
Polya定理 


計算幾何 / 解析幾何 

計算幾何的核心：叉積 / 面積 
解析幾何的主力：複數 

基本形 
點 
直線，線段 
多邊形 

凸多邊形 / 凸包 
凸包算法的引進，卷包裹法 

Graham掃瞄法 
水平序的引進，共線凸包的補丁 

完美凸包算法 

相關判定 
兩直線相交 
兩線段相交 
點在任意多邊形內的判定 
點在凸多邊形內的判定 

經典問題 
最小外接圓 
近似O(n)的最小外接圓算法 
點集直徑 
旋轉卡殼，對踵點 
多邊形的三角剖分 


數學 / 數論 

最大公約數 
Euclid算法 
擴展的Euclid算法 
同余方程 / 二元一次不定方程 
同余方程組 

線性方程組 
高斯消元法 
解mod 2域上的線性方程組 
整係數方程組的精確解法 

矩陣 
行列式的計算 
利用矩陣乘法快速計算遞推關係 

分數 
分數樹 
連分數逼近 

數論計算 
求N的約數個數 
求phi(N) 
求約數和 
快速數論變換 
…… 

素數問題 
概率判素算法 
概率因子分解 


數據結構 

組織結構 
二叉堆 
左偏樹 
二項樹 
勝者樹 
跳躍表 
樣式圖標 
斜堆 
reap 

統計結構 
樹狀數組 
虛二叉樹 
線段樹 
矩形面積並 
圓形面積並 

關係結構 
Hash表 
並查集 
路徑壓縮思想的應用 

STL中的數據結構 
vector 
deque 
set / map 


動態規劃 / 記憶化搜索 

動態規劃和記憶化搜索在思考方式上的區別 

最長子序列系列問題 
最長不下降子序列 
最長公共子序列 
最長公共不下降子序列 

一類NP問題的動態規劃解法 

樹型動態規劃 

背包問題 

動態規劃的優化 
四邊形不等式 
函數的凸凹性 
狀態設計 
規劃方向 


線性規劃 

常用思想 

二分 最小表示法 

串 

KMP Trie結構 
後綴樹/後綴數組 LCA/RMQ 
有限狀態自動機理論 

排序 
選擇/冒泡 快速排序 堆排序 歸併排序 
基數排序 拓撲排序 排序網絡 


中級: 
一.基本算法: 
(1)C++的標準模版庫的應用. (poj3096,poj3007) 
(2)較為複雜的模擬題的訓練(poj3393,poj1472,poj3371,poj1027,poj2706) 
二.圖算法: 
(1)差分約束系統的建立和求解. (poj1201,poj2983) 
(2)最小費用最大流(poj2516,poj2516,poj2195) 
(3)雙連通份量(poj2942) 
(4)強連通分支及其縮點.(poj2186) 
(5)圖的割邊和割點(poj3352) 
(6)最小割模型、網絡流規約(poj3308, ) 
三.數據結構. 
(1)線段樹. (poj2528,poj2828,poj2777,poj2886,poj2750) 
(2)靜態二叉檢索樹. (poj2482,poj2352) 
(3)樹狀樹組(poj1195,poj3321) 
(4)RMQ. (poj3264,poj3368) 
(5)並查集的高級應用. (poj1703,2492) 
(6)KMP算法. (poj1961,poj2406) 
四.搜索 
(1)最優化剪枝和可行性剪枝 
(2)搜索的技巧和優化 (poj3411,poj1724) 
(3)記憶化搜索(poj3373,poj1691) 

五.動態規劃 
(1)較為複雜的動態規劃(如動態規劃解特別的施行商問題等) 
(poj1191,poj1054,poj3280,poj2029,poj2948,poj1925,poj3034) 
(2)記錄狀態的動態規劃. (POJ3254,poj2411,poj1185) 
(3)樹型動態規劃(poj2057,poj1947,poj2486,poj3140) 
六.數學 
(1)組合數學: 
1.容斥原理. 
2.抽屜原理. 
3.置換群與Polya定理(poj1286,poj2409,poj3270,poj1026). 
4.遞推關係和母函數. 

(2)數學. 
1.高斯消元法(poj2947,poj1487, poj2065,poj1166,poj1222) 
2.概率問題. (poj3071,poj3440) 
3.GCD、擴展的歐幾里德(中國剩餘定理) (poj3101) 
(3)計算方法. 
1.0/1分數規劃. (poj2976) 
2.三分法求解單峰(單谷)的極值. 
3.矩陣法(poj3150,poj3422,poj3070) 
4.迭代逼近(poj3301) 
(4)隨機化算法(poj3318,poj2454) 
(5)雜題. 
(poj1870,poj3296,poj3286,poj1095) 
七.計算幾何學. 
(1)坐標離散化. 
(2)掃瞄線算法(例如求矩形的面積和周長並,常和線段樹或堆一起使用). 
(poj1765,poj1177,poj1151,poj3277,poj2280,poj3004) 
(3)多邊形的內核(半平面交)(poj3130,poj3335) 
(4)幾何工具的綜合應用.(poj1819,poj1066,poj2043,poj3227,poj2165,poj3429) 


高級: 
一.基本算法要求: 
(1)代碼快速寫成,精簡但不失風格 
(poj2525,poj1684,poj1421,poj1048,poj2050,poj3306) 
(2)保證正確性和高效性. poj3434 
二.圖算法: 
(1)度限制最小生成樹和第K最短路. (poj1639) 
(2)最短路,最小生成樹,二分圖,最大流問題的相關理論(主要是模型建立和求解) 
(poj3155, poj2112,poj1966,poj3281,poj1087,poj2289,poj3216,poj2446 
(3)最優比率生成樹. (poj2728) 
(4)最小樹形圖(poj3164) 
(5)次小生成樹. 
(6)無向圖、有向圖的最小環 
三.數據結構. 
(1)trie圖的建立和應用. (poj2778) 
(2)LCA和RMQ問題(LCA(最近公共祖先問題) 有離線算法(並查集+dfs) 和 在線算法 
(RMQ+dfs)).(poj1330) 
(3)雙端隊列和它的應用(維護一個單調的隊列,常常在動態規劃中起到優化狀態轉移的 
目的). (poj2823) 
(4)左偏樹(可合併堆). 
(5)後綴樹(非常有用的數據結構,也是賽區考題的熱點). 
(poj3415,poj3294) 
四.搜索 
(1)較麻煩的搜索題目訓練(poj1069,poj3322,poj1475,poj1924,poj2049,poj3426) 
(2)廣搜的狀態優化:利用M進制數存儲狀態、轉化為串用hash表判重、按位壓縮存儲狀態、雙向廣搜、A*算法. (poj1768,poj1184,poj1872,poj1324,poj2046,poj1482) 
(3)深搜的優化:儘量用位運算、一定要加剪枝、函數參數儘可能少、層數不易過大、可以考慮雙向搜索或者是輪換搜索、IDA*算法. (poj3131,poj2870,poj2286) 
五.動態規劃 
(1)需要用數據結構優化的動態規劃. 
(poj2754,poj3378,poj3017) 
(2)四邊形不等式理論. 
(3)較難的狀態DP(poj3133) 
六.數學 
(1)組合數學. 
1.MoBius反演(poj2888,poj2154) 
2.偏序關係理論. 
(2)博奕論. 
1.極大極小過程(poj3317,poj1085) 
2.Nim問題. 
七.計算幾何學. 
(1)半平面求交(poj3384,poj2540) 
(2)可視圖的建立(poj2966) 
(3)點集最小圓覆蓋. 
(4)對踵點(poj2079) 
八.綜合題. 
(poj3109,poj1478,poj1462,poj2729,poj2048,poj3336,poj3315,poj2148,poj1263) 

初期: 
一.基本算法: 
(1)枚舉. (poj1753,poj2965) (2)貪心(poj1328,poj2109,poj2586) 
(3)遞歸和分治法. (4)遞推. 
(5)構造法.(poj3295) (6)模擬法.(poj1068,poj2632,poj1573,poj2993,poj2996) 
二.圖算法: 
(1)圖的深度優先遍歷和廣度優先遍歷. 
(2)最短路徑算法(dijkstra,bellman-ford,floyd,heap+dijkstra) 
(poj1860,poj3259,poj1062,poj2253,poj1125,poj2240) 
(3)最小生成樹算法(prim,kruskal) 
(poj1789,poj2485,poj1258,poj3026) 
(4)拓撲排序 (poj1094) 
(5)二分圖的最大匹配 (匈牙利算法) (poj3041,poj3020) 
(6)最大流的增廣路算法(KM算法). (poj1459,poj3436) 
三.數據結構. 
(1)串 (poj1035,poj3080,poj1936) 
(2)排序(快排、歸併排(與逆序數有關)、堆排) (poj2388,poj2299) 
(3)簡單並查集的應用. 
(4)哈希表和二分查找等高效查找法(數的Hash,串的Hash) 
(poj3349,poj3274,POJ2151,poj1840,poj2002,poj2503) 
(5)哈夫曼樹(poj3253) 
(6)堆 
(7)trie樹(靜態建樹、動態建樹) (poj2513) 
四.簡單搜索 
(1)深度優先搜索 (poj2488,poj3083,poj3009,poj1321,poj2251) 
(2)廣度優先搜索(poj3278,poj1426,poj3126,poj3087.poj3414) 
(3)簡單搜索技巧和剪枝(poj2531,poj1416,poj2676,1129) 
五.動態規劃 
(1)背包問題. (poj1837,poj1276) 
(2)型如下表的簡單DP(可參考lrj的書 page149): 
1.E[j]=opt{D+w(i,j)} (poj3267,poj1836,poj1260,poj2533) 
2.E[i,j]=opt{D[i-1,j]+xi,D[i,j-1]+yj,D[i-1][j-1]+zij} (最長公共子序列) 
(poj3176,poj1080,poj1159) 
3.C[i,j]=w[i,j]+opt{C[i,k-1]+C[k,j]}.(最優二分檢索樹問題) 
六.數學 
(1)組合數學: 
1.加法原理和乘法原理. 
2.排列組合. 
3.遞推關係. 
(POJ3252,poj1850,poj1019,poj1942) 
(2)數論. 
1.素數與整除問題 
2.進制位. 
3.同余模運算. 
(poj2635, poj3292,poj1845,poj2115) 
(3)計算方法. 
1.二分法求解單調函數相關知識.(poj3273,poj3258,poj1905,poj3122) 
七.計算幾何學. 
(1)幾何公式. 
(2)叉積和點積的運用(如線段相交的判定,點到線段的距離等). (poj2031,poj1039) 
(3)多邊型的簡單算法(求面積)和相關判定(點在多邊型內,多邊型是否相交) 
(poj1408,poj1584) 
(4)凸包. (poj2187,poj1113) 

（七）



第一階段：練經典常用算法，下面的每個算法給我打上十到二十遍，同時自己精簡代碼， 
因為太常用，所以要練到寫時不用想，10-15分鐘內打完，甚至關掉顯示器都可以把程序打 
出來. 
1.最短路(Floyd、Dijstra,BellmanFord) 
2.最小生成樹(先寫個prim,kruscal要用並查集，不好寫) 
3.大數（高精度）加減乘除 
4.二分查找. (代碼可在五行以內) 
5.叉乘、判線段相交、然後寫個凸包. 
6.BFS、DFS,同時熟練hash表(要熟，要靈活,代碼要簡) 
7.數學上的有：輾轉相除（兩行內），線段交點、多角形面積公式. 
8. 調用系統的qsort, 技巧很多，慢慢掌握. 
9. 任意進制間的轉換 

第二階段：練習複雜一點，但也較常用的算法。 
如： 
1. 二分圖匹配（匈牙利），最小路徑覆蓋 
2. 網絡流，最小費用流。 
3. 線段樹. 
4. 並查集。 
5. 熟悉動態規劃的各個典型：LCS、最長遞增子串、三角剖分、記憶化dp 
6.博弈類算法。博弈樹，二進製法等。 
7.最大團，最大獨立集。 
8.判斷點在多邊形內。 
9. 差分約束系統. 
10. 雙向廣度搜索、A*算法，最小耗散優先. 

（八）

搞實際項目的話基本用不著多少。lss說的那點都已經多了。當然，偶個人覺得，判斷一個問題是否NPC/NPH還是比較有用的，判是以後就不會把自己的經歷浪費在尋找多項式算法上了。這點acm要用，實際項目偶覺得也有用。 

acm的話上面貼的那一長串還不夠用。所謂不夠用，第一，指這些就算都會都不會寫錯，不會建立dp模型不會建立圖論模型的話一樣能掛得很慘，這種活的東西不是死做題就能會的。第二，這表還不全。既然圖可以扯到最優比率生成樹，那博弈的話至少也得扯SG定理，串的話至少也得扯AC自動機（吐槽：不是自動AC機），



（九）補充中。。。。



浙江大學 http://acm.zju.edu.cn 北京大學 http://acm.pku.edu.cn/JudgeOnline 
天津大學 http://acm.tju.edu.cn 廈門大學 http://acm.xmu.edu.cn/JudgeOnline 
福州大學 http://acm.fzu.edu.cn 華中科技 http://acm.hust.edu.cn/JudgeOnline 
寧波理工 http://acm.nit.net.cn 合肥工大 http://acm.tdzl.net:83/JudgeOnline 
汕頭大學 http://acm.stu.edu.cn 北大內部 http://ai.pku.cn/JudgeOnline 
中國科大 http://acm.ustc.edu.cn 暨南大學 http://202.116.24.78/JudgeOnline 
浙江工業 http://acm.zjut.edu.cn 中山大學 http://202.116.77.69/sicily 
福建師範 http://acm.fjnu.edu.cn 哈工業大 http://acm.hit.edu.cn/ojs/ojs.php 
杭電科大 http://acm.hziee.edu.cn 四川大學 http://acm.scu.edu.cn/soj 
哈工程大 http://acm.hrbeu.edu.cn 武漢大學 http://acm.whu.edu.cn/noah 
同濟大學 http://acm.tongji.edu.cn 湖南大學 http://acm.hnu.cn:8080/online/? 
上海大學 http://pc.shu.edu.cn/openjudge/problemlist.php 
蘭州大學 http://acm.sundayclub.cn/JudgeOnline/problemlist 



OJ上的一些水題(可用來練手和增加自信) 
(poj3299,poj2159,poj2739,poj1083,poj2262,poj1503,poj3006,poj2255,poj3094) 
初期: 
一.基本算法: 
(1)枚舉. (poj1753,poj2965) 
(2)貪心(poj1328,poj2109,poj2586) 
(3)遞歸和分治法. 
(4)遞推. 
(5)構造法.(poj3295) 
(6)模擬法.(poj1068,poj2632,poj1573,poj2993,poj2996) 
二.圖算法: 
(1)圖的深度優先遍歷和廣度優先遍歷. 
(2)最短路徑算法(dijkstra,bellman-ford,floyd,heap+dijkstra) 
(poj1860,poj3259,poj1062,poj2253,poj1125,poj2240) 
(3)最小生成樹算法(prim,kruskal) 
(poj1789,poj2485,poj1258,poj3026) 
(4)拓撲排序 (poj1094) 
(5)二分圖的最大匹配 (匈牙利算法) (poj3041,poj3020) 
(6)最大流的增廣路算法(KM算法). (poj1459,poj3436) 
三.數據結構. 
(1)串 (poj1035,poj3080,poj1936) 
(2)排序(快排、歸併排(與逆序數有關)、堆排) (poj2388,poj2299) 
(3)簡單並查集的應用. 
(4)哈希表和二分查找等高效查找法(數的Hash,串的Hash) 
(poj3349,poj3274,POJ2151,poj1840,poj2002,poj2503) 
(5)哈夫曼樹(poj3253) 
(6)堆 
(7)trie樹(靜態建樹、動態建樹) (poj2513) 
四.簡單搜索 
(1)深度優先搜索 (poj2488,poj3083,poj3009,poj1321,poj2251) 
(2)廣度優先搜索(poj3278,poj1426,poj3126,poj3087.poj3414) 
(3)簡單搜索技巧和剪枝(poj2531,poj1416,poj2676,1129) 
五.動態規劃 
(1)背包問題. (poj1837,poj1276) 
(2)型如下表的簡單DP(可參考lrj的書 page149): 
1.E[j]=opt{D[i]+w(i,j)} (poj3267,poj1836,poj1260,poj2533) 
2.E[i,j]=opt{D[i-1,j]+xi,D[i,j-1]+yj,D[i-1][j-1]+zij} (最長公共子序列) 
(poj3176,poj1080,poj1159) 
3.C[i,j]=w[i,j]+opt{C[i,k-1]+C[k,j]}.(最優二分檢索樹問題) 
六.數學 
(1)組合數學: 
1.加法原理和乘法原理. 
2.排列組合. 
3.遞推關係. 
(POJ3252,poj1850,poj1019,poj1942) 
(2)數論. 
1.素數與整除問題 
2.進制位. 
3.同余模運算. 
(poj2635, poj3292,poj1845,poj2115) 
(3)計算方法. 
1.二分法求解單調函數相關知識.(poj3273,poj3258,poj1905,poj3122) 
七.計算幾何學. 
(1)幾何公式. 
(2)叉積和點積的運用(如線段相交的判定,點到線段的距離等). (poj2031,poj1039) 
(3)多邊型的簡單算法(求面積)和相關判定(點在多邊型內,多邊型是否相交) 
(poj1408,poj1584) 
(4)凸包. (poj2187,poj1113) 
中級: 
一.基本算法: 
(1)C++的標準模版庫的應用. (poj3096,poj3007) 
(2)較為複雜的模擬題的訓練(poj3393,poj1472,poj3371,poj1027,poj2706) 
二.圖算法: 
(1)差分約束系統的建立和求解. (poj1201,poj2983) 
(2)最小費用最大流(poj2516,poj2516,poj2195) 
(3)雙連通份量(poj2942) 
(4)強連通分支及其縮點.(poj2186) 
(5)圖的割邊和割點(poj3352) 
(6)最小割模型、網絡流規約(poj3308, ) 
三.數據結構. 
(1)線段樹. (poj2528,poj2828,poj2777,poj2886,poj2750) 
(2)靜態二叉檢索樹. (poj2482,poj2352) 
(3)樹狀樹組(poj1195,poj3321) 
(4)RMQ. (poj3264,poj3368) 
(5)並查集的高級應用. (poj1703,2492) 
(6)KMP算法. (poj1961,poj2406) 
四.搜索 
(1)最優化剪枝和可行性剪枝 
(2)搜索的技巧和優化 (poj3411,poj1724) 
(3)記憶化搜索(poj3373,poj1691) 

五.動態規劃 
(1)較為複雜的動態規劃(如動態規劃解特別的施行商問題等) 
(poj1191,poj1054,poj3280,poj2029,poj2948,poj1925,poj3034) 
(2)記錄狀態的動態規劃. (POJ3254,poj2411,poj1185) 
(3)樹型動態規劃(poj2057,poj1947,poj2486,poj3140) 
六.數學 
(1)組合數學: 
1.容斥原理. 
2.抽屜原理. 
3.置換群與Polya定理(poj1286,poj2409,poj3270,poj1026). 
4.遞推關係和母函數. 

(2)數學. 
1.高斯消元法(poj2947,poj1487, poj2065,poj1166,poj1222) 
2.概率問題. (poj3071,poj3440) 
3.GCD、擴展的歐幾里德(中國剩餘定理) (poj3101) 
(3)計算方法. 
1.0/1分數規劃. (poj2976) 
2.三分法求解單峰(單谷)的極值. 
3.矩陣法(poj3150,poj3422,poj3070) 
4.迭代逼近(poj3301) 
(4)隨機化算法(poj3318,poj2454) 
(5)雜題. 
(poj1870,poj3296,poj3286,poj1095) 
七.計算幾何學. 
(1)坐標離散化. 
(2)掃瞄線算法(例如求矩形的面積和周長並,常和線段樹或堆一起使用). 
(poj1765,poj1177,poj1151,poj3277,poj2280,poj3004) 
(3)多邊形的內核(半平面交)(poj3130,poj3335) 
(4)幾何工具的綜合應用.(poj1819,poj1066,poj2043,poj3227,poj2165,poj3429) 
高級: 
一.基本算法要求: 
(1)代碼快速寫成,精簡但不失風格 
(poj2525,poj1684,poj1421,poj1048,poj2050,poj3306) 
(2)保證正確性和高效性. poj3434 
二.圖算法: 
(1)度限制最小生成樹和第K最短路. (poj1639) 
(2)最短路,最小生成樹,二分圖,最大流問題的相關理論(主要是模型建立和求解) 
(poj3155, poj2112,poj1966,poj3281,poj1087,poj2289,poj3216,poj2446 
(3)最優比率生成樹. (poj2728) 
(4)最小樹形圖(poj3164) 
(5)次小生成樹. 
(6)無向圖、有向圖的最小環 
三.數據結構. 
(1)trie圖的建立和應用. (poj2778) 
(2)LCA和RMQ問題(LCA(最近公共祖先問題) 有離線算法(並查集+dfs) 和 在線算法 
(RMQ+dfs)).(poj1330) 
(3)雙端隊列和它的應用(維護一個單調的隊列,常常在動態規劃中起到優化狀態轉移的 
目的). (poj2823) 
(4)左偏樹(可合併堆). 
(5)後綴樹(非常有用的數據結構,也是賽區考題的熱點). 
(poj3415,poj3294) 
四.搜索 
(1)較麻煩的搜索題目訓練(poj1069,poj3322,poj1475,poj1924,poj2049,poj3426) 
(2)廣搜的狀態優化:利用M進制數存儲狀態、轉化為串用hash表判重、按位壓縮存儲狀態、雙向廣搜、A*算法. (poj1768,poj1184,poj1872,poj1324,poj2046,poj1482) 
(3)深搜的優化:儘量用位運算、一定要加剪枝、函數參數儘可能少、層數不易過大、可以考慮雙向搜索或者是輪換搜索、IDA*算法. (poj3131,poj2870,poj2286) 
五.動態規劃 
(1)需要用數據結構優化的動態規劃. 
(poj2754,poj3378,poj3017) 
(2)四邊形不等式理論. 
(3)較難的狀態DP(poj3133) 
六.數學 
(1)組合數學. 
1.MoBius反演(poj2888,poj2154) 
2.偏序關係理論. 
(2)博奕論. 
1.極大極小過程(poj3317,poj1085) 
2.Nim問題. 
七.計算幾何學. 
(1)半平面求交(poj3384,poj2540) 
(2)可視圖的建立(poj2966) 
(3)點集最小圓覆蓋. 
(4)對踵點(poj2079) 
八.綜合題. 
(poj3109,poj1478,poj1462,poj2729,poj2048,poj3336,poj3315,poj2148,poj1263)



同時由於個人練習的時候可能有些偏向性,可能上面的總結不是很全,還請大家提出和指正,而且由於ACM的題目中專門針對某個算法的題目可能比較少出現,所以上面的分類中的題有可能有多種解法或者是一些算法的綜合,這都不會影響大家做題,希望練習的同學能夠認真,紮實地訓練,做到真正的理解算法,掌握算法.同時在論壇上還有許多前輩的分類,總結,大家也可以按自己的情況採用.注意FTP上有很多的資料,希望大家好好地利用.


如果同學能在明年暑假前能掌握上面大部分算法,那你也基本上達到了訓練的目的,到暑假的時候你就可以選擇自己比較喜歡的方面進行加深和強化,而且同學們不要覺得看算法的證明是很麻煩的事,這可以加強你的思維能力,這在ACM中也很重要.同時也希望老隊員能幫助我整理習題和題目分類.同時ACM的題目是沒有範圍的,只能在平時中多積累多練習,多比別人多努力一點,你就會比別人多一線希望.


我補充些動態規劃、搜索方面的資料吧。 

Dp狀態設計與方程總結 

1.不完全狀態記錄 
<1>青蛙過河問題 
<2>利用區間dp 
2.背包類問題 
<1> 0-1背包，經典問題 
<2>無限背包，經典問題 
<3>判定性背包問題 
<4>帶附屬關係的背包問題 
<5> + -1背包問題 
<6>雙背包求最優值 
<7>構造三角形問題 
<8>帶上下界限制的背包問題(012背包) 
3.線性的動態規劃問題 
<1>積木遊戲問題 
<2>決鬥（判定性問題） 
<3>圓的最大多邊形問題 
<4>統計單詞個數問題 
<5>棋盤分割 
<6>日程安排問題 
<7>最小逼近問題(求出兩數之比最接近某數/兩數之和等於某數等等) 
<8>方塊消除遊戲(某區間可以連續消去求最大效益) 
<9>資源分配問題 
<10>數字三角形問題 
<11>漂亮的打印 
<12>郵局問題與構造答案 
<13>最高積木問題 
<14>兩段連續和最大 
<15>2次冪和問題 
<16>N個數的最大M段子段和 
<17>交叉最大數問題 
4.判定性問題的dp(如判定整除、判定可達性等) 
<1>模K問題的dp 
<2>特殊的模K問題，求最大(最小)模K的數 
<3>變換數問題 
5.單調性優化的動態規劃 
<1>1-SUM問題 
<2>2-SUM問題 
<3>序列劃分問題(單調隊列優化) 
6.剖分問題(多邊形剖分/石子合併/圓的剖分/乘積最大) 
<1>凸多邊形的三角剖分問題 
<2>乘積最大問題 
<3>多邊形遊戲(多邊形邊上是操作符,頂點有權值) 
<4>石子合併(N^3/N^2/NLogN各種優化) 
7.貪心的動態規劃 
<1>最優裝載問題 
<2>部分背包問題 
<3>乘船問題 
<4>貪心策略 
<5>雙機調度問題Johnson算法 
8.狀態dp 
<1>牛仔射擊問題(博弈類) 
<2>哈密頓路徑的狀態dp 
<3>兩支點天平平衡問題 
<4>一個有向圖的最接近二部圖 
9.樹型dp 
<1>完美服務器問題(每個節點有3種狀態) 
<2>小胖守皇宮問題 
<3>網絡收費問題 
<4>樹中漫遊問題 
<5>樹上的博弈 
<6>樹的最大獨立集問題 
<7>樹的最大平衡值問題 
<8>構造樹的最小環



先掌握搜索，動態規劃，貪心這些思想方法 
然後學習各種技巧

ACM基本算法分類



ACM基本算法分類、推薦學習資料和配套pku習題一.動態規劃 

參考資料： 

劉汝佳《算法藝術與信息學競賽》《算法導論》 

推薦題目： 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1141 

簡單 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2288 

中等，經典TSP問題 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2411 

中等，狀態壓縮DP 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1112 

中等 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1848 

中等，樹形DP。可參考《算法藝術與信息學競賽》動態規劃一節的樹狀模型 

http://acm.zju.edu.cn/show_problem.php?pid=1234 

中等，《算法藝術與信息學競賽》中的習題 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1947 

中等，《算法藝術與信息學競賽》中的習題 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1946 

中等，《算法藝術與信息學競賽》中的習題 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1737 

中等，遞推 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1821 

中等，需要減少冗餘計算 

http://acm.zju.edu.cn/show_problem.php?pid=2561 

中等，四邊形不等式的簡單應用 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1038 

較難，狀態壓縮DP，《算法藝術與信息學競賽》中有解答 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1390 

較難，《算法藝術與信息學競賽》中有解答 

http://acm.pku.edu.cn/JudgeOnline/problem?id=3017 

較難，需要配合數據結構優化（我的題目^_^） 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1682 

較難，寫起來比較麻煩 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2047 

較難 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2152 

難，樹形DP 

http://acm.pku.edu.cn/JudgeOnline/problem?id=3028 

難，狀態壓縮DP，題目很有意思 

http://acm.pku.edu.cn/JudgeOnline/problem?id=3124 

難 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2915 

非常難 



二.搜索 

參考資料： 

劉汝佳《算法藝術與信息學競賽》 

推薦題目： 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1011 

簡單，深搜入門題 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1324 

中等，廣搜 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2044 

中等，廣搜 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2286 

較難，廣搜 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1945 

難，IDA*，迭代加深搜索，需要較好的啟發函數 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2449 

難，可重複K最短路，A*。可參考解題報告: 

http://acm.pku.edu.cn/JudgeOnline/showcontest?contest_id=1144 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1190 

難，深搜剪枝，《算法藝術與信息學競賽》中有解答 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1084 

難，《算法藝術與信息學競賽》習題 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2989 

難，深搜 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1167 

較難，《算法藝術與信息學競賽》中有解答 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1069 

很難 


三. 常用數據結構 

參考資料： 

劉汝佳《算法藝術與信息學競賽》 

《算法導論》 

線段樹資料： 

http://home.ustc.edu.cn/~zhuhcheng/ACM/segment_tree.pdf 

樹狀數組資料 

http://home.ustc.edu.cn/~zhuhcheng/ACM/tree.ppt 

關於線段樹和樹狀數組更多相關內容可在網上搜到

後綴數組資料 

http://home.ustc.edu.cn/~zhuhcheng/ACM/suffix_array.pdf 

http://home.ustc.edu.cn/~zhuhcheng/ACM/linear_suffix.pdf 

推薦題目 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2482 

較難，線段樹應用，《算法藝術與信息學競賽》中有解答 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1151 

簡單，線段樹應用矩形面積並，《算法藝術與信息學競賽》中有解答 

http://acm.pku.edu.cn/JudgeOnline/problem?id=3225 

較難，線段樹應用，可參考解題報告 

http://acm.pku.edu.cn/JudgeOnline/showcontest?contest_id=1233 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2155 

難，二維樹狀數組。 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2777 

中等，線段樹應用。 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2274 

難，堆的應用，《算法藝術與信息學競賽》中有解答 

http://acm.zju.edu.cn/show_problem.php?pid=2334 

中等，左偏樹，二項式堆或其他可合併堆的應用。 

左偏樹參考 http://www.nist.gov/dads/HTML/leftisttree.html 

二項式堆參見《算法導論》相關章節 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1182 

中等，並查集 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1816 

中等，字典樹 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2778 

較難，多串匹配樹 

參考： http://home.ustc.edu.cn/~zhuhcheng/ACM/zzy2004.pdf 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1743 

難，後綴數組 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2774 

較難，最長公共子串，經典問題，後綴數組 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2758 

很難，後綴數組 

可參考解題報告 

http://acm.pku.edu.cn/JudgeOnline/showcontest?contest_id=1178 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2448 

很難，數據結構綜合運用 

四.圖論基礎 

參考資料： 

劉汝佳《算法藝術與信息學競賽》《算法導論》《網絡算法與複雜性理論》謝政 

推薦題目: 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2337 

簡單，歐拉路 

http://acm.pku.edu.cn/JudgeOnline/problem?id=3177 

中等，無向圖割邊 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2942 

較難，無向圖雙連通分支 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1639 

中等，最小度限制生成樹，《算法藝術與信息學競賽》中有解答 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2728 

中等，最小比率生成樹，《算法藝術與信息學競賽》中有解答 

http://acm.pku.edu.cn/JudgeOnline/problem?id=3013 

簡單，最短路問題 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1275 

中等，差分約束系統，Bellman-Ford求解，《算法藝術與信息學競賽》中有解答 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1252 

簡單，Bellman-Ford 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1459 

中等，網絡流 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2391 

較難，網絡流 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1325 

中等，二部圖最大匹配 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2226 

較難，二部圖最大匹配 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2195 

中等，二部圖最大權匹配 

KM算法參考《網絡算法與複雜性理論》 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2516 

較難，二部圖最大權匹配 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1986 

中等，LCA（最近公共祖先）問題 

參考Tarjan's LCA algorithm 《算法導論》第21章習題 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2723 

較難，2-SAT問題 

參考：http://home.ustc.edu.cn/~zhuhcheng/ACM/2-SAT.PPT 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2749 

較難，2-SAT問題 

http://acm.pku.edu.cn/JudgeOnline/problem?id=3164 

較難，最小樹形圖 

參考《網絡算法與複雜性理論》中朱-劉算法 

五.數論及組合計數基礎 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1811 

簡單，素數判定，大數分解 

參考算法導論相關章節 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2888 

較難，Burnside引理 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2891 

中等，解模方程組 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2154 

中等，經典問題，波利亞定理 

http://cs.scu.edu.cn/soj/problem.action?id=2703 

難，極好的題目，Burnside引理+模線性方程組 

http://acm.pku.edu.cn/JudgeOnline/problem?id=2764 

較難，需要數學方法，該方法在《具體數學》第七章有講 

http://acm.pku.edu.cn/JudgeOnline/problem?id=1977 

簡單，矩陣快速乘法

第01篇 ACM/ICPC競賽之基礎篇 
一、ACM/ICPC競賽的特點 

ACM/ICPC（國際大學生程序設計競賽）是以算法設計為主的程序設計競賽，並不涉及具體的應用技術。 


ACM/ICPC競賽以組隊形式參賽，每個參賽隊由三名隊員組成，共同使用一台計算機解題。通常每場比賽的試題為6至10題，根據各隊的完成題數和罰時進行排名。題目提交通過稱為完成，從比賽開始到提交成功所用的時間為題目的基礎罰時，另外，一道題目每提交失敗一次，將增加20分鐘罰時。也就是說，參賽隊要儘可能用最快的速度、最少的失敗次數，解決最多的題目。 

二、輸入和輸出處理 
試題一般採用標準輸入和輸出方式讀取輸入和產生輸出，在題目中會詳細描述輸入和輸出的格式和值域範圍，所寫的程序一定要嚴格遵守題目指定的輸入輸出格式。 

在比賽試題的輸入和輸出處理上，針對一些常見的情形，有一些常用的方法。 

1、多測試用例的輸入和輸出 

有些試題在一次輸入中只包含一個測試用例，也就是說，程序每運行一次，只算一道題。也有些試題在一次輸入中包含多個測試用例，也就是說，程序每運行一次，要計算多道題。 


對多用例輸入，通常會先輸入要計算的用例的個數，然後依次輸入每個測試用例的輸入數據，但程序並不需要等到所有的測試用例都計算完後再輸出所有測試用例的計算結果，而是可以讀入一個測試用例，輸出一個結果，再讀入一個測試用例，再輸出一個結果。因此對多用例輸入的試題，可以用這樣的輸入模式： 

以C++為例： 

int n; 

cin >> n; 

for (int i=0; i<n; i++) 

{ 

讀入測試用例數據 

計算 

輸出計算結果 

} 

2、單測試用例輸入的結束判斷 
對單用例輸入，最主要的問題是如何知道輸入什麼時候結束。 

有些試題會指定某種特殊的輸入值作為輸入的結束標誌，這種情況比較容易處理，只須在讀入後，判斷一下讀入的內容是否為約定結束值即可。 

有些試題並不指定特殊的輸入值，而是以EOF（文件結束標誌）作為結束標誌。如果從文件流讀入，當讀到文件尾時，輸入返回EOF。如果從鍵盤讀入時，在Windows的終端中，是以Ctrl+Z表示EOF。對於這種情況，可以用這樣的輸入模式： 

以C++為例： 

int m, n; // 假設要連續輸入一組整數對 

while (cin>>m>>n) 

{ 

處理整數對(m, n) 

} 

以C語言為例： 

int m, n; 

while (scanf("%d%d", &m, &n)==2) 

{ 

處理整數對(m, n) 

} 

三、數據結構的設計 
很多試題中已經給出了數據量的上限，因此可以很方便地以數組的方式定義數據結構。但也要注意到有些題目中沒有明確指出數據上限時，切不可盲目定義數組大小。 


例如在題1070（多項式求和）中，並未說明輸入多項式的項數，對這種情況就不宜用數組方式來表示多項式了——除非你的運氣足夠好，所開闢的數組大小能夠經受所有的測試用例的考驗。 

除了使用一般的數組或鏈表結構外，對使用C++的選手來說，STL也是一大利器，充分運用可以有效提高編程的效率和正確性。 

四、測試用例的考慮 
在試題中通常會給出測試用例的樣例，這通常會被我們用來測試自己的程序，而且很多選手往往在正確計算出測試用例樣例時，會認為自己的程序是正確的。 


其實測試用例的樣例只是測試用例的個例，實際用於測試的測試用例往往會涵蓋各種極限情況和邊界情況，而且有時測試用例的數量還會比較大，甚至會重複測試同一個測試用例。因此我們的程序能夠通過樣例測試，未必能夠通過所有的測試用例的測試，一方面要全面考慮所有可能的極限情況和邊界情況，一方面程序要有足夠的效率。 



2008-7-17 01:29 回覆 


狂暈的迷戰士 
14位粉絲 
2樓
第03篇 ACM/ICPC競賽之STL--pair 
STL的<utility>頭文件中描述了一個看上去非常簡單的模板類pair，用來表示一個二元組或元素對，並提供了按照字典序對元素對進行大小比較的比較運算符模板函數。 

例如，想要定義一個對象表示一個平面坐標點，則可以： 

pair<double, double> p1; 
cin >> p1.first >> p1.second; 


pair模板類需要兩個參數：首元素的數據類型和尾元素的數據類型。pair模板類對象有兩個成員：first和second，分別表示首元素和尾元素。 

在<utility>中已經定義了pair上的六個比較運算符：<、>、<=、>=、==、!=，其規則是先比較first，first相等時再比較second，這符合大多數應用的邏輯。 
當然，也可以通過重載這幾個運算符來重新指定自己的比較邏輯。 

除了直接定義一個pair對象外，如果需要即時生成一個pair對象，也可以調用在<utility>中定義的一個模板函數：make_pair。make_pair需要兩個參數， 
分別為元素對的首元素和尾元素。 

在題1067--Ugly Numbers中，就可以用pair來表示推演樹上的結點，用first表示結點的值，用second表示結點是由父結點乘以哪一個因子得到的。 

#include <iostream> 
#include <queue> 
using namespace std; 
typedef pair<unsigned long, int> node_type; 
main() 
{ unsigned long result[1500]; 
priority_queue< node_type, vector<node_type>, greater<node_type> > Q; 
Q.push( make_pair(1, 2) ); 
for (int i=0; i<1500; i++) 
{ 
node_type node = Q.top(); 
Q.pop(); 
switch(node.second) 
{ case 2: Q.push( make_pair(node.first*2, 2) ); 
case 3: Q.push( make_pair(node.first*3, 3) ); 
case 5: Q.push( make_pair(node.first*5, 5) ); 
} 
result[i] = node.first; 
} 
int n; cin >> n; 
while (n>0) 
{ 
cout << result[n-1] << endl; 
cin >> n; 
} 
return 1; 
} 
<utility>看上去是很簡單的一個頭文件，但是<utility>的設計中卻濃縮反映了STL設計的基本思想。有意深入瞭解和研究STL的同學，仔細閱讀和體會這個簡單的頭文件， 
不失為一種入門的途徑。
2008-7-17 01:31 回覆 


狂暈的迷戰士 
14位粉絲 
3樓
第04篇 ACM/ICPC競賽之STL--vector 
在STL的<vector>頭文件中定義了vector（向量容器模板類），vector容器以連續數組的方式存儲元素序列，可以將vector看作是以順序結構實現的線性表。 
當我們在程序中需要使用動態數組時，vector將會是理想的選擇，vector可以在使用過程中動態地增長存儲空間。 

vector模板類需要兩個模板參數，第一個參數是存儲元素的數據類型，第二個參數是存儲分配器的類型，其中第二個參數是可選的，如果不給出第二個參數， 
將使用默認的分配器。 

下面給出幾個常用的定義vector向量對象的方法示例： 

vector<int> s; 
定義一個空的vector對象，存儲的是int類型的元素。 

vector<int> s(n); 
定義一個含有n個int元素的vector對象。 

vector<int> s(first, last); 
定義一個vector對象，並從由迭代器first和last定義的序列[first, last)中複製初值。 

vector的基本操作有： 

s[i] 
直接以下標方式訪問容器中的元素。 

s.front() 
返回首元素。 

s.back() 
返回尾元素。 

s.push_back(x) 
向表尾插入元素x。 

s.size() 
返回表長。 

s.empty() 
當表空時，返回真，否則返回假。 

s.pop_back() 
刪除表尾元素。 

s.begin() 
返回指向首元素的隨機存取迭代器。 

s.end() 
返回指向尾元素的下一個位置的隨機存取迭代器。 

s.insert(it, x) 
向迭代器it指向的元素前插入新元素val。 

s.insert(it, n, x) 
向迭代器it指向的元素前插入n個x。 

s.insert(it, first, last) 
將由迭代器first和last所指定的序列[first, last)插入到迭代器it指向的元素前面。 

s.erase(it) 
刪除由迭代器it所指向的元素。 

s.erase(first, last) 
刪除由迭代器first和last所指定的序列[first, last)。 

s.reserve(n) 
預分配緩衝空間，使存儲空間至少可容納n個元素。 

s.resize(n) 
改變序列的長度，超出的元素將會被刪除，如果序列需要擴展（原空間小於n），元素默認值將填滿擴展出的空間。 

s.resize(n, val) 
改變序列的長度，超出的元素將會被刪除，如果序列需要擴展（原空間小於n），將用val填滿擴展出的空間。 

s.clear() 
刪除容器中的所有的元素。 

s.swap(v) 
將s與另一個vector對象v進行交換。 

s.assign(first, last) 
將序列替換成由迭代器first和last所指定的序列[first, last)。[first, last)不能是原序列中的一部分。 

要注意的是，resize操作和clear操作都是對表的有效元素進行的操作，但並不一定會改變緩衝空間的大小。 

另外，vector還有其他一些操作如反轉、取反等，不再一下列舉。 

vector上還定義了序列之間的比較操作運算符(>, <, >=, <=, ==, !=)，可以按照字典序比較兩個序列。 

還是來看一些示例代碼。輸入個數不定的一組整數，再將這組整數按倒序輸出，如下所示： 

#include <iostream> 
#include <vector> 
using namespace std; 
main() 
{ 
vector<int> L; 
int x; 
while (cin>>x) L.push_back(x); 
for (int i=L.size()-1; i>=0; i--) cout << L[i] << " "; 
cout << endl; 
return 1; 
}
2008-7-17 01:31 回覆 


狂暈的迷戰士 
14位粉絲 
4樓
第04篇 ACM/ICPC競賽之STL--vector 
在STL的<vector>頭文件中定義了vector（向量容器模板類），vector容器以連續數組的方式存儲元素序列，可以將vector看作是以順序結構實現的線性表。 
當我們在程序中需要使用動態數組時，vector將會是理想的選擇，vector可以在使用過程中動態地增長存儲空間。 

vector模板類需要兩個模板參數，第一個參數是存儲元素的數據類型，第二個參數是存儲分配器的類型，其中第二個參數是可選的，如果不給出第二個參數， 
將使用默認的分配器。 

下面給出幾個常用的定義vector向量對象的方法示例： 

vector<int> s; 
定義一個空的vector對象，存儲的是int類型的元素。 

vector<int> s(n); 
定義一個含有n個int元素的vector對象。 

vector<int> s(first, last); 
定義一個vector對象，並從由迭代器first和last定義的序列[first, last)中複製初值。 

vector的基本操作有： 

s[i] 
直接以下標方式訪問容器中的元素。 

s.front() 
返回首元素。 

s.back() 
返回尾元素。 

s.push_back(x) 
向表尾插入元素x。 

s.size() 
返回表長。 

s.empty() 
當表空時，返回真，否則返回假。 

s.pop_back() 
刪除表尾元素。 

s.begin() 
返回指向首元素的隨機存取迭代器。 

s.end() 
返回指向尾元素的下一個位置的隨機存取迭代器。 

s.insert(it, x) 
向迭代器it指向的元素前插入新元素val。 

s.insert(it, n, x) 
向迭代器it指向的元素前插入n個x。 

s.insert(it, first, last) 
將由迭代器first和last所指定的序列[first, last)插入到迭代器it指向的元素前面。 

s.erase(it) 
刪除由迭代器it所指向的元素。 

s.erase(first, last) 
刪除由迭代器first和last所指定的序列[first, last)。 

s.reserve(n) 
預分配緩衝空間，使存儲空間至少可容納n個元素。 

s.resize(n) 
改變序列的長度，超出的元素將會被刪除，如果序列需要擴展（原空間小於n），元素默認值將填滿擴展出的空間。 

s.resize(n, val) 
改變序列的長度，超出的元素將會被刪除，如果序列需要擴展（原空間小於n），將用val填滿擴展出的空間。 

s.clear() 
刪除容器中的所有的元素。 

s.swap(v) 
將s與另一個vector對象v進行交換。 

s.assign(first, last) 
將序列替換成由迭代器first和last所指定的序列[first, last)。[first, last)不能是原序列中的一部分。 

要注意的是，resize操作和clear操作都是對表的有效元素進行的操作，但並不一定會改變緩衝空間的大小。 

另外，vector還有其他一些操作如反轉、取反等，不再一下列舉。 

vector上還定義了序列之間的比較操作運算符(>, <, >=, <=, ==, !=)，可以按照字典序比較兩個序列。 

還是來看一些示例代碼。輸入個數不定的一組整數，再將這組整數按倒序輸出，如下所示： 

#include <iostream> 
#include <vector> 
using namespace std; 
main() 
{ 
vector<int> L; 
int x; 
while (cin>>x) L.push_back(x); 
for (int i=L.size()-1; i>=0; i--) cout << L[i] << " "; 
cout << endl; 
return 1; 
}
2008-7-17 01:32 回覆 


狂暈的迷戰士 
14位粉絲 
5樓
第05篇 ACM/ICPC競賽之STL--iterator簡介 
iterator(迭代器)是用於訪問容器中元素的指示器，從這個意義上說，iterator(迭代器)相當於數據結構中所說的「遍歷指針」，也可以把iterator(迭代器)看作是一種泛化的指針。 

STL中關於iterator(迭代器)的實現是相當複雜的，這裡我們暫時不去詳細討論關於iterator(迭代器)的實現和使用，而只對iterator(迭代器)做一點簡單的介紹。 

簡單地說，STL中有以下幾類iterator(迭代器)： 

輸入iterator(迭代器)，在容器的連續區間內向前移動，可以讀取容器內任意值； 
輸出iterator(迭代器)，把值寫進它所指向的容器中； 
前向iterator(迭代器)，讀取隊列中的值，並可以向前移動到下一位置(++p,p++)； 
雙向iterator(迭代器)，讀取隊列中的值，並可以向前向後遍歷容器； 
隨機訪問iterator(迭代器), 可以直接以下標方式對容器進行訪問，vector的iterator(迭代器)就是這種iterator(迭代器)； 
流iterator(迭代器)，可以直接輸出、輸入流中的值； 
每種STL容器都有自己的iterator(迭代器)子類，下面先來看一段簡單的示例代碼： 

#include <iostream> 
#include <vector> 
using namespace std; 
main() 
{ 
vector<int> s; 
for (int i=0; i<10; i++) s.push_back(i); 
for (vector<int>::iterator it=s.begin(); it!=s.end(); it++) 
cout << *it << " "; 
cout << endl; 
return 1; 
} 

vector的begin()和end()方法都會返回一個vector::iterator對象，分別指向vector的首元素位置和尾元素的下一個位置（我們可以稱之為結束標誌位置）。 

對一個iterator(迭代器)對象的使用與一個指針變量的使用極為相似，或者可以這樣說，指針就是一個非常標準的iterator(迭代器)。 

再來看一段稍微特別一點的代碼： 

#include <iostream> 
#include <vector> 
using namespace std; 
main() 
{ 
vector<int> s; 
s.push_back(1); 
s.push_back(2); 
s.push_back(3); 
copy(s.begin(), s.end(), ostream_iterator<int>(cout, " ")); 
cout <<endl; 
return 1; 
} 

這段代碼中的copy就是STL中定義的一個模板函數，copy(s.begin(), s.end(), ostream_iterator<int>(cout, " "));的意思是將由s.begin()至s.end()(不含s.end())所指定的序列複製到標準輸出流cout中，用" "作為每個元素的間隔。也就是說，這句話的作用其實就是將表中的所有內容依次輸出。 

iterator(迭代器)是STL容器和算法之間的「膠合劑」，幾乎所有的STL算法都是通過容器的iterator(迭代器)來訪問容器內容的。只有通過有效地運用iterator(迭代器)，才能夠有效地運用STL強大的算法功能。
2008-7-17 01:32 回覆 


狂暈的迷戰士 
14位粉絲 
6樓
第05篇 ACM/ICPC競賽之STL--iterator簡介 
iterator(迭代器)是用於訪問容器中元素的指示器，從這個意義上說，iterator(迭代器)相當於數據結構中所說的「遍歷指針」，也可以把iterator(迭代器)看作是一種泛化的指針。 

STL中關於iterator(迭代器)的實現是相當複雜的，這裡我們暫時不去詳細討論關於iterator(迭代器)的實現和使用，而只對iterator(迭代器)做一點簡單的介紹。 

簡單地說，STL中有以下幾類iterator(迭代器)： 

輸入iterator(迭代器)，在容器的連續區間內向前移動，可以讀取容器內任意值； 
輸出iterator(迭代器)，把值寫進它所指向的容器中； 
前向iterator(迭代器)，讀取隊列中的值，並可以向前移動到下一位置(++p,p++)； 
雙向iterator(迭代器)，讀取隊列中的值，並可以向前向後遍歷容器； 
隨機訪問iterator(迭代器), 可以直接以下標方式對容器進行訪問，vector的iterator(迭代器)就是這種iterator(迭代器)； 
流iterator(迭代器)，可以直接輸出、輸入流中的值； 
每種STL容器都有自己的iterator(迭代器)子類，下面先來看一段簡單的示例代碼： 

#include <iostream> 
#include <vector> 
using namespace std; 
main() 
{ 
vector<int> s; 
for (int i=0; i<10; i++) s.push_back(i); 
for (vector<int>::iterator it=s.begin(); it!=s.end(); it++) 
cout << *it << " "; 
cout << endl; 
return 1; 
} 

vector的begin()和end()方法都會返回一個vector::iterator對象，分別指向vector的首元素位置和尾元素的下一個位置（我們可以稱之為結束標誌位置）。 

對一個iterator(迭代器)對象的使用與一個指針變量的使用極為相似，或者可以這樣說，指針就是一個非常標準的iterator(迭代器)。 

再來看一段稍微特別一點的代碼： 

#include <iostream> 
#include <vector> 
using namespace std; 
main() 
{ 
vector<int> s; 
s.push_back(1); 
s.push_back(2); 
s.push_back(3); 
copy(s.begin(), s.end(), ostream_iterator<int>(cout, " ")); 
cout <<endl; 
return 1; 
} 

這段代碼中的copy就是STL中定義的一個模板函數，copy(s.begin(), s.end(), ostream_iterator<int>(cout, " "));的意思是將由s.begin()至s.end()(不含s.end())所指定的序列複製到標準輸出流cout中，用" "作為每個元素的間隔。也就是說，這句話的作用其實就是將表中的所有內容依次輸出。 

iterator(迭代器)是STL容器和算法之間的「膠合劑」，幾乎所有的STL算法都是通過容器的iterator(迭代器)來訪問容器內容的。只有通過有效地運用iterator(迭代器)，才能夠有效地運用STL強大的算法功能。
2008-7-17 01:33 回覆 


狂暈的迷戰士 
14位粉絲 
7樓
第06篇 ACM/ICPC競賽之STL--string 
字符串是程序中經常要表達和處理的數據，我們通常是採用字符數組或字符指針來表示字符串。STL為我們提供了另一種使用起來更為便捷的字符串的表達方式：string。string類的定義在頭文件<string>中。 

string類其實可以看作是一個字符的vector，vector上的各種操作都可以適用於string，另外，string類對象還支持字符串的拼合、轉換等操作。 

下面先來看一個簡單的例子： 

#include <iostream> 
#include <string> 
using namespace std; 
main() 
{ 
string s = "Hello! ", name; 
cin >> name; 
s += name; 
s += '!'; 
cout << s << endl; 
return 1; 
} 


再以題1064--Parencoding為例，看一段用string作為容器，實現由P代碼還原括號字符串的示例代碼片段： 

int m; 
cin >> m; // P編碼的長度 
string str; // 用來存放還原出來的括號字符串 
int leftpa = 0; // 記錄已出現的左括號的總數 
for (int j=0; j<m; j++) 
{ 
int p; 
cin >> p; 
for (int k=0; k<p-leftpa; k++) str += '('; 
str += ')'; 
leftpa = p; 
}
2008-7-17 01:33 回覆 


狂暈的迷戰士 
14位粉絲 
9樓

看下面這個簡單的示例： 

#include <iostream> 
#include <queue> 
using namespace std; 
class T 
{ 
public: 
int x, y, z; 
T(int a, int b, int c):x(a), y(b), z? 
{ 
} 
}; 
bool operator < (const T &t1, const T &t2) 
{ 
return t1.z < t2.z; // 按照z的順序來決定t1和t2的順序 
} 
main() 
{ 
priority_queue<T> q; 
q.push(T(4,4,3)); 
q.push(T(2,2,5)); 
q.push(T(1,5,4)); 
q.push(T(3,3,6)); 

while (!q.empty()) 
{ 
T t = q.top(); q.pop(); 
cout << t.x << " " << t.y << " " << t.z << endl; 
} 
return 1; 
} 

輸出結果為(注意是按照z的順序從大到小出隊的)： 

3 3 6 
2 2 5 
1 5 4 
4 4 3 

再看一個按照z的順序從小到大出隊的例子： 

#include <iostream> 
#include <queue> 
using namespace std; 
class T 
{ 
public: 
int x, y, z; 
T(int a, int b, int c):x(a), y(b), z? 
{ 
} 
}; 
bool operator > (const T &t1, const T &t2) 
{ 
return t1.z > t2.z; 
} 
main() 
{ 
priority_queue<T, vector<T>, greater<T> > q; 
q.push(T(4,4,3)); 
q.push(T(2,2,5)); 
q.push(T(1,5,4)); 
q.push(T(3,3,6)); 

while (!q.empty()) 
{ 
T t = q.top(); q.pop(); 
cout << t.x << " " << t.y << " " << t.z << endl; 
} 
return 1; 
} 

輸出結果為： 

4 4 3 
1 5 4 
2 2 5 
3 3 6 

如果我們把第一個例子中的比較運算符重載為： 

bool operator < (const T &t1, const T &t2) 
{ 
return t1.z > t2.z; // 按照z的順序來決定t1和t2的順序 
} 

則第一個例子的程序會得到和第二個例子的程序相同的輸出結果。 

再回顧一下用優先隊列實現的題1067--Ugly Numbers的代碼： 

#include <iostream> 
#include <queue> 
using namespace std; 
typedef pair<unsigned long int, int> node_type; 
main( int argc, char *argv[] ) 
{ 
unsigned long int result[1500]; 
priority_queue< node_type, vector<node_type>, greater<node_type> > Q; 
Q.push( make_pair(1, 3) ); 
for (int i=0; i<1500; i++) 
{ 
node_type node = Q.top(); 
Q.pop(); 
switch(node.second) 
{ 
case 3: Q.push( make_pair(node.first*2, 3) ); 
case 2: Q.push( make_pair(node.first*3, 2) ); 
case 1: Q.push( make_pair(node.first*5, 1) ); 
} 
result[i] = node.first; 
} 
int n; 
cin >> n; 
while (n>0) 
{ 
cout << result[n-1] << endl; 
cin >> n; 
} 
return 1; 
}
2008-7-17 01:34 回覆 


狂暈的迷戰士 
14位粉絲 
10樓
第09篇 ACM/ICPC競賽之STL--algorithm 
<algorithm>無疑是STL中最大的一個頭文件，它是由一大堆模板函數組成的。 

下面列舉出<algorithm>中的模板函數： 

adjacent_find / binary_search / copy / copy_backward / count / count_if / equal / equal_range / fill / fill_n / find / find_end / find_first_of / find_if / for_each / generate / generate_n / includes / inplace_merge / iter_swap / lexicographical_compare / lower_bound / make_heap / max / max_element / merge / min / min_element / mismatch / next_permutation / nth_element / partial_sort / partial_sort_copy / partition / pop_heap / prev_permutation / push_heap / random_shuffle / remove / remove_copy / remove_copy_if / remove_if / replace / replace_copy / replace_copy_if / replace_if / reverse / reverse_copy / rotate / rotate_copy / search / search_n / set_difference / set_intersection / set_symmetric_difference / set_union / sort / sort_heap / stable_partition / stable_sort / swap / swap_ranges / transform / unique / unique_copy / upper_bound 

如果詳細敘述每一個模板函數的使用，足夠寫一本書的了。還是來看幾個簡單的示例程序吧。 

示例程序之一，for_each遍歷容器： 

#include <iostream> 
#include <vector> 
#include <algorithm> 
using namespace std; 

int Visit(int v) // 遍歷算子函數 
{ 
cout << v << " "; 
return 1; 
} 

class MultInt // 定義遍歷算子類 
{ 
private: 
int factor; 
public: 
MultInt(int f) : factor(f) 
{ 
} 
void operator()(int &elem) const 
{ 
elem *= factor; 
} 
}; 

main() 
{ 
vector<int> L; 
for (int i=0; i<10; i++) L.push_back(i); 
for_each(L.begin(), L.end(), Visit); 
cout << endl; 
for_each(L.begin(), L.end(), MultInt(2)); 
for_each(L.begin(), L.end(), Visit); 
cout << endl; 
return 1; 
} 

程序的輸出結果為： 

0 1 2 3 4 5 6 7 8 9 
0 2 4 6 8 10 12 14 16 18 

示例程序之二，min_element/max_element，找出容器中的最小/最大值： 

#include <iostream> 
#include <vector> 
#include <algorithm> 
using namespace std; 

main() 
{ 
vector<int> L; 
for (int i=0; i<10; i++) L.push_back(i); 
vector<int>::iterator min_it = min_element(L.begin(), L.end()); 
vector<int>::iterator max_it = max_element(L.begin(), L.end()); 
cout << "Min is " << *min_it << endl; 
cout << "Max is " << *max_it << endl; 
return 1; 
} 

程序的輸出結果為： 

Min is 0 
Max is 9 

示例程序之三，sort對容器進行排序： 

#include <iostream> 
#include <vector> 
#include <algorithm> 
using namespace std; 
void Print(vector<int> &L) 
{ 
for (vector<int>::iterator it=L.begin(); it!=L.end(); it++) 
cout << *it << " "; 
cout << endl; 
} 
main() 
{ 
vector<int> L; 
for (int i=0; i<5; i++) L.push_back(i); 
for (int i=9; i>=5; i--) L.push_back(i); 
Print(L); 
sort(L.begin(), L.end()); 
Print(L); 
sort(L.begin(), L.end(), greater<int>()); // 按降序排序 
Print(L); 
return 1; 
} 

程序的輸出結果為： 

0 1 2 3 4 9 8 7 6 5 
0 1 2 3 4 5 6 7 8 9 
9 8 7 6 5 4 3 2 1 0 

示例程序之四，copy在容器間複製元素： 

#include <vector> 
#include <algorithm> 
#include <iostream> 
using namespace std; 
main( ) 
{ 
// 先初始化兩個向量v1和v2 
vector <int> v1, v2; 
for (int i=0; i<=5; i++) v1.push_back(10*i); 
for (int i=0; i<=10; i++) v2.push_back(3*i); 

cout << "v1 = ( " ; 
for (vector <int>::iterator it=v1.begin(); it!=v1.end(); it++) 
cout << *it << " "; 
cout << ")" << endl; 

cout << "v2 = ( " ; 
for (vector <int>::iterator it=v2.begin(); it!=v2.end(); it++) 
cout << *it << " "; 
cout << ")" << endl; 

// 將v1的前三個元素複製到v2的中間 
copy(v1.begin(), v1.begin()+3, v2.begin()+4); 

cout << "v2 with v1 insert = ( " ; 
for (vector <int>::iterator it=v2.begin(); it!=v2.end(); it++) 
cout << *it << " "; 
cout << ")" << endl; 

// 在v2內部進行複製，注意參數2表示結束位置，結束位置不參與複製 
copy(v2.begin()+4, v2.begin()+7, v2.begin()+2); 

cout << "v2 with shifted insert = ( " ; 
for (vector <int>::iterator it=v2.begin(); it!=v2.end(); it++) 
cout << *it << " "; 
cout << ")" << endl; 
return 1; 
} 

程序的輸出結果為： 

v1 = ( 0 10 20 30 40 50 ) 
v2 = ( 0 3 6 9 12 15 18 21 24 27 30 ) 
v2 with v1 insert = ( 0 3 6 9 0 10 20 21 24 27 30 ) 
v2 with shifted insert = ( 0 3 0 10 20 10 20 21 24 27 30 )
2008-7-17 01:37 回覆 


狂暈的迷戰士 
14位粉絲 
11樓
第10篇 ACM/ICPC競賽之算法策略 
ACM/ICPC競賽其實就是算法設計和編碼的競賽，熟悉各種常用算法和算法設計策略並能靈活運用是非常必要的。 

這裡對幾種在競賽中經常用到的算法設計策略做一簡單的介紹。 

1、窮舉法 
窮舉法是最基本的算法設計策略，其思想是列舉出問題所有的可能解，逐一進行判別，找出滿足條件的解。 

窮舉法的運用關鍵在於解決兩個問題： 

如何列舉所有的可能解； 

如何判別可能解是否滿足條件； 

在運用窮舉法時，容易出現的問題是可能解過多，導致算法效率很低，這就需要對列舉可能解的方法進行優化。 

以題1041--純素數問題為例，從1000到9999都可以看作是可能解，可以通過對所有這些可能解逐一進行判別，找出其中的純素數，但只要稍作分析，就會發現其實可以大幅度地降低可能解的範圍。根據題意易知，個位只可能是3、5、7，再根據題意可知，可以在3、5、7的基礎上，先找出所有的二位純素數，再在二位純素數基礎上找出三位純素數，最後在三位純素數的基礎上找出所有的四位純素數。 

2、分治法 
分治法也是應用非常廣泛的一種算法設計策略，其思想是將問題分解為若干子問題，從而可以遞歸地求解各子問題，再綜合出問題的解。 

分治法的運用關鍵在於解決三個問題： 

確定分治規則，即如何分解問題。 

確定終結條件，即問題分解到什麼狀態時可以直接求解。 

確定歸納方法，即如何由子問題的解得到原問題的解。這一步並不總是需要的，因為對某些問題來說，並不需要對子問題的解進行複雜的歸納。 

我們熟知的如漢諾塔問題、折半查找算法、快速排序算法等都是分治法運用的典型案例。 

以題1045--Square Coins為例，先對題意進行分析，可設一個函數f(m, n)等於用面值不超過n2的貨幣構成總值為m的方案數，則容易推導出： 

f(m, n) = f(m-0*n*n, n-1)+f(m-1*n*n, n-1)+f(m-2*n*n, n-1)+...+f(m-k*n*n, n-1) 
這裡的k是幣值為n2的貨幣最多可以用多少枚，即k=m/(n*n)。 

也很容易分析出，f(m, 1) = f(1, n) = 1 

對於這樣的題目，一旦分析出了遞推公式，程序就非常好寫了。所以在動手開始寫程序之前，分析工作做得越徹底，邏輯描述越準確、簡潔，寫起程序來就會越容易。 

3、動態規劃法 
動態規劃法多用來計算最優問題，動態規劃法與分治法的基本思想是一致的，但處理的手法不同。動態規劃法在運用時，要先對問題的分治規律進行分析，找出終結子問題，以及子問題向父問題歸納的規則，而算法則直接從終結子問題開始求解，逐層向上歸納，直到歸納出原問題的解。 

動態規劃法多用於在分治過程中，子問題可能重複出現的情況，在這種情況下，如果按照常規的分治法，自上向下分治求解，則重複出現的子問題就會被重複地求解，從而增大了冗餘計算量，降低了求解效率。而採用動態規劃法，自底向上求解，每個子問題只計算一次，就可以避免這種重複的求解了。 

動態規劃法還有另外一種實現形式，即備忘錄法。備忘錄的基本思想是設立一個稱為備忘錄的容器，記錄已經求得解的子問題及其解。仍然採用與分治法相同的自上向下分治求解的策略，只是對每一個分解出的子問題，先在備忘錄中查找該子問題，如果備忘錄中已經存在該子問題，則不須再求解，可以從備忘錄中直接得到解，否則，對子問題遞歸求解，且每求得一個子問題的解，都將子問題及解存入備忘錄中。 

例如，在題1045--Square Coins中，可以採用分治法求解，也可以採用動態規劃法求解，即從f(m, 1)和f(1, n)出發，逐層向上計算，直到求得f(m, n)。 

在競賽中，動態規劃和備忘錄的思想還可以有另一種用法。有些題目中的可能問題數是有限的，而在一次運行中可能需要計算多個測試用例，可以採用備忘錄的方法，預先將所有的問題的解記錄下來，然後輸入一個測試用例，就查備忘錄，直接找到答案輸出。這在各問題之間存在父子關係的情況下，會更有效。例如，在題1045--Square Coins中，題目中已經指出了最大的目標幣值不超過300，也就是說問題數隻有300個，而且各問題的計算中存在重疊的子問題，可以採用動態規劃法，將所有問題的解先全部計算出來，再依次輸入測試用例數據，並直接輸出答案。 

4、回溯法
回溯法是基於問題狀態樹搜索的求解法，其可適用範圍很廣。從某種角度上說，可以把回溯法看作是優化了的窮舉法。回溯法的基本思想是逐步構造問題的可能解，一邊構造，一邊用約束條件進行判別，一旦發現已經不可能構造出滿足條件的解了，則退回上一步構造過程，重新進行構造。這個退回的過程，就稱之為「回溯」。 

回溯法在運用時，要解決的關鍵問題在於： 

如何描述局部解。 

如何擴展局部解和回溯局部解。 

如何判別局部解。 

回溯法的經典案例也很多，例如全排列問題、N後問題等。 

5、貪心法 
貪心法也是求解最優問題的常用算法策略，利用貪心法策略所設計的算法，通常效率較高，算法簡單。貪心法的基本思想是對問題做出目前看來最好的選擇，即貪心選擇，並使問題轉化為規模更小的子問題。如此迭代，直到子問題可以直接求解。 

基於貪心法的經典算法例如：哈夫曼算法、最小生成樹算法、最短路徑算法等。 

但是，貪心法的運用是有條件的，必須能夠證明貪心選擇能夠導出最優解，且轉化出的子問題與原問題是同性質的問題，才能使用貪心法求解。 

一個比較經典的貪心法求解的問題就是找硬幣問題：有1、2、5、10、20、50、100七種面值的硬幣，要支付指定的金額，問怎麼支付所用的硬幣個數最少。這是一個非常日常化的問題，憑直覺我們會想到，儘可能先用大面值的硬幣，這就是「貪心選擇」，而在這個問題上，這個貪心選擇也是正確的。 

6、限界剪枝法 
限界剪枝法是求解較複雜最優問題的一種算法策略，與回溯法類似的是，限界剪枝法也是在問題狀態空間樹上進行搜索，但回溯法是搜索一般解，而限界剪枝法則是搜索最優解。限界剪枝法的基本思想是通過找出權值函數的上下界函數，以下界函數來指導搜索的方向，以上界函數來幫助翦除一些不可能含有最優解的分枝。 

關於算法和算法策略的討論是一個非常龐大的話題，幾乎每個問題點都能擴展出一大堆可討論的內容和案例。我實在不知道該怎樣用簡短的幾篇文字就能夠把這個話題說透，這裡只能蜻蜓點水地對競賽中經常用到的幾種策略做一極為簡略的介紹。 

也許我們可以在以後的文章中，針對具體的題目進行算法和策略的分析，效果可能會更好。
2008-7-17 01:37 回覆 


狂暈的迷戰士 
14位粉絲 
12樓
第11篇 ACM/ICPC競賽之調試 
在寫程序時，調試程序也是一個重要的環節。怎樣才能夠更有效地調試程序，發現並修正錯誤呢？ 

1、調試中的輸入輸出 
為了調試程序，我們可能需要反覆執行程序，也就需要反覆輸入相同或不相同的測試數據。如果每次調試運行時都是以手工的方式輸入測試數據，相信很多人都會覺得不勝其煩。其實我們可以用一些輔助的手段來簡化這個過程。 

方法一：使用剪貼板 

可以將輸入數據預先寫好（用記事本、開發環境的編輯器或隨便什麼能夠錄入的東西），再將輸入數據複製到剪貼板上（也就是說我們通常所說的複製操作）。在調試運行時，就可以直接將輸入數據粘貼上去，不需要手工輸入，這對於反覆調試同一組測試數據尤其方便。 

方法二：使用重定向 

使用剪貼板對於多組測試數據或者比較長的測試數據就會顯得不那麼好用了。而使用輸入輸出的重定向則會更方便。 

輸入輸出重定向是在終端窗口下的一種命令行功能，在命令行上可以用「<」表示輸入重定向，在「<」後跟隨輸入文件名，則程序將從指定的輸入文件中獲取輸入數據，而不再從鍵盤讀入數據。也可以用「>」表示輸出重定向。在「>」後跟輸出文件名，則程序產生的標準輸出將寫入指定的輸出文件中，而不是顯示在屏幕上。 

我們可以預先將輸入數據存到文本文件中（如果有多組測試數據，可以存成多個文件），用重定向指定準備使用的輸入數據。 

例如，程序名為myprog，輸入數據已經存到文件test.txt中，則在命令行下可以這樣執行： 

C:>myprog < test.txt 

則程序會直接從test.txt中讀取輸入。如果想把輸出結果也存到文件中（這在輸出結果比較多的時候尤其有用，因為直接輸出到屏幕上可能會來不及看到輸出，或看不全所有的輸出），例如，可以這樣執行： 

C:>myprog > test.out 

這樣我們就可以在執行後，用一個文本編輯器打開輸出文件，慢慢閱讀和分析輸出結果。 

如果把輸入和輸出的重定向結合起來，也可以這樣執行： 

C:>myprog < test.txt > test.out 

2、輸出調試信息 
在調試時，很多同學往往首先想到的是使用開發環境所提供的調試功能：設置斷點、單步執行、查看和修改變量，甚至改變程序的流程。不可否認，使用開發環境所提供的調試功能的確很方便，但當你過分依賴於這些集成工具時，你可能忽略了很多更有效的手段：仔細地分析、充分的信息。 

當我們發現程序沒有按照自己預期得那樣工作時，不要急於跟蹤甚至修改程序，而是應該首先仔細對程序的邏輯、語句、表達式進行檢查和分析，儘可能使程序在表達上更簡潔、更乾淨。如果實在難以發現問題所在，也不必急於借助於集成工具去跟蹤程序的運行。早期的程序員在調試程序時經常會在程序中加入輸出調試信息的語句或過程，用以觀察程序的運行過程，分析程序的運行邏輯，這種調試手段即使在今天也仍然是非常有效的。 

輸出的調試信息要儘量容易閱讀，格式清楚，在必要的時候，可以借助工具程序或自己編寫的程序對輸出信息進行處理，以幫助分析問題。 

3、發現線索 
調試的目的就是要分析錯誤發生的原因，尋找線索。盲目的調試只會浪費時間。 

調試中的技巧很多，這裡提出幾條基本原則： 

首先是要使錯誤可重現，要設法保證能夠使錯誤按照自己的意願重複出現。對於不知道什麼時候會冒出來的錯誤，分析起來會困難得多！ 

縮小導致錯誤的輸入，設法構造出最小的又能保證錯誤出現的輸入，這樣可以減少變化的可能性，使分析範圍更集中。經常可以採用二分選擇的方法來選擇輸入，就是舍掉一半輸入，看看錯誤是否會出現，如果不出現，則選擇另一半輸入，如此反覆，並不斷縮小導致錯誤的輸入。 

4、構造測試數據和測試程序 
在題目中所給出的測試樣例只是一小組測試數據，這雖然通常是我們用來測試程序的第一組數據，但卻是遠遠不夠的。我們應該根據題意自行構造更多的測試數據，尤其是一些邊界狀態的測試數據（數據極大、數據極小、數據量極多、數據量極少、預期出現極端結果等情況）。 

邊界測試數據可以用於檢查程序中是否存在邊界錯誤，設計有缺陷的程序，在處理邊界測試數據時往往容易暴露出錯誤。但如果沒有發生明顯的運行錯誤，就需要對結果的正確性進行驗證。 

有些測試數據可以通過手工計算求出結果，再與程序的計算結果相對比，而也有些問題，可以通過構造測試程序來進行驗證。 

測試程序通常是用確定可靠的算法編寫的解題程序，但不須考慮時間和空間的消耗，用測試程序對測試數據進行求解，用計算結果與待測試程序的計算結果進行對比。 

以題1041--純素數問題為例，我們可以用最簡單的窮舉法進行求解，也許這樣的解法是不被接受的，因為效率太低，但這個解法卻可以用作我們的測試程序，甚至——有同學索性在本地先用這個程序把結果算出來，再寫一個程序直接輸出結果——居然也被接受了！ 

寫得有點疲了，腦子也有點麻木了~~~~先這樣吧，等緩一緩再說吧。
2008-7-17 01:40 回覆 


狂暈的迷戰士 
14位粉絲 
13樓
第02篇 ACM/ICPC競賽之STL簡介 
一、關於STL 

STL(Standard Template Library，標準模板庫）是C++語言標準中的重要組成部分。STL以模板類和模板函數的形式為程序員提供了各種數據結構和算法的精巧實現，程序員如果能夠充分地利用STL，可以在代碼空間、執行時間和編碼效率上獲得極大的好處。 


STL大致可以分為三大類：算法(algorithm)、容器(container)、迭代器(iterator)。 

STL容器是一些模板類，提供了多種組織數據的常用方法，例如vector(向量，類似於數組)、list(列表，類似於鏈表)、deque(雙向隊列)、set(集合)、map(映像)、stack(棧)、queue(隊列)、priority_queue(優先隊列)等，通過模板的參數我們可以指定容器中的元素類型。 

STL算法是一些模板函數，提供了相當多的有用算法和操作，從簡單如for_each（遍歷）到複雜如stable_sort（穩定排序）。 

STL迭代器是對C中的指針的一般化，用來將算法和容器聯繫起來。幾乎所有的STL算法都是通過迭代器來存取元素序列進行工作的，而STL中的每一個容器也都定義了其本身所專有的迭代器，用以存取容器中的元素。有趣的是，普通的指針也可以像迭代器一樣工作。 

熟悉了STL後，你會發現，很多功能只需要用短短的幾行就可以實現了。通過STL，我們可以構造出優雅而且高效的代碼，甚至比你自己手工實現的代碼效果還要好。 

STL的另外一個特點是，它是以源碼方式免費提供的，程序員不僅可以自由地使用這些代碼，也可以學習其源碼，甚至按照自己的需要去修改它。 

下面是用STL寫的題1067--Ugly Numbers的代碼： 

#include <iostream>#include <queue>using namespace std;typedef pair<unsigned long, int> node_type;main(){ unsigned long result[1500]; priority_queue< node_type, vector<node_type>, greater<node_type> > Q; Q.push( make_pair(1, 2) ); for (int i=0; i<1500; i++) { node_type node = Q.top(); Q.pop(); switch(node.second) { case 2: Q.push( make_pair(node.first*2, 2) ); case 3: Q.push( make_pair(node.first*3, 3) ); case 5: Q.push( make_pair(node.first*5, 5) ); } result[i] = node.first; } int n; cin >> n; while (n>0) { cout << result[n-1] << endl; cin >> n; } return 1;} 在ACM競賽中，熟練掌握和運用STL對快速編寫實現代碼會有極大的幫助。 
二、使用STL 
在C++標準中，STL被組織為以下的一組頭文件（注意，是沒有.h後綴的！）： 

algorithm / deque / functional / iterator / list / map 

memory / numeric / queue / set / stack / utility / vector 

當我們需要使用STL的某個功能時，需要嵌入相應的頭文件。但要注意的是，在C++標準中，STL是被定義在std命名空間中的。如下例所示： 

#include <stack> 

main() 

{ 

std::stack<int> s; 

s.push(0); 

... 

return 1; 

} 

如果希望在程序中直接引用STL，也可以在嵌入頭文件後，用using namespace語句將std命名空間導入。如下例所示： 

#include <stack> 

using namespace std; 

main() 

{ 

stack<int> s; 

s.push(0); 

... 

return 1; 

} 

STL是C++語言機制運用的一個典範，通過學習STL可以更深刻地理解C++語言的思想和方法。在本系列的文章中不打算對STL做深入的剖析，而只是想介紹一些STL的基本應用。 

有興趣的同學，建議可以在有了一些STL的使用經驗後，認真閱讀一下《C++ STL》這本書（電力出版社有該書的中文版）。
2008-7-17 01:54 回覆 


狂暈的迷戰士 
14位粉絲 
14樓
第08篇 ACM/ICPC競賽之STL--map 
在STL的頭文件<map>中定義了模板類map和multimap，用有序二叉樹來存貯類型為pair<const Key, T>的元素對序列。序列中的元素以const Key部分作為標識，map中所有元素的Key值都必須是唯一的，multimap則允許有重複的Key值。 

可以將map看作是由Key標識元素的元素集合，這類容器也被稱為「關聯容器」，可以通過一個Key值來快速確定一個元素，因此非常適合於需要按照Key值查找元素的容器。 

map模板類需要四個模板參數，第一個是鍵值類型，第二個是元素類型，第三個是比較算子，第四個是分配器類型。其中鍵值類型和元素類型是必要的。 

map的基本操作有： 

1、定義map對象，例如： 

map<string, int> m; 

2、向map中插入元素對，有多種方法，例如： 

m[key] = value; 
[key]操作是map很有特色的操作，如果在map中存在鍵值為key的元素對，則返回該元素對的值域部分，否則將會創建一個鍵值為key的元素對，值域為默認值。所以可以用該操作向map中插入元素對或修改已經存在的元素對的值域部分。 

m.insert( make_pair(key, value) ); 
也可以直接調用insert方法插入元素對，insert操作會返回一個pair，當map中沒有與key相匹配的鍵值時，其first是指向插入元素對的迭代器，其second為true；若map中已經存在與key相等的鍵值時，其first是指向該元素對的迭代器，second為false。 

3、查找元素對，例如： 

int i = m[key]; 
要注意的是，當與該鍵值相匹配的元素對不存在時，會創建鍵值為key的元素對。 

map<string, int>::iterator it = m.find(key); 
如果map中存在與key相匹配的鍵值時，find操作將返回指向該元素對的迭代器，否則，返回的迭代器等於map的end()（參見vector中提到的begin和end操作）。 

4、刪除元素對，例如： 

m.erase(key); 
刪除與指定key鍵值相匹配的元素對，並返回被刪除的元素的個數。 

m.erase(it); 
刪除由迭代器it所指定的元素對，並返回指向下一個元素對的迭代器。 

看一段簡單的示例代碼： 

#include<map>#include<iostream> using namespace std; typedef map<int, string, less<int> > M_TYPE;typedef M_TYPE::iterator M_IT;typedef M_TYPE::const_iterator M_CIT; int main(){ M_TYPE MyTestMap; MyTestMap[3] = "No.3"; MyTestMap[5] = "No.5"; MyTestMap[1] = "No.1"; MyTestMap[2] = "No.2"; MyTestMap[4] = "No.4"; M_IT it_stop = MyTestMap.find(2); cout << "MyTestMap[2] = " << it_stop->second << endl; it_stop->second = "No.2 After modification"; cout << "MyTestMap[2] = " << it_stop->second << endl; cout << "Map contents : " << endl; for(M_CIT it = MyTestMap.begin(); it != MyTestMap.end(); it++) { cout << it->second << endl; } return 0;} 
程序執行的輸出結果為： 

MyTestMap[2] = No.2 
MyTestMap[2] = No.2 After modification 
Map contents : 
No.1 
No.2 After modification 
No.3 
No.4 
No.5 

再看一段簡單的示例代碼： 

#include <iostream> 
#include <map> 
using namespace std; 
main() 
{ 
map<string, int> m; 
m["one"] = 1; 
m["two"] = 2; 
// 幾種不同的insert調用方法 
m.insert(make_pair("three", 3)); 
m.insert(map<string, int>::value_type("four", 4)); 
m.insert(pair<string, int>("five", 5)); 

string key; 
while (cin>>key) 
{ 
map<string, int>::iterator it = m.find(key); 
if (it==m.end()) 
{ 
cout << "No such key!" << endl; 
} 
else 
{ 
cout << key << " is " << it->second << endl; 
cout << "Erased " << m.erase(key) << endl; 
} 
} 
return 1; 
}


主流算法：

1.搜索　//回溯

2.DP（動態規劃）　

3.貪心　
4.圖論　//Dijkstra、最小生成樹、網絡流

5.數論　//解模線性方程

6.計算幾何　//凸殼、同等安置矩形的並的面積與周長

7.組合數學　//Polya定理

8.模擬　

9.數據結構　//並查集、堆

10.博弈論　

1、 排序

1423, 1694, 1723, 1727, 1763, 1788, 1828, 1838, 1840, 2201, 2376, 2377, 2380, 1318, 1877, 

1928, 1971, 1974, 1990, 2001, 2002, 2092, 2379, 

1002（需要字符處理，排序用快排即可） 1007（穩定的排序） 2159（題意較難懂） 2231 2371（簡單排

序） 2388（順序統計算法） 2418（二叉排序樹）

2、 搜索、回溯、遍歷

1022 1111 1118 1129 1190 1562 1564 1573 1655 2184 2225 2243 2312 2362 2378 2386 

1010,1011,1018,1020,1054,1062,1256,1321,1363,1501，

1650,1659,1664,1753,2078,2083,2303,2310,2329

簡單：1128, 1166, 1176, 1231, 1256, 1270, 1321, 1543, 1606, 1664, 1731, 1742, 1745, 1847, 

1915, 1950, 2038, 2157, 2182, 2183, 2381, 2386, 2426, 
不易：1024, 1054, 1117, 1167, 1708, 1746, 1775, 1878, 1903, 1966, 2046, 2197, 2349, 
推薦：1011, 1190, 1191, 1416, 1579, 1632, 1639, 1659, 1680, 1683, 1691, 1709, 1714, 1753, 

1771, 1826, 1855, 1856, 1890, 1924, 1935, 1948, 1979, 1980, 2170, 2288, 2331, 2339, 

2340,1979（和迷宮類似） 1980（對剪枝要求較高）

3、 曆法

1008 2080 （這種題要小心）

4、 枚舉

1012，1046， 1387， 1411， 2245， 2326， 2363， 2381，1054（剪枝要求較高），1650 （小數的精

度問題）

5、 數據結構的典型算法

容易：1182, 1656, 2021, 2023, 2051, 2153, 2227, 2236, 2247, 2352, 2395, 
不易：1145, 1177, 1195, 1227, 1661, 1834, 
推薦：1330, 1338, 1451, 1470, 1634, 1689, 1693, 1703, 1724, 1988, 2004, 2010, 2119, 2274, 

1125(弗洛伊德算法) ，2421（圖的最小生成樹）

6、 動態規劃

1037 A decorative fence、

1050 To the Max、

1088 滑雪、

1125 Stockbroker Grapevine、

1141 Brackets Sequence、

1159 Palindrome、

1160 Post Office、

1163 The Triangle、

1458 Common Subsequence、

1579 Function Run Fun、

1887 Testing the CATCHER、

1953 World Cup Noise、

2386 Lake Counting

7、 貪心

1042, 1065, 1230, 1323, 1477, 1716, 1784,1328 1755（或用單純形方法），2054，1017， 1328，

1862， 1922 ，2054， 2209， 2313， 2325， 2370。

8、 模擬

容易：1006, 1008, 1013, 1016, 1017, 1169, 1298, 1326, 1350, 1363, 1676, 1786, 1791, 1835, 

1970, 2317, 2325, 2390, 

不易：1012, 1082, 1099, 1114, 1642, 1677, 1684, 1886,1281 1928 2083 2141 2015

9、 遞歸

1664

10、字符串處理

1488, 1598, 1686, 1706, 1747, 1748, 1750, 1760, 1782, 1790, 1866, 1888, 1896, 1951, 2003, 

2121, 2141, 2145, 2159, 2337, 2359, 2372, 2406, 2408, 1016 1051 1126 1318 1572 1917 1936 

2039 2083 2136 2271 2317 2330，2121 2403

11、數論

1006,1014,1023,1061,1152,1183,1730,2262

12、幾何有關的題目

凸包：1113, 1228, 1794, 2007, 2187,1113 wall，2187 beauty contest

容易：1319, 1654, 1673, 1675, 1836, 2074, 2137, 2318, 
不易：1685, 1687, 1696, 1873, 1901, 2172, 2333,

13、任意精度運算、數字遊戲、高精度計算

1001 1023 1047 1060 1079 1131 1140 1142 1207 1220 1284 1289 1306 1316 1338 1405 1454 1503 

1504 1519 1565 1650 1969 2000 2006 2081 2247 2262 2305 2316 2389 
1001, 1220, 1405, 1503,1001（高精度乘法） 2413(高精度加法，還有二分查找)

14、概率統計

1037,1050

15、小費用最大流、最大流

2195 going home，2400 supervisor, supervisee，1087 a plug for UNIX，1149 PIGS，1273 drainage 

ditches，1274 the perfect stall，1325 machine schedule，1459 power network，2239 selecting 

courses

16、壓縮存儲的DP

1038 bugs integrated inc，1185 砲兵陣地，2430 lazy cow

17、最長公共子串（LCS）

1080 human gene functions，1159 palindrome，1458 common subsequence，2192 zipper

18、圖論及組合數學

2421 Constructing Roads、

2369 Permutations、

2234 Matches Game、

2243 Knight Moves、

2249 Binomial Showdown、

2255 Tree Recovery、

2084 Game of Connections、

1906 Three powers、

1833 排列、

1850 Code、

1562 Oil Deposits、

1496 Word Index、

1306 Combinations、

1125 Stockbroker Grapevine、

1129 Channel Allocation、

1146 ID Codes、

1095 Trees Made to Order、找規律

2247 Humble Numbers、

2309 BST、

2346 Lucky tickets、

2370 Democracy in danger、

2365 Rope、

2101 Honey and Milk Land 
2028 When Can We Meet?、

2084 Game of Connections、

1915 Knight Moves、

1922 Ride to School、

1941 The Sierpinski Fractal、

1953 World Cup Noise、

1958 Strange Towers of Hanoi、

1969 Count on Canton、

1806 Manhattan 2025、

1809 Regetni、

1844 Sum、

1870 Bee Breeding、

1702 Eva\'s Balance、

1728 A flea on a chessboard、

1604 Just the Facts、

1642 Stacking Cubes、

1656 Counting Black、

1657 Distance on Chessboard、

1662 CoIns、

1663 Number Steps、

1313 Booklet Printing、

1316 Self Numbers、

1320 Street Numbers、

1323 Game Prediction、

1338 Ugly Numbers、

1244 Slots of Fun、

1250 Tanning Salon、

1102 LC-Display、

1147 Binary codes、

1013 Counterfeit Dollar、

19、博弈類

1067 取石子遊戲、

1740 A New Stone Game、

2234 Matches Game、

1082 Calendar Game 、

2348 Euclid\'s Game、

2413 How many Fibs?、

2419 Forest

20、簡單、模擬題
1001 Exponentiation 、

1002 487-3279、

1003 Hangover 、

1701 Dissatisfying Lift、

2301 Beat the Spread!、

2304 Combination Lock、

2328 Guessing Game、

2403 Hay Points 、

2406 Power Strings、

2339 Rock, Scissors, Paper、

2350 Above Average、

2218 Does This Make Me Look Fat?、

2260 Error Correction、

2262 Goldbach\'s Conjecture、

2272 Bullseye、

2136 Vertical Histogram、

2174 Decoding Task、

2183 Bovine Math Geniuses、

2000 Gold Coins、

2014 Flow Layout、

2051 Argus、

2081 Calendar、

1918 Ranking List、

1922 Ride to School、

1970 The Game、

1972 Dice Stacking、

1974 The Happy Worm、

1978 Hanafuda Shuffle、

1979 Red and Black、

1617 Crypto Columns、

1666 Candy Sharing Game、

1674 Sorting by Swapping、

1503 Integer Inquiry、

1504 Adding Reversed Numbers、

1528 Perfection、

1546 Basically Speaking、

1547 Clay Bully、

1573 Robot Motion、

1575 Easier Done Than Said?、

1581 A Contesting Decision、

1590 Palindromes、

1454 Factorial Frequencies、

1363 Rails、

1218 THE DRUNK JAILER、

1281 MANAGER、

1132 Border、

1028 Web Navigation、

21、初等數學

1003 Hangover、

1045 Bode Plot、

1254 Hansel and Grethel、

1269 Intersecting Lines、

1401 Factorial、

1410 Intersection、

2363 Blocks 、

2365 Rope、

2242 The Circumference of the Circle、

2291 Rotten Ropes、

2295 A DP Problem、

2126 Factoring a Polynomial、

2191 Mersenne Composite Numbers、

2196 Specialized Four-Digit Numbers、

1914 Cramer\'s Rule、

1835 宇航員、

1799 Yeehaa!、

1607 Deck、

1244 Slots of Fun、

1269 Intersecting Lines、

1299 Polar Explorer、

1183 反正切函數的應用、

22、匹配

1274, 1422, 1469, 1719, 2060, 2239,

-------------------------------------------------------------------------------------------

經典
1011（搜索好題） 
1012（學會打表）
1013
1019（它體現了很多此類問題的特點）
1050（絕對經典的dp）
1088（dp好題）
1157（花店，經典的dp）
1163（怎麼經典的dp那麼多呀？？？）
1328（貪心）
1458（最長公共子序列）
1647（很好的真題，考臨場分析準確和下手迅速）
1654（學會多邊形面積的三角形求法）
1655（一類無根樹的dp問題）
1804（逆序對）
2084（經典組合數學問題）
2187（用凸包求最遠點對，求出凸包後應該有O(N)的求法，可我就是調不出來）
2195（二分圖的最佳匹配）
2242（計算幾何經典）
2295（等式處理）
2353（dp，但要記錄最佳路徑）
2354（立體解析幾何）
2362（搜索好題）
2410（讀懂題是關鍵）
2411（經典dp）

趣味
1067（很難的數學，但仔細研究，是一片廣闊的領域）
1147（有O(n)的算法，需要思考）
1240（直到一棵樹的先序和後序遍歷，那麼有幾種中序遍歷呢？dp）
1426（是數論嗎？錯，是圖論！）
1648（別用計算幾何，用整點這個特點繞過精度的障礙吧）
1833（找規律）
1844（貌似dp或是搜索，其實是道有趣的數學題）
1922（貪心，哈哈）
2231
2305（不需要高精度噢）
2328（要仔細噢）
2356（數論知識）
2359（約瑟夫問題變種）
2392（有趣的問題）

很繁的題
1001
1008
1087（構圖很煩，還有二分圖的最大匹配）
1128（USACO）
1245
1329
1550（考的是讀題和理解能力）
1649（dp）
2200（字符串處理+枚舉）
2358（枚舉和避免重複都很煩）
2361（仔細仔細再仔細）

難題
1014（數學證明比較難，但有那種想法更重要）
1037（比較難的dp）
1405（高精度算法也分有等級之分，不斷改進吧）
2002（不知道有沒有比O(n^2*logn)更有的算法？）
2054（極難，很強的思考能力）
2085（組合數學）
2414（dp，但要剪枝）
2415（搜索）
2423（計算幾何+統計）

多解題
1002（可以用排序，也可以用統計的方法）
1338（搜索和dp都可以）
1664（搜索和dp都練一練吧）
2082（這可是我講的題噢）
2352（桶排和二叉樹都行）
Note:
1011: 很經典的剪支
1014: 難在數學上
1017: 嚴格的數學證明貌似不容易
1021: 有點繁,考察對圖形進行各種旋轉的處理
1083: 巧妙的思考角度
1150: 分奇偶討論,lg(n)算法
1218: 三行就夠了,雖然簡單,但也有優劣之別
1505: 二分加貪心
1654: 做法也許很多吧,本人用有向面積做的
1674: 計算圈的個數(算是graph 吧)
1700: 數學證明不容易
1742: O(m*n)的算法
1863: 要耐心地慢慢寫…^_^
1988: 並查集
2051: 堆
2078: 不難，但剪支可以做到很好
2082::O(n),你想到了嗎？
2084: 卡特蘭數
2182: 線段樹
2195: 最小費用最大流
2234: 經典博弈算法
2236: 並查集
2299: 二分思想
2395: Kruskal 最小生成樹的拓展
2406: KMP
2411: 用二進制串來表示狀態



1、 排序

1423, 1694, 1723, 1727, 1763, 1788, 1828, 1838, 1840, 2201, 2376, 2377, 2380, 1318, 1877, 1928, 1971, 1974, 1990, 2001, 2002, 2092, 2379,

1002（需要字符處理，排序用快排即可） 1007（穩定的排序） 2159（題意較難懂） 2231
2371（簡單排序） 2388（順序統計算法） 2418（二*排序樹）

2、 搜索、回溯、遍歷

1022,1111,1118,1129,1190,1562,1564,1573,1655,2184,2225,2243,2312,2362,2378,2386,1010,1011,1018,1020,1054,1062,1256,1321,1363,1501,1650,1659,1664,1753,2078,208
3,2303,2310,2329

簡單：1128, 1166, 1176, 1231, 1256, 1270, 1321, 1543, 1606, 1664, 1731, 1742, 1745, 1847, 1915, 1950, 2038, 2157, 2182, 2183, 2381, 2386, 2426,
不易：1024, 1054, 1117, 1167, 1708, 1746, 1775, 1878, 1903, 1966, 2046, 2197, 2349,
推薦：1011, 1190, 1191, 1416, 1579, 1632, 1639, 1659, 1680, 1683, 1691, 1709, 1714, 1753, 1771, 1826, 1855, 1856, 1890, 1924, 1935, 1948, 1979, 1980, 2170, 2288, 2331, 2339, 2340,1979（和迷宮類似） 1980（對剪枝要求較高）

3、 曆法

1008 2080 （這種題要小心）

4、 枚舉

1012，1046， 1387， 1411， 2245， 2326， 2363， 2381，1054（剪枝要求較高），1650(小數的精度問題）

5、 數據結構的典型算法

容易：1182, 1656, 2021, 2023, 2051, 2153, 2227, 2236, 2247, 2352, 2395,
不易：1145, 1177, 1195, 1227, 1661, 1834,
推薦：1330, 1338, 1451, 1470, 1634, 1689, 1693, 1703, 1724, 1988, 2004, 2010, 2119, 2274, 1125(弗洛伊德算法) ，2421（圖的最小生成樹）

6、 動態規劃

1037 A decorative fence、
1050 To the Max、
1088 滑雪、
1125 Stockbroker Grapevine、
1141 Brackets Sequence、
1159 Palindrome、
1160 Post Office、
1163 The Triangle、
1458 Common Subsequence、
1579 Function Run Fun、
1887 Testing the CATCHER、
1953 World Cup Noise、
2386 Lake Counting

動態規劃 
容易： 
1018, 1050, 1083, 1088, 1125, 1143, 1157, 1163, 1178, 1179, 1189, 1208, 1276, 1322, 1414, 1456, 1458, 1609, 1644, 1664, 1690, 1699, 1740, 1742, 1887, 1926, 1936, 1952, 1953, 1958, 1959, 1962, 1975, 1989, 2018, 2029, 2033, 2063, 2081, 2082, 2181, 2184, 2192, 2231, 2279, 2329, 2336, 2346, 2353, 2355, 2356, 2385, 2392, 2424, 
不易： 
1019, 1037, 1080, 1112, 1141, 1170, 1192, 1239, 1655, 1695, 1707, 1733, 1737, 1837, 1850, 1920, 1934, 1937, 1964, 2039, 2138, 2151, 2161, 2178, 
推薦： 
1015, 1635, 1636, 1671, 1682, 1692, 1704, 1717, 1722, 1726, 1732, 1770, 1821, 1853, 1949, 2019, 2127, 2176, 2228, 2287, 2342, 2374, 2378, 2384, 2411, 

7、 貪心

1042, 1065, 1230, 1784,1328 1755（或用單純形方法），2054，1017， 1328，1862， 1922 ，2054， 2209， 2313， 2325， 2370。

8、 模擬

容易：1006, 1008, 1013, 1016, 1017, 1169, 1298, 1326, 1350, 1363, 1676, 1786, 1791, 1835, 1970, 2317, 2325, 2390,
不易：1012, 1082, 1099, 1114, 1642, 1677, 1684, 1886,1281 1928 2083 2141 2015

9、 遞歸

1664

10、字符串處理

1488, 1598, 1686, 1706, 1747, 1748, 1750, 1760, 1782, 1790, 1866, 1888, 1896, 1951, 2003, 2121, 2141, 2145, 2159, 2337, 2359, 2372, 2406, 2408, 1016 1051 1126 1318 1572 1917 1936 2039 2083 2136 2271 2317 2330，2121 2403

11、數論

1006,1014,1023,1061,1152,1183,1730,2262

12、幾何有關的題目

凸包：1113, 1228, 1794, 2007, 2187,1113 wall，2187 beauty contest
容易：1319, 1654, 1673, 1675, 1836, 2074, 2137, 2318,
不易：1685, 1687, 1696, 1873, 1901, 2172, 2333,

13、任意精度運算、數字遊戲、高精度計算

1001 1023 1047 1060 1079 1131 1140 1142 1207 1220 1284 1289 1306 1316 1338 1405 14541503 1504 1519 1565 1650 1969 2000 2006 2081 2247 2262 2305 2316 2389
1001, 1220, 1405, 1503,1001（高精度乘法） 2413(高精度加法，還有二分查找)

14、概率統計

1037,1050

15、小費用最大流、最大流

2195 going home，2400 supervisor, supervisee，1087 a plug for UNIX，1149 PIGS，1273 drainage ditches，1274 the perfect stall，1325 machine schedule，1459 power network，2239 selecting courses

16、壓縮存儲的DP

1038 bugs integrated inc，1185 砲兵陣地，2430 lazy cow

17、最長公共子串（LCS）

1080 human gene functions，1159 palindrome，1458 common subsequence，2192 zipper

18、圖論及組合數學

2421 Constructing Roads、
2369 Permutations、
2234 Matches Game、
2243 Knight Moves、
2249 Binomial Showdown、
2255 Tree Recovery、
2084 Game of Connections、
1906 Three powers、
1833 排列、
1850 Code、
1562 Oil Deposits、
1496 Word Index、
1306 Combinations、
1125 Stockbroker Grapevine、
1129 Channel Allocation、
1146 ID Codes、
1095 Trees Made to Order、找規律
2247 Humble Numbers、
2309 BST、
2346 Lucky tickets、
2370 Democracy in danger、
2365 Rope、
2101 Honey and Milk Land
2028 When Can We Meet?、
2084 Game of Connections、
1915 Knight Moves、
1922 Ride to School、
1941 The Sierpinski Fractal、
1953 World Cup Noise、
1958 Strange Towers of Hanoi、
1969 Count on Canton、
1806 Manhattan 2025、
1809 Regetni、
1844 Sum、
1870 Bee Breeding、
1702 Eva\'s Balance、
1728 A flea on a chessboard、
1604 Just the Facts、
1642 Stacking Cubes、
1656 Counting Black、
1657 Distance on Chessboard、
1662 CoIns、
1663 Number Steps、
1313 Booklet Printing、
1316 Self Numbers、
1320 Street Numbers、
1323 Game Prediction、
1338 Ugly Numbers、
1244 Slots of Fun、
1250 Tanning Salon、
1102 LC-Display、
1147 Binary codes、
1013 Counterfeit Dollar、

19、博弈類

1067 取石子遊戲、
1740 A New Stone Game、
2234 Matches Game、
1082 Calendar Game 、
2348 Euclid\'s Game、
2413 How many Fibs?、
2419 Forest

20、簡單、模擬題
1001 Exponentiation 、
1002 487-3279、
1003 Hangover 、
1701 Dissatisfying Lift、
2301 Beat the Spread!、
2304 Combination Lock、
2328 Guessing Game、
2403 Hay Points 、
2406 Power Strings、
2339 Rock, Scissors, Paper、
2350 Above Average、
2218 Does This Make Me Look Fat?、
2260 Error Correction、
2262 Goldbach\'s Conjecture、
2272 Bullseye、
2136 Vertical Histogram、
2174 Decoding Task、
2183 Bovine Math Geniuses、
2000 Gold Coins、
2014 Flow Layout、
2051 Argus、
2081 Calendar、
1918 Ranking List、
1922 Ride to School、
1970 The Game、
1972 Dice Stacking、
1974 The Happy Worm、
1978 Hanafuda Shuffle、
1979 Red and Black、
1617 Crypto Columns、
1666 Candy Sharing Game、
1674 Sorting by Swapping、
1503 Integer Inquiry、
1504 Adding Reversed Numbers、
1528 Perfection、
1546 Basically Speaking、
1547 Clay Bully、
1573 Robot Motion、
1575 Easier Done Than Said?、
1581 A Contesting Decision、
1590 Palindromes、
1454 Factorial Frequencies、
1363 Rails、
1218 THE DRUNK JAILER、
1281 MANAGER、
1132 Border、
1028 Web Navigation、

21、初等數學

1003 Hangover、
1045 Bode Plot、
1254 Hansel and Grethel、
1269 Intersecting Lines、
1401 Factorial、
1410 Intersection、
2363 Blocks 、
2365 Rope、
2242 The Circumference of the Circle、
2291 Rotten Ropes、
2295 A DP Problem、
2126 Factoring a Polynomial、
2191 Mersenne Composite Numbers、
2196 Specialized Four-Digit Numbers、
1914 Cramer\'s Rule、
1835 宇航員、
1799 Yeehaa!、
1607 Deck、
1244 Slots of Fun、
1269 Intersecting Lines、
1299 Polar Explorer、
1183 反正切函數的應用、

22、匹配

1274, 1422, 1469, 1719, 2060, 2239

===================================

經典
1011（搜索好題）
1012（學會打表）
1013
1019（它體現了很多此類問題的特點）
1050（絕對經典的dp）
1088（dp好題）
1157（花店，經典的dp）
1163（怎麼經典的dp那麼多呀？？？）
1328（貪心）
1458（最長公共子序列）
1647（很好的真題，考臨場分析準確和下手迅速）
1654（學會多邊形面積的三角形求法）
1655（一類無根樹的dp問題）
1804（逆序對）
2084（經典組合數學問題）
2187（用凸包求最遠點對，求出凸包後應該有O(N)的求法，可我就是調不出來）
2195（二分圖的最佳匹配）
2242（計算幾何經典）
2295（等式處理）
2353（dp，但要記錄最佳路徑）
2354（立體解析幾何）
2362（搜索好題）
2410（讀懂題是關鍵）
2411（經典dp）

趣味
1067（很難的數學，但仔細研究，是一片廣闊的領域）
1147（有O(n)的算法，需要思考）
1240（直到一棵樹的先序和後序遍歷，那麼有幾種中序遍歷呢？dp）
1426（是數論嗎？錯，是圖論！）
1648（別用計算幾何，用整點這個特點繞過精度的障礙吧）
1833（找規律）
1844（貌似dp或是搜索，其實是道有趣的數學題）
1922（貪心，哈哈）
2231
2305（不需要高精度噢）
2328（要仔細噢）
2356（數論知識）
2359（約瑟夫問題變種）
2392（有趣的問題）

很繁的題
1001
1008
1087（構圖很煩，還有二分圖的最大匹配）
1128（USACO）
1245
1329
1550（考的是讀題和理解能力）
1649（dp）
2200（字符串處理+枚舉）
2358（枚舉和避免重複都很煩）
2361（仔細仔細再仔細）

難題

1014（數學證明比較難，但有那種想法更重要）
1037（比較難的dp）
1405（高精度算法也分有等級之分，不斷改進吧）
2002（不知道有沒有比O(n^2*logn)更有的算法？）
2054（極難，很強的思考能力）
2085（組合數學）
2414（dp，但要剪枝）
2415（搜索）
2423（計算幾何+統計）

多解題
1002（可以用排序，也可以用統計的方法）
1338（搜索和dp都可以）
1664（搜索和dp都練一練吧）
2082（這可是我講的題噢）
2352（桶排和二*樹都行）

Note:
1011: 很經典的剪支
1014: 難在數學上
1017: 嚴格的數學證明貌似不容易
1021: 有點繁,考察對圖形進行各種旋轉的處理
1083: 巧妙的思考角度
1150: 分奇偶討論,lg(n)算法
1218: 三行就夠了,雖然簡單,但也有優劣之別
1505: 二分加貪心
1654: 做法也許很多吧,本人用有向面積做的
1674: 計算圈的個數(算是graph 吧)
1700: 數學證明不容易
1742: O(m*n)的算法
1863: 要耐心地慢慢寫…^_^
1988: 並查集
2051: 堆
2078: 不難，但剪支可以做到很好
2082::O(n),你想到了嗎？
2084: 卡特蘭數
2182: 線段樹
2195: 最小費用最大流
2234: 經典博弈算法
2236: 並查集
2299: 二分思想
2395: Kruskal 最小生成樹的拓展
2406: KMP
2411: 用二進制串來表示狀態



主流算法：
1.搜索　//回溯
2.DP（動態規劃）　
3.貪心　
4.圖論　//Dijkstra、最小生成樹、網絡流
5.數論　//解模線性方程
6.計算幾何　//凸殼、同等安置矩形的並的面積與周長
7.組合數學　//Polya定理
8.模擬　
9.數據結構　//並查集、堆
10.博弈論　

1、 排序
1423, 1694, 1723, 1727, 1763, 1788, 1828, 1838, 1840, 2201, 2376, 2377, 2380, 1318, 1877,
1928, 1971, 1974, 1990, 2001, 2002, 2092, 2379,
1002（需要字符處理，排序用快排即可） 1007（穩定的排序） 2159（題意較難懂） 
2231 2371（簡單排序） 2388（順序統計算法） 2418（二叉排序樹）

2、 搜索、回溯、遍歷
1022 1111 1118 1129 1190 1562 1564 1573 1655 2184 2225 2243 2312 2362 2378 2386 
1010,1011,1018,1020,1054,1062,1256,1321,1363,1501,1650,1659,1664,1753,2078,2083,2303,2310,2329

簡單：1128, 1166, 1176, 1231, 1256, 1270, 1321, 1543, 1606, 1664, 1731, 1742, 1745, 1847,
1915, 1950, 2038, 2157, 2182, 2183, 2381, 2386, 2426,
不易：1024, 1054, 1117, 1167, 1708, 1746, 1775, 1878, 1903, 1966, 2046, 2197, 2349,
推薦：1011, 1190, 1191, 1416, 1579, 1632, 1639, 1659, 1680, 1683, 1691, 1709, 1714, 1753,
1771, 1826, 1855, 1856, 1890, 1924, 1935, 1948, 1979, 1980, 2170, 2288, 2331, 2339,
2340,1979（和迷宮類似） 1980（對剪枝要求較高）

3、 曆法
1008 2080 （這種題要小心）

4、 枚舉
1012，1046， 1387， 1411， 2245， 2326， 2363， 2381，
1054（剪枝要求較高），1650 （小數的精度問題）

5、 數據結構的典型算法
容易：1182, 1656, 2021, 2023, 2051, 2153, 2227, 2236, 2247, 2352, 2395,
不易：1145, 1177, 1195, 1227, 1661, 1834,
推薦：1330, 1338, 1451, 1470, 1634, 1689, 1693, 1703, 1724, 1988, 2004, 2010, 2119, 2274,
1125(弗洛伊德算法) ，2421（圖的最小生成樹）

6、 動態規劃
1037 A decorative fence、
1050 To the Max、
1088 滑雪、
1125 Stockbroker Grapevine、
1141 Brackets Sequence、
1159 Palindrome、
1160 Post Office、
1163 The Triangle、
1458 Common Subsequence、
1579 Function Run Fun、
1887 Testing the CATCHER、
1953 World Cup Noise、
2386 Lake Counting

7、 貪心

1042, 1065, 1230, 1323, 1477, 1716, 1784,1328 1755（或用單純形方法），2054，1017， 1328，
1862， 1922 ，2054， 2209， 2313， 2325， 2370。

8、 模擬
容易：1006, 1008, 1013, 1016, 1017, 1169, 1298, 1326, 1350, 1363, 1676, 1786, 1791, 1835,
1970, 2317, 2325, 2390
不易：1012, 1082, 1099, 1114, 1642, 1677, 1684, 1886,1281 1928 2083 2141 2015

9、 遞歸
1664

10、字符串處理
1488, 1598, 1686, 1706, 1747, 1748, 1750, 1760, 1782, 1790, 1866, 1888, 1896, 1951, 2003,
2121, 2141, 2145, 2159, 2337, 2359, 2372, 2406, 2408, 1016 1051 1126 1318 1572 1917 1936
2039 2083 2136 2271 2317 2330，2121 2403

11、數論
1006,1014,1023,1061,1152,1183,1730,2262

12、幾何有關的題目
凸包：1113, 1228, 1794, 2007, 2187,1113 wall，2187 beauty contest
容易：1319, 1654, 1673, 1675, 1836, 2074, 2137, 2318,
不易：1685, 1687, 1696, 1873, 1901, 2172, 2333,

13、任意精度運算、數字遊戲、高精度計算
1001 1023 1047 1060 1079 1131 1140 1142 1207 1220 1284 1289 1306 1316 1338 1405 1454 1503
1504 1519 1565 1650 1969 2000 2006 2081 2247 2262 2305 2316 2389
1001, 1220, 1405, 1503,1001（高精度乘法） 2413(高精度加法，還有二分查找)

14、概率統計
1037,1050

15、小費用最大流、最大流
2195 going home，2400 supervisor, supervisee，1087 a plug for UNIX，1149 PIGS，
1273 drainage ditches，1274 the perfect stall，1325 machine schedule，
1459 power network，2239 selecting courses

16、壓縮存儲的DP
1038 bugs integrated inc，1185 砲兵陣地，2430 lazy cow

17、最長公共子串（LCS）
1080 human gene functions，1159 palindrome，1458 common subsequence，2192 zipper

18、圖論及組合數學

2421 Constructing Roads、

2369 Permutations、

2234 Matches Game、

2243 Knight Moves、

2249 Binomial Showdown、

2255 Tree Recovery、

2084 Game of Connections、

1906 Three powers、

1833 排列、

1850 Code、

1562 Oil Deposits、

1496 Word Index、

1306 Combinations、

1125 Stockbroker Grapevine、

1129 Channel Allocation、

1146 ID Codes、

1095 Trees Made to Order、找規律

2247 Humble Numbers、

2309 BST、

2346 Lucky tickets、

2370 Democracy in danger、

2365 Rope、

2101 Honey and Milk Land
2028 When Can We Meet?、

2084 Game of Connections、

1915 Knight Moves、

1922 Ride to School、

1941 The Sierpinski Fractal、

1953 World Cup Noise、

1958 Strange Towers of Hanoi、

1969 Count on Canton、

1806 Manhattan 2025、

1809 Regetni、

1844 Sum、

1870 Bee Breeding、

1702 Eva\'s Balance、

1728 A flea on a chessboard、

1604 Just the Facts、

1642 Stacking Cubes、

1656 Counting Black、

1657 Distance on Chessboard、

1662 CoIns、

1663 Number Steps、

1313 Booklet Printing、

1316 Self Numbers、

1320 Street Numbers、

1323 Game Prediction、

1338 Ugly Numbers、

1244 Slots of Fun、

1250 Tanning Salon、

1102 LC-Display、

1147 Binary codes、

1013 Counterfeit Dollar、

19、博弈類

1067 取石子遊戲、

1740 A New Stone Game、

2234 Matches Game、

1082 Calendar Game 、

2348 Euclid\'s Game、

2413 How many Fibs?、

2419 Forest

20、簡單、模擬題
1001 Exponentiation 、

1002 487-3279、

1003 Hangover 、

1701 Dissatisfying Lift、

2301 Beat the Spread!、

2304 Combination Lock、

2328 Guessing Game、

2403 Hay Points 、

2406 Power Strings、

2339 Rock, Scissors, Paper、

2350 Above Average、

2218 Does This Make Me Look Fat?、

2260 Error Correction、

2262 Goldbach\'s Conjecture、

2272 Bullseye、

2136 Vertical Histogram、

2174 Decoding Task、

2183 Bovine Math Geniuses、

2000 Gold Coins、

2014 Flow Layout、

2051 Argus、

2081 Calendar、

1918 Ranking List、

1922 Ride to School、

1970 The Game、

1972 Dice Stacking、

1974 The Happy Worm、

1978 Hanafuda Shuffle、

1979 Red and Black、

1617 Crypto Columns、

1666 Candy Sharing Game、

1674 Sorting by Swapping、

1503 Integer Inquiry、

1504 Adding Reversed Numbers、

1528 Perfection、

1546 Basically Speaking、

1547 Clay Bully、

1573 Robot Motion、

1575 Easier Done Than Said?、

1581 A Contesting Decision、

1590 Palindromes、

1454 Factorial Frequencies、

1363 Rails、

1218 THE DRUNK JAILER、

1281 MANAGER、

1132 Border、

1028 Web Navigation、

21、初等數學

1003 Hangover、

1045 Bode Plot、

1254 Hansel and Grethel、

1269 Intersecting Lines、

1401 Factorial、

1410 Intersection、

2363 Blocks 、

2365 Rope、

2242 The Circumference of the Circle、

2291 Rotten Ropes、

2295 A DP Problem、

2126 Factoring a Polynomial、

2191 Mersenne Composite Numbers、

2196 Specialized Four-Digit Numbers、

1914 Cramer\'s Rule、

1835 宇航員、

1799 Yeehaa!、

1607 Deck、

1244 Slots of Fun、

1269 Intersecting Lines、

1299 Polar Explorer、

1183 反正切函數的應用、

22、匹配

1274, 1422, 1469, 1719, 2060, 2239,

-------------------------------------------------------------------------------------------

經典
1011（搜索好題）
1012（學會打表）
1013
1019（它體現了很多此類問題的特點）
1050（絕對經典的dp）
1088（dp好題）
1157（花店，經典的dp）
1163（怎麼經典的dp那麼多呀？？？）
1328（貪心）
1458（最長公共子序列）
1647（很好的真題，考臨場分析準確和下手迅速）
1654（學會多邊形面積的三角形求法）
1655（一類無根樹的dp問題）
1804（逆序對）
2084（經典組合數學問題）
2187（用凸包求最遠點對，求出凸包後應該有O(N)的求法，可我就是調不出來）
2195（二分圖的最佳匹配）
2242（計算幾何經典）
2295（等式處理）
2353（dp，但要記錄最佳路徑）
2354（立體解析幾何）
2362（搜索好題）
2410（讀懂題是關鍵）
2411（經典dp）

趣味
1067（很難的數學，但仔細研究，是一片廣闊的領域）
1147（有O(n)的算法，需要思考）
1240（直到一棵樹的先序和後序遍歷，那麼有幾種中序遍歷呢？dp）
1426（是數論嗎？錯，是圖論！）
1648（別用計算幾何，用整點這個特點繞過精度的障礙吧）
1833（找規律）
1844（貌似dp或是搜索，其實是道有趣的數學題）
1922（貪心，哈哈）
2231
2305（不需要高精度噢）
2328（要仔細噢）
2356（數論知識）
2359（約瑟夫問題變種）
2392（有趣的問題）

很繁的題
1001
1008
1087（構圖很煩，還有二分圖的最大匹配）
1128（USACO）
1245
1329
1550（考的是讀題和理解能力）
1649（dp）
2200（字符串處理+枚舉）
2358（枚舉和避免重複都很煩）
2361（仔細仔細再仔細）

難題
1014（數學證明比較難，但有那種想法更重要）
1037（比較難的dp）
1405（高精度算法也分有等級之分，不斷改進吧）
2002（不知道有沒有比O(n^2*logn)更有的算法？）
2054（極難，很強的思考能力）
2085（組合數學）
2414（dp，但要剪枝）
2415（搜索）
2423（計算幾何+統計）

多解題
1002（可以用排序，也可以用統計的方法）
1338（搜索和dp都可以）
1664（搜索和dp都練一練吧）
2082（這可是我講的題噢）
2352（桶排和二叉樹都行）

Note:
1011: 很經典的剪支
1014: 難在數學上
1017: 嚴格的數學證明貌似不容易
1021: 有點繁,考察對圖形進行各種旋轉的處理
1083: 巧妙的思考角度
1150: 分奇偶討論,lg(n)算法
1218: 三行就夠了,雖然簡單,但也有優劣之別
1505: 二分加貪心
1654: 做法也許很多吧,本人用有向面積做的
1674: 計算圈的個數(算是graph 吧)
1700: 數學證明不容易
1742: O(m*n)的算法
1863: 要耐心地慢慢寫…^_^
1988: 並查集
2051: 堆
2078: 不難，但剪支可以做到很好
2082::O(n),你想到了嗎？
2084: 卡特蘭數
2182: 線段樹
2195: 最小費用最大流
2234: 經典博弈算法
2236: 並查集
2299: 二分思想
2395: Kruskal 最小生成樹的拓展
2406: KMP
2411: 用二進制串來表示狀態
