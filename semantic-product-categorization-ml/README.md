# 🧠 Semantic Product Categorization using Embeddings & Pinecone

This project builds a semantic search-based product categorization feature using **Cohere's Embeddings API** and **Pinecone vector database**, designed to assist catalog teams in quickly assigning product categories.

---

## 🎯 Objective

The goal was to build a proof of concept (POC) that integrates into a catalog management app to automate the product categorization process.  
This feature benefits the catalog team by:

- ✅ Helping new members easily suggest categories without memorizing full taxonomy  
- ✅ Reducing manual UI steps like scrolling long lists  
- ✅ Suggesting **top 3 category options** using semantic similarity for better user decision-making  

---

## ⚙️ Tools & Technologies

- **[Cohere](https://cohere.com/):** Used to generate semantic embeddings from product names  
- **[Pinecone](https://www.pinecone.io/):** Used as a vector store to search similar products  
- **[Retool](https://retool.com/):** UI prototype platform (optional)  
- **Python Libraries:** `pandas`, `tqdm`, `cohere`, `pinecone`, `IPython`  

---

## 🧬 What Are Embeddings?

Embeddings convert text into numeric vectors.  
These vectors allow the model to understand **semantic similarity** between product names.  
Closer vectors = similar meaning.

📚 Learn more: [Cohere Embeddings Guide](https://docs.cohere.com/docs/embeddings)

---

## 🔁 End-to-End Pipeline

### ✅ Step 1: Generate embeddings for all known product names  
### ✅ Step 2: Store embeddings + categories in Pinecone  
### ✅ Step 3: When a new product comes in, generate its embedding  
### ✅ Step 4: Search Pinecone for the **top N similar products**  
### ✅ Step 5: Extract their categories  
### ✅ Step 6: Return the **top 3 recommended categories**  

---
## 🧪 Sample Demo Flow

**Input Product Name:**  
`Samsung 55-inch 4K LED Smart TV`

**→ Top 3 Suggested Categories:**
1. **Electronics > Televisions**  
2. **Home Appliances > Smart Devices**  
3. **Consumer Goods > Display Screens**

---

## 👩‍💻 Author

**Krina Patel**  
AI/ML Engineer | Data Science | NLP | ML Pipelines  
💼 [LinkedIn](https://www.linkedin.com/in/krinap08/)  


---

⭐ *If you like this project, consider giving it a ⭐ and following for more AI/ML projects!*
