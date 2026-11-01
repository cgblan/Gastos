---
name: Primer acceso y privacidad
description: Requisito de inicio de sesión y separación de cuentas para Gastos rápidos.
---

La app no debe pedir autenticación durante el desarrollo ni en la vista previa del navegador. Debe solicitarla solo cuando cada persona abra por primera vez la PWA instalada en su teléfono. Los gastos deben quedar privados y separados por cuenta.

**Why:** el usuario pidió posponer el inicio de sesión hasta instalar y abrir la app por primera vez.

**How to apply:** gatear el acceso a la autenticación por la apertura instalada de la PWA y vincular los datos a la cuenta autenticada; nunca mostrar los datos locales de otra cuenta.
