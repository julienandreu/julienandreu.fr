+++
title = "Content Cheatsheet : misc implementations #1"
image = "/images/my-posts/oCc_9ptUqSM.jpg"
author = "Julien Andreu"
date = 2019-12-15
description = "Content sample, code highlighting, dynamic graph, different picture implementations"
type = "post"
categories = ["Guide"]
[[plugins.css]]
URL = "plugins/code-highlight/code-highlight.css"
[[plugins.js]]
URL = "plugins/mermaid/mermaid.min.js"
[cta]
enable = true

+++

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec rhoncus mattis justo, id viverra lorem laoreet quis. Integer posuere nisi efficitur, aliquam nibh quis, sollicitudin elit. Ut eleifend nisl accumsan, posuere odio vel, eleifend velit. Aliquam sit amet dapibus leo. Sed vel quam ullamcorper, sagittis metus ac, tincidunt turpis. Aenean pellentesque dui in felis ornare hendrerit. Fusce hendrerit massa a lorem porttitor, non convallis mauris auctor. Morbi vestibulum at diam id fringilla. Praesent est quam, faucibus congue egestas et, eleifend ac augue. Duis vel nulla et odio mollis tincidunt non quis nisi. Phasellus in nunc quis nibh ultrices ultricies a eget nibh. Ut nec ipsum orci. Vivamus quis turpis hendrerit, commodo ante feugiat, euismod eros. Phasellus ornare justo id luctus condimentum. Sed lacinia nibh et metus fringilla ornare. Nullam at interdum purus.

---
## Code highlight

{{< highlight html "linenos=table,hl_lines=2 4-6,linenostart=199">}}
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
        {{ .Render "summary"}}
    {{ end }}
    TEST --> Ok === Youhou
  </div>
</section>
{{< /highlight >}}

---
## Graph

[Graph sample through MermaidJS library](https://mermaid-js.github.io/mermaid/)

{{<mermaid class="full">}}
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
{{</mermaid>}}

---
## Fixed pictures 

Thanks to Nitish Meena : [https://unsplash.com/photos/oCc_9ptUqSM](https://unsplash.com/photos/oCc_9ptUqSM)

![Thanks to Nitish Meena](/images/my-posts/oCc_9ptUqSM.jpg)

Thanks to Andrew Welch : [https://unsplash.com/photos/kwXby58kRSo](https://unsplash.com/photos/kwXby58kRSo)

![Thanks to Andrew Welch](/images/my-posts/kwXby58kRSo.jpg)

Thanks to Justine Milton : [https://unsplash.com/photos/xr5whzQaers](https://unsplash.com/photos/xr5whzQaers)

![Thanks to Justine Milton](/images/my-posts/xr5whzQaers.jpg)

---
## Full width pictures, add trailing # to picture URL

Thanks to Nitish Meena : [https://unsplash.com/photos/oCc_9ptUqSM](https://unsplash.com/photos/oCc_9ptUqSM)

![Thanks to Nitish Meena](/images/my-posts/oCc_9ptUqSM.jpg#)

Thanks to Andrew Welch : [https://unsplash.com/photos/kwXby58kRSo](https://unsplash.com/photos/kwXby58kRSo)

![Thanks to Andrew Welch](/images/my-posts/kwXby58kRSo.jpg#)

Thanks to Justine Milton : [https://unsplash.com/photos/xr5whzQaers](https://unsplash.com/photos/xr5whzQaers)

![Thanks to Justine Milton](/images/my-posts/xr5whzQaers.jpg#)

---
## Raw text

Proin sagittis, elit ac vulputate viverra, diam quam hendrerit felis, ornare varius lorem eros quis erat. Sed convallis eu sem id vulputate. Donec ullamcorper convallis vehicula. Aenean hendrerit lectus quis orci ultricies commodo. Nam sodales ex in egestas semper. Nullam sed hendrerit ipsum. Fusce laoreet iaculis urna.

---

Vivamus vel arcu sit amet justo feugiat faucibus a ac ligula. Curabitur tristique quam placerat, pretium quam quis, malesuada augue. Integer quis egestas sapien. Proin eget eleifend nisi. Quisque dapibus dapibus leo, sed viverra sapien. Donec rhoncus nisl commodo nibh molestie gravida. Curabitur dictum varius facilisis. Curabitur mauris velit, cursus a nisl non, sollicitudin gravida metus. Praesent nec nunc quis tortor pharetra varius. Morbi lacinia a elit ac egestas. Mauris vitae purus non tortor tincidunt sodales et ut diam. Proin auctor ante ac rhoncus feugiat. Sed eu lectus id lorem convallis fermentum eget sed sapien.