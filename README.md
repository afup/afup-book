Livre blanc de l'AFUP
=====================

Installation
------------

```
mkdir  afup-book
git clone http://github.com/omansour/afup-book.git afup-book
cd afup-book
wget http://getcomposer.org/composer.phar
php composer.phar install
```

Contribution
------------
dans le répertoire doc. pour gérer le plan du livre il faut éditer le fichier config.yml sous doc/livre-blanc-afup


Publication du livre
--------------------
```
./book publish livre-blanc-afup --dir="doc/" 
```

enjoy ;)

