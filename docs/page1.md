# Eksempel Side 1

For fuld dokumentation besøg [mkdocs.org](https://www.mkdocs.org). Samt [Material for MkDocs](https://squidfunk/github.io/mkdocs-material/), hvis du bruger Material-temaet, hvilket jeg anbefaler, da det ser bedre ud end MkDocs-temaet.

## Kode Annotation Eksempler

### Codeblock

Her har vi noget `kode` vist på en enkelt linje.

### En almindelig kodeblok

En almindelig kodeblok indledes og afsluttes _altid_ med 3 `backticks` **\`\`\`**:

```txt
some code here
def myfunction()
// Some comment here
Denne kodeblok giver ikke nogen mening
Den tjener kun som illustration for en kodeblok.
```

#### En Kodeblok I Et Specifikt Sprog

Her er noget kode skrevet i en `py` kodeblok:

```py
import tensorflow as tf
def whatever()
```

#### Denne gang giver vi vore kodeblok en titel

```py title="bubble_sort.py"
def bubble_sort(items):
  for i in range(len(items)):
    for j in range(len(items) -1 -i):
      if items[j] > items[j + 1]:
          items[j], items[j + 1] = items[j + 1], items[j]:
```

#### Vi kan også have linje numre

```py title="bubble_sort.py" linenums="1"
def bubble_sort(items):
  for i in range(len(items)):
    for j in range(len(items) -1 -i):
      if items[j] > items[j + 1]:
          items[j], items[j + 1] = items[j + 1], items[j]:
```

#### Det kan også lade sig gøre at highlighte en eller flere linjer

```py title="bubble_sort.py" linenums="1" hl_lines="3 4"
def bubble_sort(items):
  for i in range(len(items)):
    for j in range(len(items) -1 -i):
      if items[j] > items[j + 1]:
          items[j], items[j + 1] = items[j + 1], items[j]:
```

## Brugen af Ikoner og Emojis

:smile:

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }
