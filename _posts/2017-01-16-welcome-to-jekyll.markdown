---
layout: post
title: Jekyll vs Wordpress ¿Porqué Jekyll nos capturo?
excerpt: "Una comparativa en la que te explicamos las razones porqué Jekyll ha sido un gran descubrimiento para nososotros"
categories: articles
tags: [desarrollo]
image:
  feature: jekyll-desarrollo.jpg
  credit: Unsplash
  creditlink: https://unsplash.com/search/developement?photo=OqtafYT5kTw
---

Wordpress no necesita introducción, ha sido durante los últimos años un compañero fiel. Ha ayudado a miles de desarrolladores y emprendedores en su búsqueda de conseguir un gestor de contenidos (CMS) versatil y completo para su blog o página de empresa. Siendo esto así cada vez más Wordpress se aleja de ser perfecto. El mayor problema que tiene la plataforma lo define bien el refranero español:

> Quien mucho abarca poco aprieta

Esto se traslada a un aumento de tamaño que lo ha convertido en un mastodonte con centenas de features que solo ralentizan y desestabilizan el sistema (no tienen sentido para la mayoria de desarrollos). Para arreglar sus deficiencias han aparecido centenas de plugins para mejorar su rendimiento (W3 Total Cache, P3, Bj Lazy load...), ayudaban y se optimizaban los tiempos de respuesta pero no solucionaban la raiz del problema, su tamaño y complejidad.

## Jekyll

Jekyll es un generador de páginas estáticas (aquí me voy a poner algo ténico, en cualquier avisadnos si quereis que os expliquemos algo con más profundidad, en cualquier caso podeís saltar a la lista de beneficios), esto significa que en vez de tener software corriendo en tus servidores para generar las páginas a tus usuarios, lo que haces es subir directamente archivos html, css y js listos para consumir. Cuando un usuario quiere ver una página directamente se le envia porque hemos subido esa pagina completa, en vez de tener que lidiar con operaciones y bases de datos. Tener los archivos listos para ser enviados tiene bastantes ventajas.

1. Es muy rápido

Con Wordpress puedes conseguir buenas velocidades si te esfuerzas en optimizarlo pero siempre tendras un tope complicado de romper. Jekyll en cambio al trabajar con archivos planos no tiene que "construir" con contenido dinámico ninguna vista, no tiene bases de datos que consultar y eso le da una rapidez sin ni siquiera optimizar que wordpress no es capaz de conseguir.

2. No tiene problemas de seguridad

Cada vez más somos conscientes que con Wordpress tienes que actualizar a nuevas versiones lo antes posible para no verte con problemas de seguridad. Pero es un riesgo y una preocupación sobre todo de mantenimiento tanto del CMS como de los plugins, y eso complica la vida. Cuando solo tienes archivos estáticos de lo unico que tienes que tener cuidado es en que no adivinen la contraseña de tu cuenta, tienes tranquilidad que de ahí no se va a mover la página.

3. Es barato

Dejamos lo mejor para el final. Utilizando Amazon S3 o GitHub tener tu página te cuesta poco o nada (en GitHub tenemos hosting gratuito!!). Al no tener que pagar bases de datos ni capacidad de proceso la factura se hunde por los suelos.

##Conclusión

Cada vez más hay que ver que se está haciendo en el sector para evolucionar y ofrecer un buen servicio a nuestros clientes. No podemos quedarnos en el One-Size-Fit-All. Con esto no digo que todo el mundo tiene que migrar su blog o página personal a Jekyll, solo que hay que estudiarlo caso a caso.
