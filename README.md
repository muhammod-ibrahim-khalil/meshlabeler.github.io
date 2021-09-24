# MeshLabeler
**MeshLabeler** is a tool to help label the unlabeled (*i.e new or self made*) dataset manually over a private network so that together can make the task easier with a friendly UI.


```mermaid
graph TB
A[Unlabeled Dataset] --- B((Worker#1))
A --- C((Worker#2))
A --- D((Worker#3))
A --- E((...))
A --- F((Worker#n))

```

### Supported :

| **Data type** | **File** | **Perform** | **Status**
| Text | csv | Multi-label, Label | Developing
| Image | jpg | Segmentation, Label, Multi-label, Annotation |Not yet
| Video | mp4 | Segmentation, Label, Multi-label |Not yet
| Audio | wav | Segmentation, Label, Multi-label |Not yet

###**Limitation :**

 - Manage only one dataset at a time.
 - Save file will produce a file.
