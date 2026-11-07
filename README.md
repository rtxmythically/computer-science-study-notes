# 計算機概論互動筆記

Ch01–Ch05 的繁體中文學習筆記，包含概念解釋、進位換算、二／八／十六進位加減、互動示範與第一章選擇題，以及第三章資料表示、編碼與多媒體互動，第四章邏輯閘、布林代數與計算／記憶電路，第五章電腦元件、von Neumann 架構、fetch-execute 週期、儲存裝置與平行架構。

**直接閱讀：[計算機概論互動筆記](https://rtxmythically.github.io/computer-science-study-notes/)**

## 如何使用

1. 從「第一章學習路線」開始，讀解釋後操作各節的互動。
2. 完成本節情境練習，再做章末 30 題選擇題。
3. 第二章包含進位換算、二進位加減與資料單位；「不同進位加減」逐步教練可輸入二／八／十六進位整數，逐欄看進位、借位與連續借位。完成後做 20 題加減法測驗：英文題目、選項與作答提示，中文讀題及逐步解析，另附考試用語表；保留 20 題進位轉換測驗。直接選 A／B／C／D，答完看計算步驟與錯題解析。
4. 從「第三章學習路線」操作補數、小數乘 2、RLE／Huffman、聲音取樣及 RGB，最後做 18 題章末練習。
5. 第四章逐頁對照 38 頁講義，包含六種閘的符號與真值表、電晶體導通模型、等效電路比較、De Morgan 驗證、半／全加器、8-to-1 MUX、NAND 型 S-R latch 記憶實驗，以及 IC／CPU。最後做 36 題英文題目與選項的測驗，答完看中文推理、講義頁碼與錯題解析。直接前往 [第四章](https://rtxmythically.github.io/computer-science-study-notes/#ch4-start) 或 [第四章測驗](https://rtxmythically.github.io/computer-science-study-notes/#ch4-test)。
6. 第五章依 ch05.pdf 整理：規格表與 K／M／G／T 單位、von Neumann 五大單元、PC 與 IR、bus／cache／pipelining、Fetch-Execute 步進器（可逐步看 PC 與暫存器）、位址線計算機、磁碟時間計算機、嵌入式系統與平行架構，最後做 39 題英文測驗。直接前往 [第五章](https://rtxmythically.github.io/computer-science-study-notes/#ch5-start) 或 [第五章測驗](https://rtxmythically.github.io/computer-science-study-notes/#ch5-test)。

7. [老師題型練習](https://rtxmythically.github.io/computer-science-study-notes/#exam-style)：依兩次已結束小考和 Homework 1 的題型，新增 26 題自製新題，英文題目、計算直接填答、中文逐步解析。含第一章觀念、整數／小數換算、二／八／十六進位加減、固定 10-bit 補數與溢位、逐次 Huffman 合併與碼字、指定精度浮點數、RLE 編解碼。可依主題練習、保存計算筆記、重練錯題，或做 7 題／100 分模擬小考，交卷後才顯示解析。新區進度保存於本機；切換主題／模式會開新一輪。第四、五章等英文題庫的選項也在載入時打亂。

8. [每單元考題](https://rtxmythically.github.io/computer-science-study-notes/#unit-past-exams)：35 個教學單元各有可收合的考題區，共 92 題（10 題本學期已出小考題、15 題 Homework 1 作業題、10 題實習講義導練、57 題同型練習）。英文題目與填答／選擇，核對後看中文步驟，可保存答案及計算筆記、重練本節與錯題。原題逐題標來源及題號；數值與要求保留，部分題目補充核對欄位或明確規則，詳見頁面說明。第四章另有實習講義導練；第五章仍標示自編，尚未取得往年同課考卷。

9. [助教實習複習路線](https://rtxmythically.github.io/computer-science-study-notes/#ta-review)：對照 68 頁實習 PDF，各單元補上頁碼與重點。新增 Exercises 55–62 的 SVG 電路、切換輸入與逐閘推導、完整真值表及英文導練；標示「實習課未講」的四題預設不列入教練。Huffman 檢查原字串與檢討補齊版本的差異；作業浮點數依 p.59 改採截取，只重置該題舊核對紀錄，保留其他答題與計算筆記。

不需要安裝軟體或登入。主題偏好、已學標記與部分答題進度保存在各自瀏覽器中。

「電路實驗講義」介面依 Damir Sokolovsky 的 [unslop](https://github.com/heydamir/unslop) 方法整理（CC BY 4.0）。

## 檔案

- `index.html`：完整互動筆記。
- `ch01_p05.png`：第一章六層架構的講義對照圖。

筆記依課堂 ch01.pdf、ch02.pdf、ch03.pdf、ch04.pdf、ch05.pdf 整理，互動中的理解用例另有標示。本頁為學習整理，考試範圍與用語仍以老師的教材為準。

## 更新本機筆記後發布

在原本的筆記資料夾將更新內容同步至網站首頁：

```sh
cp '計算機概論_Ch01-Ch02_互動筆記.html' index.html
git add index.html ch01_p05.png
git commit -m 'Update study notes'
git push
```

GitHub Pages 的發布來源為 `main` 分支的根目錄。
