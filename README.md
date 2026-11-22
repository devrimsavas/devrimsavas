<div align="center">

<img src="Github-Banner-Devrim1.png" alt="Devrim Savas Yilmaz – Full-Stack Developer" width="100%"/>

I'm a full-stack developer based in Drammen, Norway, with a strong focus on back-end architecture, clean API design and running my own production infrastructure. Right now I'm building a suite of products for small Norwegian businesses, all based on open public data.

🌐 **Portfolio:** [devrimdev.no](https://www.devrimdev.no) · 💼 [LinkedIn](https://www.linkedin.com/in/devrimsavas/) · 📄 [CV](https://github.com/devrimsavas/CV-Resume)

</div>

---

## 🛠️ What I'm building

* 🛡️ **[Leverandørvakt](https://leverandorvakt.devrimdev.no)** ([code](https://github.com/devrimsavas/LEVERANDORVAKT)): live in production. An early-warning service that follows your suppliers and customers in the Brønnøysund registers and notifies you when something important changes, with explainable risk signals and an AI assistant. *Node.js, TypeScript, Express 5, PostgreSQL, Next.js, Designsystemet*
* 📅 **[Regelvakt](https://regelvakt.devrimdev.no)** ([code](https://github.com/devrimsavas/REGELVAKT)): live as a pilot. Enter an organization number, and a versioned rules engine shows which official obligations and deadlines apply to an ENK or AS, with calendar export, email reminders and an AI assistant that answers with numbered sources. About 370 unit and integration tests plus Playwright e2e tests with accessibility checks. *TypeScript, Express 5, PostgreSQL, Next.js, Designsystemet*
* 🚢 **Tollvakt** ([code](https://github.com/devrimsavas/TOLLVAKT)): in development. AI-assisted customs classification for Norwegian importers: describe a product in your own words and get the most likely customs codes with their reasoning, plus duty and VAT for the chosen origin country. A Python ETL pipeline loads 17 datasets from Tolletaten's open data, with full-text and semantic search (pgvector). *TypeScript, Express, PostgreSQL, pgvector, Python, Gemini, Ollama*

## ⚙️ Infrastructure

* 🐳 Everything runs in Docker Compose on my own VPS and a self-hosted Ubuntu home server, published through Cloudflare Tunnel with no open ports, with nightly database backups
* ✅ Automated tests and GitHub Actions CI on every project

---

## 🚀 More projects

| Project | Description | Tech |
|---|---|---|
| [**NorskHandverk**](https://github.com/devrimsavas/NorskHandverk) ([live](https://norsk-handverk.vercel.app)) | Full-stack e-commerce platform for Norwegian handcrafts with Stripe payments (idempotent checkout, webhooks), dynamic cart and relational data modeling | .NET 9, Next.js 16, PostgreSQL, Stripe |
| [**Aurora Trails**](https://github.com/devrimsavas/NorthernTourGuide) | Booking platform for Arctic adventure tours in Northern Norway. Overbooking-safe bookings with row-level locking, JWT auth with automatic token refresh, role-based customer and guide flows, live weather and aurora forecasts, and 43 automated tests in GitHub Actions | Django REST Framework, PostgreSQL, Angular, Tailwind |
| [**Order Store**](https://github.com/devrimsavas/mongorabbit) | Asynchronous order processing: orders are saved to MongoDB and published to RabbitMQ, where a background consumer reserves stock atomically, with a dead-letter queue for failed messages | ASP.NET Core 9, MongoDB, RabbitMQ, Angular |
| [**GraphQLBlogAPI**](https://github.com/devrimsavas/GraphQLBlogAPI) | GraphQL blog API with JWT authentication and resolver-level role-based authorization | ASP.NET Core, HotChocolate, GraphQL, EF Core |
| [**BIT4 – 4-bit CPU Emulator**](https://github.com/devrimsavas/CPU-4-BIT-EMULATOR) | Handcrafted 4-bit computer built from scratch: custom CPU, ALU, RAM, VPU, assembler and instruction set, without frameworks | C#, WinForms |
| [**DOSBox-X Toolkit**](https://github.com/devrimsavas/dos_box_utils) | Python toolset for live DOSBox-X processes: memory trainer, VGA and CGA video-memory viewers, and a snapshot diff tool for locating game addresses | Python, Tkinter |

---

## 🧰 Tech Stack

**Frontend**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/Django_REST-A30000?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=flat-square&logo=blazor&logoColor=white)

**Databases**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![MSSQL](https://img.shields.io/badge/MSSQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Cloud & DevOps**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

---

## 👋 About me

* 🧑‍🏫 Former instructor at JobLoop and mentor at Noroff, teaching C#, ASP.NET, Node.js and JavaScript
* 🌍 Fluent in 6 languages: English, Norwegian, Turkish, German, French, Russian

## 📬 Get in touch

I'm open to new opportunities and collaborations. Feel free to reach out!

- 📧 **devrimsavasyilmaz@gmail.com**
- 💼 [LinkedIn](https://www.linkedin.com/in/devrimsavas/)
- 📄 [CV / Resume](https://github.com/devrimsavas/CV-Resume)
