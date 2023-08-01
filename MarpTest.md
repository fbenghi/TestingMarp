---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')

style: |
    svg[id^="mermaid-"] { 
    min-width: 480px; 
    max-width: 960px; 
    min-height: 200px; 
    max-height: 500px; 
    margin-left: 200px
    }



---

<!-- Add this anywhere in your Markdown file -->
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

# **Marp**

Markdown Presentation Ecosystem

https://marp.app/
https://github.com/codebytes/marp-slides-template


---

# How to write slides

Split pages by horizontal ruler (`---`). It's very simple! :satisfied:

```markdown
# Slide 1
d foobar
```


---
# Mermaid
<div class="mermaid">
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->Ess;
</div>

---
# Images
## Horizontal
![bg right:40%](https://picsum.photos/720?image=3)
![bg](https://picsum.photos/720?image=20)

---
# Images
## Vertical
![bg vertical top:30% right:40%](https://fakeimg.pl/800x600/0288d1/fff/?text=A)
![bg](https://fakeimg.pl/800x600/02669d/fff/?text=B)
![bg](https://fakeimg.pl/800x600/67b8e3/fff/?text=C)

<!-- 
This is a presentation note
i, fiz xixi
-->

---
# Links
[Marp](https://marpit.marp.app/) 
[Customization](https://chris-ayers.com/2023/03/31/customizing-marp)
[ImageSyntex](https://marpit.marp.app/image-syntax)

--- 
# Extensions
* Name: Marp for VS Code
Id: marp-team.marp-vscode
Description: Create slide deck written in Marp Markdown on VS Code VS 
[Link](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)

* Markdown Preview Mermaid Support
Description: Adds Mermaid diagram and flowchart support to VS Code's builtin 
[Link](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)
