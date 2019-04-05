---
title: "Hips rubber band"
date: 2019-04-05T14:25:44+02:00
draft: false
---


## Here goes some rubber band stuff


{{< highlight html >}}
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}