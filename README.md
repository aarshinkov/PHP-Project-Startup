# Стартиране на PHP приложение с MySQL база данни

## 1. Необходими програми

1. PHP - свали от [тук](https://windows.php.net/downloads/releases/php-7.4.0-Win32-vc15-x64.zip)
2. WampServer - свали от [тук](https://sourceforge.net/projects/wampserver/files/latest/download)

## 2. Инсталиране на PHP

### 2.1. Проверете дали нямате вече инсталирана версия на PHP

За да проверите дали нямате вече инсталирана версия на PHP, отворете **Командният прозорец** (**_Command prompt_**).
<code>Win -> Command prompt</code>. В конзолата напишете <code>php -v</code>.

1. Ако ви изпише "php is not recognized as an internal or external command" това значи, че нямате инсталиран PHP на вашия компютър.
2. Ако получите резултат подобен на този в картинката отдолу, означава, че вече имате инсталиран PHP на компютъра си.

![PHP Validation](https://github.com/aarshinkov/PHP-Project-Startup/blob/master/images/php_validation_s.PNG "PHP Validation")


### 2.2. Сваляне и инсталиране на PHP

#### 2.2.1 Сваляне на PHP

1. Кликнете върху този [линк](https://windows.php.net/downloads/releases/php-7.4.0-Win32-vc15-x64.zip) и свалете <code>.zip</code> файла.
2. Разархивирайте в папка по избор.

### 2.2.2. Инсталиране на PHP
1. Копирайте папката **php** от архива в диск **C:**. Трябва да получите директорията **C:\php**
2. Влезте в папката **C:\php** и намерете файла *php.ini-development*.
3. Преименувайте го на **_php.ini_**
4. Отворете файла с някой текстов редактор.
5. Намерете реда, на който пише <code>extension_dir</code> и го променете на <code>extension_dir = "C:/php/ext"</code>

![PHP Extension Dir](https://github.com/aarshinkov/PHP-Project-Startup/blob/master/images/php_extension_dir.PNG "PHP Extension dir")

6. Намерете следните редове и премахнете символа **;** пред тях.

![PHP Extensions](https://github.com/aarshinkov/PHP-Project-Startup/blob/master/images/php_extensions.PNG "PHP Extensions")

7. Намерете менюто за **Environment variables**, цъкнете на бутоните от снимката по-долу.

![PHP Environment Variables](https://github.com/aarshinkov/PHP-Project-Startup/blob/master/images/php_env_var.PNG "PHP Environment Variables")

8. Добавете "C:\php" като нов запис.

![PHP New environment variable](https://github.com/aarshinkov/PHP-Project-Startup/blob/master/images/php_env_var_new.PNG "PHP New environment variable")

9. Проверете в **Командният прозорец** дали **PHP** е инсталиран успешно, както направихме в точка **2.1**

## 3. Инсталиране на WampServer

1. Свалете WampServer от [тук](https://sourceforge.net/projects/wampserver/files/latest/download)
2. Стартирайте <code>.exe</code> файла и инсталирайте в папка по избор.
3. За стартиране отидете в инсталационната директория и стартирайте файла **wampmanager.exe**.
4. За да отворите проект, копирайте папката на проекта и го поставете в папка **www** в инсталационната директория на **WampServer**.

## 4. За автора

Атанас Аршинков - Софтуерен разработчик <br>
[GitHub](https://github.com/aarshinkov) профил <br>
[LinkedIn](https://www.linkedin.com/in/atanas-arshinkov/) профил
