---
marp: true
title: Product Documentation Presentation
paginate: true
theme: custom-theme
class: lead
---

<!-- Custom Theme -->
<style>
section {
  font-family: "Segoe UI", sans-serif;
}

h1 {
  color: #1a73e8;
}

.custom-box {
  padding: 15px;
  border-radius: 10px;
  background: #eef6ff;
  border-left: 6px solid #1a73e8;
}
</style>

<!-- Title Slide WITH background image (visible on slide) -->
<!-- This block ensures the image actually renders -->
<!-- Marp requires the background to be inside slide metadata -->

<!-- _backgroundImage: url('images/background.jpg') -->
<!-- _backgroundSize: cover -->

# **Product Documentation Overview**
### Ramya IITM  
📧 **22f3002140@ds.study.iitm.ac.in**
### December 2025


---

# **Goals of This Documentation**

<div class="custom-box">
• Maintainable in version control  
• Exportable to PDF/HTML/Slides  
• Uses a custom Marp theme  
• Includes design and engineering details
</div>

---

# **Architecture Overview**

```mermaid
flowchart TD
    A[Client App] --> B(API Gateway)
    B --> C[Microservice 1]
    B --> D[Microservice 2]
    C --> E[Database]
