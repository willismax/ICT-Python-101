---
slideOptions:
  transition: slide
---
###### tags: `WDA` `ICT` `AI` `區塊鏈` `Python`

# WDA-資訊科技ICT_101
>[name=Yu-Wei Chen] 
>:email: willis@wda.gov.tw 

![TCNR-WDA](https://i.imgur.com/7SXaWfi.png "title" =300x300)

----


:::info
課程目標
 - [ ] 能簡要說明未來資訊趨勢:smile:
 - [ ] 掌握資訊科技發展相關概念、平台應用、與職場關聯之實際案例解析。:+1:
 - [ ] Python程式基礎及運用方式。:+1:
 - [ ] 手把手資料分析及應用基礎。:100:
:::
----
大綱
![](https://i.imgur.com/Fh6oRUI.png)


[TOC]

----
## 課程講義
### 本課程講義：
- 以QR_Code掃描
![本課程](https://i.imgur.com/Lg2Lgig.png "title" =200x200)
- 超連結(二擇一):
    - https://hackmd.io/s/S1akuJl4V  或
    - https://ppt.cc/fcOpkx
        
### 程式碼環境

1. 本課程的[GitHub](https://github.com/willismax/ICT-Python-101)
    - https://github.com/willismax/ICT-Python-101
    - GitHub是免費的開源程式碼集散地，是你不重複造輪子，回饋社會的好夥伴。
    - *.ipynb檔案可透過 https://nbviewer.ipython.org/ 開啟瀏覽(不能互動)，但進入後按介面右上方"Excute on Binder"可以建立為互動環境！ 
        - [01.Python常用語法入門.ipynb](https://nbviewer.ipython.org/github/willismax/ICT-Python-101/blob/master/01.Python%E5%B8%B8%E7%94%A8%E8%AA%9E%E6%B3%95%E5%85%A5%E9%96%80.ipynb)
        - [02.Python資料分析入門-打底篇.ipynb](https://nbviewer.ipython.org/github/willismax/ICT-Python-101/blob/master/02.Python%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90%E5%85%A5%E9%96%80-%E6%89%93%E5%BA%95%E7%AF%87.ipynb)
        - [03.Python資料分析入門-資料擷取篇crawler.ipynb](https://nbviewer.ipython.org/github/willismax/ICT-Python-101/blob/master/03.Python%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90%E5%85%A5%E9%96%80-%E8%B3%87%E6%96%99%E6%93%B7%E5%8F%96%E7%AF%87crawler.ipynb)
        - [04.Python資料分析應用-語意分析篇NLP.ipynb](https://nbviewer.ipython.org/github/willismax/ICT-Python-101/blob/master/04.Python%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90%E6%87%89%E7%94%A8-%E8%AA%9E%E6%84%8F%E5%88%86%E6%9E%90%E7%AF%87NLP.ipynb)
        - [05.Python深度學習入門-標準神經網路DNN做手寫辨識（MNIST）.ipynb](https://nbviewer.ipython.org/github/willismax/ICT-Python-101/blob/master/05.Python%E6%B7%B1%E5%BA%A6%E5%AD%B8%E7%BF%92%E5%85%A5%E9%96%80-%E6%A8%99%E6%BA%96%E7%A5%9E%E7%B6%93%E7%B6%B2%E8%B7%AFDNN%E5%81%9A%E6%89%8B%E5%AF%AB%E8%BE%A8%E8%AD%98%EF%BC%88MNIST%EF%BC%89.ipynb)
        - [06.Python資料分析應用-股票分析入門.ipynb](https://nbviewer.ipython.org/github/willismax/ICT-Python-101/blob/master/06.Python%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90%E6%87%89%E7%94%A8-%E8%82%A1%E7%A5%A8%E5%88%86%E6%9E%90%E5%85%A5%E9%96%80.ipynb)

1. [Microsoft Azure Notebook](https://notebooks.azure.com/willismax/projects/wda-python101)
    - 沒註冊帳號可以看程式碼，登入後即可以執行程式互動。
    - 起始步驟
        1. 點擊[Microsoft Azure Notebook](https://notebooks.azure.com/willismax/projects/wda-python101)連結。
        2. 登入您的微軟帳號。
        3. 點擊頁面右上方"Clone"按鈕。
        4. 為你複製的資源命名。
        5. 點擊"RUN On Free ...."即可使用程式互動。

1. [Google的 Colab](https://colab.research.google.com/notebooks/welcome.ipynb)
    - 可以使用GPU運算的雲端資源，亦可線上共同作業，並整合google雲端硬碟。
        - [01.Python常用語法入門.ipynb]( https://colab.research.google.com/drive/1jWWSbrzb9OwAT5NHvMNSdkfFYZx4qZGx)
        - [02.Python資料分析入門-打底篇.ipynb](https://colab.research.google.com/drive/1OVvt0yQY9MzwIHoTgnYjI5fuRjMPf-_X)
        - [03.Python資料分析入門-資料擷取篇crawler.ipynb](https://colab.research.google.com/drive/1QMUrD7ouVRr2GhMGJhbGDBx7wjK8NGWb)
        - [04.Python資料分析應用-語意分析篇NLP.ipynb](https://colab.research.google.com/drive/1ReEvsQulx9rMzxadc1vSTJCYfyG0jw1V)
        - [05.Python深度學習入門-標準神經網路DNN做手寫辨識（MNIST）.ipynb](https://colab.research.google.com/drive/16h83VmmqVHDdVSzHEO6uGWCYXYig3tUI)
        - [06.Python資料分析應用-股票分析入門.ipynb](https://colab.research.google.com/drive/1OgnE4PmywLPjW9BneaTJ28bnQwNTw_Ma)

1. [Anaconda](https://www.anaconda.com/)本地端安裝工具包
    - 安裝好即可擁有Python,R語言的開發環境。
    - 程式碼在本課程的GitHub:https://github.com/willismax/ICT-Python-101 下載Zip檔，解壓縮後可執行使用。
    - 可以安裝在自己的筆電，歡迎自備筆電學習使用，學習更完整。


 

## 課程內容
---

### Part1.資通訊技術與趨勢
![](https://i.imgur.com/WOPezvd.png)

#### ICT趨勢
- [Gartner 2018 年新興技術發展週期報告：人類與機器的界線更難劃分](https://cdn.technews.tw/2018/08/27/gartner-2018-hype-cycle-for-emerging-technologies/)
- [Gartner 發布 2019 十大科技預言：量子運算、AI、區塊鏈將迎來爆炸性發展](https://buzzorange.com/techorange/2018/10/18/gartner-2019-top-10-trend/)
- [Trending Cse Technology /Challenges](http://www.csneophyte.com/blogging.html#)


#### BigData
- [2020年全球資料量將成長至44ZB](https://www.ithome.com.tw/article/87190) 
- [Big Data經典案例：星期五、尿布與啤酒](https://www.digitimes.com.tw/tw/dt/n/shwnws.asp?cnlid=10&cat=35&id=401927)
- [尿布、啤酒、星期五─每個人都該懂的Data mining](http://androchen.blogspot.com/2012/07/5945-data-mining.html)
- [大數據轉化為多種演算法 成就Netflix精準影片推薦系統](https://www.cool3c.com/article/131945)
- [人才擠爆數據科學行業！五年前的「最性感」職業如今邁向泡沫化](https://buzzorange.com/techorange/2019/03/05/how-to-be-a-data-scientists/)


#### 區塊鏈
- [wiki](https://zh.wikipedia.org/wiki/%E5%8C%BA%E5%9D%97%E9%93%BE)
- [區塊鏈：模擬挖礦與流程說明](https://medium.com/%E4%B8%80%E5%80%8B%E4%BA%BA%E7%9A%84%E6%96%87%E8%97%9D%E5%BE%A9%E8%88%88/%E5%8D%80%E5%A1%8A%E9%8F%88-%E6%A8%A1%E6%93%AC%E6%8C%96%E7%A4%A6%E8%88%87%E6%B5%81%E7%A8%8B%E8%AA%AA%E6%98%8E-463a067da50f)
- [連猴子都懂的區塊鏈介紹](https://www.youtube.com/watch?v=LZt3FSiFVps)
- [模擬區塊鏈](https://anders.com/blockchain/tokens.html)
- [區塊鏈崛起 奪回自主權](https://udn.com/news/story/11596/3167178)
- [央行 : 虛擬貨幣與數位經濟](https://www.cbc.gov.tw/public/Attachment/8879501971.pdf)
- [臺灣保險區塊鏈平臺測試環境啟用，6家壽險5月開始試用2大主流區塊鏈](https://www.ithome.com.tw/news/130344)
- [Libra 是什麼？Libra 懶人包、最新資訊、技術學習統整](https://www.johntool.com/facebook-libra-information/?sfns=mo)
- [從 Libra 的誕生看網路支付工具的演進與區塊鏈代幣的未來 - INSIDE](https://www.inside.com.tw/article/16706-Libra-and-the-future-of-blockchain?sfns=mo)
- [臉書幣 Libra 在美國國會聽證會上的重點整理](https://www.inside.com.tw/article/16929-Highlights-from-Facebook-Libra-Senate-hearing)
- ![](https://i.imgur.com/8eLV8Fo.png)


#### AI
- [中國棋王柯潔2017年5月與AlphaGo對弈　李開復：人類勝率是0%](https://www.limitlessiq.com/news/post/view/id/394/)
- [Understanding AlphaGo](https://machinelearnings.co/understanding-alphago-948607845bb1)
- [DeepMind and Blizzard to release StarCraft II as an AI research environment](https://deepmind.com/blog/deepmind-and-blizzard-release-starcraft-ii-ai-research-environment/)
- [DeepMind and Blizzard open StarCraft II as an AI research environment](https://deepmind.com/blog/deepmind-and-blizzard-open-starcraft-ii-ai-research-environment/)
- [為了培養下一個 AlphaGo，暴雪想把《星海爭霸 II》變成 AI 實驗室](https://technews.tw/2017/08/10/deepmind-and-blizzard-open-starcraft-ii-as-an-ai-research-environment/)
- [星際2玩家們，你們很快就會在天梯上爲DeepMind的論文做貢獻了](http://bangqu.com/PX475N.html)
- [開放《Dota2》全球玩家線上挑戰，OpenAI廝殺7千場拿下99%勝率
](https://www.bnext.com.tw/article/53043/openai-five-arena)
- [AI來襲！全台高中職生明年底前全面接觸新興科技](https://news.ltn.com.tw/news/life/breakingnews/2724423)
- [我讀《人工智慧在台灣》搞懂的四件事｜經理人學習人工智慧的第一本書](https://easypresentation2016.blogspot.com/2019/06/blog-post_19.html)
- [深度學習的發展遇到了 3 個瓶頸！霍金的學生：原因是「組合爆炸」](https://buzzorange.com/techorange/2019/02/12/deep-learning-bottleneck/)
- [AI 臉部辨識將告訴賭場經理 誰是今晚的肥羊](https://udn.com/news/story/6897/3909025)

#### 物聯網
- [什麼是物聯網 (IoT)？](https://www.sap.com/taiwan/trends/internet-of-things.html)

#### 自駕車 :car: 
- [wiki](https://zh.wikipedia.org/wiki/%E8%87%AA%E5%8B%95%E9%A7%95%E9%A7%9B%E6%B1%BD%E8%BB%8A)
- [自動駕駛正當紅，但它的定義、原理與未來應用問題在哪裡？](https://technews.tw/2017/01/18/what-is-autopilot/)
- [自動駕駛車發展現況與未來趨勢](https://www.artc.org.tw/upfiles/ADUpload/knowledge/tw_knowledge_594122328.pdf)
- [開車能一路睡到底了！Tesla 創辦人 Elon Musk 表示：3 到 6 個月內就能實現「真．無人駕駛」](https://buzzorange.com/techorange/2017/01/25/tesla-true-self-driving-cars-will-come-out-in-3-months/) :no_good: 
- [培育人工智慧人才-2020年起ai課程納入基礎教育](https://tw.news.yahoo.com/%E5%9F%B9%E8%82%B2%E4%BA%BA%E5%B7%A5%E6%99%BA%E6%85%A7%E4%BA%BA%E6%89%8D-2020%E5%B9%B4%E8%B5%B7ai%E8%AA%B2%E7%A8%8B%E7%B4%8D%E5%85%A5%E5%9F%BA%E7%A4%8E%E6%95%99%E8%82%B2-124551340.html)
- [影／累犯？肇事特斯拉曾遭直擊邊開邊睡　驚險畫面曝光](https://www.setn.com/News.aspx?NewsID=469657)
- ![](https://i.imgur.com/5Ltwf9g.png)
- [Uber竟然把兩年前炫耀過的自動駕駛可視化軟件開源了](http://bangqu.com/7B7576.html)

#### 智慧製造
- [【圖解】工業機器人之五大機械結構及關鍵零組件/](https://dahetalk.com/2018/02/19/%e3%80%90%e5%9c%96%e8%a7%a3%e3%80%91%e5%b7%a5%e6%a5%ad%e6%a9%9f%e5%99%a8%e4%ba%ba%e4%b9%8b%e4%ba%94%e5%a4%a7%e6%a9%9f%e6%a2%b0%e7%b5%90%e6%a7%8b%e5%8f%8a%e9%97%9c%e9%8d%b5%e9%9b%b6%e7%b5%84%e4%bb%b6/)
- [機器流程自動化RPA](https://www.ithome.com.tw/tech/124213)
- [工業4.0最後一哩路:AI大數據](https://ithelp.ithome.com.tw/articles/10210804?sc=pt)
- [Node-Red](https://oranwind.org/-aws-she-ding-node-red-lai-shi-jue-hua-xian-shi-gan-ce-zi-liao-jiao-xue/)


#### 資安
- [';--have i been pwned?](https://haveibeenpwned.com/) 你已被駭檢測

#### 5G
- [【5G科普】只要9張圖，看懂什麼是5G｜大和有話說](https://meethub.bnext.com.tw/%E3%80%905g%E7%A7%91%E6%99%AE%E3%80%91%E5%8F%AA%E8%A6%819%E5%BC%B5%E5%9C%96%EF%BC%8C%E7%9C%8B%E6%87%82%E4%BB%80%E9%BA%BC%E6%98%AF5g%EF%BD%9C%E5%A4%A7%E5%92%8C%E6%9C%89%E8%A9%B1%E8%AA%AA/)
- [還看不懂什麼是5G？從定義到各國電信商發展進度，都在這篇5G知識懶人包中](https://www.inside.com.tw/article/13523-5g-background)
- [5G 首波釋 2790MHz 頻寬，NCC 拚 2020 年上半年如期完成](http://technews.tw/2019/03/26/ncc-5g-2020/)
---

### Part2. Python程式設計基礎
![](https://i.imgur.com/kKcr80a.png)


- [MS Azure notebook，本次課程所用的筆記本](https://wdapython101-willismax.notebooks.azure.com/j/notebooks/lesson/01.Python101.ipynb)，同樣，有帳號的話可以直接按右上方"Clone"按鈕，您即可在自己的Azure帳號環境中使用程式互動。

```Python=
Print("helo world")

#常用資料型態
print(type(100))        #int
print(type(3.14))       #float
print(type("安安"))      #str
print(type(True))       #bool
print(type([1,2,3,4,5]) #list
#dictionary
print(type({"Andy":[183,70],"Alice":[163,45]})) 

# +加 -減 *乘 /除 %取餘數 **次方
# print()輸出、 input()輸入
```

- Python工業4.0 - 工廠監控系統 [github程式碼及說明](https://github.com/willismax/TCPY20180922_Python-industry-IoT)、[Youtube影片](https://www.youtube.com/watch?v=2dYeGf7xBtI)

- [Python While(有動畫解釋)](http://www.runoob.com/python/python-while-loop.html)

---
### Part3. AI技術入門
![](https://i.imgur.com/NSgLFtB.png)



- 深度學習
    - 神經網路介紹
        - 神經元構造
        - 激勵函數
    - CNN與RNN介紹
    - 動手執行看看
    - 案例
        - [姿態預估](https://www.facebook.com/groups/1126153717456741/permalink/2858757920862970/)
        - [為想像力加色添彩：使用 GauGAN 人工智慧藝術工具，創造出超過五十萬個影像](https://blogs.nvidia.com.tw/2019/07/gaugan-ai-painting/?fbclid=IwAR1Ry5GY9-lBBYIOR0wPqzmIAumLQRpXpTlVlDhb4Bb4QfnJ48Ndfuy8Bik)
    - 延伸教程
        - https://github.com/imhuay/Algorithm_Interview_Notes-Chinese/tree/master/A-%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0

- FinTech
    - 時間序列概念
    - 股市技術分析
    - Python畫線圖
- AIOT
    - 樹梅派
        - [NASA被駭](https://www.ptt.cc/bbs/Gossiping/M.1561258145.A.2A7.html)
     (https://www.ptt.cc/bbs/Gossiping/M.1561258145.A.2A7.html)
    - Arduino
    - [NVIDIA Jetson Nano](https://github.com/NVIDIA-AI-IOT/jetbot)
    - 運用在工業物聯網SCADA+MES情境案例
- 資料競賽Kaggle
    - [KOBE會不會進球?](https://www.kaggle.com/c/kobe-bryant-shot-selection/overview)


---

## 課程之後...
這門ICT課程目的是讓學員接觸ICT技術，並透過Python基礎與應用，如果已經不再害怕接觸程式，甚至願意挽起袖子動手實作解決問，那已經達成課程目的了，希望各位喜歡！

以下提供當初幫助我很多，真心推薦的後續學習資源：
- 影音
    - [PY]蔡炎龍老師([Github](https://github.com/yenlung/Python-3-Data-Analysis-Basics)):非常生動的介紹與解說，主要環境也是用Jupyter Notebook，老師覺得最好入門磚。
    - [PY]莫煩Python[(web)](https://morvanzhou.github.io/tutorials/)：簡短而清晰的主題Youtube，無論新手至高手都非常推薦反覆觀看。
    - 線上學習平台Udemy[(web)](https://www.udemy.com/)
        - 裡面有許多高品質的學習課程，不要被訂價嚇到，請配合"[Soft & Share 軟體開發資訊分享](https://www.facebook.com/softdevtools/)"的折扣優惠碼購買，幾乎都可以用300元台幣購買課程。
        - [PY][Python 程式設計入門(課程)](https://www.udemy.com/python-tutorial-from-start/):這門中文課程也滿多人推薦的，彭彭老師
    - [AI 大神吳恩達最新 TensorFlow 課程來啦，初學者也能快速掌握！](https://buzzorange.com/techorange/2019/06/24/tensorflow-andrew-ng/)
- 書籍
    - [PY]良葛格的學習筆記([web](https://openhome.cc/Gossip/Python/)、:Python3.x技術手冊[(book)](http://books.gotop.com.tw/v_ACL054400))
        - 通常Python靠網路資源及線上技術文件即可，如果真的要買一本技術手冊，推薦此本，各大書商皆有售。
    - [PY][Python炫風之旅](https://github.com/doggy8088/A-Whirlwind-Tour-of-Python-zh-tw)
        - 本電子書為 A Whirlwind Tour of Python (GitHub) 的 正體中文版 翻譯，你可以線上閱讀這份電子書，也可以下載 PDF 閱讀。
- 技術文章
    - [PY][R 語言使用者的 Python 學習筆記](https://ithelp.ithome.com.tw/users/20103511/ironman/1077):30篇一次學2種語言
    - [[PY]Python-100-Days](https://github.com/jackfrued/Python-100-Days)
    

- 各種社群
    - [PY]Python Taiwan([FB](https://www.facebook.com/groups/pythontw/))：非常活躍的臉書社團
    - [PY]PyLadies Python([web](https://tw.pyladies.com/))

- 懶人包
    - [超過 30 個優質線上學習網站，課程平台資源大全，持續成長靠自學課程](https://medium.com/y-pointer/30-%E5%80%8B%E5%84%AA%E8%B3%AA%E7%B7%9A%E4%B8%8A%E5%AD%B8%E7%BF%92%E7%B6%B2%E7%AB%99%E5%B9%B3%E5%8F%B0%E8%B3%87%E6%BA%90%E5%A4%A7%E5%85%A8-37a4f4a8888f)
    - [【GitHub 上破萬顆星】Python 新手 100 天學習計劃](https://buzzorange.com/techorange/2019/05/07/python-100-days/)
    
    

- 後續學習的方向:
    - [提問的智慧](https://ryanhanwu.gitbooks.io/how-to-ask-questions-the-smart-way/?sfns=mo/)
        - 這是一個在社群發問必須要的禮貌指引，如何問一個Good Question是需要學習的，強烈建議閱讀。
    - 爬蟲
        - 爬蟲其實是指「資料擷取」，讓你有更多的技巧收集到該主題的資訊，包含別人整理好的(如:政府開放資料、Excel等)、網站上面的資訊、網站提供的API等，更要知道如何自動化處理節省時間，如果你想要做一個比價網站，那會搜集資訊勢必需的。
            - [大樹學堂](https://www.largitdata.com/course_list/1):清晰的爬蟲教學，都是實戰解說，鼓勵同學觀看。
            - [Python 網路爬蟲與資料分析入門實戰 ](https://www.tenlong.com.tw/products/9789864343386):豐富的台灣在地爬蟲應用，[github](https://github.com/willismax/py-scraping-analysis-book)有該書的程式碼。
    -  GitHub
        - GitHub是強大的版本控制系統，老師課堂上是作為資源庫，但功能不僅如此，如要從事軟體開發，Git版本控制是必備技能。
            - [猴子都能懂得git](https://backlog.com/git-tutorial/tw/)
            -  [30 天精通 Git 版本控管](https://github.com/doggy8088/Learn-Git-in-30-days/blob/master/zh-tw/README.md)
    -  IoT
        -  [超圖解 Python 物聯網實作入門：使用 ESP8266 與 MicroPython@博客來](https://www.books.com.tw/products/0010786530)
    
    
----
:::info
> [**問卷調查**](https://forms.gle/HFiPzrmVF9aKDnNk8)
> 課程更新中
> 若有課程補充資訊將列於本文件，也歡迎學員共筆

----
- 學員共筆時，請尊重他人及避免非課程相關內容