# Specops Password Auditor 🔐
Un outil puissant pour analyser les mots de passe Active Directory et détecter les vulnérabilités associées à leur sécurité.  

![License](https://img.shields.io/badge/license-Free-green.svg)  
![Security](https://img.shields.io/badge/security-High-red.svg)  

## 🛡️ Fonctionnalités de Sécurité  
✔️ **Détection des mots de passe compromis** via bases de données connues  
✔️ **Identification des comptes à risque** (admin, comptes dormants, etc.)  
✔️ **Vérification des politiques de mot de passe** (expiration, complexité, unicité)  
✔️ **Rapports détaillés** pour une remédiation rapide  
✔️ **Analyse hors ligne** sans impact sur l'Active Directory  

## 📋 Prérequis  
- Windows 10/11 ou Windows Server  
- Accès en lecture sur Active Directory  
- .NET Framework 4.5 ou supérieur  

## 🛠️ Installation  
Téléchargez la dernière version sur le site officiel :  
➡ **[Télécharger Specops Password Auditor](https://specopssoft.com/product/specops-password-auditor/)**  

Ou utilisez GitHub :  
```sh
git clone https://github.com/Specops/PasswordAuditor.git  
cd PasswordAuditor  
```

## 📖 Guide d'utilisation  

### Lancer un audit des mots de passe  
```sh
SpecopsPasswordAuditor.exe --scan --server mon-domaine.local
```

### Générer un rapport détaillé  
```sh
SpecopsPasswordAuditor.exe --scan --server mon-domaine.local --export report.html
```

### Vérifier les comptes les plus exposés  
```sh
SpecopsPasswordAuditor.exe --high-risk-accounts
```

## 📢 Assistance

N'hésite pas a me contacter via discord ou telegram **(check mon read.me)** pour toute demande d'assistance concernant l'utilisation de l'outil !

---

**by user99x** ⚡

<p align="center">
  <img src="user99x.jpeg" alt="Logo github" width="200" align="right">
</p>

