# Introduction

In this project, we will utilize the project management tools provided by GitHub at the very beginning. After formating our own introduction, we will write some C code and try to get the workflow badge. After the completion of registration of all team member, we will update our readme file with some new content and register our team repo at the very end.

# Code

``` c
{% include_relative code.c %}
```

![example workflow](https://github.com/csci3251-2022/project-team-b/blob/main/.github/workflows/c-cpp.yml/badge.svg)

![code](https://s1.328888.xyz/2022/04/30/A0c5g.png)

# Contributors

- loookforanans
- lalalam123
- ColsonCZH
- viscory
- byydzh
- JunboShen
- thomaskwan98
- HoongyuKong
{% for member in site.stu %}
  <h2>
    <a href="https://github.com/{{ member.user }}">
      {{ member.user }} - {{ member.name }}
    </a>
  </h2>
  ![image]({{ member.image }})
  <p>{{ member.content | markdownify }}</p>
{% endfor %}

Last updated: {{ site.time }}
# Workflow

![workflow](https://github.com/csci3251-2022/project-team-b/actions/workflows/c-cpp.yml/badge.svg)
