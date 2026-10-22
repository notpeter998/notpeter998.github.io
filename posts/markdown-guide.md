# Markdown 語法與寫作範例

*發布日期：2026-10-22*

這篇文章整理了常用的 Markdown 格式與展示範例，可作為後續撰寫文章時的快速參考。

---

## 標題層級

使用 `#` 符號可以建立不同層級的標題：

```markdown
# 一級標題
## 二級標題
### 三級標題
```

---

## 樣式與醒目提示

- **粗體文字**：`**粗體文字**`
- *斜體文字*：`*斜體文字*`
- ~~刪除線~~：`~~刪除線~~`
- 行內程式碼：`code`

---

## 引言（Blockquotes）

> 這是一段引言文字。
> 可以用來引用名言、重點提醒或備註說明。

---

## 程式碼區塊

使用三個反引號，並指定語言（例如 `python`、`bash`）以啟用語法高亮：

```python
def greet(name: str) -> str:
    """向訪客問好"""
    return f"Hello, {name}! Welcome to notpeter998's blog."

if __name__ == "__main__":
    print(greet("Reader"))
```

```bash
# 啟動本地 Python 預覽伺服器
python -m http.server 3000
```

---

## 表格

| 欄位名稱 | 型態 | 說明 |
| :--- | :---: | :--- |
| `id` | int | 唯一識別碼 |
| `title` | string | 文章標題 |
| `is_published` | bool | 是否發布 |

---

## 待辦事項清單

- [x] 建立 GitHub SSH 金鑰連線
- [x] 初始化 Docsify 網誌結構
- [ ] 推送程式碼至 GitHub 儲存庫
- [ ] 啟用 GitHub Pages 線上發布
