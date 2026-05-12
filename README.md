# ⚡ Performance Testing Project

A comprehensive performance testing suite built with **Apache JMeter**, covering 4 test types to validate system behavior under different conditions.

---

## 📋 Test Types

| Test | Description | Duration |
|------|-------------|----------|
| **Load** | Normal expected load on the system | ~1 min |
| **Stress** | Push the system beyond its limits | ~1 min |
| **Soak** | Sustained load over a long period | ~60 min |
| **Scalability** | Gradually increase load to measure scaling | ~2 min |

---

## 📁 Project Structure

```
├── reports/
│   ├── load/          # Load test JMeter dashboard
│   ├── stress/        # Stress test JMeter dashboard
│   ├── soak/          # Soak test JMeter dashboard
│   └── scalability/   # Scalability test JMeter dashboard
```

---

## 🚀 How to View Reports

  Open any report by navigating to its folder and opening `index.html` in your browser
   ```
   reports/load/index.html
   reports/stress/index.html
   reports/soak/index.html
   reports/scalability/index.html
   ```

---

## 🛠️ Tools Used

- [Apache JMeter] - Performance testing tool
- JMeter HTML Dashboard Reporter

---

## 📊 Reports Include

- **APDEX Score** — Application Performance Index
- **Requests Summary** — Pass/Fail pie chart
- **Statistics Table** — Response times, throughput, error rates
- **Errors Table** — Detailed error breakdown
- **Top 5 Errors by Sampler**

