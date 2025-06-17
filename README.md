# 💼 Logiciel de Facturation – David Limousine

## 🧾 Présentation du projet

Ce projet consiste à développer un **logiciel de génération de factures** destiné à la société **David Limousine**, une entreprise belge spécialisée dans le **transport de personnes sous licence LVC**. Actuellement, la facturation est effectuée manuellement à l'aide de fichiers Excel, ce qui est peu optimal, sujet à erreur et chronophage.  

L'objectif est de fournir une **application simple, fiable et moderne**, adaptée aux besoins quotidiens du gérant : création rapide de factures conformes aux exigences légales, gestion d’un carnet de clients, génération de documents PDF, et envoi des factures par e-mail.

Ce logiciel est développé dans le cadre d’un **travail de fin d’études (TFE)** réalisé en dernière année du bachelier en informatique à l’EPHEC.

---

## 🎯 Objectifs principaux

- Gérer une base de données clients
- Générer différents types de factures (simples, détaillées, forfaitaires)
- Intégrer toutes les mentions légales (TVA, numérotation, mentions obligatoires)
- Exporter les factures au format PDF avec QR code de paiement
- Permettre l’envoi direct des factures par mail
- Fournir une interface intuitive, adaptée à un utilisateur non technique
- Fonctionner **hors-ligne**, sur **MacOS**, en **mono-utilisateur**

---

## 🧰 Technologies utilisées

- **Python** : langage principal, simple et puissant pour un développement rapide
- **PySide6 (Qt for Python)** : création de l’interface graphique
- **SQLite** : base de données locale légère et intégrée
- **WeasyPrint / ReportLab** : génération de fichiers PDF
- **smtplib** : envoi de mails via SMTP
- **qrcode** : génération de QR codes de paiement
- **Git + GitHub** : gestion du versionnage et du suivi de projet

---

## 🔧 Environnement de développement

- Développement réalisé sous **Windows**
- Application finale prévue pour une utilisation sous **MacOS** ( dans un premier temps )
- Utilisation de **GitHub Projects (Kanban)** pour le suivi des tâches

