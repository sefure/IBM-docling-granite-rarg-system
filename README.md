# AI-Powered Document Retrieval System with Docling & IBM Granite

This project is an advanced Document Retrieval System developed as part of the **IBM AI Training Program**. It leverages **IBM's Granite** large language model and **DS4SD's Docling** to parse complex documents (like PDFs, DOCX) and build an efficient, intelligent Retrieval-Augmented Generation (RAG) pipeline.

---

## English

## 🚀 Overview

Traditional document search often fails when dealing with complex layouts, tables, and unstructured text. This system solves that problem by combining a state-of-the-art document parser with a powerful enterprise-grade LLM to retrieve precise answers from localized knowledge bases.

### Key Features
* **Intelligent Document Parsing:** Uses **Docling** to accurately chunk and extract layout-aware text and tables from rich documents.
* **Enterprise-Grade AI:** Powered by **IBM Granite** to generate context-aware, accurate, and fluent responses based on retrieved data.
* **Semantic Search:** Vector embeddings allow the system to understand the user's intent rather than just matching exact keywords.

---

## 🛠️ Architecture

The system follows a classic **Retrieval-Augmented Generation (RAG)** workflow:

1.  **Ingestion:** Unstructured documents are processed and chunked using Docling.
2.  **Embedding & Storage:** Text chunks are converted into vector embeddings and stored in a vector database.
3.  **Retrieval:** When a user asks a question, the system retrieves the most relevant document chunks.
4.  **Generation:** The IBM Granite model uses the retrieved context to generate a precise answer.

---

## 🧰 Tech Stack

* **LLM Ecosystem:** IBM Granite via Watsonx.ai / Ollama (or specify how you accessed it)
* **Programming Language:** Python 3.10+
* **Vector Database:** [Specify what you used, e.g., ChromaDB, FAISS, or Milvus]
* **Framework:** [Specify if you used LangChain, LlamaIndex, or Native Python]

---
# Docling ve IBM Granite ile Yapay Zeka Destekli Doküman Erişim Sistemi

Bu proje, **IBM Yapay Zeka Eğitim Programı** kapsamında geliştirilmiş gelişmiş bir Doküman Erişim Sistemidir. Proje, karmaşık dokümanları (PDF, DOCX vb.) anlamlı parçalara ayırmak ve verimli bir **RAG (Retrieval-Augmented Generation / Doküman Destekli Nesil)** hattı kurmak için **IBM Granite** büyük dil modelini ve **DS4SD Docling** kütüphanesini kullanır.

---

## Türkçe

## 🚀 Genel Bakış

Geleneksel doküman arama sistemleri; karmaşık sayfa düzenleri, tablolar ve yapılandırılmamış metinler söz konusu olduğunda genellikle yetersiz kalır. Bu sistem, gelişmiş bir doküman ayrıştırıcıyı (parser) kurumsal düzeyde bir LLM ile birleştirerek, yerel bilgi tabanlarından (dokümanlarınızdan) kesin ve doğru yanıtlar üretilmesini sağlar.

### Öne Çıkan Özellikler
* **Akıllı Doküman Ayrıştırma:** Sayfa düzenini ve tabloları kaybetmeden dokümanları doğru şekilde parçalamak (chunking) için **Docling** kullanır.
* **Kurumsal Düzeyde Yapay Zeka:** Alınan verilere dayanarak bağlama uygun, doğru ve akıcı yanıtlar üretmek için **IBM Granite** modelinden yararlanır.
* **Anlamsal Arama (Semantic Search):** Vektör gömme (embedding) teknolojisi sayesinde sistem, sadece kelime eşleştirmesi yapmaz, kullanıcının sorusundaki gerçek niyeti anlar.

---

## 🛠️ Sistem Mimarisi

Sistem, klasik bir **RAG (Doküman Destekli Nesil)** iş akışını takip eder:

1.  **Veri Alımı (Ingestion):** Yapılandırılmamış dokümanlar Docling kullanılarak işlenir ve anlamlı metin parçalarına bölünür.
2.  **Vektörleştirme ve Depolama:** Metin parçaları vektör gömme (embedding) modelleriyle dönüştürülerek bir vektör veritabanına saklanır.
3.  **Arama/Erişim (Retrieval):** Kullanıcı bir soru sorduğunda, sistem dokümanlar arasındaki en ilgili metin parçalarını bulur.
4.  **Yanıt Üretimi (Generation):** IBM Granite modeli, getirilen bu bağlamı (context) kullanarak kullanıcıya kesin ve doğru bir cevap hazırlar.

---

## 🧰 Teknolojik Altyapı

* **LLM Ekosistemi:** IBM Granite (Watsonx.ai veya Ollama entegrasyonu - *nasıl eriştiyseniz buraya not edebilirsiniz*)
* **Programlama Dili:** Python 3.10+
* **Vektör Veritabanı:** [Kullandığınız veritabanını yazın, örn: ChromaDB, FAISS veya Milvus]
* **Çatı / Framework:** [Varsa yazın, örn: LangChain, LlamaIndex veya Saf Python]
