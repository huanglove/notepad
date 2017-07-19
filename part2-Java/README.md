# Java篇

{% mermaid %}
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
{%endmermaid%}

```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```



