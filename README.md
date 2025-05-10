![Om Kolekar's GitHub Banner](https://github.com/kolekarom/kolekarom/blob/main/banner.png)

# 👋 Hi, I'm Om Kolekar!

I'm a passionate developer from India with a strong interest in full-stack web development and backend engineering. I enjoy solving real-world problems through code and continuously learning new technologies to enhance my skills and build scalable solutions.

---

## 🛠️ Tech Stack

- **Languages:** C++, JavaScript, Python  
- **Web Development:** HTML, CSS, React.js, Node.js  
- **Databases:** MySQL, MongoDB, Realm  
- **Cloud & DevOps:** AWS (EC2, Lambda)

---

## 📫 Connect With Me

- 🔗 [GitHub](https://github.com/kolekarom)  
- 🔗 [LinkedIn](https://www.linkedin.com/in/om-kolekar/)  
- 🔗 [Portfolio](https://portfolio-beige-six-45.vercel.app/)

---

## 🚀 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kolekarom&show_icons=true&theme=github_dark&hide_border=true" alt="Om Kolekar GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kolekarom&layout=compact&theme=github_dark&hide_border=true" alt="Om Kolekar's Top Languages" />
</p>

---

## 📊 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=kolekarom&theme=github-compact&hide_border=true&radius=8" alt="Om Kolekar GitHub Activity Graph" />
</p>

---

## 🧠 Projects & Scripts

### 📌 Outlier Detection in Python

```python
import numpy as np

def detect_outliers(data):
    q1, q3 = np.percentile(data, [25, 75])
    iqr = q3 - q1
    lower_bound = q1 - 1.5 * iqr
    upper_bound = q3 + 1.5 * iqr
    return [x for x in data if x < lower_bound or x > upper_bound]

# Example usage
data = [12, 18, 25, 7, 10, 15, 8, 19, 3, 100, 16]
print("Outliers detected:", detect_outliers(data))
