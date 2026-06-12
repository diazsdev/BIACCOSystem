# 🎓 BIACCOSystem - Academic File Management

<div align="left">
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="Typescript"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="Javascript"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="Nodejs"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind"/>
  <img height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL"/>
</div>

## 📌 About the Project
**BIACCOSystem** is a platform developed to optimize study material sharing between professors and students in **AI** (Artificial Intelligence) and **CCO** (Computer Science) courses. It centralizes file uploads, organizes content by modules, and provides quick access to files.

### Prerequisites

- Node.js 18+
- MySQL 8.0+ (Local or Cloud)
- PNPM (Install via `npm i -g pnpm`)

---

## ⚙️ Database Configuration

### 1. Create the Schema (Requires a MySQL Database)

Run the SQL script (`schema.sql`) located in the scripts folder inside your MySQL instance to generate the table structure:

```sql
├── scripts/         # Automation scripts
│   ├── migrar.ts    # Database migration script
│   └── schema.sql   # SQL table definitions
