## C# 目前筆記整理規劃
1. Lab 重點整理
	- Note：根據上課內容補充以及觀念說明
	- Goal：詳列 Lab 中的知識點以及學習目標
	- Further Reading：根據 Lab 內容延伸的更多練習，以及在 MS Docs 中詳細說明
2. 上課影片 Lab 時間軸整理(?)

## 講師介紹與課程說明(0:00:00 - 0:28:11)

## 學習方法以及歷程(0:29:00)

## C# 的社群及活動 (0:53:00 )

## 增進學習效果(1:25:00)

## C# 發展歷程以及工具概要(1:29:00)
- 上課講義 Ch01 P.16
- .NET Framework .NET Core 簡介
- Visual Studio 開發環境簡介

## 上課 Lab 須知(1:38:30)
- 上課講義 Ch01 P.21

## Lab01 使用 Visual Studio 新增專案(1:41:00)
- 上課講義 Ch01 P.22
### Goal
1. 了解方案檔 .sln 與專案檔 .csproj 的差異
2. 設定特定的專案範本：主控台應用程式(.NET Framework)
3. 設定專案框架版本：.NET Framework 4.7.2 or .NET Framework 4.8 (上課範例用 .NET Framework) or .NET Core 
4. 設定方案名稱、專案名稱
5. 設定存放位置
### Note
- 在一個方案底下可以同時存在多個專案，專案名稱和方案名稱未必一定要相同
- 存放程式的資料夾建議不要放桌面，若將存放程式的資料夾置於雲端硬碟同步的目錄內，可能會被鎖定而無法正常編譯專案。

