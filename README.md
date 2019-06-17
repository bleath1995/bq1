建置環境，安裝XAMPP 選7以上   
安裝git，(看個人使用習慣有Bash、GUI)    
安裝composer，網址:https://getcomposer.org/download/  
以上安裝之後，去檢查，這邊以git bash為例，輸入php -v確認php版本、輸入composer，確認composer有沒有安裝成功、確認php版本是不是7以上   
建置laravel,先下載laravel安裝器，在git bash 輸入composer global require "laravel/installer"   
建置Laravel專案資料夾，去git bash 輸入laravel new 專案名稱   
安裝好之後，git bash 輸入cd 專案名稱/，到專案夾目錄下   
去git bash，輸入:php artisan serve，出現網址，例:<http://127.0.0.1:8000>，貼到網址列，出現Laravel 就算裝好
