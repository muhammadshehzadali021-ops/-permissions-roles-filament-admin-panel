
# Permissions & Roles Filament Admin Panel

A Laravel Filament admin panel project focused on implementing **roles and permissions management** using Filament’s admin UI to control user access and authorization levels.

## 🚀 Features

- Role-based access control (RBAC)
- User role assignment
- Permissions management for Filament resources
- Clean and extendable admin UI
- Built for Laravel with Filament integration

## 🛠️ Tech Stack

- PHP (Laravel)
- Filament Admin Panel
- Spatie Permissions (or similar package)
- Blade & Livewire

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/muhammadshehzadali021-ops/-permissions-roles-filament-admin-panel.git
````

2. Navigate to the project directory:

   ```bash
   cd permissions-roles-filament-admin-panel
   ```
3. Install PHP dependencies:

   ```bash
   composer install
   ```
4. Copy the environment file:

   ```bash
   cp .env.example .env
   ```
5. Generate an app key:

   ```bash
   php artisan key:generate
   ```
6. Configure your database credentials in the `.env` file.
7. Run migrations:

   ```bash
   php artisan migrate
   ```
8. (Optional) Seed roles & permissions:

   ```bash
   php artisan db:seed
   ```

## 🚀 Usage

* Start the local server:

  ```bash
  php artisan serve
  ```
* Visit `http://localhost:8000/admin` to access the Filament admin panel.
* Manage users, roles, and permissions via the admin interface.

## 📂 Structure

```
app/
├── Filament/
├── Models/
├── Policies/
...
```

## 🤝 Contributing

Contributions are welcome!
Feel free to open issues or submit pull requests for enhancements.

## 📄 License

This project is licensed under the **MIT License**.

```

::contentReference[oaicite:0]{index=0}
```
