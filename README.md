# Astro Backgrounds

Example code:

```astro
---
import Layout from "../layouts/Layout.astro";

import Backgrounds from "@ilijazm/astro-styled-background-components";
---

<Layout>
  <section
    class="relative flex justify-center items-center py-96 overflow-hidden"
  >
    <Backgrounds.WavyBackground />
    <h1 class="text-display-1 text-white font-mono">
      &lt;WavyBackground /&gt;
    </h1>
  </section>
</Layout>
```

Example results:

![WavyBackground](docs/WavyBackground.png)
