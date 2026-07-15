# org-ai-assisted

Machine account operated by [@adrelanos](https://github.com/adrelanos).
Repositories here are maintained with AI assistance, and all AI-generated
content is marked as such.

This org hosts code, not discussion. Do not open issues or discussions here.

## Is Kicksecure / Whonix "vibecoded" now?

No. Here is how AI assistance is actually handled.

**AI has no write access to any Kicksecure or Whonix repository.** Code that
could reach those projects is treated as untrusted: assumed malicious until
proven otherwise, and reviewed in depth by a human before a human integrates
it. AI has attempted malicious changes before, which is exactly why it is
treated this way. A large amount of human-written code continues to go into
these projects.

**This org is the sandbox where AI does have write access.** Some repositories
here (for example [`dist-ai`](https://github.com/org-ai-assisted/dist-ai)) are
the AI's own tooling and tests. They are minimally reviewed by design, because
they never ship to users, never enter Kicksecure or Whonix, and run only on
disposable, untrusted CI systems. Treat them the way you would treat any
untrusted analysis tool such as Coverity Scan: something that runs, not output
to trust.

Longer writeup: https://org-ai-assisted.github.io

## What is here

- **Mirrors** of Kicksecure and Whonix components. The canonical source and
  issue tracker for these live upstream, under
  [Kicksecure](https://github.com/Kicksecure) and
  [Whonix](https://github.com/Whonix). Go there.
- **Origin repositories** native to this org, with no upstream mirror:
  - [`dist-ai`](https://github.com/org-ai-assisted/dist-ai) -- the AI test,
    reproduction, and fuzzing tooling.
  - Self-contained reproducers and bug reports:
    [`onion-client-refetch-stall-arti`](https://github.com/org-ai-assisted/onion-client-refetch-stall-arti),
    [`onion-client-refetch-stall-tor`](https://github.com/org-ai-assisted/onion-client-refetch-stall-tor),
    [`onion-grater-bugs`](https://github.com/org-ai-assisted/onion-grater-bugs),
    [`qemu-x86_64-aes-gcm-miscompile-ppc64el`](https://github.com/org-ai-assisted/qemu-x86_64-aes-gcm-miscompile-ppc64el).
  - [`Git-Mediawiki`](https://github.com/org-ai-assisted/Git-Mediawiki) -- a
    patched fork.

## References

- Whonix AI policy discussion: https://forums.whonix.org/t/is-whonix-vibecoded-now/23405
- Build documentation: https://www.kicksecure.com/wiki/Dev/Build_Documentation
