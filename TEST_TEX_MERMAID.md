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

Another small updates: `**Note**` (case-sensitive) at the beginning of blockquotes will be transformed to a blue one with icon.

> **Note** xxx
> > **Note** what about inner ones?
> 
> **Note** well, it is easy to write a regex though --
> ```rb
> /^>\s*\*\*Note\*\*/
> ```
