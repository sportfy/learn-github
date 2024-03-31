## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
ZHANJingchun ->> Yida: Hello Yida, how are you?
Yida-->>John: How about you John?
Yida--x ZHANJingchun: I am good thanks!
Yida-x John: I am good thanks!
Note right of John: Yida thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Yida-->ZHANJingchun: Checking with John...
ZHANJingchun->John: Yes... John, how are you?
```

```mermaid
journey
    title My working day
    section Go to work
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 5: Me
```



```mermaid
gantt
    title A Gantt Diagram
    dateFormat YYYY-MM-DD
    section Section
        A task          :a1, 2014-01-01, 30d
        Another task    :after a1, 20d
    section Another
        Task in Another :2014-01-12, 12d
        another task    :24d
```
