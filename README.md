# cyy
這是一個簡單的猜數字遊戲程式，允許玩家猜測一個隨機生成的數字，並提供相應的反饋。

## 安裝

1. 克隆存儲庫：

    ```bash
    git clone https://github.com/your_username/guess-number-game.git
    ```

2. 進入項目目錄：

    ```bash
    cd guess-number-game
    ```

3. 創建和激活虛擬環境（可選）：

    ```bash
    python -m venv venv
    source venv/bin/activate  # 在 Windows 上，使用 venv\Scripts\activate
    ```

4. 安裝相依套件：

    ```bash
    pip install -r requirements.txt
    ```

## 配置

- 在項目目錄中，創建一個名為 `config.xml` 的 XML 配置文件，並填入您想要的初始值：

    ```xml
    <config>
        <x1>1</x1>
        <x2>100</x2>
        <n>10</n>
    </config>
    ```

## 使用

執行 `guess_the_number.py` 文件，按照提示進行遊戲：

```bash
python guess_the_number.py
