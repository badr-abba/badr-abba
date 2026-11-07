<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:0b1220,100:0f766e&height=170&section=header&text=Badreddine%20ABBA&fontSize=40&fontColor=f1f5f9&fontAlignY=45&desc=Automate%20everything%20%C2%B7%20Observe%20everything&descSize=16&descAlignY=68&descColor=99f6e4" alt="Badreddine ABBA - Automate everything, observe everything" width="100%" />

<p align="center">
  <b>Cloud · Data Engineering · Automation</b><br/>
  <i>If it runs twice, it gets automated. If it runs at all, it gets observed.</i>
</p>

## My profile, as a Dockerfile

```dockerfile
FROM engineer:cloud-data-automation

LABEL name="Badreddine ABBA"
LABEL role="Cloud & Data Engineer"
LABEL github="badr-abba"

ENV FOCUS="cloud data-engineering automation observability"
ENV MINDSET="automate everything, observe everything"

WORKDIR /platform

COPY ./infrastructure ./as-code        # Terraform, Ansible, cloud-init
COPY ./pipelines      ./reproducible   # ingestion, transformation, quality
COPY ./observability  ./always-on      # metrics, logs, alerts, dashboards

HEALTHCHECK --interval=1d CMD curiosity --still-running

CMD ["provision", "ingest", "transform", "ship", "observe", "repeat"]
```

## What's running

```console
$ kubectl get focus
NAME          LAYER            WHAT I DO                                          STATUS
cloud         infrastructure   architecture, IaC, virtualization, security        Running
data          pipelines        ingestion, batch & streaming, data quality         Running
automation    delivery         CI/CD, GitOps, configuration management            Running
observability monitoring       metrics, logs, alerting, SLOs                      Running
```

## How I work

- **Everything as code**: infrastructure, configuration, pipelines and dashboards live in Git and are reviewable.
- **Reproducible by default**: same inputs, same environment, same result, from a local VM to the cloud.
- **Data you can trust**: ingestion, validation and quality checks are part of the pipeline, not an afterthought.
- **Observable from day one**: metrics, logs and alerts ship with the service, not after the first incident.
- **Small, frequent, safe changes**: automated tests, automated rollbacks, boring deployments.

<!--
  STACK: add only what you really use, then uncomment.
  Icons: https://github.com/tandpfun/skill-icons#icons-list

  ## Stack
  <img src="https://skillicons.dev/icons?i=aws,azure,gcp,terraform,ansible,docker,kubernetes,githubactions,linux,bash,python,sql,postgres,spark,kafka,airflow,prometheus,grafana&theme=dark" alt="Stack" />
-->

## Build stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=badr-abba&hide_border=true&background=0b1220&stroke=2dd4bf&ring=2dd4bf&fire=2dd4bf&currStreakLabel=cbd5e1&sideLabels=cbd5e1&currStreakNum=f1f5f9&sideNums=f1f5f9&dates=64748b" alt="GitHub streak" height="150" />
</p>

<p align="center">
  <a href="https://github.com/badr-abba">
    <img src="https://img.shields.io/badge/github-badr--abba-0b1220?style=flat-square&logo=github&logoColor=2dd4bf" alt="GitHub" />
  </a>
</p>

<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:0b1220,100:0f766e&height=60&section=footer" alt="" width="100%" />
