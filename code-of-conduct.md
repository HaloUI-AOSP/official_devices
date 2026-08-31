# HaloUI Maintainers & Team Members Code of Conduct

Maintainers and team members are the public face of HaloUI. This document sets the baseline expected of anyone building, signing, or supporting a device under the HaloUI name.

---

## 1. Conduct
- Be respectful toward teammates, contributors, and users, even in disagreement.
- Personal attacks, harassment, and discriminatory language are not acceptable in any project space.
- Resolve conflicts through discussion, not hostility.

---

## 2. Ownership of Your Device(s)
- Once you claim a device, you're responsible for keeping it updated and working.
- If you're going away, going quiet, or can't keep up, tell the team early rather than letting a device go stale silently.
- Test a build thoroughly and confirm a clean compile before it goes out — don't ship something you haven't run yourself.
- Cap yourself at 1–2 active projects total (HaloUI included) — spreading thinner than that shows in build quality.
- Every maintainer signs their own builds with their own keys — no shared or borrowed signing.
- Device trees belong in the official HaloUI device organization, not a personal fork.

---

## 3. Device Support Rules
- Use erofs for the build when the kernel supports it.
- Drop support for OrangeFox, TWRP, or any other outdated recovery.
- No AI-generated code anywhere in a device tree or kernel.
- HaloUI recovery is the only recovery shipped.
- Nothing that risks permanent hardware damage — overclocking, disabling thermal limits, etc. — ships in any build.
- Root is never included by default.
- On 5.10/Android 12 devices with closed kernel source that are GKI-only, default to the Millennium Common Kernel (KagamiChihiro) unless there's a specific reason not to.

---

## 4. Communication
- Post progress, blockers, and findings where the team can see them.
- Keep project discussion in official channels — side-channel decisions make coordination harder for everyone.
- Give a hand when you can; a maintainer who never helps anyone else drags the team down.
- If you know about a bug or regression, say so before or at release — not after users find it themselves.

---

## 5. Build & Source Quality
- Stick to HaloUI's coding standards and structure.
- Keep your source tree readable and documented, not just working.
- Untested or half-finished code doesn't belong in an official build.
- Changes that touch HaloUI's branding, features, or policies need approval first — that's not a unilateral call.
- Give credit where it's due for kernels, trees, and patches you're building on.

---

## 6. Boundaries
- No pushing changes without going through review.
- HaloUI isn't yours to redistribute, rebrand, or sell.
- Respect licenses — no proprietary code, no code you don't have the right to use.
- Don't add, swap, or strip pre-installed apps or services outside what's already been agreed for HaloUI.

---

## 7. Users & Bug Reports
- Take user reports seriously and respond professionally, even when they're low-quality.
- Push people toward proper bug reports — logs, reproduction steps, device info.
- Investigate before dismissing; "can't reproduce" isn't a first response.
- Anything with real damage potential (thermal, battery, etc.) gets escalated immediately, not queued.

---

## 8. Privacy & Security
- User data is never collected, shared, or used beyond what's necessary.
- Builds should follow standard security practice — no shortcuts that weaken the device.
- Security issues get reported through the proper channel, not posted publicly first.

---

## 9. Going Quiet
- A device with no maintainer activity and no communication for a long stretch may get reassigned or dropped to unofficial status.
- If you're handing off, leave the next maintainer something usable — tree, signing notes, known issues.

---

## 10. What Happens If You Don't Follow This
Violations are handled case by case — a warning, a temporary suspension, or removal from the team, depending on what happened and how serious it was.

---

Being part of HaloUI means holding to this. It's what keeps the project usable, trustworthy, and worth maintaining.

**Thanks for putting in the work for HaloUI. 🌙**
