# <B>NEXTCLOUD DIRECTORIES</B>

APPS downloaded/enabled from within the app are stored here
- ``` /usr/local/www/nextcloud/apps ```
    - <em>How to use this?</em> 
       - PERMISSION ISSUES!
       - Gives the main directory and recursively everything below it the same user:group ownership. Adding the * does the recursive work
       - ``` chown -R www:www * ```
