# Day 15 — Phần B: Research Thị Trường & Track Decision Memo
**Họ tên:** Tạ Duy Xuân | **MSSV:** 2A202600970 | **Ngày:** 18/06/2026

---

## B1 · Ghi chú Research Thị Trường

### Nguồn đọc
- WEF Future of Jobs Report 2025
- PwC 2026 Global AI Jobs Barometer
- Second Talent — Vietnam AI Engineer Market 2026
- ITviec Vietnam IT Salary & Recruitment Market 2025–2026

---

### Nghề / kỹ năng đang tăng nhanh

| Kỹ năng / Role | Tín hiệu |
|---|---|
| AI & Big Data | WEF: top fastest-growing skill, >90% doanh nghiệp sẽ tăng sử dụng |
| Agentic AI / Multi-agent | Exploded 2025–2026; LangGraph, A2A, MCP trở thành baseline JD |
| LLM Engineer / GenAI Engineer | Job postings tăng 8× nhanh hơn thị trường chung (PwC) |
| RAG Engineer | Hybrid search, reranking, vector DB trở thành yêu cầu standard |
| LLMOps / AI Observability | Langfuse, Phoenix, OpenTelemetry — nhu cầu tăng mạnh khi AI ra production |

### Nghề / kỹ năng đang khan (cầu vượt cung)

- Vietnam chỉ có ~300 AI engineer được công nhận là thực sự chuyên sâu, đáp ứng ~10% nhu cầu
- Senior AI Engineer biết dẫn team: cực khan, demand tăng 60% YoY
- Engineer có kinh nghiệm production AI (không chỉ demo): rất hiếm
- LLM Engineer chuyên sâu (fine-tuning, alignment, eval): toàn cầu thiếu, lương $220K–$280K

### Điều bất ngờ / năng lực đang bị định giá lại

- **+62% lương premium** cho người có AI skills (PwC 2026) — không phải 10–20% mà là hơn gấp đôi
- AI-exposed entry-level roles đang đòi kỹ năng senior-level: judgement, system design, tracing lỗi production — không còn là công việc "junior" nữa
- Observability + eval trở thành differentiation thật sự: biết Langfuse, RAGAS, DeepEval mà nhiều ứng viên không có
- Thị trường phân tách 2 nhánh (PwC "two-track"): người nắm AI tools → lương tăng mạnh; người không theo kịp → bị tự động hóa

### Một câu: thị trường tương lai thưởng cho năng lực nào?

> **Người có thể build và vận hành hệ thống AI production-grade — không chỉ gọi API mà còn thiết kế pipeline, đánh giá output, debug khi hệ thống fail.**

---

## B2 · Research Role 2 Chiều

### Role được chọn: **AI Engineer / GenAI Engineer**
*(Pathway D — tự build sản phẩm; role end-to-end từ kỹ thuật tới deploy)*

### 2–3 JD thật phân tích

**JD 1 — Agentic AI Engineer (Remote, 2026)**
Nguồn: Medium / AY Automate job postings

**JD 2 — Gen AI / RAG Engineer (Dice.com / Deloitte Consulting)**

**JD 3 — AI Engineer Vietnam (Glints / Glassdoor listings)**

---

### Bên ngoài — Role này đòi hỏi gì

| Kỹ năng / Năng lực | Tần suất trong JD | Mức độ |
|---|---|---|
| Python production-grade | Tất cả JD | Bắt buộc |
| RAG pipeline (hybrid search, reranking, vector DB) | 3/3 | Core |
| Multi-agent (LangGraph, CrewAI, A2A) | 3/3 | Core |
| LLM API (OpenAI, Anthropic, Gemini, OpenRouter) | Tất cả JD | Bắt buộc |
| Evaluation (RAGAS, DeepEval, LLM-as-judge) | 2/3 | Quan trọng |
| Observability (Langfuse, Phoenix, OpenTelemetry) | 2/3 | Quan trọng |
| MCP / Tool calling / Function calling | 2/3 | Đang tăng nhanh |
| Fine-tuning (LoRA, DPO, SFT) | 1/3 | Nâng cao / senior |
| FastAPI / API deployment | 2/3 | Thực tế |
| Vector DB (ChromaDB, Weaviate, Pinecone) | 3/3 | Core |

**Mức seniority kỳ vọng:** Mid-level (1–3 năm) với portfolio có artifact chạy được thật, không chỉ tutorial.

---

### Bên trong — Đối chiếu với bản thân (từ Phase 1)

