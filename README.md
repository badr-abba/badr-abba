<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:0b1220,100:0f766e&height=170&section=header&text=Badreddine%20ABBA&fontSize=40&fontColor=f1f5f9&fontAlignY=45&desc=Cloud%20%C2%B7%20DevOps%20%C2%B7%20Big%20Data&descSize=16&descAlignY=68&descColor=99f6e4" alt="Badreddine ABBA - Cloud, DevOps, Big Data" width="100%" />

## My profile, as a Dockerfile

```dockerfile
FROM engineer:cloud-devops-bigdata

LABEL name="Badreddine ABBA"
LABEL role="Cloud, DevOps & Big Data Engineer"
LABEL github="badr-abba"

ENV FOCUS="cloud devops bigdata"
ENV MINDSET="automate everything, observe everything"

WORKDIR /pipelines

COPY ./infrastructure ./as-code
COPY ./bigdata ./trusted

HEALTHCHECK --interval=1d CMD curiosity --still-running

CMD ["design", "build", "ship", "observe"]
```

## What's running

```console
$ kubectl get focus
NAME     LAYER            WHAT I DO                                   STATUS
cloud    infrastructure   architecture, IaC, security                 Running
devops   delivery         CI/CD, containers, monitoring               Running
bigdata  pipelines        ingestion, distributed processing, quality  Running
```

<!--
  STACK: add only what you really use, then uncomment.
  Icons: https://github.com/tandpfun/skill-icons#icons-list

  ## Stack
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,githubactions,python,sql&theme=dark" alt="Stack" />
-->

## Build stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=badr-abba&show_icons=true&hide_border=true&bg_color=0b1220&title_color=2dd4bf&text_color=cbd5e1&icon_color=2dd4bf" alt="GitHub stats" height="150" />
  <img src="https://streak-stats.demolab.com?user=badr-abba&hide_border=true&background=0b1220&stroke=2dd4bf&ring=2dd4bf&fire=2dd4bf&currStreakLabel=cbd5e1&sideLabels=cbd5e1&currStreakNum=f1f5f9&sideNums=f1f5f9&dates=64748b" alt="GitHub streak" height="150" />
</p>

<p align="center">
  <a href="https://github.com/badr-abba">
    <img src="https://img.shields.io/badge/github-badr--abba-0b1220?style=flat-square&logo=github&logoColor=2dd4bf" alt="GitHub" />
  </a>
</p>

<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:0b1220,100:0f766e&height=60&section=footer" alt="" width="100%" />
