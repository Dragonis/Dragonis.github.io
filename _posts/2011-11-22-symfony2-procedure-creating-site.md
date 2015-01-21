---
layout: post
title: symfony2-procedure-creating-site

---

{{ page.title }}
================



COMMANDS: <br>
php app/console generate:bundle --namespace=Johnny/BDDTutorial/RiversBundle --dir=src --no-interaction <br>
mysql -u root < 00-extra/db/create-empty-database.sql <br>
doctrine:schema:update --force <br>
php app/console doctrine:generate:crud <br>

create the admin account: <br>
php app/console fos:user:create admin admin@example.net loremipsum --super-admin <br>
or <br>
php app/console fos:user:create <br>
php app/console fos:user:promote --super admin <br>