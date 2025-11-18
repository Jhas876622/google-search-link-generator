# Google Search Link Generator

A simple Python-based project (Jupyter Notebook) that automatically generates a valid, clickable Google search link based on user input. This tool helps convert plain text queries into shareable Google search URLs.

---

## 📌 Features

* Converts any text keyword or query into a valid Google search link
* URL encoding support
* Easy to use and modify
* Beginner-friendly Python code
* Works directly inside Jupyter Notebook

---

## 🧰 Technologies Used

| Tool                      | Description                                      |
| ------------------------- | ------------------------------------------------ |
| Python                    | Core programming language                        |
| Jupyter Notebook (.ipynb) | Interactive development and execution playground |
| URL Encoding (urllib)     | To format the search query correctly             |

---

## 📂 Project Structure

```
📁 Google Search Link Generator
│
├── Google search Link Generator.ipynb    # Main notebook file
└── README.md                              # Documentation file
```

---

## 🚀 How to Use

1. Open the `.ipynb` notebook using Jupyter Notebook / JupyterLab / Google Colab
2. Run all cells in sequence
3. Enter your desired search query when prompted
4. Copy the generated clickable link and use it anywhere

---

## 🧪 Example

**Input:**

```
Artificial Intelligence applications
```

**Output:**

```
https://www.google.com/search?q=Artificial+Intelligence+applications
```

---

## 🔧 Requirements

| Requirement      | Version |
| ---------------- | ------- |
| Python           | 3.x     |
| Jupyter Notebook | Latest  |
| requests         | Latest  |
| beautifulsoup4   | Latest  |

---

## 📥 Installation

Run the following commands to install required dependencies:

```bash
pip install requests
pip install beautifulsoup4
```

---

----------|---------|
| Python | 3.x |
| Jupyter Notebook | Latest |

The project uses the following external libraries:

* `requests`
* `BeautifulSoup` (from `bs4`)

---

## 🌐 Live Demo (Optional)

> Add a Binder / Colab link here if published.

---

## 💻 Code Snippet

```python
from urllib.parse import quote_plus

query = input("Enter your search query: ")
encoded_query = quote_plus(query)
link = f"https://www.google.com/search?q={encoded_query}"
print("Generated Google Search Link:", link)
```


---

## ✨ Contributions

Pull requests, feature suggestions, and improvements are welcome!

---


⭐ **If you like this project, don't forget to give it a star!** ⭐
