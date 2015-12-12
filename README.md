# HackAcademy.org servers

## Overview

Manage our hackacademy.org servers centrally

## Done

* hir.hackacademy.org -> hir.cloudapp.net 

## decrypting secrets

certificates, passwords, API keys should be placed in secrets/ so that they are encrypted by git-crypt:

```
git-crypt unlock ../git-crypt-hackacademy-key-file 
```

## Running ansible

Operation should be idempotent:

```
./ansible.sh
```
