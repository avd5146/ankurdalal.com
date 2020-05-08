# Markdown references.

## Collapsible

<details>
<summary> <- press </summary>
<!-- Necessary empty line -->

  [photography test](./photography/docs/index.md)

</details>

## Include from other file
<!-- jekyll specific -->
{% include README.md %}
<br>
<br>
{% include_relative photography/README.md %}

## Lets try both together

<details>
<summary> <- press </summary>
<!-- Necessary empty line -->

  {% include_relative photography/README.md %}

</details>

## Test include in a box

<details>
<summary> <- press </summary>
<!-- Necessary empty line -->

```
  {% include_relative photography/README.md %}
```

</details>

---
### ankurdalal.com