NeuroLink 知覺連線 - 特教資源媒合平台
Vue.js Spring Boot PostgreSQL Tailwind CSS

NeuroLink 是一個專為「特殊教育需求家長」與「特教專家」打造的雙邊媒合平台 (Two-sided Marketplace)。旨在透過資訊透明化與專業審核機制，讓資源精準連結，解決特教資源尋找不易的痛點。

✨ 核心功能 (Key Features)
🔐 角色化存取控制 (RBAC)：支援 PARENT (家長)、EXPERT (專家)、ADMIN (管理員) 三種身分，並透過 JWT 進行安全的狀態驗證。
🚀 漸進式註冊與審核機制 (Progressive Onboarding)：
雙分段註冊系統：使用 Email 驗證碼暫存表 (VerificationRecord) 保障主用戶表 (Users) 的資料完整性。
專家註冊後可預覽全站案件產生動機 (FOMO)，但須引導完善「專業履歷」並經後台審核 (Pending Approval) 後方可接案。
💎 點數經濟與解鎖系統：家長免費發布需求，專家透過消耗平台點數 (P幣) 解鎖家長的聯絡資訊。
🔎 全站模糊檢索 (Global Search)：後台支援跨欄位 (Email, 姓名, 標籤等) 的高效模糊搜尋機制。
🎨 現代化 UX/UI：基於 Tailwind CSS 打造高質感的響應式介面，包含專家履歷數位名片 (Modal) 與流暢的狀態引導。
🛠️ 技術堆疊 (Tech Stack)
Backend (後端)
Framework: Java, Spring Boot 3
Security: Spring Security, JWT (JSON Web Tokens)
Database: PostgreSQL, Spring Data JPA, Hibernate
Tools: Lombok, JavaMailSender
Frontend (前端)
Framework: Vue 3 (Composition API)
Router/State: Vue Router, Pinia
Styling: Tailwind CSS
HTTP Client: Axios

