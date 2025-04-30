<h1 align="center" style="font-family: Inter, sans-serif; font-style: normal; font-weight: 700;">m:lop</h1>

<p align="center">
  <strong>A tool for understanding and improving ML models</strong>
</p>

<p align="center">
<a href="https://app.mlop.ai">Application</a> |
  <a href="https://docs.mlop.ai">Documentation</a> |
  <a href="https://github.com/mlop-ai/mlop">GitHub</a>
</p>

**mlop** is a fully open source dev tool for machine learning engineers that traces key metrics of model training, all the way down to the parameters and gradients level. Unlike other tools, we are laser focused on efficiency and stability. Our platform is designed from the ground up to be fast and scalable - we help you catch issues early and prevent wasted compute.

---

## 📚 Our Stack

- **[Server](https://github.com/mlop-ai/server)**
    - **[Rust](https://github.com/mlop-ai/ingest)** - the ultra-performant data ingestion service
    - **[Node.js](https://github.com/mlop-ai/web)** - the web application
    - **[Python](https://github.com/mlop-ai/py)** - miscellaneous enrichment services
- **Client**
    - **[Python](https://github.com/mlop-ai/mlop/tree/main/mlop)** - a super lightweight and *truly* asynchronous logging system

---

## 🎥 Our Demo

**mlop** adopts a KISS philosophy that allows it to outperform all other tools in this category. Supporting high and stable data throughput should be *THE* top priority for efficient MLOps.
<video loop src='https://github.com/user-attachments/assets/efd9720e-6128-4278-85ec-ee6139a851af' alt="demo" width="1200" style="display: block; margin: auto;"></video>

<p align="center">
<strong>mlop</strong> logger (bottom left) v. a conventional logger (bottom right)
</p>

---

## 📦 Our Packages

- Try **mlop** on our platform in [a notebook](https://colab.research.google.com/github/mlop-ai/mlop/blob/main/examples/intro.ipynb) & start integrating in just 5 lines of Python code:

```python
!pip install mlop

import mlop

mlop.init(project="hello-world")
mlop.log({"e": 2.718})
mlop.finish()
```

- Self-host your very own **mlop** instance & get started in just 3 commands with **docker-compose**

```bash
git clone --recurse-submodules https://github.com/mlop-ai/server.git; cd server
cp .env.example .env
sudo docker-compose --env-file .env up --build
```


---

## 🫡 Our Vision

**mlop** is a platform built for and by ML engineers, supported by [our community](https://discord.gg/ybfVZgyFCX)! We were tired of the current state of the art in ML observability tools, and this tool was born to help mitigate the inefficiencies - specifically, we hope to better inform you about your model performance and training runs; and actually **save you**, instead of charging you, for your precious compute time! 

🌟 Be sure to star our repos if they help you ~

