cakephp-lib
===========

CakePHP version 2.5.7 (not altered), git submodule dependency

Just a git project to add CakePHP as a submodule in you CakePHP project.

```
git submodule add https://github.com/Kwaadpepper/cakephp-lib.git lib/Cake
```

So it won't be included in your project it allows you to save space, make a leaner git tree.
Next time you clone you project just do ```git submodule update --init``` to update all dependencies via git.
see also Composer https://getcomposer.org/ and Packagist https://packagist.org/ to find and manage dependencies for youre php project.
