## Hi there 👋 I'm Ali

A software engineer who's been shipping production code for **20+ years** — most of it deep in the `.NET` ecosystem — and who still gets a genuine kick out of the moment a gnarly problem finally clicks into place.

These days I'm pouring two decades of C# muscle memory into a deliberate pivot toward **Go** and **AI-assisted engineering**. Turns out clean architecture, SOLID, and a healthy respect for the transaction boundary translate across languages just fine. 🙂

### 🛠️ My toolbox

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

### 🔭 What I'm building

I don't learn languages from tutorials — I learn them by building things that would actually break in production if I got them wrong:

- **An event-driven commerce backbone in Go** — a transactional outbox on PostgreSQL, SNS/SQS fan-out, and horizontally-scalable relay workers using locks and worker pools. At-least-once delivery, idempotent consumers, the whole dance.
- **[`gorm-kit`](https://github.com/akhakpouri/gorm-kit)** — a small, driver-agnostic Go module I extracted and published to tame database connection & migration boilerplate across services.
- **Infrastructure as code** — it all runs on AWS ECS Fargate, provisioned with Terraform and OIDC-secured CI/CD (no long-lived keys, thank you).

Every real decision gets an ADR. Yes, even on personal projects. Old habits. 📓

### 🌱 The Go rabbit holes I'm currently down

Coming from `async`/`await` in C#, I *thought* I understood concurrency — then I met **goroutines** and channels and realized how much ceremony I'd been quietly carrying around. Letting a worker pool coordinate over a channel, instead of babysitting `Task` continuations and worrying about which call secretly blocks, has been one of those "oh — *that's* how it should feel" moments.

Also, an opinion I'll happily defend: after years of `nuget`, Go's "the import path *is* the dependency" model feels refreshingly un-over-engineered. Fight me — politely, in an issue. 😄

### 📊 A little GitHub telemetry

<div align="center">

![Ali's GitHub stats](https://github-readme-stats.vercel.app/api?username=akhakpouri&show_icons=true&count_private=true&theme=tokyonight&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=akhakpouri&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=akhakpouri&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

</div>

### ☀️ Let's build something

If you've got a project in `go`, `.net`, `postgres`, or `aws` and could use a hand — or you just want to argue about package managers — don't hesitate to reach out.

### 📫 Where to find me

- 📧 [Email](mailto:ali.khakpouri@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/ali-khakpouri-4801558/)
- 🧠 [Stack Overflow](https://stackoverflow.com/users/1932324/ali-khakpouri)

⚡ **Fun fact:** I've been writing software for longer than Go has been a language — and I still learn something new just about every week. That's the whole point.
