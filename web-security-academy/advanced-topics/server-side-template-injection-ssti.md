---
cover: ../../.gitbook/assets/SSTI.png
coverY: 0
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Server-side template injection (SSTI)

Bu texnika ilk dəfə Portswigger Research"ları tərəfindən `Server-Side Template Injection: RCE for the Modern Web App` başlığı altında konferansda təqdim edilmişdir. Research"ün detalları aşağıdakı linkdə yerləşdirilmişdir.&#x20;

{% embed url="https://portswigger.net/research/server-side-template-injection" %}

Bu hissədə, biz Server-side template injection boşluğunun nə olduğunu və bu boşluqrdan necə istifadə edə bilərik haqqında danışacıyıq.  Həmçinin template"lərdən öz istifadəmiz üçün bu tip boşluqların aradan qaldırılması həllərini təklif edəciyik.

### What is server-side template injection? <a href="#what-is-server-side-template-injection" id="what-is-server-side-template-injection"></a>

