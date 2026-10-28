# Laravel POS From Arrays to Eloquent

**Status: starter scaffold only.** This repository is not a runnable Laravel application and does not claim that TFA6 is complete.

TFA6 asks you to rebuild the TFA5 POS pages using a database, Laravel migrations, a seeder, and Eloquent models. This scaffold records that work and the required schema. The Laravel application and its features still need to be implemented.

## Assignment checklist

* \[x] Create the Laravel application and confirm it runs locally with Artisan.
* \[x] Restore the TFA5 landing, about, customer, and user pages and their navigation.
* \[x] Create the `customers` migration with `full\\\_name`, `email`, and `phone`.
* \[x] Create the `users` migration with a unique `username` and `full\\\_name`.
* \[x] Create `Customer` and `User` Eloquent models.
* \[x] Add a seeder with at least five sample customers and five sample users.
* \[x] Update `CustomerController` and `UserController` to query their Eloquent models.
* \[x] Confirm both Blade account views display the database records.
* \[x] Run the migrations and seeder, then verify all four pages.
* \[x] Include the migration and seeder files (or database export) in the repository.
* \[x] Deploy the application and add its live URL here.

**Hosted application:** Not deployed.

## Scaffold layout

* `routes/` — notes for the routes to retain from TFA5.
* `app/Models/` — notes for the `Customer` and `User` models.
* `app/Http/Controllers/` — notes for controller changes.
* `database/migrations/` — required table fields.
* `database/seeders/` — sample data requirements.
* `resources/views/` — requirements for displaying Eloquent records.

## Publish this scaffold to GitHub

Create an empty GitHub repository named `laravel-pos-eloquent-starter`. Do not initialize it with a README, `.gitignore`, or license. Then, from this folder, run:

```bash
git add .
git commit -m "Add TFA6 Eloquent scaffold"
git remote add origin https://github.com/IcenbergCryoN0x/laravel-pos-eloquent-starter.git
git push -u origin main
```

If you choose a different repository name or owner, replace the remote URL with the HTTPS URL shown by GitHub. Publishing this scaffold does not fulfill the working app or hosting requirements above.

