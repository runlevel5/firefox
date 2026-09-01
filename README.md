<img width="794" height="261" alt="trung" src="https://github.com/user-attachments/assets/52623c36-2bfa-4c0e-b982-7a62d0d2e3c6" />

[Firefox](https://firefox.com/) is a fast, reliable and private web browser from the non-profit [Mozilla organization](https://mozilla.org/).

This fork add JIT SpiderMonkey and PPC64/PPC64LE VSX optimizations (POWER8, POWER9, Power10). The ESR (Extended Support Release) version also
support VMX optimization for PowerPC970 (PowerMac G5).

The source codes of the work could be found in following Pull Requests

* [Firefox 153 ESR](https://github.com/runlevel5/firefox-ppc64/pull/2)
* [Firefox 155 or newer](https://github.com/runlevel5/firefox-ppc64/pull/1)

There's been already efforts to upstream the work, please see [proposal](https://bugzilla.mozilla.org/show_bug.cgi?id=1860412).
While waiting for the work to be reviewed upstream, users and Linux distribution packagers can adopt the [patches](https://github.com/runlevel5/firefox-ppc64/releases) downstream.

Please report any issue by creating new tickets in [GitHub Issues](https://github.com/runlevel5/firefox-ppc64/issues).