### Further Reading
- [MS: Visual Studio 中的方案和專案是什麼？](https://learn.microsoft.com/zh-tw/visualstudio/ide/solutions-and-projects-in-visual-studio?view=vs-2022)

## Lab02 方案總管(1:54:00)
- 上課講義 Ch01 P.34
### Goal
1. 在 visual studio 中側邊欄找到方案總管
2. 在上方列表找到 [檢視] > [方案總管]
3. 了解方案總管的釘選功能
4. 了解如何在方案屬性中設定起始專案
### Further Reading
- [MS:  體驗 Visual Studio IDE](https://learn.microsoft.com/zh-tw/visualstudio/ide/quickstart-ide-orientation?view=vs-2022&source=recommendations)
- [MS: 在 Visual Studio 中建立新專案](https://learn.microsoft.com/zh-tw/visualstudio/ide/create-new-project?view=vs-2022)

## Lab03 改個好用的字型(2:03:41)
- 上課講義 Ch01 P.39
### Goal
1. 設定利於辨識文字(I, i, l, O, o, 0)的等寬字型
2. 設定位置 [工具] > [選項] > [環境] > [字型與色彩]

## Lab04 認識程式碼檔案(2:07:00)
- 上課講義 Ch01 P.42
### Goal
1. 了解如何在程式中引用命名空間 Namespace
2. 程式出錯時善用 Visual Studio 中燈泡錯誤提示功能
3. 在 Console App 中程式預設的程式進入點為 Program 類別中的 Main 方法
4. 了解程式碼中的區塊 `{}`
5. 在 C# 中型別 Type 可以大致分為以下
	- Class 類別
	- Struct 結構
	- Interface 介面
	- Enum 列舉
	- Delegate 委派
5. 在 Visual Studio 中，將滑鼠移至變數名稱上方即可顯示該變數的型別，或右鍵點選變數移至定義
### Further Reading
- [MS: Main() 和命令列引數](https://learn.microsoft.com/zh-tw/dotnet/csharp/fundamentals/program-structure/main-command-line)

---

## Lab05 建立第一個程式(Part1: 2:27:00, Part2: 0:00:00)
- 上課講義 Ch01 P.46
### Goal
1. 如何在  Visual Studio 中建置專案
2. 了解 Debug, Release Mode 以及編譯各種平台(CPU)
### Note
1. 建置時，編譯器會將 C# 程式碼轉為中間碼 ILCode
2. 執行程式碼時會再將 IL Code 編譯為機器碼再執行
3. 執行模式：Debug, Release
4. 平台：x86, x64, arm64, arm32

## Further Reading

### C# Console App 更多練習
- [MS 教學課程：在 Visual Studio 中建立簡單的 C# 主控台應用程式 (第 1/2 部分)](https://learn.microsoft.com/zh-tw/visualstudio/get-started/csharp/tutorial-console?view=vs-2022)
- [MS 教學課程：在 Visual Studio 中擴充 C# 主控台應用程式和偵錯 (第 2 部分之 2)](https://learn.microsoft.com/zh-tw/visualstudio/get-started/csharp/tutorial-console-part-2?view=vs-2022)
### Top Level Statement (.NET 6 範本)
- [MS 最上層陳述式](https://learn.microsoft.com/zh-tw/dotnet/csharp/fundamentals/program-structure/top-level-statements)
- [MS 教學課程：探索使用最上層陳述式在您學習時建置程式碼的概念](https://learn.microsoft.com/zh-tw/dotnet/csharp/whats-new/tutorials/top-level-statements)
- [Top-Level Statements in C# 範例](https://trailheadtechnology.com/top-level-statements-in-c/)

## Lab 利用 Console 類別練習閱讀 Microsoft docs 13:00
- [MS Console ](https://learn.microsoft.com/zh-tw/dotnet/api/system.console?view=net-7.0)

## 進入 C# 30:00
- 變數宣告
- C# 內建型別

## Lab 讀取並顯示
### Goal
1. 了解如何從既有方案下新增專案
2. 了解如何在多專案的方案中指定起始專案偵錯
3. 了解如何在多專案的方案屬性中指定起始專案偵錯
### Further Reading
- [MS 專案和解決方案簡介](https://learn.microsoft.com/zh-tw/visualstudio/get-started/tutorial-projects-solutions?view=vs-2022)
- [MS 建立、使用和刪除 Visual Studio 專案和解決方案](https://learn.microsoft.com/zh-tw/visualstudio/ide/creating-solutions-and-projects?view=vs-2022)

## 程式碼註解
### Goal
1. 學習使用 `//` 單行分隔符號註解程式碼
2. 學習使用 `/** */` 多行分隔符號註解程式碼
### Further Reading
- [MS XML 文件註解](https://learn.microsoft.com/zh-tw/dotnet/csharp/language-reference/xmldoc/)

## 比較運算子
### Goal
1. 學習使用比較運算子
### Note
1. 小於運算子 `<`
2. 大於運算子 `>`
3. 小於或等於運算子 `<=`
4. 大於或等於運算子 `>=`
### Further Reading
- [MS 比較運算子](https://learn.microsoft.com/zh-tw/dotnet/csharp/language-reference/operators/comparison-operators)

## Lab 使用 `if` - `else if` - `else`
### Goal
1. 學習使用 `if` - `else if` - `else` 
### Note
- if 陳述式會根據運算式的 Boolean 值識別要執行的陳述式
### Further Reading
- [MS  `if`、 `if-else`和 `switch`](https://learn.microsoft.com/zh-tw/dotnet/csharp/language-reference/statements/selection-statements)

## Lab 使用 `switch` - `case`
### Goal
1. 學習使用 `switch` - `case` 語句寫法以及撰寫順序
### Further Reading
- [MS  `if`、 `if-else`和 `switch`](https://learn.microsoft.com/zh-tw/dotnet/csharp/language-reference/statements/selection-statements)


## 陣列
### Goal
1. 學習使用陣列結構儲存多種相同型別的變數
### Note
1. 陣列可以是一維、多維或不規則
2. 建立陣列實例時，會確定陣列每個維度的長度
3. 陣列為以零為基底索引：具有 `n` 個元素的陣列，會從 `0` 到 `n-1` 編製索引
4. 實值型別陣列元素在宣告後，陣列元素即有預設值
    - 以實質型別 `int[]` 為例，陣列元素會設定為 `0`
    ```csharp
    int[] intArray = new int[3]; // new int[3] { 0, 0, 0}
    ```
    - 以參考型別 `MyData[]` 為例，陣列元素會設定為 `null`
    ```csharp
    MyData[] myDataArray = new MyData[3]; // new MyData[3] { null, null, null}
    ```
    

### Further Reading
- [MS 陣列](https://learn.microsoft.com/zh-tw/dotnet/csharp/language-reference/builtin-types/arrays)

## 反覆運算陳述式 (迴圈) - `for`, `while`, `do` `while`, `foreach`-`in`
### Further Reading
- [MS 反覆運算語句 - `for` 、 `foreach` 、 `do` 和 `while`](https://learn.microsoft.com/zh-tw/dotnet/csharp/language-reference/statements/iteration-statements)

## Lab 使用 `for` 迴圈做 1~10 加總
### Goal
1. 學習使用 `for` 迴圈
2. 了解 `for` 語句起始值、執行條件區段、遞增值

## Lab 使用 `while` 迴圈做 1~10 加總
### Goal
1. 學習使用 `while` 迴圈

## Lab 使用 `do while` 迴圈做 1~10 加總
### Goal
1. 學習使用 `do`, `while` 迴圈

## Lab 使用 `foreach` 逐一顯示集合內資料
### Goal
1. 學習使用 `foreach` 迴圈
### Note
1. `foreach` 語句會針對實作 `IEnumerable`, `IEnumerable<T>`的實例(相同型別的一個集合)，逐一執行語句或語句區塊

## 跳躍陳述式
### Note
 1. 跳躍陳述式用於移轉程式的控制權 (執行路徑) 
 2. break：會終止它所在之最靠近的封閉式迴圈或 switch 陳述式 
 3. continue：跳出當前的反覆項目，進入下一輪反覆項目
 4. return：陳述式終止其所在處之方法的執行，並且轉移程式控制權至呼叫的方法
	 - 如果 return 陳述式位於 try 區塊內，則會先執行finally (如果有的話)，控制權才會回到呼叫的方法

## Lab 在迴圈內使用 break
### Goal
1. 學習在使用 `break` 終止所在的迴圈

## Lab 在迴圈內使用 continue
### Goal
1. 學習使用 `continue` 會直接跳出當前的反覆項目進入下一迭代反覆

## 論 + 運算子
### Goal
1. 了解 `+` 運算時會根據兩側的型別而有不同的運算結果
### Note
1. `X + Y` 當 X 與 Y 皆為數值型態時，即為數學的加法 
2. `X + Y` 當 X 與 Y 皆為字串或任一方為字串時，代表字串連結

## 布林值邏輯運算子
### Note
#### `x && y`
1. And
2. 當 x 與 y 皆為 true，回傳結果才為 true。
3. 判斷的條件是有順序的，當 x 為 false，直接回傳 false，不會再判斷 y

#### `x || y`
1. Or
2. 當 x 或 y 其中一個為 true ，回傳結果即為 true
3. 判斷的條件是有順序的，當 x 為 true，直接回傳 true，不會再判斷 y

#### `!x`
1. not `x`
### Further Reading
- [MS 條件邏輯 AND 運算子 &&](https://learn.microsoft.com/zh-tw/dotnet/csharp/language-reference/operators/boolean-logical-operators#conditional-logical-and-operator-)

## Lab使用條件運算子
### Goal
- 依據情境在判斷式中用 `&&`, `||`, `!` 撰寫程式碼

## Lab 讓咱們來寫個 Method 吧
### Goal
1. 根據方法簽章設計一個 Method，並且在 Console App 中的 `Main` 方法呼叫它
### Note
1. Method 是包含一系列陳述式的程式碼區塊
2. `Main` Method 是每個 C# 應用程式的進入點，而且當程式啟動時，Common Language Runtime （CLR） 會呼叫它
3. 方法簽章(Method Signatures)：宣告方法必須滿足以下條件
	1. 方法會在類別、結構或介面中宣告
	2. 方法會指定其存取層級， 例如 `public` 或 `private` 
	3. 方法必須定義其傳入方法參數型別
	4. 方法必須定義其傳回值或是不回傳值 `void`
	5. 方法有 `abstract`, `sealed` 選擇性修飾詞
4. 方法在宣告時會定義要傳入得值以及型別稱為參數 parameter
5. 方法在實際呼叫時會傳入的值稱為引數 argment 
### Further Reading
- [MS 方法 (C# 程式設計手冊)](https://learn.microsoft.com/zh-tw/dotnet/csharp/programming-guide/classes-and-structs/methods)

## Lab 建立 Windows Forms Application
### Goal
1. 開一個新的 Windows Form Application 專案
2. 了解如何開啟 Form 的設計工具以及檢視程式碼
	- `Form1.cs` 右鍵點擊選擇開啟設計工具以及設計工具
3. 從檢視 > 屬性開啟，點擊特定元件，查看外觀、事件
5. 了解 Form1.Designer.cs 中的 `InitializeComponent` 方法的內容
6. 了解建構式主要功能：初始化類別欄位成員
7. 了解如何在 Form1 設計工具中，藉由拖曳、放大縮小、變更元件的屬性
	- 在變更原件屬性後，回到 Form1.designer.cs 觀察變更的
### Note
#### Form1.cs
-  在 Form1.cs 中 `public partial class Form1 : Form` 代表
	1. `partial`: 在撰寫 class, struct, interface, method 時(以 class 為例)，我們可能將一個 class 分割到兩個以上的來源檔案分別撰寫，而當建置應用程式時，CLR 就會將所有同名的 partial class 結合起來一起編譯。
	2. `Form1 : Form` 這個名為 `Form1` 的應用程式繼承了父類別 `Form` 
	3. `public Form1()`：這個與類別名稱同名的方法稱為此類別建構式，為類別初始化時會呼叫此方法 
### Further Reading
- [MS 使用 C# 在 Visual Studio 中建立 Windows Forms 應用程式](https://learn.microsoft.com/zh-tw/visualstudio/ide/create-csharp-winform-visual-studio?view=vs-2022)
- [MS 部分類別和方法 (C# 程式設計手冊)](https://learn.microsoft.com/zh-tw/dotnet/csharp/programming-guide/classes-and-structs/partial-classes-and-methods)
- [MS 繼承 - 衍生類型以建立更特製化的行為](https://learn.microsoft.com/zh-tw/dotnet/csharp/fundamentals/object-oriented/inheritance)
- [MS 建構函式 (C# 程式設計手冊)](https://learn.microsoft.com/zh-tw/dotnet/csharp/programming-guide/classes-and-structs/constructors)

## Lab 加個 Button
### Goal
1. 從檢視 > 工具箱開啟，選擇 Button 拖曳至 Winform 中
2. 選擇 Button1，檢視並編輯 Text, Font 等屬性
	- 觀察 Form1.designer.cs 此時 Button1 在 `InitializeComponent` 屬性變更了
3. 雙擊 Button 新增點擊委派事件
	- 觀察 Form1.designer.cs 此時 `Button1.Click` 新增了一個 EventHander 事件
	- 觀察 Form1.cs 此時 `Button1.Click` 新增了一個 Button1_Click 方法
### Further Reading
- [MS 使用 C# 在 Visual Studio 中建立 Windows Forms 應用程式](https://learn.microsoft.com/zh-tw/visualstudio/ide/create-csharp-winform-visual-studio?toc=%2Fvisualstudio%2Fget-started%2Fcsharp%2Ftoc.json&bc=%2Fvisualstudio%2Fget-started%2Fcsharp%2Fbreadcrumb%2Ftoc.json&view=vs-2022)

## Lab 簡單加減器
### Goal
1. 根據提示建構畫面 UI
2. 在 Form1.cs 設計工具雙擊按鈕元件，為點擊事件產生一個委派方法
## Lab 消除重複程式碼
### Goal
1. 根據提示建構畫面 UI
2. 將 `Lab 簡單加減器` 中的重複程式碼進行重構
### Further Reading
- [MS 擷取方法重構](https://learn.microsoft.com/zh-tw/visualstudio/ide/reference/extract-method?view=vs-2022)

## 學習自訂類別 (Class)
### Note
- 類別是一種參考型別
- 類別的概念就像是製造物品的藍圖或模具
- 類別是透過 `new` 關鍵字建立該類別的執行個體(Instance)
- 類別成員
	1. 建構式
	2. 常數
	3. 欄位
	4. 屬性
	5. 方法
	6. 事件
	7. 索引子
### Further Reading
- [C# 類別簡介](https://learn.microsoft.com/zh-tw/dotnet/csharp/fundamentals/types/classes)

## Lab 加入一個類別
### Goal
1. 在 Visual Studio 中方案總管，對既有的專案新增一個類別 Class
## 欄位
### Note
1. **定義：**
    - 欄位是任意類型的變數，可在類別或結構中直接宣告
2. **執行個體與靜態欄位：**
    - 類別或結構可以擁有執行個體欄位和靜態欄位，或同時擁有兩者。
    - 執行個體欄位是屬於類型的實例(Instance)，而靜態欄位是屬於類別(Class)本身。
    - 執行個體欄位必須透過建立執行個體後，透過執行個體使用執行個體欄位
    - 靜態欄位在使用時即使沒有類型執行個體，仍可透過類別名稱使用靜態欄位。
3. **欄位的存取限制：**
    - 使用 private 或 protected 修飾符宣告協助工具欄位，以提供資料隱私性。
    - 公開的資料最好透過方法、屬性和索引子提供，以間接存取內部欄位。
4. **欄位的宣告和存取：**
    - 在類別或結構區塊中宣告欄位，指定存取層級、類型，然後是欄位名稱。
5. **存取修飾詞：**
    - 可使用不同存取修飾詞（public、private、protected、internal等）定義欄位的可見性和存取權限。
### Further Reading
- [MS 欄位 (C# 程式設計手冊)](https://learn.microsoft.com/zh-tw/dotnet/csharp/programming-guide/classes-and-structs/fields)

## 屬性
### Note
1. **屬性的定義：**
    - 屬性提供讀取、寫入或計算私有欄位值的彈性機制，類似於公用資料成員，但使用存取子方法。
2. **屬性的基本概念：**
    - 屬性具有存取子（get 和 set 存取子），允許公開取得和設定值的公用方式。
    - 使用 `get` 存取子來傳回屬性值，`set` 存取子用於指派新值。
3. **自動實作屬性：**
    - 簡化屬性定義的語法，自動實作屬性可以由編譯器提供支援欄位，無需額外的邏輯。
### Further Reading
- [MS 屬性 (C# 程式設計手冊)](https://learn.microsoft.com/zh-tw/dotnet/csharp/programming-guide/classes-and-structs/properties)

## 方法
### Note
- 方法是包含一系列陳述式的程式碼區塊，可透過呼叫來執行這些陳述式。 
- 方法簽章：
	- 存取修飾詞
	- 選擇性修飾詞（如 `abstract`、`sealed`）
	- 傳回值型別
	- 方法名稱
	- 方法參數
- 方法參數與引數
	- 方法定義時指定所需的參數(parameter)名稱和類型
	- 呼叫時提供對應的引數(argument)
- 方法呼叫
	- 在物件上呼叫執行個體方法，在執行個體變數名稱後面加上句點、方法的名稱與括號，傳入必要的引數。
	- 用類別名加上呼叫靜態方法，在類別名稱後面加上句點、靜態方法的名稱與括號，傳入必要的引數。

### Further Reading
- [MS 方法 (C# 程式設計手冊)](https://learn.microsoft.com/zh-tw/dotnet/csharp/programming-guide/classes-and-structs/methods)
- [MS 使用建構函式 (C# 程式設計手冊)](https://learn.microsoft.com/zh-tw/dotnet/csharp/programming-guide/classes-and-structs/using-constructors)
## Lab 使用 MyData類別
### Goal
-  透過類別的建構式初始化欄位
	- 在 Form1.cs 中的 Form1 class 中新增型別為 MyData 的 private 欄位
- 透過欄位初始設定式初始化欄位(通常不建議這麼寫)
- 實作計算求和公式的方法
## 雞蛋糕的故事 – class and object
### Goal
- 了解類別中執行個體欄位、靜態欄位、建構式
### Note
- **靜態欄位（Static Fields）：**
	- 靜態欄位屬於類別本身，而不是類別的執行個體(instance)。
	- 所有該類別的執行個體(instance)共享相同的靜態欄位。
- **執行個體欄位（Instance Fields）：**
	- 執行個體欄位屬於類別的執行個體欄位，每個執行個體欄位都有自己的一組執行個體欄位。
	- 每當你創建一個新的執行個體欄位時，它的執行個體欄位就會初始化。
- 靜態欄位和執行個體欄位的差異主要在以下幾點：
	- **存取方式不同**：靜態欄位可以使用類型名稱來存取，而執行個體欄位只能使用執行個體名稱來存取。
	- **共用性不同**：靜態欄位共用於該類型的所有執行個體間，而執行個體欄位每個執行個體都有自己的。
	- **初始化順序不同**：靜態欄位會在類型載入時初始化，而執行個體欄位會在執行個體建立時初始化。

- 以下是一些使用靜態欄位和執行個體欄位的例子：
	- **使用靜態欄位來儲存全域狀態、儲存共用的資源**：雞蛋糕的模具
	- **使用執行個體欄位來儲存特定物件的狀態**：雞蛋糕的內餡
### Further Reading
- [MS 靜態類別和靜態類別成員 (C# 程式設計手冊)](https://learn.microsoft.com/zh-tw/dotnet/csharp/programming-guide/classes-and-structs/static-classes-and-static-class-members)
- [MS 實例建構函式 （C# 程式設計指南）](https://learn.microsoft.com/zh-tw/dotnet/csharp/programming-guide/classes-and-structs/instance-constructors)