| Kỹ năng JD đòi | Artifact Phase 1 tương ứng | Trạng thái |
|---|---|---|
| RAG pipeline (chunking → retrieval → generation) | Day 8: full 10-task pipeline (semantic + lexical + rerank + fallback + citation) | **Đã có** |
| Multi-agent / LangGraph | Day 9: distributed multi-agent A2A system (law/tax/compliance agents, registry, parallel delegation) | **Đã có** |
| A2A protocol / MCP | Day 9: A2A SDK, dynamic discovery, trace propagation | **Đã có** |
| Evaluation (RAGAS / DeepEval) | Day 8 group project: golden dataset + eval pipeline + A/B comparison | **Đã có** |
| LLM Observability / Langfuse | Day 13: Langfuse tracing, structured logging, PII scrubbing, SLO, alerting | **Đã có** |
| Vector DB (ChromaDB) | Day 8: ChromaDB indexing + semantic search | **Đã có** |
| FastAPI + production API | Day 13: FastAPI agent với middleware, correlation ID, metrics | **Đã có** |
| Fine-tuning (LoRA / DPO) | Chưa làm | **Cần học** |
| Graph DB (Neo4j / Memgraph) | Chưa làm | **Cần học** |
| Voice agent / Browser agent | Chưa làm | **Nice-to-have** |

**Loại công việc cho năng lượng (từ buổi sáng):**
- Thích nhất: thiết kế pipeline (D8 retrieval pipeline), debug multi-agent khi agent không route đúng (D9), hiểu tại sao RAG fail và sửa
- Ít thích: viết báo cáo thuần, không có artifact code chạy được

**→ Một câu kết:** Role AI Engineer nghiêng rõ về **T3 AI Engineering** vì core JD demands đều là kỹ thuật xây hệ thống (RAG, agent, eval, observability), không phải ra quyết định sản phẩm (T1) hay thuần hạ tầng vận hành (T2).

---

## B3 · Track Decision Memo

---

### Suy nghĩ trước khi chốt

**Nhìn lại Phase 1 và thị trường vừa research, loại công việc nào mình vừa làm được vừa muốn làm tiếp?**

Hai loại công việc rất khác nhau xuất hiện trong Phase 1:
- **Kỹ thuật:** viết RAG pipeline (D8), xây multi-agent A2A (D9), setup Langfuse (D13) — làm được, nhưng thỏa mãn kiểu "hoàn thành bài"
- **Product:** phân tích app Moni/MoMo (D5), tìm ra "AI lý thuyết hóa thay vì thực thi hóa", đề xuất spec change cụ thể — làm xong thấy muốn đào sâu hơn, muốn hỏi thêm "vậy feature tiếp theo nên là gì?"

Loại thứ hai cho năng lượng hơn. Kỹ thuật là công cụ, product thinking mới là thứ mình muốn đi sâu.

**Track nào để đi sâu vào loại công việc đó?**

T1 AI Product — biến năng lực kỹ thuật hiện có thành lợi thế khi ra quyết định sản phẩm: hiểu AI thật sự làm được gì, nên đặt boundary ở đâu, success metric là gì, và thiết kế luồng xử lý khi AI sai.

**Mình đang do dự giữa hai track nào?**

T1 vs T3. T3 hấp dẫn vì đã build nhiều artifact kỹ thuật ở Phase 1 và thị trường đang rất cần — nhưng nếu làm thuần T3, mình sẽ là một trong nhiều AI engineers. Nếu làm T1 với nền kỹ thuật sâu, mình có thể là AI Product person hiếm: người vừa đọc được trace Langfuse vừa viết được PRD.

**Lý lẽ mạnh nhất cho T3 (track không chọn):**
JD thị trường 2026 đang trả +62% lương cho AI skills kỹ thuật; các artifact D8/D9 đã là portfolio T3 sẵn sàng. Bỏ T3 có nghĩa là không khai thác hết những gì đã build.

**Phản bác:** Nền kỹ thuật D8/D9/D13 vẫn là lợi thế của mình khi làm T1 — không phải bỏ đi mà là dùng khác. Người T1 biết kỹ thuật sẽ không bị engineer "dắt mũi" và ra quyết định sản phẩm chính xác hơn.

**Nếu 6 tháng nữa nhìn lại và thấy chọn chưa đúng, dấu hiệu sẽ là gì?**
Nếu thấy mình chỉ đang viết doc/spec mà không hiểu tại sao kỹ thuật không làm được — nghĩa là đã mất nền kỹ thuật, cần bổ sung lại. Hoặc nếu cứ muốn tự implement thay vì định nghĩa bài toán → thì T3 đúng hơn.

---

## TRACK DECISION MEMO — Day 15

**Họ tên:** Tạ Duy Xuân &nbsp;&nbsp;&nbsp;&nbsp; **MSSV:** 2A202600970 &nbsp;&nbsp;&nbsp;&nbsp; **Pathway:** D (tự build sản phẩm)

---

### ① ĐỊNH HƯỚNG — Job/role hướng tới

