# MCP 伺服器實作筆記

本文總結了實作 MCP 伺服器時遇到的關鍵步驟和問題。

## 關鍵步驟

1.  使用者要求我 fetch sdk 的內容說明。(下午7:40)
2.  使用者想要建立一個 `mcpServer` 目錄，然後依照網站的說明來實作。(下午7:42)
3.  使用者已安裝 Python 和 uv。(下午7:43)
4.  我引導使用者使用 `pip install "mcp[cli]"` 命令安裝 MCP。(下午7:43)
5.  我嘗試使用 MCP Inspector 來測試伺服器，但遇到了一些問題，包括語法錯誤和找不到 Claude 應用程式。(下午7:44 - 下午7:51)
6.  我更正了 `server.py` 檔案中的語法錯誤。(下午7:45 - 下午7:51)
7.  我建立了 `mcpServer` 目錄，並在其中使用 uv 建立了一個新的 Python 專案。(下午7:57)
8.  我建立了一個簡單的 MCP 伺服器，並將其儲存到 `server.py` 檔案中。(下午7:58)

## 遇到的問題

*   由於 docstring 中使用了不正確的引號，導致 `server.py` 中出現語法錯誤。
*   找不到 Claude 應用程式，導致無法在 Claude Desktop 中安裝 MCP 伺服器。
*   `mcp dev` 和 `python server.py` 命令之間存在衝突。

## 後續步驟

*   進一步偵錯和測試 MCP 伺服器。
*   探索在沒有 Claude Desktop 的情況下部署和測試伺服器的替代方法。
