# Information
This repo contains task for frontend programming and we would like to see Dashboard/placeholder created through following frontend technologies

There are multiple Web Development setup like
XAMPP, LAMP, WAMP etc so we recommend you to start with XAMPP that will install required softwares in your laptop to get this test done i.e PHP, Apache, Mysql.

NOTE: We don't require Mysql as of now and mostly you will be using Apache as Webserver and PHP as Backend programming language.

Laravel itself provides small inbuilt webserver named artesian to test the application so we recommend to use this as part of your setup/testing and README.md file contains all such steps.

# Frontend Framework
 Laravel LiveWire - We want you to use Laravel LiveWire as Web Frontend solution and it has similar features in comparison to Svelte, ReactJs etc.

# Backend Framework
PHP - We are using PHP as Backend Programming language to get this work done so please use PHP. There are other alternatives like DJango, NodeJS etc.

# Setup Steps


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

# References

[1. Youtube Laravel in Hindi including XAMPP setup](https://www.youtube.com/watch?v=0yVDMcGp97g&list=PLjVLYmrlmjGfh2rwJjrmKNHzGxCZwBsqj)

[1.1 Youtube Laravel in English](https://www.youtube.com/watch?v=4RhY1JJgLsM&list=PLe30vg_FG4OTxKekbWLABcpstdeCDA4LQ)

[1.2 Youtube Laravel LiveWire](https://www.youtube.com/watch?v=xldTvs1BgzA&list=PLe30vg_FG4OQ8b813BDykoYz95Zc3xUWK)

[2. Laravel Documentation Reference](https://laravel.com/)

[3. XAMPP Download Page](https://sourceforge.net/projects/xampp/)



[4. Understsand Tailwind readymade CSS Framework ](https://tailwindcss.com/)

[5. Metronics Pre built themes for different types of Dashboard understanding](https://preview.keenthemes.com/metronic8/demo1/index.html)

[6. Download Visual Studio Code for IDE](https://code.visualstudio.com/download)

[7. Youtube to Learn how to use Visual Studio Code](https://www.youtube.com/watch?v=VqCgcpAypFQ)

[7. Download Git Tool](https://git-scm.com/downloads)


# Interview Tasks
[1. LiveWire Frontend Task](TASK-1-Frontend.md)

[2. Task 2(NA)](TASK-2)


Best of luck!


Thanks & Regards,

Zielbox Interview Team

[www.zielbox.com](http://www.zielbox.com)
