# Anshen Louisin

> Full Stack Developer | Backend Specialist | Paris 🇫🇷

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/p-louisin/)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=flat&logo=twitter)](https://x.com/AnshenLouisin)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=flat&logo=gmail)](mailto:anshen99@gmail.com)

---

## 🎯 Technical Profile

**Spécialisation :** Développement backend avec architectures scalables et APIs performantes

**Expertise principale :**
- Architecture backend moderne avec **NestJS**
- APIs **GraphQL** & **REST**
- Bases de données **MongoDB** & **PostgreSQL**
- Authentification & sécurité (**JWT**, **Passport**)
- Conteneurisation avec **Docker**

**Philosophie :** Clean Code, SOLID principles, Test-Driven Development

---

## 🏗️ Architecture & Stack Technique

### Backend Development

| Catégorie | Technologies | Niveau |
|-----------|--------------|--------|
| **Framework** | NestJS, Express | ⭐⭐⭐⭐⭐ |
| **Runtime** | Node.js | ⭐⭐⭐⭐⭐ |
| **API Design** | GraphQL, REST | ⭐⭐⭐⭐⭐ |
| **Auth** | JWT, Passport, OAuth | ⭐⭐⭐⭐ |
| **Validation** | Class-validator, Joi | ⭐⭐⭐⭐⭐ |

### Database & ORM

| Type | Technologies | Niveau |
|------|--------------|--------|
| **NoSQL** | MongoDB | ⭐⭐⭐⭐⭐ |
| **SQL** | PostgreSQL, MySQL | ⭐⭐⭐⭐ |
| **ODM/ORM** | Mongoose, TypeORM, Prisma | ⭐⭐⭐⭐ |
| **Caching** | Redis | ⭐⭐⭐ |

### Frontend Development

| Catégorie | Technologies | Niveau |
|-----------|--------------|--------|
| **Framework** | Next.js, React | ⭐⭐⭐⭐ |
| **Styling** | Tailwind CSS, CSS3 | ⭐⭐⭐⭐ |
| **State** | React Query, Context API | ⭐⭐⭐⭐ |

### DevOps & Tools

| Catégorie | Technologies | Niveau |
|-----------|--------------|--------|
| **Conteneurs** | Docker, Docker Compose | ⭐⭐⭐⭐ |
| **CI/CD** | GitHub Actions | ⭐⭐⭐ |
| **Version Control** | Git, GitHub | ⭐⭐⭐⭐⭐ |
| **API Testing** | Postman, Insomnia | ⭐⭐⭐⭐⭐ |

### Languages

| Language | Usage | Niveau |
|----------|-------|--------|
| **TypeScript** | Principal | ⭐⭐⭐⭐⭐ |
| **JavaScript** | Quotidien | ⭐⭐⭐⭐⭐ |
| **SQL** | Requêtes DB | ⭐⭐⭐⭐ |

---

## 💼 Featured Projects

### 🔐 [JWT Authentication System](https://github.com/Anshen-oss/jwt-auth-with-mongo-db-nest-js)

**Description :** Système d'authentification complet utilisant JSON Web Tokens (JWT), NestJS et MongoDB

**Architecture :**
```
Client → Guard → Strategy → Service → Repository → Database
```

**Stack Technique :**
- **Backend:** NestJS ^11.0
- **Database:** MongoDB + Mongoose
- **Auth:** Passport + JWT
- **Security:** Bcrypt, Class-validator
- **Patterns:** Repository, Dependency Injection

**Fonctionnalités :**
- ✅ Inscription & connexion sécurisées
- ✅ Gestion des tokens JWT
- ✅ Guards personnalisés
- ✅ Système de rôles
- ✅ Validation des données
- ✅ Hash des mots de passe

**Métriques :**
- Tests unitaires : Coverage TBD
- Performance : < 100ms response time
- Security : JWT + Bcrypt

---

### 📚 [GraphQL Books API](https://github.com/Anshen-oss/Nestjs-graphql-mongodb)

**Description :** API GraphQL moderne pour la gestion d'une collection de livres

**Architecture :**
```
GraphQL Request → Resolver → Service → Model → MongoDB
```

**Stack Technique :**
- **Backend:** NestJS ^11.0
- **API:** GraphQL ^16.12, Apollo Server ^4.0
- **Database:** MongoDB ^8.19 + Mongoose
- **Language:** TypeScript ^5.7
- **Validation:** Class-validator ^0.14

**Fonctionnalités :**
- ✅ CRUD complet (Queries & Mutations)
- ✅ Code-first approach
- ✅ GraphQL Playground intégré
- ✅ Validation automatique
- ✅ Architecture modulaire
- ✅ DTOs typés

**Avantages GraphQL :**
- Pas d'over-fetching
- Un seul endpoint
- Typage fort
- Documentation auto-générée

**Schéma :**
```graphql
type Book {
  _id: ID!
  title: String!
  description: String!
  author: String!
}

type Query {
  getAllBooks: [Book!]!
  getBook(id: String!): Book!
}

type Mutation {
  createBook(input: CreateBookInput!): Book!
  updateBook(input: UpdateBookInput!): Book!
  deleteBook(id: String!): Boolean!
}
```

---

## 📊 GitHub Statistics

<div align="center">

![Anshen's GitHub stats](https://github-readme-stats.vercel.app/api?username=Anshen-oss&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Anshen-oss&layout=compact&theme=github_dark&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Anshen-oss&theme=github-dark-blue&hide_border=true)

</div>

---

## 🎓 Compétences Techniques

### Paradigmes & Patterns

```typescript
const technicalSkills = {
  paradigms: [
    'Object-Oriented Programming (OOP)',
    'Functional Programming',
    'Reactive Programming'
  ],
  patterns: [
    'Repository Pattern',
    'Dependency Injection',
    'Factory Pattern',
    'Singleton Pattern',
    'Observer Pattern'
  ],
  principles: [
    'SOLID',
    'DRY (Don\'t Repeat Yourself)',
    'KISS (Keep It Simple, Stupid)',
    'YAGNI (You Aren\'t Gonna Need It)',
    'Clean Code'
  ],
  architecture: [
    'Monolithic',
    'Microservices (learning)',
    'RESTful',
    'GraphQL'
  ]
};
```

### Best Practices

- ✅ **Code Quality:** ESLint, Prettier, Husky
- ✅ **Testing:** Jest, Supertest (unit, integration, e2e)
- ✅ **Documentation:** JSDoc, README, API docs
- ✅ **Security:** Input validation, JWT, environment variables
- ✅ **Performance:** Caching, database indexing, query optimization
- ✅ **Git:** Conventional commits, feature branches, PR reviews

---

## 🔬 En Cours d'Apprentissage

### 2024-2025 Learning Path

```mermaid
graph LR
    A[Current] --> B[Microservices]
    B --> C[Cloud Platforms]
    C --> D[Kubernetes]
    D --> E[Advanced DevOps]
    
    style A fill:#00ff00
    style B fill:#ffff00
    style C fill:#ff9900
    style D fill:#ff0000
    style E fill:#cc0000
```

| Technologie | Statut | Progrès |
|-------------|--------|---------|
| Microservices Architecture | 🟡 En cours | ████░░░░░░ 40% |
| AWS / GCP | 🔴 Prévu | ██░░░░░░░░ 20% |
| Kubernetes | 🔴 Prévu | █░░░░░░░░░ 10% |
| Event-Driven Architecture | 🟡 En cours | ███░░░░░░░ 30% |
| Message Queues (RabbitMQ) | 🔴 Prévu | ░░░░░░░░░░ 0% |

---

## 🌍 Langues & Communication

| Langue | Niveau | Usage |
|--------|--------|-------|
| **Français** 🇫🇷 | Natif | Quotidien |
| **Créole** 🇭🇹 | Natif | Quotidien |
| **Anglais** 🇬🇧 | Intermédiaire+ | Technique (lecture/écoute) |

**Note :** Consommation quotidienne de contenu technique en anglais (YouTube, documentation, articles)

---

## 🎯 Intérêts & Veille Technologique

### Domaines de veille active

- **Backend Development:** NestJS, Node.js patterns, API design
- **GraphQL:** Optimisations, DataLoader, subscriptions
- **Architecture:** Clean Architecture, DDD, microservices
- **DevOps:** Docker, CI/CD, cloud platforms
- **Best Practices:** Clean Code, design patterns, testing

### Sources d'apprentissage

- 📺 YouTube (contenu technique anglophone)
- 📚 Documentation officielle
- 💻 Projets personnels & open-source
- 🎓 Tutoriels & cours en ligne

---

## 🎵 Au-delà du code

```javascript
const personalLife = {
  music: {
    instrument: "Tambours 🥁",
    styles: ["Nayabingi", "6/8"],
    philosophy: "Le rythme comme expression de l'âme"
  },
  wellness: {
    practice: "Yoga 🧘‍♂️",
    benefits: ["Focus mental", "Équilibre", "Discipline"]
  },
  learning: {
    method: "Immersion continue",
    sources: ["YouTube Tech", "Docs", "Practice"],
    mindset: "Growth mindset"
  }
};
```

---

## 📫 Contact Professionnel

**Disponible pour :**
- Opportunités de collaboration
- Projets open-source
- Discussions techniques
- Mentorat junior developers

**Moyens de contact :**

| Canal | Lien | Usage |
|-------|------|-------|
| **LinkedIn** | [p-louisin](https://www.linkedin.com/in/p-louisin/) | Networking professionnel |
| **Twitter** | [@AnshenLouisin](https://x.com/AnshenLouisin) | Veille tech & partage |
| **Email** | [anshen99@gmail.com](mailto:anshen99@gmail.com) | Contact direct |

---

## 📈 Roadmap 2024-2025

### Q4 2024
- [x] Authentification JWT complète
- [x] API GraphQL avec NestJS
- [ ] Guides & Documentation projets
- [ ] Blog personnel (en cours)

### Q1 2025
- [ ] Projet avec relations & DataLoader
- [ ] Pagination & filtres avancés
- [ ] Système de rôles avancé
- [ ] Tests e2e complets

### Q2 2025
- [ ] Microservices architecture
- [ ] Event-driven patterns
- [ ] Cloud deployment (AWS/GCP)
- [ ] Open-source contributions

---

<div align="center">

**"Any fool can write code that a computer can understand. Good programmers write code that humans can understand."**

*— Martin Fowler*

---

![Profile Views](https://komarev.com/ghpvc/?username=Anshen-oss&style=flat&color=blue)

⭐ **From [Anshen-oss](https://github.com/Anshen-oss)**

</div>
