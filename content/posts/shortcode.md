+++
title = "Shortcodes Example"
date = 2021-11-12
+++

## Details

{% details(summary="Summary") %}
Hello!
{% end %}

```
{%/* details(summary="Summary") */%}
Hello!
{%/* end */%}
```

## Reference

{% reference(title="Reference") %}

- [Link 1](https://www.github.com)
- [Link 2](https://www.github.com)
- [Link 3](https://www.github.com)

{% end %}

```
{%/* reference(title="Reference") */%}

- [Link 1](https://www.github.com)
- [Link 2](https://www.github.com)
- [Link 3](https://www.github.com)

{%/* end */%}
```

## Tips

{% tips(type="info") %}
Infomation
{% end %}

{% tips(type="warning") %}
Warning
{% end %}

```tera
{%/* tips(type="info") */%}
Infomation !
{%/* end */%}

{%/* tips(type="warning") */%}
Warning
{%/* end */%}
```

## Image

{{ img(src="/posts/with-image/mel-3IA4-tUDyKI-unsplash.webp",caption="Figure 1") }}

{{ img(src="/posts/with-image/mel-3IA4-tUDyKI-unsplash.webp",caption="Figure 1. Width=100", width="100") }}

```
{{/* img(src="/posts/with-image/mel-3IA4-tUDyKI-unsplash.webp",caption="Figure 1") */}}

{{/* img(src="/posts/with-image/mel-3IA4-tUDyKI-unsplash.webp",caption="Figure 1. Width=100", width="100") */}}
```