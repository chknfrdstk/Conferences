# Enterprise Kubernetes at Home: A Homelabber's Guide to OKD — Thomas Cameron

Texas Linux Fest 2026 — November 6–7, 2026, JJ Pickle Research Campus, Austin, TX

Summaries verified live November 12, 2026 from the Texas Linux Fest YouTube channel @texaslinuxfest3002, cross-checked against the official pretalx schedule. View counts and upload dates are as of November 12, 2026. Upload date is inferred from YouTube's "2 days ago" at the time of checking.

- **Video title (YouTube):** "Texas Linux Festival 2026-11-07: Enterprise Kubernetes at Home A Homelabbers Guide to OKD"
- **URL:** [https://www.youtube.com/watch?v=Ztc0k-HjM5Q](https://www.youtube.com/watch?v=Ztc0k-HjM5Q)
- **Duration:** 52:19 · **Uploaded:** November 10, 2026 (inferred) · Views at check: 32
- **Description (YouTube):** not verified — the video page could not be loaded at check time, so the description is unknown, not confirmed empty.
- **Repository:** [https://github.com/ryanhay/ocp4-metal-install](https://github.com/ryanhay/ocp4-metal-install) — Install OpenShift 4 on Bare Metal UPI, credited in Cameron's deck; and [https://github.com/okd-project/okd](https://github.com/okd-project/okd) — OKD itself
- **Content:** How to run OKD — the community distribution of OpenShift — at home, set up as close as possible to an enterprise network. The build uses 8 virtual machines across two networks: a production network (172.31.100.0/24) and a private network for the OKD cluster (10.31.100.0/24), connected by a VM running HAProxy (kickstarted from the production network), plus NFS for storage. Cameron credits Ryan Hay, whose video and instructions he first used several years ago and has updated since ([https://github.com/ryanhay/ocp4-metal-install](https://github.com/ryanhay/ocp4-metal-install)). Slides: [https://people.redhat.com/tcameron/TXLF-2026/OKD_TXLF_2026.pdf](https://people.redhat.com/tcameron/TXLF-2026/OKD_TXLF_2026.pdf) — note the slides list Thomas Cameron as sole author. Correction to earlier notes: pretalx lists Thomas Cameron alone for this talk; Neal Gompa was presenting a different, simultaneous talk at the same 3:00 PM slot ("Transactional Systems in the Fedora Ecosystem" with Shawn W Dunn, Balcones), not co-presenting OKD. The TXLF pretalx abstract itself could not be retrieved. Pretalx: Saturday 3:00 PM, Lil Tex.
- **Most useful for:** homelabbers wanting enterprise-style Kubernetes at home; anyone weighing OKD / single-node OKD, KubeVirt, and GPU passthrough questions.
