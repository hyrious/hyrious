```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

$ E = mc^2 - \LaTeX $

$$ e^{ \pm i\theta } = \cos \theta \pm i\sin \theta $$

There's a little bug in inline latex expressions, you can only trigger it via either:

- Put no spaces before/after `$` symbols, i.e. `$E=mc^2$` is ok, `$ E=mc^2 $`, `$E=mc^2 $`, `$ E=mc^2$` won't work.
- `$ E=mc^2 $` works if it forms the whole paragraph. (but that's useless, right?)

- - -

> [!Note]
> Highlights information that users should take into account, even when skimming.

> [!important]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.

Test color codes: `#39c5bb`.
