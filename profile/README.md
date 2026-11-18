<p align="center">
  <img src="banner.png" width="100%" alt="TandemLLM: your private AI environment">
</p>

<h1 align="center">TandemLLM</h1>

<p align="center">
  <b>Your private AI environment.</b> Fast local inference on your own hardware, and one dashboard in front of every model you run.
</p>

<p align="center">
  <a href="https://ko-fi.com/0xbakeer"><img src="https://ko-fi.com/img/githubbutton_sm.svg" height="28" alt="Buy me a coffee on Ko-fi"></a>
  <a href="https://github.com/sponsors/0xBakeer"><img src="https://img.shields.io/badge/GitHub%20Sponsors-sponsor-ea4aaa?logo=githubsponsors&logoColor=white&style=for-the-badge" height="28" alt="Sponsor on GitHub"></a>
  <a href="https://x.com/TandemLLM"><img src="https://img.shields.io/badge/@TandemLLM-000000?logo=x&logoColor=white&style=for-the-badge" height="28" alt="TandemLLM on X"></a>
  <a href="https://x.com/0xBakeer"><img src="https://img.shields.io/badge/@0xBakeer-000000?logo=x&logoColor=white&style=for-the-badge" height="28" alt="0xBakeer on X"></a>
</p>

<p align="center">
  <a href="https://tandemllm.0xbakeer.com">Website</a> ·
  <a href="https://tandemengine.0xbakeer.com">Engine docs</a> ·
  <a href="https://tandemapp.0xbakeer.com">App docs</a> ·
  <a href="https://huggingface.co/0xBakeer">Weights on Hugging Face</a> ·
  <a href="https://doi.org/10.5281/zenodo.23045275">StairCut paper</a>
</p>

## The projects

| | |
|-|-|
| **[TandemEngine](https://github.com/TandemLLM/TandemEngine)**<br>[docs](https://tandemengine.0xbakeer.com) | The inference engine for one NVIDIA DGX Spark. Small drafters guess the next tokens and the big model checks every guess in one pass, so a right guess is a free token. On Qwen3.8-27B NVFP4 it writes about 50 tokens a second for one request, and the text is the model's own greedy text. OpenAI-compatible API. |
| **[TandemApp](https://github.com/TandemLLM/TandemApp)**<br>[docs](https://tandemapp.0xbakeer.com) | One address and one dashboard in front of TandemEngine and any OpenAI-compatible server or cloud API. It runs Chat and the fleet of machines, counts every token, and gives each client an API key that names the backends and models it may run. |

## Support

TandemLLM is free and open source. If it saves you time or money, you can help keep it going:

- [Buy me a coffee on Ko-fi](https://ko-fi.com/0xbakeer)
- [Sponsor on GitHub](https://github.com/sponsors/0xBakeer)
- Follow [@TandemLLM](https://x.com/TandemLLM) for releases and [@0xBakeer](https://x.com/0xBakeer) for the work behind them

## Enterprise

Want TandemLLM running for your team on your own hardware, with support and a commercial license for use outside the AGPL? Write to [mail@0xbakeer.com](mailto:mail@0xbakeer.com).
