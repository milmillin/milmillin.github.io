---
layout: page
title: Loop Termination Buffer
description: A SystemVerilog implementation of Loop Termination Buffer, an extension to branch predictor, on BlackParrot processor.
img: assets/img/ltb.png
importance: 5
category: class
selected: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ltb.png" title="Loop Termination Buffer" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

I implemented a branch predictor that predicts the branch pattern $$(1^N0)^M$$ where $$N$$ is the inner loop size and $$M$$ is the outer loop size, and successfully integrated to the [BlackParrot](https://github.com/black-parrot/black-parrot) processor. The work is heavily based on a paper [Loop Termination Prediction](https://cseweb.ucsd.edu/~calder/papers/ISHPC2K-LOOP.pdf) by Timothy Sherwood and Brad Calder.

<div class="links">
<a href="https://github.com/milmillin/black-parrot" class="btn btn-sm z-depth-0" role="button">Code</a>
<a href="{{ 'ltb.pdf' | prepend: 'assets/pdf/' | relative_url}}" class="btn btn-sm z-depth-0" role="button">PDF</a>
</div>