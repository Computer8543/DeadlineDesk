# 📰 DeadlineDesk

**DeadlineDesk** is an open-source editorial planning system for newsrooms, publishing teams, and content creators.  
It helps you **plan issues, assign stories, manage contributors, and track deadlines** from pitch to publication — all in one place.

Built with **Laravel**, **PHP**, and **MySQL**, DeadlineDesk is designed with:
- A **copyleft core** to encourage improvements flowing back to the community
- A clean **API** for in-house extensions and proprietary workflow tools
- Scalability to support everything from student publications to enterprise media outlets

---

## ✨ Features

- **Multi-Issue Management**  
  Plan and track multiple upcoming issues at once.

- **Story Assignment & Status Tracking**  
  Assign stories to contributors, track drafts, edits, and approvals.

- **Deadline Tracking & Alerts**  
  Receive customizable reminders for story, photography, and layout deadlines.

- **Contributor Management**  
  Maintain contact info, roles, and workload visibility.

- **Role-Based Permissions**  
  Different views and capabilities for writers, editors, photographers, and admins.

- **API for Workflow Extensions**  
  Build proprietary, in-house tools that integrate without modifying the open core.

---

## 📦 Tech Stack

- **Backend:** [Laravel](https://laravel.com/) (PHP framework)
- **Database:** MySQL (or MariaDB)
- **Frontend:** Laravel Blade templates (Vue.js optional)
- **Auth:** Laravel Breeze or Laravel Jetstream
- **Containerization:** Docker (optional, recommended for dev/prod parity)

---

## 🚀 Installation

### Prerequisites
- PHP >= 8.2
- Composer
- MySQL (or MariaDB)
- Node.js & npm (for frontend assets)
- Git

### Setup Steps
```bash
# 1. Clone the repository
git clone https://github.com/YOUR-ORG/DeadlineDesk.git
cd DeadlineDesk

# 2. Install dependencies
composer install
npm install && npm run build

# 3. Copy and configure environment file
cp .env.example .env
php artisan key:generate

# 4. Set up the database
php artisan migrate --seed

# 5. Start the development server
php artisan serve
