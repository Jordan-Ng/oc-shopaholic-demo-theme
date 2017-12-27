# Installation guide

1. Use the composer update command
```bash
use the composer update command
```
2. Create clear database
3. Copy file .env.example => .env
```bash
cp .env.exemple .env
```
4. Change settings in .env file
5. Run database migrations
```bash
php artisan october:up
```
6. Install plugins:
  * [Static Pages](http://octobercms.com/plugin/rainlab-pages) - required
  * [Translate](http://octobercms.com/plugin/rainlab-translate) - required
  * [Toolbox](http://octobercms.com/plugin/lovata-toolbox) - required
  * [Shopaholic](http://octobercms.com/plugin/lovata-shopaholic) - required
7. Run database migrations
```bash
php artisan october:up
```
8. Reinstall Lovata.Basecode plugin
```bash
php artisan plugin:refresh Lovata.Basecode
```

**If you add new extensions of [Shopaholic](http://octobercms.com/plugin/lovata-shopaholic) plugin, you can reinstall the Lovata.Basecode plugin.
Database will be automatically filled with test data**