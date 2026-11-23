---
layout: about
title: about
permalink: /
subtitle: M.S. Student, <a href='https://ssl.kaist.ac.kr/'>Semiconductor System Lab (SSL)</a>, School of Electrical Engineering, KAIST

profile:
  align: right
  image: jungwan_lee.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>School of Electrical Engineering</p>
    <p>KAIST, Daejeon, Korea</p>
    <p>milelion@kaist.ac.kr</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
---

<style>
  /* On wide screens, place the photo in a right-hand column that starts level with the name. */
  @media (min-width: 576px) {
    .post:has(> article > .profile) {
      display: grid;
      grid-template-columns: minmax(0, 1fr) 30%;
      grid-template-rows: auto 1fr;
      column-gap: 1rem;
    }
    .post:has(> article > .profile) > .post-header {
      grid-column: 1;
      grid-row: 1;
    }
    .post:has(> article > .profile) > article {
      display: contents;
    }
    .post > article > * {
      grid-column: 1 / -1;
    }
    .post > article > .clearfix {
      grid-column: 1;
      grid-row: 2;
    }
    .post > article > .profile {
      grid-column: 2;
      grid-row: 1 / span 2;
      align-self: start;
      float: none;
      width: auto;
      margin-left: 0;
      /* offset by the name's line-height leading so the photo top meets the top of the letters */
      margin-top: 0.6rem;
      margin-top: calc((3rem - 2.5cap) / 2);
    }
  }
</style>

I am an M.S. student in Electrical Engineering at [KAIST](https://www.kaist.ac.kr/), advised by [Prof. Hoi-Jun Yoo](https://ssl.kaist.ac.kr/) in the Semiconductor System Lab (SSL). I received my B.S. in Electrical Engineering with a minor in Computer Science from KAIST (magna cum laude).

My research focuses on **efficient AI inference** across algorithms and hardware, including:

- **Low-bit quantization and model compression** for large language models, covering both weights and KV cache
- **LLM/VLM acceleration** on resource-constrained hardware such as edge FPGAs and mobile SoCs
- **Edge AI systems**, including on-device agentic LLMs for tablet-class devices

Recently, I designed **VectorFLASH**, a long-context LLM accelerator with dual vector quantization on an edge FPGA (A-SSCC 2026). I also co-authored **Slim-Llama** (ISSCC 2025, Hot Chips 2025), a 4.69 mW LLM processor with binary/ternary weights for billion-parameter Llama models.
