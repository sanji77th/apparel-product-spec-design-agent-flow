# Next Season Apparel Trend Analysis and Product Spec. Design Using Crew AI

This project uses a multi-agent workflow powered by **Crew AI** to conduct comprehensive market research, analyze future apparel trends, and generate innovative product concepts. By integrating **Gemma2-9B-IT** from Groq, the project maintains high inference efficiency while delivering accurate and actionable insights.

---

## Ὠ0 **Project Overview**
In the fast-evolving fashion industry, staying ahead of trends is critical for success. This project combines state-of-the-art AI with multi-agent collaboration to:
- Perform extensive market research on emerging apparel trends.
- Analyze market data to generate detailed and insightful reports.
- Design five unique apparel products with precise technical specifications, including sizes, materials, measurements, and color options.

---

## 🧐 **Agents and Tasks**

### **1. Researcher Agent**
- **Role:** Senior Data Researcher  
- **Goal:** Identify cutting-edge developments in apparel trends  
- **Task:** Conduct in-depth market research and compile 10 key insights  

### **2. Reporting Analyst Agent**
- **Role:** Reporting Analyst  
- **Goal:** Generate detailed reports based on research findings  
- **Task:** Expand key insights into comprehensive report sections formatted in Markdown  

### **3. Product Designer Agent**
- **Role:** Senior Product Designer  
- **Goal:** Craft detailed product designs for five future apparel types  
- **Task:** Develop five distinct products with full technical specifications  

---

## 🛠️ **Technologies Used**
- **Crew AI:** For multi-agent orchestration  
- **Gemma2-9B-IT (Groq):** High-performance inference model  
- **YAML Configuration:** Flexible agent and task management  

---

## 🛆 **Key Deliverables**
- **Market Research Insights:** Top 10 trends in the future apparel market  
- **Analytical Reports:** Comprehensive, actionable reports on trend analysis  
- **Product Designs:** Detailed specifications for five apparel concepts  

---

## 🚀 **How to Run the Project**
1. Clone this repository:  
   ```bash
   git clone <repo-url>
   cd <repo-directory>
   ```  
2. Configure agent parameters in `agents.yaml` and `tasks.yaml`.  
3. Execute the workflow using Crew AI:  
   ```bash
   crew run
   ```  
4. View generated reports in `report.md` and product designs in `product.md`.  

---

## 🧱 **Contributing**
Contributions are welcome! Please submit issues or pull requests to help improve this project.  

---

## 📜 **License**
This project is licensed under the MIT License.
