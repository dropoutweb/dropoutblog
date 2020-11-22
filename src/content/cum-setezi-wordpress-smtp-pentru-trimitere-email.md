---
title: 'Cum să îți setezi WordPress SMTP pentru a trimite și primi mailuri.'
author: [Andrei]
tags:
  - Tehnic
  - Tips&Tricks
image: img\cum-sa-setezi-wordpress-smtp-mailuri-min.jpg
date: '1922-12-12T10:00:00.000Z'
excerpt: Această setare din WordPress, care vine neconfigurata și fără un tutorial sau o informație asupra acesteia, îți permite să trimit mailuri prin intermediul unui server SMTP.
draft: false
---

### Cum să îți setezi WordPress SMTP pentru a trimite și primi mailuri.
<br>
Pentru început, ce este și ce face WordPress SMTP, sau pe scurt WP SMTP. Această setare din WordPress, care vine neconfigurata și fără un tutorial sau o informație asupra acesteia, îți permite să trimit mailuri prin intermediul unui server SMTP. Acest lucru va împiedică că mailurile tale să între în folderul junk / spam al destinatarilor, dar și să le poți trimite.

Haide să începem:

### 1. Instalare și activare plugin WP Mail SMTP
<br>
În meniul principal din stânga, intră la “Plugins”, apasă pe butonul “Add New”, iar în căsuța de căutare scrie: WP Mail SMTP by WPForms

Dacă dorești să-l adaugi prin import, plugin-ul îl găsești pe magazinul oficial wordpress:
[https://ro.wordpress.org/plugins/wp-mail-smtp/](https://ro.wordpress.org/plugins/wp-mail-smtp/)

![plugin-ul wp mail smtp](https://i0.wp.com/dropoutweb.com/wp-content/uploads/2020/06/image-2.png)

După ce l-ai instalat, nu uitați să-l și activezi.

### 2. Configurare WP Mail SMTP
<br>
cum că ai acest plugin, a mai rămas doar configurarea lui.

Atenție, presupun că ai un webhost destul de bun, cu un serviciu de email de calitate, așa că o să folosim opțiunea default de trimitere prin Php.

Setările acestui plugin le găsești în meniul principal, sub “Settings”, s-a creat un sub-meniu numit: WP Mail SMTP

Când intri în panoul plugin-ului o să te întâmpine direct setările acestuia. O să le explic pe scurt pe cele care trebuiesc modificate.

**From Email**: Aceasta este adresa de email de pe care o să se trimită mail-urile către diverși destinatari. Aici poți să utilizezi adrese personale (Gmail, Yahoo, Outlook, etc) dar și adrese create cu webhost de genul contact@dropoutweb.com.

**From Name**: Acesta este numele care o să apară atunci când un email este trimis de succes, noi de exemplu folosim: DropoutWeb România.

**Mailer**: Cum am spus și mai sus, presupunem că ai un webhost decent, deci vom rămâne la setarea Default.

În final, apăsăm pe butonul “Save Settings”.

### 3. Testare trimitere mail-uri
<br>
Ca să testăm setările făcute asupra plugin-ului, putem să le testăm din panoul principal WP Mail SMTP, în meniul acestuia, la “Email Test”.
![testare trimite email prin wp mail smtp](https://i2.wp.com/dropoutweb.com/wp-content/uploads/2020/06/image-3.png)

Procesul de testare este unul foarte simplu. Trebuie doar să treci la “Send To” un email destinatar, preferabil diferit de cel pus la “From Email” de mai sus.

După ce ai pus email destinatar tot ce mai trebuie să faci este să apeși pe Send Email.

Cam asta a fost tot! Sper că v-a ajutat acest tutorial și sport în continuare la vizite și vânzări!
