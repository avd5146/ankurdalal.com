# Markdown references.

## Collapsible

<details>
<summary> <- press </summary>
<!-- Necessary empty line -->

  [photography test](./photography/docs)

</details>

## Include from other file
<!-- jekyll specific -->
<!-- if using only 'include', it must be contained in _include -->
{% include_relative README.md %}
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

```md
  {% include_relative photography/README.md %}
```

</details>

## PHP

[try php](./sample.html)

---
### ankurdalal.com
