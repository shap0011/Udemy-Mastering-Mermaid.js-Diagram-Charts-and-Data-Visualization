# Flowchart Diagram

## Introduction to Flowchart

---

## Flowchart Basics

````
```mermaid
flowchart
    a-->b

```
````

```mermaid
flowchart
    a-->b

```

---

## Orientation and Error Handling

TD; TB;

````
```mermaid
flowchart LR
      A[start]; B[car]; C[toy]
      A --> B
      A --> C & D
      C --> F
      B --> F
      D --> G
      D --> H

```
````

```mermaid
flowchart
      A[start]; B[car]; C[toy]
      A --> B
      A --> C & D
      C --> F
      B --> F
      D --> G
      D --> H

```

---

## Working with Nodes - Node Text

````
```mermaid
flowchart
      A["A:Family()"]
      B["B:Man 👨"]
      C["`C:Woman👩
      **#quot;Bags#quot;**
      _Shows_`"]
      A --> B
      A --> C & D[D:Children]
      C --> F[F:Married #9829;]
      B --> F
      D --> G["`G:**Boy**`"]
      D --> H[H:Girl]

```
````

```mermaid
flowchart
      A["A:Family()"]
      B["B:Man 👨"]
      C["`C:Woman👩
      **#quot;Bags#quot;**
      _Shows_`"]
      A --> B
      A --> C & D[D:Children]
      C --> F[F:Married #9829;]
      B --> F
      D --> G["`G:**Boy**`"]
      D --> H[H:Girl]

```

---

## Working with Links

---

## More on Working with Links

---

## Working with Subgraph

---

## Flowchart Node Interactivity

---

## Flowchart - Styling Lines and Nodes
