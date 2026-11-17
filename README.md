<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:191724,50:31748f,100:c4a7e7&height=210&section=header&text=Rahul%20Nayak&fontSize=58&fontColor=e0def4&animation=fadeIn&fontAlignY=36&desc=Backend%20%E2%80%A2%20Distributed%20Systems%20%E2%80%A2%20LLM%20Inference&descAlignY=58&descSize=18" width="100%" alt="Rahul Nayak" />

<a href="https://github.com/prometheus-97">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=3000&pause=900&color=C4A7E7&center=true&vCenter=true&width=640&lines=Building+fault-tolerant+backend+systems;Durable+execution+%E2%80%A2+Queues+%E2%80%A2+Crash+recovery;Heading+into+LLM+inference+serving" alt="Introduction" />
</a>

<br/>

<img src="https://img.shields.io/badge/NIT_Rourkela-B.Tech_CSE_%C2%B7_2029-c4a7e7?style=flat-square&labelColor=191724" alt="NIT Rourkela, B.Tech CSE, class of 2029" />
<img src="https://img.shields.io/badge/Focus-Backend_%C2%B7_Inference-9ccfd8?style=flat-square&labelColor=191724" alt="Focus: backend and inference" />
<img src="https://img.shields.io/badge/Status-Open_to_internships-f6c177?style=flat-square&labelColor=191724" alt="Open to internships" />

</div>

<br/>

## About

I am a Computer Science undergraduate at **NIT Rourkela** who learns by building production-style systems end to end. I pay particular attention to how systems behave under failure: delivery guarantees, retries, idempotency, leases, and crash recovery. Significant design decisions are recorded as Architecture Decision Records, documenting the alternatives considered and the trade-offs accepted.

<table width="100%">
<tr>
<td width="33%" valign="top" align="center">
<b>Now</b><br/><br/>
Building <b>Helmrun</b>, a distributed runtime for AI agents
</td>
<td width="33%" valign="top" align="center">
<b>Next</b><br/><br/>
LLM inference serving, with engine-level projects
</td>
<td width="33%" valign="top" align="center">
<b>Always</b><br/><br/>
Data structures and algorithms, practised weekly
</td>
</tr>
</table>

<br/>

## Featured Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

### Helmrun

<img src="https://img.shields.io/badge/In_development-f6c177?style=flat-square" alt="In development" />
<img src="https://img.shields.io/badge/Private-6e6a86?style=flat-square" alt="Private" />

A distributed platform for executing AI agents, with asynchronous scheduling, multi-provider LLM support, MCP and tool integration, isolated runtimes, durable run state, retries, cancellation, checkpointing, and crash recovery.

**Architecture highlights**
- PostgreSQL as the single source of truth
- Amazon SQS behind a transactional outbox
- One isolated Kubernetes Job per attempt
- SSRF-hardened HTTP tooling
- End-to-end tracing with OpenTelemetry

`TypeScript` `PostgreSQL` `SQS` `Kubernetes` `Redis`

</td>
<td width="50%" valign="top">

### [Tessera](https://github.com/prometheus-97/Tessera)

<img src="https://img.shields.io/badge/Design_phase-9ccfd8?style=flat-square" alt="Design phase" />
<img src="https://img.shields.io/badge/Public-31748f?style=flat-square" alt="Public" />

A distributed video processing platform that accepts large uploads, transcodes them into multiple quality levels, and prepares them for reliable streaming through horizontally scalable background workers.

**Focus areas**
- Resumable uploads
- Job pipelines and background processing
- Adaptive bitrate streaming
- Horizontally scalable workers

`Distributed Systems` `Background Jobs` `Streaming`

</td>
</tr>
</table>

<br/>

## Tech Stack

<table width="100%">
<tr>
<td width="28%"><b>Languages and Runtime</b></td>
<td><img src="https://skillicons.dev/icons?i=ts,js,nodejs&theme=dark" alt="TypeScript, JavaScript, Node.js" /></td>
</tr>
<tr>
<td><b>Backend and Data</b></td>
<td><img src="https://skillicons.dev/icons?i=express,nextjs,postgres,redis&theme=dark" alt="Express, Next.js, PostgreSQL, Redis" /></td>
</tr>
<tr>
<td><b>DevOps and Tooling</b></td>
<td><img src="https://skillicons.dev/icons?i=docker,githubactions,vitest,git,linux,pnpm&theme=dark" alt="Docker, GitHub Actions, Vitest, Git, Linux, pnpm" /></td>
</tr>
<tr>
<td><b>Currently Learning</b></td>
<td><img src="https://skillicons.dev/icons?i=kubernetes,aws,terraform,prometheus,grafana&theme=dark" alt="Kubernetes, AWS, Terraform, Prometheus, Grafana" /></td>
</tr>
</table>

<br/>

## Roadmap: LLM Inference

<table width="100%">
<tr>
<td width="50%" valign="top" align="center">
<b>Serving</b> &nbsp;<sub>primary focus</sub><br/><br/>
<img src="https://skillicons.dev/icons?i=python,go&theme=dark" alt="Python, Go" /><br/><br/>
<img src="https://img.shields.io/badge/vLLM-191724?style=flat-square" alt="vLLM" />
<img src="https://img.shields.io/badge/SGLang-191724?style=flat-square" alt="SGLang" />
<img src="https://img.shields.io/badge/Triton_Inference_Server-191724?style=flat-square&logo=nvidia&logoColor=76B900" alt="NVIDIA Triton Inference Server" />
<img src="https://img.shields.io/badge/KServe-191724?style=flat-square" alt="KServe" />
</td>
<td width="50%" valign="top" align="center">
<b>Engines</b> &nbsp;<sub>project work</sub><br/><br/>
<img src="https://skillicons.dev/icons?i=python,pytorch&theme=dark" alt="Python, PyTorch" /><br/><br/>
<img src="https://img.shields.io/badge/KV_Cache-191724?style=flat-square" alt="KV cache" />
<img src="https://img.shields.io/badge/Continuous_Batching-191724?style=flat-square" alt="Continuous batching" />
<img src="https://img.shields.io/badge/Paged_Attention-191724?style=flat-square" alt="Paged attention" />
<img src="https://img.shields.io/badge/Triton_Kernels-basics-6e6a86?style=flat-square&labelColor=191724" alt="OpenAI Triton kernels, basics" />
</td>
</tr>
</table>

<br/>

## GitHub Activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=prometheus-97&theme=rose-pine&hide_border=true&border_radius=10" alt="Contribution streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=prometheus-97&bg_color=191724&color=c4a7e7&line=31748f&point=e0def4&area=true&hide_border=true&radius=10" width="100%" alt="Contribution graph" />

</div>

<br/>

<div align="center">

<a href="https://github.com/prometheus-97"><img src="https://img.shields.io/badge/GitHub-prometheus--97-191724?style=for-the-badge&logo=github&logoColor=e0def4" alt="GitHub" /></a>

<sub>Open to backend and infrastructure engineering internships.</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:c4a7e7,50:31748f,100:191724&height=110&section=footer" width="100%" alt="" />
