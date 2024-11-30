















DEV:


/home/USER/packages.json:
````
{
    "packages": {
        "jarrin/wplat": {
            "dev-master": {
                "name": "jarrin/wplat",
                "version": "1.1.3",
                "dist": {
                    "url": "./Projects/WPLT",
                    "type": "path"
                }
            }
        }
    }
}
````

``
composer create-project --repository=./packages.json jarrin/wplat WPLAT-demo
``

Prevent Symlink, add to ENV:
``
COMPOSER_MIRROR_PATH_REPOS=1
``