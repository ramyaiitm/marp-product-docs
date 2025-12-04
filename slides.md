---
marp: true
paginate: true
size: 16:9
header: "Product Documentation — Software Engineering Team"
footer: "22f3002140@ds.study.iitm.ac.in"
theme: custom
style: |
  /* ---------- Custom Marp Theme ---------- */
  :root {
    --bg: #0d1117;
    --fg: #e6edf3;
    --primary: #58a6ff;
    --accent: #2ea043;
    --muted: #8b949e;
    --card: rgba(255,255,255,0.06);
  }

  section {
    background-color: var(--bg);
    color: var(--fg);
    font-family: 'Segoe UI', Helvetica, Arial, sans-serif;
    padding: 40px;
  }

  h1, h2, h3 {
    color: var(--primary);
    margin-bottom: 10px;
  }

  .card {
    background: var(--card);
    border-radius: 14px;
    padding: 18px;
    margin-top: 18px;
  }

  pre {
    background: rgba(20,20,20,0.5);
    padding: 10px;
    border-left: 4px solid var(--primary);
    border-radius: 8px;
    color: white;
  }

  .email {
    font-size: 0.8rem;
    color: var(--muted);
    position: absolute;
    bottom: 18px;
    right: 28px;
  }
---

# **Product Documentation Presentation**
## DataSync Engine — Developer Guide

**Technical Writer:** Documentation Team  
<u>22f3002140@ds.study.iitm.ac.in</u>

---

# Overview  
This presentation is built using **Marp**, designed for:

- Maintainability in version control  
- Multi-format export (HTML / PDF / PPTX)  
- Developer-friendly documentation  

<div class="card">
<strong>Key Components:</strong><br>
✔ Architecture<br>
✔ API Reference<br>
✔ Deployment<br>
✔ Troubleshooting
</div>

---

---
backgroundImage: "https://images.unsplash.com/photo-1527443224154-d8f76c3b3c54?q=80&w=1920"
backgroundSize: cover
backgroundPosition: center
---

# Architecture Overview

> The DataSync Engine connects client agents to cloud ingestion pipelines securely.

<div class="email">22f3002140@ds.study.iitm.ac.in</div>

---

# Installation

### 1. Download and extract
```bash
tar xzf datasync-1.0.0.tar.gz
cd datasync
