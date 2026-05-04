# 2. Promts CJourney 'n MFunnel

## 2.1. APROPIACIÓN DEL 'USERFLOW' EN UML (Primer diagrama creado):

> Explícame por favor el siguiente 'userflow' que se encuentra diagramado en PlantUML:
[COPIAR UML]

## 2.2. CUSTOMER/USER JOURNEY CON MERMAID: [Mermaid.live](https://mermaid.live/edit#pako:eNpVjUFvgkAQhf_KZk5tggYBQfbQpGLrxaQ9eCp4mMjIEmWXLEusBf57F0zTdk4z733vTQdHlRNwOF3U9ShQG7bfZJLZeU4TocvGVNgc2Gz21G_JsEpJuvVs_bBVrBGqrktZPN759QixpNuNGDEjSnke7lYy5d8k9WyT7rA2qj78dfZX1bOXtHwXtv6_IzTZ1Gt6Qn7C2RE1S1BPCDhQ6DIHbnRLDlSkKxxP6EY3AyOoogy4XXPU5wwyOdhMjfJDqeonplVbCLDdl8ZebZ2joU2JhcZfhGROOlGtNMAX0VQBvINP4L4bzBeRG0ee74VhHHuhAzcrL-eBHwVRbLVVELqrYHDga_rqzlfRcvgGKANzSw)

> Teniendo en cuenta lo anterior, diseña un gráfico tipo 'journey' en una caja de código mermaid.js que represente el flujo de usuario para dicho modelo de negocio. Considera el paradigma de las 5A's de Philip Kotler el cual describe las etapas clave del viaje del comprador en la era digital (Atención, Atracción, Averiguación, Acción y Apología). Ten presente por favor, que es imperativo guiarte por el siguiente modelo de código mermaid.js, representar los 3 roles o actores involucrados en cada paso del flujo (usuario, sistema y otros) y NO incluir caracteres especiales en la salida, como por ejemplo: (|_->=-<#´'):
> journey
  title Customer Journey
    section ATENCIÓN
      Buscar el producto o servicio: 5: Usuario
    section ATRACCIÓN
      Mostrar producto o servicio: 4: Sistema
    section APOLOGÍA
      Recomendar la marca: 4: Usuario, Otros

## 2.3. PUNTOS DE CONTACTO/INTERACCIÓN (TOUCHPOINTS):

> Indícame por favor qué puntos de contacto o 'touchpoints' tanto digital como offline podrían considerarse para cada una de las etapas identificadas en el journey anterior, esto, para poder determinar el nivel de satisfacción y los puntos clave a desarrollar.

## 2.4. APROPIACIÓN DEL CUSTOMER JOURNEY:

> Explica detalladamente el siguiente código MERMAID.JS que representa un 'customer journey' de un modelo de negocio en eCommerce.
[CODIGO.MERMAID.CUSTOMER.JOURNEY]

## 2.5. MARKETING FUNNEL (MÉTODO AIDA) EN DOT: [Edotor.net](https://edotor.net/)

> Teniendo en cuenta la anterior explicación, genera un diagrama DOT que represente un marketing funnel bajo el método AIDA para esa tienda en línea. Cada etapa debe estar conectada en orden descendente y representada como un trapecio invertido (invtrapezium), donde el trapecio superior sea el más ancho y el trapecio inferior sea el más estrecho. Para conseguir esto, debes seguir el siguiente ejemplo de patrón de código:
digraph AIDA_Marketing_Funnel {
    rankdir=TB;
    node [shape=invtrapezium, style=filled];
    ATENCIÓN [label="ATENCIÓN\n(Acciones implicadas)", fontsize=22, width=18, height=4, fillcolor="#607880", fontcolor=black, fontname="Helvetica"];
    INTERÉS [label="INTERÉS\n(Acciones implicadas)", fontsize=18, width=10, height=3, fillcolor="#86a8b3", fontcolor=black, fontname="Helvetica"];
    DESEO [label="DESEO\n(Acciones implicadas)", fontsize=14, width=5.5, height=2, fillcolor="#a3ccd9", fontcolor=black, fontname="Helvetica"];
    ACCIÓN [label="ACCIÓN\n(Acciones implicadas)", fontsize=10, width=3, height=2, fillcolor=white, fontcolor=black, fontname="Helvetica"];
    ATENCIÓN -> INTERÉS;
    INTERÉS -> DESEO;
    DESEO -> ACCIÓN;
}
Recuerda que el embudo debe reflejar el flujo del usuario desde la primera interacción con la marca hasta convertirse en un defensor de la misma, las etapas deben estar nombradas en mayúsculas y de ser necesario, incluir en cada label un \n donde se relacione (n) la (s) acción (es) implicada (s).

## 2.6. [*] OPCIONAL - PUNTOS DE CONTACTO MARKETING FUNNEL:

> Indícame por favor qué puntos de contacto o 'touchpoints' tanto digital como offline podrían considerarse para cada una de las etapas identificadas en el funnel anterior, esto para poder determinar el nivel de satisfacción y los puntos clave a desarrollar.
