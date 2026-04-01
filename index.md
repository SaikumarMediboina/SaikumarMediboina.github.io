# Sai Kumar Mediboina
**Backend Software Engineer | Java | Spring Boot | Oracle**

📍 Rajahmundry, Andhra Pradesh, India  
✉️ [msaikumar6789@gmail.com](mailto:msaikumar6789@gmail.com) | 🔗 [LinkedIn](https://www.linkedin.com/in/saikumar-mediboina-1b8258136/) 

---

## 🚀 Objective
Backend engineer specializing in performance optimization (97% batch, 85% real-time improvements) and distributed systems at scale. Proven track record of migrating enterprise search engines and reducing database CPU loads, looking to architect scalable Java/Spring systems.

---

## 🛠️ Technical Skills

* **Languages:** Java, SQL, PL/SQL
* **Frameworks & Architecture:** Spring, Spring Boot, Hibernate, RESTful APIs, Microservices, Apache Kafka
* **Databases & Search:** Oracle 19c, Oracle Text, OpenSearch, MySQL
* **Cloud & Tools:** OCI, Grafana, APM, Git, Maven

---

## 💼 Professional Experience

### **Application Developer IC1** | Oracle
*Bangalore, India | Aug 2023 – Present*

* Architected a highly scalable, cloud-native compliance platform on OCI/Kubernetes for enterprise Customer Screening (CS) and Transaction Filtering (TF). 
* Leveraged OpenSearch and Oracle Text to process real-time and high-volume batch workloads, driven by a hybrid decision engine blending deterministic matching with AI semantic search.

---

## 💻 Projects & Architecture

### **Matching & Scoring Engine** *OpenSearch, Oracle Text, Kubernetes, OCI, Microservices*

* **Intelligent Data Ingestion:** Designed secure, REST-based Spring APIs to handle 100 concurrent real-time JSON payloads alongside high-volume nightly batch screening (CS, TF). Engineered a fault-tolerant PL/SQL pipeline using advanced regex and XML aggregations to automatically cleanse, denoise, and transliterate global watchlist data prior to indexing.
* **Core Search Engine Migration & Scale:** Spearheaded the backend transition from OpenSearch to an Oracle Text matching engine, leveraging storage-level computation to significantly reduce infrastructure costs. Scaled the system to process millions of transactions against billions of records, achieving 100+ TPS with sub-2.5s average latency across 23,000-message volume runs (screening 8 simultaneous global watchlists with zero errors).
* **High-Volume Batch Processing:** Achieved 97% latency reduction (2h 5min &rarr; 3min) for 5K-transaction compliance screening by: strategic database indexing on hot paths, intelligent batching to eliminate N+1 queries (N+500 calls &rarr; single aggregated query), and multi-threaded parallel processing with transaction isolation. Scaled to 25K transaction volumes with consistent 8-second average latency.
* **Narrative Text Extraction Engine:** Built intelligent text parser that tokenizes unstructured input and extracts best-match substrings using configurable exact/fuzzy matching. Designed multi-factor scoring algorithm (match quality, length, gap penalties) to rank candidate entities with high precision.
* **Real-Time Screening Optimization:** Achieved an 85% latency reduction (2s &rarr; 300ms) by redesigning synchronous processing into an asynchronous CompletableFuture-based pipeline. Parallelized database queries across thread pools and eliminated JSON aggregation bottlenecks via incremental result streaming to the staging tables.
* **Multi-Service Performance Tuning:** Improved throughput across Alert, Swift, and Data Transform services by migrating JSON processing to stored procedures with alert suppression (70% fewer round-trips), implementing Executor Framework async inserts, optimizing Coherence cache serialization, and deploying strategic query caching.
* **Advanced Hybrid Scoring Engine:** Developed configurable scoring microservice using mathematical edit distances (CED, CMP, WMP, WED) and ML-driven fuzzy matching to blend AI similarity scores with deterministic rules, reducing false positives and improving entity resolution accuracy for global watchlists.

---

## 🎓 Education

* **M.Tech in Information Technology** | *NIT Karnataka* | Aug 2021 – July 2023  
  **CGPA:** 8.96
* **B.Tech in Information Technology** | *JNTU Vizianagaram* | June 2016 – Sept 2020  
  **CGPA:** 8.36

---

## 📜 Certifications & Training

* **Oracle Cloud Infrastructure (OCI) AI Foundations** | *Oracle* (2024)
* **Oracle Database 19c: PL/SQL Workshop** | *Oracle* (2023)
* **Spring 6 with Spring Boot 3 & Java EE: Concurrency** | *LinkedIn Learning* (2024)
* **Advanced Core Java & Spring Boot Architecture** | *Udemy* (2026)

---

## 🏆 Awards & Academic Achievements

* **FSGIU Pacesetter - Spark Award (Oracle):** Awarded for achieving a 7x performance improvement by reducing latency from 5s to 700ms (86%) and playing a key role in migrating core search systems from OpenSearch to Oracle Text.
* **Oracle Agent IR Hackathon (2025):** Engineered an enterprise application to automate daily IUT check-in activities, securing 5th place out of 200 teams and earning official Oracle recognition for rapid prototyping and technical execution.
* **Competitive Examination Excellence:** Secured a **98.0 percentile in GATE 2021** (CS/IT) and a **top 2% statewide rank in EAMCET 2016**, earning a full four-year merit tuition scholarship.
* **Vice President of India Scholarship:** Awarded Scholarship for academic excellence (2019).

<script>
  document.addEventListener("DOMContentLoaded", function() {
      // Find the specific auto-generated link in the sidebar
      var profileLink = document.querySelector("header p.view a");
      if (profileLink) {
          // Change the URL to your LeetCode
          profileLink.href = "https://leetcode.com/u/msaikumar6789/";
          // Change the display text
          profileLink.textContent = "View My LeetCode Profile";
          // Optional: Make it open in a new tab
          profileLink.target = "_blank"; 
      }
  });
</script>
