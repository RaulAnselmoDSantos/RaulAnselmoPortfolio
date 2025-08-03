---
layout: default
title: Bem-vindo
---

<script>
  const lang = navigator.language || navigator.userLanguage;
  const userLang = lang.toLowerCase().startsWith('pt') ? 'pt' : 'en';

  if (!window.location.pathname.includes('/pt/') && !window.location.pathname.includes('/en/')) {
    window.location.href = `/RaulAnselmoPortfolio/${userLang}/`;
  }
</script>

# 🌐 Redirecionando...

Caso não seja redirecionado automaticamente, selecione uma versão:

- [Versão em Português](/RaulAnselmoPortfolio/pt/)
- [English Version](/RaulAnselmoPortfolio/en/)
