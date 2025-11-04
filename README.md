# P. Louisin

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

## 📊 Parcours de Compétences

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
| **NestJS** | Framework principal | ⭐⭐⭐⭐ | 2 projets |
| **TypeScript** | Langage backend | ⭐⭐⭐⭐ | Quotidien |
| **MongoDB** | Base NoSQL | ⭐⭐⭐⭐ | 2 projets |
| **GraphQL** | API moderne | ⭐⭐⭐ | 1 projet |
| **JWT/Passport** | Authentification | ⭐⭐⭐⭐ | 1 projet |
| **Docker** | Conteneurisation | ⭐⭐⭐ | Apprentissage |
| **Jest** | Testing | ⭐⭐ | En cours |

### Compétences Transversales

| Compétence | Niveau | Notes |
|------------|--------|-------|
| **Git/GitHub** | ⭐⭐⭐⭐ | Workflows, branches, PR |
| **Documentation** | ⭐⭐⭐⭐⭐ | README, comments, guides |
| **Architecture** | ⭐⭐⭐ | Patterns, SOLID (en cours) |
| **Problem Solving** | ⭐⭐⭐⭐ | Debug, recherche |
| **Auto-formation** | ⭐⭐⭐⭐⭐ | Docs, tutos, AI guidance |

---

## 💼 Projets de Reconversion

### 🔐 Système d'Authentification JWT

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

---

### 📚 API GraphQL Books Management

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

---

## 📈 Progression Technique

### Timeline de Reconversion

```
2024 Q4 - FONDATIONS ✅
├─ Apprentissage NestJS basics
├─ Projet JWT Authentication
├─ Projet GraphQL Books API
└─ Maîtrise TypeScript

2024-2025 Q1 - APPROFONDISSEMENT 🔄
├─ Relations & DataLoader (GraphQL)
├─ Pagination & filtres avancés
├─ Tests (Jest, e2e)
└─ 2-3 projets portfolio

2025 Q2 - PROFESSIONNALISATION 📝
├─ Microservices architecture
├─ Cloud deployment (AWS/GCP)
├─ CI/CD pipelines
└─ Recherche premier poste

2025 Q3+ - OBJECTIF 🎯
└─ Backend Developer @ Tech Company
```

### Métriques d'Apprentissage

| Métrique | Valeur | Notes |
|----------|--------|-------|
| **Projets complétés** | 2 | JWT Auth + GraphQL API |
| **Lignes de code** | ~5000+ | TypeScript/NestJS |
| **Technologies maîtrisées** | 6 | NestJS, TS, MongoDB, GraphQL, JWT, Git |
| **Documentation créée** | 100% | Tous projets documentés |
| **Heures d'apprentissage** | 200+ | Tutos, docs, pratique |
| **Collaboration AI** | Quotidienne | Claude pour guidance |

---

## 🎓 Méthodologie d'Apprentissage

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

---

## 🌍 Langues & Communication

| Langue | Niveau | Usage Technique |
|--------|--------|-----------------|
| **Français** 🇫🇷 | Natif | Communication, docs |
| **Créole** 🇭🇹 | Natif | - |
| **Anglais** 🇬🇧 | Intermédiaire+ | Lecture docs, vidéos |

**Note :** Consommation quotidienne de contenu technique en anglais (documentation, tutoriels YouTube, articles). Bonne compréhension écrite et orale.

---

## 🎯 Objectifs de Reconversion

### Court Terme (3-6 mois)

- [ ] Maîtriser relations GraphQL avec DataLoader
- [ ] Implémenter pagination et filtres avancés
- [ ] Créer 3-4 projets portfolio solides
- [ ] Contribuer à l'open-source
- [ ] Améliorer couverture tests

### Moyen Terme (6-12 mois)

- [ ] Apprendre microservices architecture
- [ ] Explorer cloud platforms (AWS/GCP)
- [ ] Maîtriser Docker & CI/CD
- [ ] **Objectif principal :** Premier poste Backend Developer

### Long Terme (1-2 ans)

- [ ] Backend Developer confirmé
- [ ] Contribuer à projets open-source majeurs
- [ ] Partager connaissances (blog, tutoriels)
- [ ] Continuer veille technologique

---

## 💪 Atouts de Reconversion

### Ce Qui Me Différencie

| Atout | Détail |
|-------|--------|
| **🎯 Expérience Terrain** | Années en tant que Webmaster |
| **📚 Apprenant Structuré** | Méthodologie claire, projets concrets |
| **💡 Motivation Prouvée** | Reconversion assumée avec résultats |
| **📖 Documentation** | Code propre, README complets |
| **🤖 AI-Assisted Learning** | Utilisation Claude pour best practices |
| **🌱 Growth Mindset** | Humble mais déterminé |

### Proposition de Valeur

```typescript
interface MyValue {
  experience: "Webmaster confirmé qui comprend le cycle projet complet";
  technical: "Maîtrise progressive stack moderne (NestJS, GraphQL, MongoDB)";
  learning: "Apprentissage rapide et structuré avec projets à l'appui";
  mindset: "Junior en backend mais pas débutant en tech";
  motivation: "Reconversion choisie avec investissement temps/énergie massif";
}
```

---

## 📊 Activité GitHub

<div align="center">

![Anshen's GitHub stats](https://github-readme-stats.vercel.app/api?username=Anshen-oss&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Anshen-oss&layout=compact&theme=github_dark&hide_border=true&langs_count=8)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Anshen-oss&theme=github-dark-blue&hide_border=true)

</div>

---

## 🎵 Équilibre Vie/Code

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

---

## 📫 Contact & Opportunités

**Intéressé par mon profil de reconversion ?**

Je suis **activement à l'écoute d'opportunités** en tant que :
- Backend Developer Junior
- Développeur NestJS/Node.js
- Alternance/Stage Backend
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