| Job | Kỹ năng cần (từ JD thật + report) |
|---|---|
| AI Product Manager / AI PM | Problem framing, success metric, ROI, user research, spec writing, stakeholder alignment |
| AI Product Engineer | Đủ kỹ thuật để prototype, đủ product để định bài toán — T1 với coding ability |
| Founder / Builder tự build sản phẩm AI | End-to-end: ideation → spec → build (tự hoặc dẫn kỹ thuật) → pilot → đo adoption |

---

### ② ĐỐI CHIẾU BẢN THÂN — từ Phase 1

**Những việc đã làm được:**
- Phân tích AI feature của sản phẩm thật (Moni/MoMo): xác định failure mode đúng tầng (Intent + UX Recovery), đề xuất spec change có logic (D5)
- Build full RAG pipeline và multi-agent system (D8, D9) → hiểu bên trong AI hoạt động thế nào, không bị "hộp đen"
- Viết finding → product decision → requirement theo đúng luồng product (D5)
- Nhận ra "AI lý thuyết hóa thay vì thực thi hóa" — đây là product insight, không phải kỹ thuật

**Loại công việc cho năng lượng, muốn làm tiếp:**
Phân tích tại sao một AI feature fail, quyết định feature nào nên build tiếp và feature nào không nên build, định nghĩa "thành công" cho hệ thống AI trước khi implement

**Lợi thế so với T1 người không có kỹ thuật:**
Tự đọc được Langfuse trace để biết AI fail ở bước nào → ra quyết định product dựa trên data thật, không phải cảm tính. Tự prototype được để test giả thuyết sản phẩm nhanh hơn.

---

### ③ KỸ NĂNG ĐỊNH PHÁT TRIỂN

- **Ưu tiên 1:** Problem framing & success metric — định nghĩa bài toán AI rõ ràng trước khi build
- **Ưu tiên 2:** ROI & business case cho AI feature — biến kết quả kỹ thuật thành số business
- **Ưu tiên 3:** Thiết kế trust/UX cho sản phẩm AI — luồng xử lý khi AI sai, khi confidence thấp

**Gap lớn nhất + artifact sẽ build để thấy tiến bộ:**
Viết PRD đầy đủ cho AI Booking Assistant (đang có ở "Chon de tai"): problem statement rõ, need vs feature, success metric đo được, failure mode và recovery UX — rồi dùng nền kỹ thuật D8/D9 để tự prototype, đo kết quả thật.

---

### ④ QUYẾT ĐỊNH TRACK

**Track chọn: T1 — AI Product**

**Vì:** D5 cho thấy mình tự nhiên nghĩ theo hướng "feature này design sai ở tầng nào" và "spec mới cần gì" — không phải "implement thế nào". Đó là product mindset thật. Kỹ thuật D8/D9/D13 không mất đi — nó trở thành lợi thế cạnh tranh của một AI PM hiểu sâu hơn người khác. Thị trường đang thiếu người vừa đọc được code vừa ra được quyết định sản phẩm đúng.

**Track cân nhắc nhưng KHÔNG chọn: T3 — AI Engineering**

Lý lẽ mạnh nhất của T3: đã có artifact portfolio (D8, D9) và JD thị trường đang trả cao cho kỹ năng này. Nhưng nếu chỉ làm kỹ thuật, mình sẽ là một trong nhiều AI engineers — không phải vị trí mình muốn đứng. Nền kỹ thuật này sẽ được dùng tốt hơn khi phục vụ product decisions.

**Dấu hiệu sẽ khiến xem lại lựa chọn:**
Nếu sau 3 tháng thấy mình chỉ viết doc mà không hiểu bên dưới hệ thống đang làm gì — cần bổ sung kỹ thuật. Nếu vẫn cứ muốn tự code hơn là định bài toán → thì T3 đúng hơn.

---

### ⑤ ĐỊNH HƯỚNG & CHUẨN BỊ

**Định hướng tiếp theo:**
1. Viết PRD hoàn chỉnh cho AI Booking Assistant: problem statement, need vs feature, success metric, failure modes + recovery UX
2. Dùng nền kỹ thuật D8 (RAG) + D9 (agent) để tự prototype → đo pilot adoption thật
3. Học cách đọc số business từ kết quả kỹ thuật: convert eval score → user metric → ROI
4. Thực hành defend product decision trước phản biện kỹ thuật ("tại sao không làm X?" → phải trả lời được bằng data)

**Câu hỏi còn mở:**
- Success metric cho AI feature là gì khi output không deterministic?
- Khi nào nên build AI feature in-house vs dùng tool bên ngoài — quyết định product hay kỹ thuật?
- Làm sao đo "trust" của người dùng với AI trong sản phẩm?

---

*Memo hoàn thành: 18/06/2026*
