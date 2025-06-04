# 🐳 Dockerized Python Script: Hello World

This is a minimal example of using Docker to run a Python script.  
It demonstrates how to containerize a simple Python application and execute it consistently across environments — without needing to install Python locally.

## 🧠 What it does

This container runs a basic Python script that prints:

```
Hello docker world
```

It serves as a first step in mastering Docker for data science, development, and reproducible environments.

---

## 📁 Project structure

```
.
├── Dockerfile
└── my_script.py
```

- `Dockerfile`: defines the environment (Python 3) and how the script is executed.
- `my_script.py`: simple Python file that prints a message: "Hello docker".

---

## 🚀 How to run

Make sure you have Docker installed. Then:

1. **Clone the repo**:

```bash
git clone https://github.com/your-username/docker-hello-world.git
cd docker-hello-world
```

2. **Build the image**:

```bash
docker build -t my_first_docker .
```

3. **Run the container**:

```bash
docker run my_first_docker
```

You should see the output:

```
Hello docker 
```

---

## 📦 Why this matters

This simple example proves that:

- You can run Python code inside containers.
- You can create portable, isolated environments.
- You are ready to move toward more complex setups (e.g., data science, Jupyter, APIs).

---

## 🔧 Next steps (ideas)

- Add dependencies with `pip install`
- Mount a volume to work on real data interactively
- Turn this into a Jupyter-based container for analysis
- Publish your container to Docker Hub

---

## 📫 Contact

Created by **Luis Cano** – feel free to connect on [LinkedIn](https://www.linkedin.com) or reach out if you're exploring Docker and AI for health and pathology.
