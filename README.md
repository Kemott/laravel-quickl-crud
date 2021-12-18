# What does Laravel Quick CRUD do?
Like a name suggests, it is way to make less steps when creating CRUD within any Laravel project. It's basic functionality is generating, based on properly prepared JSON file:
1. migration file
2. Eloquent model file
3. Controller file with standard CRUD methods:
   - GET index() for showing a list
   - GET create() for showing new entry form
   - POST store() for saving data to database
   - GET show($id) for showing single entry
   - GET edit($id) for showing form to editing the entry
   - PUT update($id) for saving changes in database
   - DELETE destroy($id) for removing entry from database
4. Proper entry ( ```Route::resource()```) in app/routes.php
5. Adequate views for index(), create(), show() and edit() methods of controller (AdminLTE or Twitter Bootstrap powered)
6. OPTIONALY: Adequate positions in AdminLTE menu (using jeroennoten/Laravel-AdminLTE)

Next I want to add that JSON file generator, based on asked questions.

# Why is Laravel Quick CRUD usefull?
If you creating project in Laravel, especially if you need to setup one from scratch, you must know how long it take to prepare basic functionality. With Laravel Quick CRUD you can make that part much quicker, and focus on more advanced elements. For some projects it can almost make you ready for work application. All of that in about 5 minutes if you already know how your database entities should work.

# How to get started?

