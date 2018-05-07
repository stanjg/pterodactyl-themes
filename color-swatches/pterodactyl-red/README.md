# pterodactyl-red

### Installation guide

1. Copy the folder called `pterodactyl-red` in `/public` to `/public/themes/pterodactyl-red` on your panel install.
2. Open `/config/themes.php` on your panel install.
3. On the bottom of the file file replace the `themes` array with this one: 
```php
    'themes' => [
        'pterodactyl' => [
            'extends' => null,
            'views-path' => 'pterodactyl',
            'asset-path' => 'themes/pterodactyl',
        ],
        'pterodactyl-red' => [
            'extends' => null,
            'views-path' => 'pterodactyl',
            'asset-path' => 'themes/pterodactyl-red',
        ],
    ],
```
4. Go to your .env file and edit `APP_THEME` so that it is set to `pterodactyl-red`
5. You're done :)