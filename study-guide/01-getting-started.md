## Getting started{{attrs[#blk-mdgi19f8j8yx]}}

Welcome to **test3**. This is your first study-guide section — replace it
with your own material. Each section keeps a permanent invisible label (the
`{{attrs[#…]}}` marker) so worksheets and slides generated from it stay
connected even as you edit.

Chemistry notation works out of the box: H~2~O, CO~3~^2-^, and equations like
$K_a = \frac{[\mathrm{H^+}][\mathrm{A^-}]}{[\mathrm{HA}]}$.

Fly worker rebuilt with orz-mdhtml@0.6.0 and redeployed — machine healthy, health check ✔, DNS verified. /health → {"ok":true,...} (HTTP 200).

::: info
The transient "not listening on 0.0.0.0:8080" line is the same rolling-update warning as last time; the health check passed after it.
:::

The whole chain is now shipped:

:::: cols
::: col
**Host half**

editor-kit createHostAIClient + Alembic wiring (Vercel, auto-deployed).
:::
::: col
**File half**

orz-mdhtml@0.6.0 published, and now baked into the worker image.
:::
::::
Worker — generates the .md.html editing surface embedding the new app.js.
Verify it (in your authenticated session)
Open a chapter's study guide → wait for the in-file editor → select a few sentences. The copper "✦ Improve selection" chip should appear; clicking it offers Check spelling & grammar · Improve language · Enrich formatting, each running through the registry + PLATFORM_SCOPE + governance, showing a reviewable suggestion you apply into the selection.
