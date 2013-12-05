Drupal 7: Webform Simple Spam Control
=============================

This module provides a simple solution to limit automated spam webform submissions for Drupal 7.
Compared to captcha solutions, it won't penalize real visitors with characters often too much difficult to read.

## How to use

Download the module to your module folder and enable it. That's it.

Dependency : webform.module

The module automatically adds 2 non-visible fields to any webform on your Drupal web site. These fields are not stored in the database and thus don't impact the submissions content. 
This anti-spam approach is simple yet sufficient to prevent most automated spam robots to spam Drupal webform: when user fills out the webform, these fields must stay empty otherwise the webform won't validate.

[Coheractio - Agence Web Paris](http://www.coheractio.com)