# diagrams
repo for text based diagrams


## mermaid test


```mermaid
  flowchart TD;
      A[\raw bucket/]--->B(splitter/formatter function);
      B--->C[\split files bucket/];
      C--->B;
      B--->D[\formatted files bucket/];
      D--->E(task creator function);

```
