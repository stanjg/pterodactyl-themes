# pterodactyl-green

### Installation guide

1. Copy the folder called `pterodactyl-green` in `/public` to `/public/themes/pterodactyl-green` on your panel install.
2. Open `/config/themes.php` on your panel install.
3. On the bottom of the file file replace the `themes` array with this one: 
```php
    'themes' => [
        'pterodactyl' => [
            'extends' => null,
            'views-path' => 'pterodactyl',
            'asset-path' => 'themes/pterodactyl',
        ],
        'pterodactyl-green' => [
            'extends' => null,
            'views-path' => 'pterodactyl',
            'asset-path' => 'themes/pterodactyl-green',
        ],
    ],
```
4. Go to your .env file and edit `APP_THEME` so that it is set to `pterodactyl-green`
5. You're done :)