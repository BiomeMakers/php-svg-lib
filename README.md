
# Biomemakers notes II

Javi: I am using this again to support fonts in the svg


# Biomemakers notes I
 
Javi: This is not needed anymore. This is a dependency used by phpdom, the pdf generator of Portal. This was just a fork of the original library to add a temporal patch to support php 7.2. But this problem has been fixed by the library creators.
[Our issue](https://github.com/BiomeMakers/Portal/issues/27)


# Git commands

[Original repository](https://github.com/PhenX/php-svg-lib)

```
git remote add upstream https://github.com/PhenX/php-svg-lib.git
git merge upstream/master
```

`composer.json`


```
"require": {
	"biomemakers/php-svg-lib": "dev-master"
}

```

```
"repositories": [
    {
        "type": "git",
        "url": "https://github.com/BiomeMakers/php-svg-lib.git"
    }
]
```



composer remove phenx/php-svg-lib
composer update biomemakers/php-svg-lib


