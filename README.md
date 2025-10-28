## About Project
To insert dummy data for each project's models, run these commands:
1. php artisan tinker
2. \App\Models\Contact::factory()->count(5)->create()
3. \App\Models\Blog::factory()->count(5)->create() 
4. \App\Models\Project::factory()->count(5)->create()

Once that's done, run this to start the website:

php artisan serve
