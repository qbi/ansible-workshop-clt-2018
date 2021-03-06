# ansible-workshop-clt-2018

Ansible Workshop für die Chemnitzer Linux-Tage 2018

## Inhalt

Dieses Repository enthält die Slides und Übungen für einen [Ansible](https://www.ansible.com/) Workshop während der Chemnitzer Linux-Tage 2018.

## Vortragende

  * Jens Kubieziel (Spezialist für IT-Sicherheit und Datenschutzbeauftragter, [Octopi.Consulting](https://torservers.net/)) / [Homepage](https://kubieziel.de/)
  * Andreas Scherbaum (Principal Software Engineer) / [Homepage](http://andreas.scherbaum.la/)
  * Andreas Krause (Senior Specialist, Zero.One.Data, DB Systel GmbH)

## Anmeldung

https://chemnitzer.linux-tage.de/2018/en/programm/beitrag/145

## Vorkenntnisse

  * Grundlagen in der Administration eines Linux-Systems sowie in der Benutzung von SSH
  * Umgang mit einem Texteditor

## Voraussetzungen

  * Laptop mit gängiger, aktueller Linux-Distribution (z.B. Ubuntu >= 16.04, Debian >= stretch)
  * Installiertes ansible >= 2.x
  * git
  * ssh client

## Vorbereitungen

  * clone des git repos: git clone https://github.com/andreasscherbaum/ansible-workshop-clt-2018
  * Wechsel in das repo: cd ansible-workshop-clt-2018
  * Speichern der drei Dateien ansible.cfg, inventory und key.pem aus der Email mit den Zugangsdaten in das Verzeichnis ansible-workshop-clt-2018
  * Anpassen der Permissions für key.pem: chmod 0600 key.pem
  * Setzen der Umgebungsvariable ANSIBLE_CONFIG: export ANSIBLE_CONFIG=$(pwd)
