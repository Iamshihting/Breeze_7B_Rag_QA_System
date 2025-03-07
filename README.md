# Breeze_Rag_QA_System
📌 專案簡介

本專案旨在透過 RAG（檢索增強生成） 方法，基於 PDF 文件提供準確的問答服務。使用 LangChain 進行檢索，並透過 Breeze-7B 模型生成回答，幫助使用者高效獲取 PDF 內的相關資訊。

📌 功能特點

1️⃣ PDF 文本處理：
解析 PDF 內容，清理與格式化文本，透過 RecursiveCharacterTextSplitter 進行文本分割

2️⃣ 向量資料庫：
將文本轉換為向量並存入 Chroma 向量資料庫，使用 HuggingFaceEmbeddings 進行文本嵌入

3️⃣ RAG 生成回應：
利用 LangChain 檢索相關文本，自訂 Prompt，結合 Breeze-7B 生成回答

4️⃣ 問答測試：
從 Excel 檔案中讀取標準答案，與模型生成的答案進行對比
