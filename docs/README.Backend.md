# Information
This repo contains task for frontend programming and we would like to see Dashboard/placeholder created through following frontend technologies

There are multiple Web Development setup like
XAMPP, LAMP, WAMP etc so we recommend you to start with XAMPP that will install required softwares in your laptop to get the test done.



# Frontend Framework
We want to use "Svelte" as Web Frontend programming language for the layout.


# Backend Framework
PHP - We are using PHP as Backend Programming language to get this work done so please use PHP. There are other alternatives like DJango, NodeJS etc.

NOTE: We don't require Backend stack as of now and mostly you will be using Apache as Webserver and Svelte as Frontend programming language.

Laravel/PHP - itself provides small inbuilt webserver like functionality using command named "artesian" to test the application so we recommend to use this as part of your setup/testing and README.md file contains all such steps.

(Optional)Laravel LiveWire - It is part of Laravel Frontend Framework and provides similar features in comparison to Svelte, ReactJs etc.

# Backend Setup Steps(Laravel)


STEP 1: Download XAMPP
```
https://sourceforge.net/projects/xampp/
```
STEP 1.1 Install XAMPP
```
- Double click on xamp EXE file
- Extract in C:\xampp
```

STEP 2: Download Composer.exe for windows
Verify Composer installation by running composer command
```
# composer
```

STEP 3: Download Laravel installer using compose
```
# composer global require laravel/installer
```

Verify Laravel installation
```
# laravel
```

STEP 5: Create Fresh Laravel installation
```
# Change Directory
cd C:\xampp\htdocs\

# Create Laraveel Project named flyfast
# laravel new flyfast #(use this)

           OR

# composer create-project laravel/laravel {flyfast} 4.2 --prefer-dist

```
STEP 6: We want you to use Laravel LiveWire for frontend work so install with below command. It will install livewire under YOURPROJECT\vendor\livewire. Livewire is similar to Frontend like Svelte or ReactJs.
```
#composer install livewire/livewire
```

STEP 7: Start the PHP Artisan Webserver to test
```
G:\xampp\htdocs\flyfast> php artisan serve

Starting Laravel development server: http://127.0.0.1:8000
[Sat Aug 12 20:08:31 2023] PHP 7.4.21 Development Server (http://127.0.0.1:8000) started
[Sat Aug 12 20:09:15 2023] 127.0.0.1:52172 Accepted
```
STEP 7: Above steps will start you test web application and you will be able to access on your browser using above URL. 
Example Page is available insdie [Working Webpage Example Image](references/Laravel-WebPage-Example.PNG)

Example Code:
```
# We have copied working example code inside the example-code/flyfast folder for your reference but you sould be able to get such code automatically after following above mentioned steps so copy this code in extreme cases to continue further!
```

Now, the actual Task steps will start so please solve the task assigned to you like TASK-1, TASK-2 etc.



