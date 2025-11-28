# **Project Roadmap (MVP)**

Repository: **[https://github.com/faizm10/coco-faiz](https://github.com/faizm10/coco-faiz)**

This roadmap lists all tasks in the order they should be completed to build a polished MVP.

---

# **🔥 Phase 1 — Foundation Setup**

### **Core Setup**

* [Infra: Add .gitignore and clean project structure](https://github.com/faizm10/coco-faiz/issues/24)
* [Setup: docker-compose for frontend](https://github.com/faizm10/coco-faiz/issues/14)

### **Backend Initialization**

* [Setup: /backend (GraphQL API)](https://github.com/faizm10/coco-faiz/issues/11)
* [Setup: /database (Supabase schema)](https://github.com/faizm10/coco-faiz/issues/12)
* [Setup: /llm (LLM module)](https://github.com/faizm10/coco-faiz/issues/13)

### **Frontend Initialization**

* Initialize Next.js app (DONE)
* [Quality: ESLint + Prettier setup](https://github.com/faizm10/coco-faiz/issues/17)

---

# **🔥 Phase 2 — Theme & Design System**

### **Design Foundation**

* [Design: Choose font & typography scale](https://github.com/faizm10/coco-faiz/issues/16)
* [Design: Choose color scheme](https://github.com/faizm10/coco-faiz/issues/15)
* [Design: Basic theme system (colors + typography)](https://github.com/faizm10/coco-faiz/issues/31)

### **Code Quality**

* [Quality: Backend linting & formatting](https://github.com/faizm10/coco-faiz/issues/18)

---

# **🔥 Phase 3 — Authentication (Supabase)**

### **Auth Setup**

* [Page: /login](https://github.com/faizm10/coco-faiz/issues/2)
* [Page: /signup](https://github.com/faizm10/coco-faiz/issues/3)
* [Integration: Supabase client setup (frontend)](https://github.com/faizm10/coco-faiz/issues/20)

### **Database**

* Complete Users table
* Connect Supabase → backend → frontend

---

# **🔥 Phase 4 — GraphQL Core**

### **Schema + API**

* Define GraphQL types: User, Entry, Concept
* Add queries + mutations for MVP
* [Integration: GraphQL schema documentation](https://github.com/faizm10/coco-faiz/issues/21)

### **Testing Foundation**

* [Quality: Basic unit tests skeleton](https://github.com/faizm10/coco-faiz/issues/19)

---

# **🔥 Phase 5 — Journal System**

### **Frontend Pages**

* [Page: /journal (list view)](https://github.com/faizm10/coco-faiz/issues/5)
* [Page: /journal/[id] (entry detail)](https://github.com/faizm10/coco-faiz/issues/6)

### **Backend Logic**

* Create Entry
* Get Entry
* List Entries

---

# **🔥 Phase 6 — Concepts System**

### **Frontend Pages**

* [Page: /concepts](https://github.com/faizm10/coco-faiz/issues/8)
* [Page: /concepts/[id]](https://github.com/faizm10/coco-faiz/issues/9)

### **LLM + DB**

* Add Concepts table
* Add LLM extraction
* Link concepts ↔ entries in GraphQL

---

# **🔥 Phase 7 — Ask (AI Querying)**

### **Frontend**

* [Page: /ask](https://github.com/faizm10/coco-faiz/issues/7)

### **Backend**

* Add search (keyword first, vector later)
* Add answerQuestion LLM pipeline
* Return relevant entries + answer

---

# **🔥 Phase 8 — Landing Page & Marketing**

### **Landing Components**

* [Hero section](https://github.com/faizm10/coco-faiz/issues/25)
* [Short feature highlights](https://github.com/faizm10/coco-faiz/issues/26)
* [Minimal screenshot or mockup](https://github.com/faizm10/coco-faiz/issues/27)
* [Clear call-to-action](https://github.com/faizm10/coco-faiz/issues/28)
* [Footer](https://github.com/faizm10/coco-faiz/issues/29)

### **Documentation**

* [Docs: Project architecture overview](https://github.com/faizm10/coco-faiz/issues/22)

---

# **🔥 Phase 9 — Onboarding + Polish**

### **UX**

* [UX: User onboarding + empty states](https://github.com/faizm10/coco-faiz/issues/30)

### **Settings**

* [Page: /settings](https://github.com/faizm10/coco-faiz/issues/10)

### **Final Polish**

* Improve UI consistency
* Add missing loading states
* Add minimal error handling
* Review responsive design
