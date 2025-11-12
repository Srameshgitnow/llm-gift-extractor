# 🧠 LLM Gift Extractor

This project demonstrates a simple Python LLM model that extracts specific structured data from text inputs.  
The model takes unstructured text and outputs a JSON object containing the following keys:

- **gift**
- **delivery_days**
- **price_value**

-----------

## 🧩 Example

### Input:
I ordered a Teddy Bear as a birthday gift, and it will be delivered in 3 days for $25.

### Output:

{
  "gift": "Teddy Bear",
  "delivery_days": 3,
  "price_value": 25
}
------------------

⚙️ Notebook

The core logic is implemented in gift_extractor.ipynb.

You can open it using:

jupyter notebook gift_extractor.ipynb

------------------

🧰 Requirements

Python 3.10+

Jupyter Notebook

openai or transformers (depending on your model)

pandas, json

------------------

🚀 Run Locally

git clone https://github.com/Srameshgitnow/llm-gift-extractor.git

cd llm-gift-extractor

jupyter notebook gift_extractor.ipynb

------------------

📄 License

This project is licensed under the MIT License.
