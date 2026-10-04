<img src="https://raw.githubusercontent.com/Galvarya/.github/main/profile/banner.png" alt="Galvarya — systems that hold their shape" width="100%">

**Galvarya** is a software studio in Romania working across education, distributed
systems and artificial intelligence. Different domains, one discipline: understand
the problem completely, then build the smallest thing that solves it.

**[galvarya.com](https://galvarya.com)**

---

## What we build

### Tomomi — [tomomi.app](https://tomomi.app)

Baccalaureate preparation for Romanian high-school students: the whole exam, on a
phone. Courses follow the official *programă*, the daily plan is computed from
spaced repetition rather than authored, and written work is marked against the
published barem — including a photograph of a page written by hand.

Lessons that need to show a mechanism don't get a video, they get a program. Rust
scene graphs compile to WebAssembly and replay through Skia on the device, at
native frame rates and interactive. The informatics track ships an interpreter for
the C++ subset the exam examines, plus *pseudocod*, so a student can step a program
one statement at a time and watch every variable change — offline, with no server
in the loop.

`Rust` · `WebAssembly` · `React` · `Capacitor` · `Cloudflare Workers` · `D1`

### Soki

Peer-to-peer encrypted notes with no server to trust. Devices are identified by
public key and dial each other directly over QUIC — hole-punched where the network
allows it, relayed where it doesn't. No account, no cloud database, no sign-in.

Notes are CRDT documents, so two devices editing the same paragraph offline both
keep their edits. Every value is encrypted at rest under a key the devices derive
between themselves at pairing, wrapped by the hardware keystore on Android. The
deliberate trade: both devices must be online at the same moment to sync — which is
exactly what removes the need for server-side durability, account recovery, and an
operator who could be compelled to hand anything over.

`Rust` · `iroh` · `Loro` · `redb` · `Tauri` — Linux, macOS, Windows, Android

*In development. Downloads will be linked from [galvarya.com](https://galvarya.com).*

---

## How we work

**Define.** We spend the first weeks reducing the brief until only the real
constraint is left.

**Prototype.** A working slice in front of real users early, so the expensive
decisions are made with evidence.

**Build.** Small teams, short cycles, tests that mean something. Nothing ships that
we would not operate ourselves.

**Hand over.** Documentation, runbooks and a team that can carry it. We aim to
become unnecessary.

---

## Contact

Tell us what is not working — we reply to every message ourselves, usually within
two working days.

**[hello@galvarya.com](mailto:hello@galvarya.com)** · **[galvarya.com](https://galvarya.com)**

<sub>Galvarya · Romania</sub>
