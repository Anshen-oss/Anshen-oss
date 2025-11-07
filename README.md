# P Louisin

> Webmaster en Reconversion | Backend Developer in Training | Paris 🇫🇷

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/p-louisin/)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=flat&logo=twitter)](https://x.com/AnshenLouisin)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=flat&logo=gmail)](mailto:anshen99@gmail.com)

---

## 🎯 Profil de Reconversion

**Background :** Webmaster avec plusieurs années d'expérience en gestion de sites web et infrastructure

**Transition :** Reconversion vers le développement backend moderne (depuis 2024)

**Approche :** Apprentissage par projets concrets + collaboration IA (Claude) pour best practices

**Objectif :** Backend Developer spécialisé NestJS, GraphQL et architectures modernes

---

## 📊 Compétences Actuelles

| Technologie | Niveau | Projets |
|-------------|--------|---------|
| **NestJS** | ⭐⭐⭐⭐ | 3 projets |
| **TypeScript** | ⭐⭐⭐⭐ | Quotidien |
| **GraphQL** | ⭐⭐⭐⭐ | 2 projets |
| **MongoDB** | ⭐⭐⭐⭐ | 3 projets |
| **JWT/Passport** | ⭐⭐⭐⭐ | 2 projets |
| **Docker** | ⭐⭐⭐ | 1 projet |

<details>
<summary>📋 Voir le parcours détaillé des compétences</summary>

### Expérience Webmaster (Acquis)

| Domaine | Compétences | Niveau |
|---------|-------------|--------|
| **Administration Système** | Linux, Apache, Nginx | ⭐⭐⭐⭐⭐ |
| **CMS** | WordPress, Drupal | ⭐⭐⭐⭐⭐ |
| **Web Classique** | HTML, CSS, JavaScript | ⭐⭐⭐⭐ |
| **SEO** | Référencement, Analytics | ⭐⭐⭐⭐ |
| **Déploiement** | FTP, SSH, cPanel | ⭐⭐⭐⭐⭐ |

### Backend Moderne (En Apprentissage)

| Technologie | Usage | Niveau Actuel | Projets |
|-------------|-------|---------------|---------|
| **NestJS** | Framework principal | ⭐⭐⭐⭐ | 3 projets |
| **TypeScript** | Langage backend | ⭐⭐⭐⭐ | Quotidien |
| **MongoDB** | Base NoSQL | ⭐⭐⭐⭐ | 3 projets |
| **GraphQL** | API moderne | ⭐⭐⭐⭐ | 2 projets |
| **JWT/Passport** | Authentification | ⭐⭐⭐⭐ | 2 projets |
| **Docker** | Conteneurisation | ⭐⭐⭐ | 1 projet |
| **Jest** | Testing | ⭐⭐ | En cours |

### Compétences Transversales

| Compétence | Niveau | Notes |
|------------|--------|-------|
| **Git/GitHub** | ⭐⭐⭐⭐ | Workflows, branches, PR |
| **Documentation** | ⭐⭐⭐⭐⭐ | README, comments, guides |
| **Architecture** | ⭐⭐⭐⭐ | Patterns, SOLID, RBAC |
| **Problem Solving** | ⭐⭐⭐⭐ | Debug, recherche |
| **Auto-formation** | ⭐⭐⭐⭐⭐ | Docs, tutos, AI guidance |

</details>

---

## 💼 Projets Portfolio

### 🚀 NestJS GraphQL Auth Starter

**Repository :** [nestjs-graphql-auth-starter](https://github.com/Anshen-oss/nestjs-graphql-auth-starter)

**Projet complet combinant :** JWT Authentication + GraphQL API + Role-Based Access Control (RBAC)

**Stack :** NestJS • GraphQL • Apollo Server • MongoDB • Passport-JWT • Docker • TypeScript

**Highlights :**
- ✅ Système d'authentification complet (Register, Login, Protected Routes)
- ✅ Authorization à 3 niveaux (USER, MODERATOR, ADMIN)
- ✅ GraphQL Playground pour tests
- ✅ Docker Compose (MongoDB + Mongo Express)
- 📘 Documentation professionnelle complète (README, CONTRIBUTING, DEPLOYMENT)
- 🐳 Production-ready avec guides de déploiement

**Architecture :**
```
GraphQL Request + JWT Token
    ↓
GqlAuthGuard (Authentication)
    ↓
RolesGuard (Authorization)
    ↓
Resolver → Service → Repository → MongoDB
```

**Ce que j'ai appris :**
- Architecture backend complète avec authentification et autorisation
- Différence entre `@ObjectType()` et `@InputType()` en GraphQL
- Gestion sécurisée des secrets avec `ConfigService`
- Documentation technique professionnelle
- Debugging méthodique (résolution problème JWT configuration)

**Durée :** 3-4 semaines | **Statut :** ✅ Production-ready

<details>
<summary>🔐 Système d'Authentification JWT (Projet 2)</summary>

### Système d'Authentification JWT

**Repository :** [jwt-auth-with-mongo-db-nest-js](https://github.com/Anshen-oss/jwt-auth-with-mongo-db-nest-js)

**Contexte :** Premier projet backend sérieux pour comprendre l'authentification moderne

**Stack Technique :**
- **Backend :** NestJS ^11.0
- **Database :** MongoDB + Mongoose
- **Auth :** Passport + JWT + Bcrypt
- **Validation :** Class-validator, Class-transformer
- **Language :** TypeScript ^5.7

**Architecture Implémentée :**
```
Client Request
    ↓
Guards (JWT/Local)
    ↓
Strategy (Passport)
    ↓
Service (Business Logic)
    ↓
Repository (Mongoose)
    ↓
MongoDB
```

**Fonctionnalités Développées :**
- ✅ Inscription utilisateur avec hash bcrypt
- ✅ Connexion avec génération JWT
- ✅ Protection routes avec Guards
- ✅ Système de rôles (USER, ADMIN)
- ✅ Validation DTOs
- ✅ Gestion erreurs centralisée

**Compétences Acquises :**
- Architecture modulaire NestJS
- Patterns : Dependency Injection, Repository
- Sécurité : Hash, JWT, Guards
- TypeScript avancé (decorators, generics)

**Durée :** 2-3 semaines | **Statut :** ✅ Fonctionnel & documenté

</details>

<details>
<summary>📚 API GraphQL Books Management (Projet 3)</summary>

### API GraphQL Books Management

**Repository :** [Nestjs-graphql-mongodb](https://github.com/Anshen-oss/Nestjs-graphql-mongodb)

**Contexte :** Exploration de GraphQL comme alternative à REST

**Stack Technique :**
- **Backend :** NestJS ^11.0
- **API :** GraphQL ^16.12, Apollo Server ^4.0
- **Database :** MongoDB ^8.19 + Mongoose
- **Language :** TypeScript ^5.7
- **Validation :** Class-validator

**Architecture Implémentée :**
```
GraphQL Request
    ↓
Resolver (Controller)
    ↓
Service (Business Logic)
    ↓
Mongoose Model
    ↓
MongoDB
```

**API Design :**
```graphql
# Queries
getAllBooks: [Book!]!
getBook(id: String!): Book!

# Mutations
createBook(input: CreateBookInput!): Book!
updateBook(input: UpdateBookInput!): Book!
deleteBook(id: String!): Boolean!
```

**Fonctionnalités Développées :**
- ✅ CRUD complet (Queries & Mutations)
- ✅ Code-first approach (auto schema generation)
- ✅ GraphQL Playground intégré
- ✅ DTOs avec validation
- ✅ Error handling
- ✅ Documentation complète

**Compétences Acquises :**
- Différences GraphQL vs REST
- Resolvers et Field Resolvers
- Apollo Server configuration
- Schema-first vs Code-first
- Optimisation requêtes

**Durée :** 1-2 semaines | **Statut :** ✅ Fonctionnel avec playground

</details>

---

## 📈 Métriques de Progression

| Métrique | Valeur |
|----------|--------|
| **Projets complétés** | 3 (JWT Auth + GraphQL API + Auth Starter) |
| **Lignes de code** | ~10 000+ lignes TypeScript/NestJS |
| **Technologies maîtrisées** | 8 (NestJS, TS, MongoDB, GraphQL, JWT, Git, Docker, RBAC) |
| **Documentation** | 100% - Tous projets documentés |
| **Heures d'apprentissage** | 300+ heures (tutos, docs, pratique) |

<details>
<summary>📅 Voir la timeline complète de reconversion</summary>

### Timeline de Reconversion

```
2024 Q4 - FONDATIONS ✅
├─ Apprentissage NestJS basics
├─ Projet JWT Authentication
├─ Projet GraphQL Books API
└─ Maîtrise TypeScript

2024-2025 Q1 - APPROFONDISSEMENT ✅
├─ Projet Auth Starter complet (JWT + GraphQL + RBAC)
├─ Documentation professionnelle
├─ Docker & DevOps basics
└─ Architecture production-ready

2025 Q2 - PROFESSIONNALISATION 🔄
├─ Relations & DataLoader (GraphQL)
├─ Pagination & filtres avancés
├─ Tests (Jest, e2e)
├─ 2-3 projets portfolio additionnels
└─ Contributions open-source

2025 Q3+ - OBJECTIF 🎯
└─ Backend Developer @ Tech Company
```

</details>

<details>
<summary>🎓 Ma méthodologie d'apprentissage</summary>

### Approche Structurée

```typescript
class LearningMethod {
  private resources = [
    "Documentation officielle (priorité)",
    "YouTube tutorials (anglais)",
    "Projets concrets guidés",
    "Claude AI pour best practices",
    "Communauté (Stack Overflow, Discord)"
  ];

  async learn(technology: string): Promise<Skill> {
    // 1. Comprendre les concepts
    await this.readDocumentation(technology);
    
    // 2. Suivre un tutoriel pratique
    await this.watchTutorial(technology);
    
    // 3. Construire un projet
    const project = await this.buildProject(technology);
    
    // 4. Valider avec AI mentor
    await this.validateWithClaude(project);
    
    // 5. Documenter et partager
    await this.documentAndShare(project);
    
    return new Skill(technology, "learned");
  }
}
```

### Sources d'Apprentissage

- 📖 **Documentation officielle** : NestJS docs, GraphQL.org
- 🎥 **YouTube** : Tutoriels techniques en anglais
- 🤖 **Claude AI** : Guidance, code reviews, best practices
- 💻 **Practice** : Projets concrets, pas que théorie
- 🌐 **Communauté** : GitHub, Stack Overflow

</details>

---

## 🎯 Objectifs de Reconversion

### Court Terme (3-6 mois)

- [x] Maîtriser authentification JWT + GraphQL + RBAC
- [x] Créer un projet production-ready avec docs complètes
- [ ] Implémenter tests (Jest) sur auth-starter
- [ ] Maîtriser relations GraphQL avec DataLoader
- [ ] Contribuer à l'open-source

### Moyen Terme (6-12 mois)

- [ ] Apprendre microservices architecture
- [ ] Explorer cloud platforms (AWS/GCP)
- [ ] Maîtriser CI/CD
- [ ] **Objectif principal :** Premier poste Backend Developer

<details>
<summary>📋 Voir tous les objectifs long terme</summary>

### Long Terme (1-2 ans)

- [ ] Backend Developer confirmé
- [ ] Contribuer à projets open-source majeurs
- [ ] Partager connaissances (blog, tutoriels)
- [ ] Continuer veille technologique

</details>

---

## 💪 Ce Qui Me Différencie

| Atout | Détail |
|-------|--------|
| **🎯 Expérience Terrain** | Années en tant que Webmaster |
| **📚 Apprenant Structuré** | Méthodologie claire, projets concrets |
| **💡 Motivation Prouvée** | Reconversion assumée avec résultats tangibles |
| **📖 Documentation** | Code propre, README complets, guides professionnels |
| **🤖 AI-Assisted Learning** | Utilisation Claude pour best practices |
| **🏗️ Production-Ready** | Projets avec Docker, tests, déploiement |
| **🌱 Growth Mindset** | Humble mais déterminé |

### Proposition de Valeur

```typescript
interface MyValue {
  experience: "Webmaster confirmé qui comprend le cycle projet complet";
  technical: "Maîtrise stack moderne (NestJS, GraphQL, MongoDB, RBAC)";
  learning: "Apprentissage rapide et structuré avec projets à l'appui";
  mindset: "Junior en backend mais pas débutant en tech";
  motivation: "Reconversion choisie avec investissement massif";
  quality: "Documentation professionnelle et bonnes pratiques";
}
```

---

## 🌍 Langues & Communication

| Langue | Niveau | Usage Technique |
|--------|--------|-----------------|
| **Français** 🇫🇷 | Natif | Communication, docs |
| **Créole** 🇭🇹 | Natif | - |
| **Anglais** 🇬🇧 | Intermédiaire+ | Lecture docs, vidéos |

**Note :** Consommation quotidienne de contenu technique en anglais

---

## 📊 Activité GitHub

<div align="center">

![Anshen's GitHub stats](https://github-readme-stats.vercel.app/api?username=Anshen-oss&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Anshen-oss&layout=compact&theme=github_dark&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Anshen-oss&theme=github-dark-blue&hide_border=true)

</div>

<details>
<summary>🎵 Équilibre Vie/Code</summary>

```javascript
const workLifeBalance = {
  coding: {
    focus: "Backend development",
    tools: ["NestJS", "GraphQL", "MongoDB"],
    hours: "Quotidien, avec discipline"
  },
  music: {
    instrument: "Tambours 🥁",
    styles: ["Nayabingi", "6/8"],
    benefit: "Rythme et discipline"
  },
  wellness: {
    practice: "Yoga 🧘‍♂️",
    benefit: "Focus mental pour debug"
  },
  learning: {
    source: "YouTube Tech 📺",
    language: "Anglais technique",
    frequency: "Quotidien"
  }
};
```

</details>

---

## 📫 Contact & Opportunités

**Intéressé par mon profil de reconversion ?**

Je suis **activement à l'écoute d'opportunités** en tant que :
- Backend Developer Junior
- Développeur NestJS/Node.js
- Projets freelance backend

**Mes critères :**
- Équipe tech bienveillante et pédagogue
- Stack moderne (NestJS, GraphQL, TypeScript)
- Possibilité de continuer à apprendre
- Projets challengeants

| Canal | Lien | Usage |
|-------|------|-------|
| **LinkedIn** | [p-louisin](https://www.linkedin.com/in/p-louisin/) | Networking professionnel |
| **Twitter** | [@AnshenLouisin](https://x.com/AnshenLouisin) | Veille tech & partage |
| **Email** | [anshen99@gmail.com](mailto:anshen99@gmail.com) | Contact direct |

---

<div align="center">

**"The expert in anything was once a beginner."**

*— Helen Hayes*

---

![Profile Views](https://komarev.com/ghpvc/?username=Anshen-oss&style=flat&color=blue)

**⭐ Webmaster → Backend Dev | En reconversion depuis 2024**

*Code avec passion, apprend avec humilité*

</div>
