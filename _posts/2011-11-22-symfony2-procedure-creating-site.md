---
layout: post
title: symfony2-procedure-creating-site

---

{{ page.title }}
================



COMMANDS: <br>
php app/console generate:bundle --namespace=Johnny/BDDTutorial/RiversBundle --dir=src --no-interaction <br>
mysql -u root < 00-extra/db/create-empty-database.sql <br>
doctrine:schema:update --force
