+++
title = "Shortcodes Examples"
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

## Bubble

{% bubble() %}
Talk Something!
{% end %}

{% bubble(left=true) %}
Talk Something!
{% end %}

{% bubble(icon="/posts/with-image/mel-3IA4-tUDyKI-unsplash.webp") %}
Custom icon
{% end %}

{% bubble() %}
Nulla facilisi. Vivamus vulputate enim auctor leo fermentum, eget tristique nisi ornare. Nam eget ligula quis dolor tempus vehicula et vitae ante. Aenean ac fermentum diam, sed hendrerit mi. Sed sollicitudin purus dolor, vel euismod nunc mattis vitae. Aenean in nulla mollis, tincidunt nisi vitae, rutrum turpis. Mauris suscipit vel tellus non pretium. Nam pretium felis magna, finibus dapibus velit dictum eget. Mauris vehicula pharetra tortor, vel rutrum quam venenatis vitae. Phasellus tempor felis semper ligula dictum, vitae elementum nisi semper. Vivamus quis pulvinar dolor, eget luctus magna. Pellentesque ipsum tortor, pharetra vitae volutpat ut, convallis a ex. Vestibulum a hendrerit ante. Nam ut magna sit amet libero suscipit accumsan.

Phasellus eget erat in lorem dignissim lobortis a at purus. Pellentesque nulla orci, congue eu nisl eu, sollicitudin volutpat arcu. Mauris non tempor orci, at convallis orci. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque blandit tempus egestas. Morbi nisi sem, elementum at arcu at, ornare euismod sem. Morbi posuere nunc id neque iaculis, vitae auctor ipsum efficitur. Sed lacinia odio ut tellus rhoncus condimentum. Quisque molestie, ex id ultricies rutrum, velit purus consectetur odio, a mollis felis dui at elit. Donec ultricies, augue eu rutrum vulputate, quam mauris sagittis nisi, ac eleifend tellus neque et nunc. Fusce in purus iaculis, tempus nisl in, posuere massa. Fusce venenatis nibh quis quam accumsan laoreet. Suspendisse eget odio tristique ipsum tincidunt dapibus sit amet et libero. Phasellus placerat aliquam nibh vel bibendum. Donec sodales tortor mattis enim sollicitudin, sit amet mattis tellus pharetra. Pellentesque eget diam aliquet, sodales sem eget, sollicitudin nulla.
{% end %}

```tera
{%/* bubble() */%}
Talk Something!
{%/* end */%}

{%/* bubble(type="left") */%}
Talk Something!
{%/* end */%}

{%/* bubble(icon="/posts/with-image/mel-3IA4-tUDyKI-unsplash.webp") */%}
Custom icon
{%/* end */%}
```
