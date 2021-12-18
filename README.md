# What does Laravel Quick CRUD do?
Like a name suggests, it is way to make less steps when creating CRUD within any Laravel project. It's basic functionality is generating, based on properly prepared JSON file:
a) migration file
b) Eloquent model file
c) Controller file with standard CRUD methods:
- GET index() for showing a list
- GET create() for showing new entry form
- POST store() for saving data to database
- GET show($id) for showing single entry
- GET edit($id) for showing form to editing the entry
- PUT update($id) for saving changes in database
- DELETE destroy($id) for removing entry from database
d) Proper entry (Route::resource()) in app/routes.php
e) Adequate views for index(), create(), show() and edit() methods of controller (AdminLTE or Twitter Bootstrap powered)
f) OPTIONALY: Adequate positions in AdminLTE menu (using jeroennoten/Laravel-AdminLTE)
