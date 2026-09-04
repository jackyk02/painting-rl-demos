# painting-rl-demos

Paintings from an RL run in which `thinkingmachines/Inkling-Small` learns to paint watercolours by
writing [p5.brush](https://github.com/acamposuribe/p5.brush) JavaScript. Each sketch is rendered
headlessly to a PNG and rewarded by a multimodal
[LLM-as-a-Verifier](https://github.com/llm-as-a-verifier/llm-as-a-verifier): paintings from the same
prompt are compared pairwise on a twenty-letter scale, aggregated with a ring pass plus one pivot round.

The site shows ten prompts, each at the four times it came up during the 200 training steps.

* Live: <https://jackyk02.github.io/painting-rl-demos/>
* Training code and full results: <https://github.com/jackyk02/paint-rl>

`index.html` is self-contained: every painting is embedded in the page.
