# build school note guide

## outline
- vscode tutorial
- vsocde installation
- vscode extension
- markdown, 心智圖整理資訊
- 合理的使用 AI 進行提問
- 如何練習解題
- 接收知識的流程

## 吸收知識的流程
- 視覺化思考 Excalidraw
- 筆記彙整 Mind Map, Markdown
- 程式實作 Coding
- 問體解決 Problem Solving
- 練習提問 GPT, Gemini
- 將學習過程自動化 Agent Skills

## tools
> mindmap, markdown, flowchart
- Xmind, Drawnix
  - <https://xmind.com/download>
  - <https://drawnix.com/>
- Hackmd, Notion, Obsidian, Affine
- Drawio, Excalidraw
  -  <https://excalidraw.com/>

## install vscode extenstions
- excalidraw
![excalidraw-vscode-extension](image-2.png)
- markmap
![markmap-vscode-extension](image-1.png)

## markdown basic syntax
- [Lab第一個程式(Console App)](https://learn.build-school.com/courses/2023%e5%a4%8f%e5%ad%a3%e7%8f%ad%e5%85%88%e4%bf%ae%e8%aa%b2/lessons/day-1-3-31-c-%e7%a8%8b%e5%bc%8f%e5%85%a5%e9%96%80/topics/lab01-%e7%ac%ac%e4%b8%80%e5%80%8b%e7%a8%8b%e5%bc%8fconsole-app/)

> Markdown 是一種輕量級標記語言，易於閱讀和編寫，非常適合快速記錄學習內容。結合 AI，能讓你的筆記整理事半功倍。純文本格式，方便版本控制與分享。

- [https://hackmd.io/s/quick-start-tw](https://hackmd.io/s/quick-start-tw)
- 標題
- bullet list
- numbered list
- quote
- info
- code
- inline code
- comment
- picture upload
> https://github.com/weberyanglalala/Dotnet10AISamples

## 練習提問 GPT, Gemini

![alt text](image-6.png)

1. 提供上下文 Context 情境
2. 描述想要達成的目標 Goal
3. 說明目前遇到的具體問題 Problem
4. 分享已經嘗試過的方法
5. 附上相關的錯誤訊息或程式碼，在提問時以分隔符號，必要時放上截圖
6. 提問時善用 chatgpt, claude, gemini 網頁搜索功能
7. 對於輸出結果進行測試

> 請問 C# 主控台應用程式程式不使用最上層陳述式是什麼意思請幫我使用網頁搜索查詢相關的 Microsoft 文件說明

> 請問 C# 主控台應用程式程式解決方案與專案的區別，請幫我使用網頁搜索查詢相關的 Microsoft 文件說明

> 請幫我彙整解決方案與專案的區別的部分筆記，以 markdown 形式輸出

### 認證 AI 輸出的正確性

* 不要盲目複製貼上程式碼
* 觀察程式運行的過程，驗證輸出的結果

## excalidraw
- [excalidraw](https://excalidraw.com/)
- Square
- Arrow
- Text
- Draw
- Export as image
- Download Packages for flowchart: Flow Chart Symbols
  - Start/End Node
  - Process
  - Decision
  - Input/Output

![alt text](image-7.png)
![alt text](image-8.png)
![alt text](image-9.png)

## 先修課考核 Q1 : 字串轉換
- 目標方案名稱 StringReplace
- 專案名稱 StringReplace
- 專案類型 主控台應用程式
- 將1~100顯示在畫面上，如果遇到2個倍數則顯示”螃蟹”，如果遇到3的倍數則顯示”章魚”，如果同時為2跟3的倍數則顯示”金槍魚”。

![alt text](image-4.png)

### version 01
```csharp
class Program
{
  static void Main(string[] args)
  {
    int i = 1;
    do
    {
      if (i % 6 == 0)
        Console.WriteLine("金槍魚");
      else if (i % 3 == 0)
        Console.WriteLine("章魚");
      else if (i % 2 == 0)
        Console.WriteLine("螃蟹");
      else
        Console.WriteLine(i);
      i++;
    } while (i < 101);
  }
}
```

### version 02

```csharp
class Program
{
  static void Main(string[] args)
  {
    for (int i = 1; i < 101; i++)
    {
      if (i % 6 == 0)
        Console.WriteLine("金槍魚");
      else if (i % 3 == 0)
        Console.WriteLine("章魚");
      else if (i % 2 == 0)
        Console.WriteLine("螃蟹");
      else
        Console.WriteLine(i);
    }
  }
}
```

## Day3 Homework 終極密碼
- 目標方案名稱 NumberGuessing
- 專案名稱 NumberGuessing
- 專案類型 主控台應用程式
- 系統隨機產生1-100的整數，使用者輸入一個1-100（包含1及100）的整數後，未猜中的話顯示剩餘數字的區間，並且可以繼續輸入要猜的數字。
- 猜中的話，顯示「猜中了，答案是：(某數字)」
- 要處理超過範圍的狀況
![alt text](image-5.png)

```csharp
using System;

namespace GuessNumber
{
    class Program
    {
        static void Main(string[] args)
        {
            int upperBound = 100;
            int lowerBound = 1;

            Random rng = new Random();
            int target = rng.Next(lowerBound, upperBound + 1);

            while (true)
            {
                Console.Write($"請猜一個數字 ({lowerBound} ~ {upperBound}): ");
                int guess = int.Parse(Console.ReadLine()!);

                if (guess == target)
                {
                    Console.WriteLine("恭喜你猜對了！");
                    break;
                }
                else if (guess < target)
                {
                    lowerBound = guess;
                    Console.WriteLine("太小了！");
                }
                else
                {
                    upperBound = guess;
                    Console.WriteLine("太大了！");
                }
            }
        }
    }
}
```