sfReadabilityPlugin
===================

Description
-----------
Symfony 1.4.X plugin for readability functionnalitie.

Forked from php-readability: https://github.com/feelinglucky/php-readability

Use
---

    $readability = new Readability($html, $charset);
    $readabilityData = $readability->getContent();

    $title = $readabilityData['title'];
    $content = $readabilityData['content'];