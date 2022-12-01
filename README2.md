php artisan make:model -mrc Chirp

This command will create three files for you:

app/Models/Chirp.php - The Eloquent model.

database/migrations/<timestamp>_create_chirps_table.php - The database migration that will create your database table.

app/Http/Controller/ChirpController.php - The HTTP controller that will take incoming requests and return responses.