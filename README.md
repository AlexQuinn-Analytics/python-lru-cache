# 🚀✨ LRU Cache Implementation in Python

🔖 **Description:**  
An efficient Least Recently Used (LRU) Cache implemented in Python using 🗂️ **doubly linked list** and 🔑 **hashmap** for O(1) operations.

---

## 🛠️ Features

✅ Supports **get(key)** and **put(key, value)** in **O(1) time**  
🔁 Automatically evicts the **least recently used item** when capacity is exceeded  
🧩 Uses:
- 🗃️ **Doubly Linked List** to maintain usage order
- ⚡ **Hash Map (dict)** for quick key-node lookup

---

## 📂 Files

- `lru_cache.py` – main implementation and example usage

---

## 💻 Example Usage

```python
lru = LRUCache(3)
lru.put(1, 1)
lru.put(2, 2)
lru.put(3, 3)
print(lru.get(1))  # Output: 1
lru.put(4, 4)      # Evicts key 2
print(lru.get(2))  # Output: -1
print(lru.get(3))  # Output: 3
print(lru.get(4))  # Output: 4
🎯 Why This Project?
💡 For CS (Computer Science) Applications:

Demonstrates proficiency in classic data structures 🏗️ and algorithm design ⚙️

Shows understanding of system performance optimization 🚀 via caching strategies

📊 For DS (Data Science) Applications:

Highlights coding 💻 and logical thinking 🧠 beyond library usage

LRU cache logic is commonly used in feature stores, database query optimization, and large-scale data pipelines

🔮 Future Work
🌟 Implement LFU Cache for frequency-based eviction
🌐 Build a RESTful API integrating this cache with a database
⚖️ Compare with Python’s built-in OrderedDict LRU implementations

🙋‍♂️ Author
Shuai Qian （Alex Quinn）
