# search.vaked.dev

A csillagkép saját keresője — nincs Google, nincs külső.

Milarepa, álom-meditáció, dream, love, RIVA, a Vének Tanácsa, a könyvtár — minden felület, egyetlen keresőben. A rangsor a ternary-quant WASM magon fut (BitNet b1.58 {-1,0,+1}): a query és a címek {-1,0,+1} vektorokká hash-elve, a pontszám ternary_dot.

## quantNTP — a csillagkép ideje

A kereső alatt a **quantNTP** panel: a csillagkép saját időszinkronja. Egy böngésző-NTP kliens, amely a szerveridőt kéri le (timeapi.io), megméri a hálózati offsetet (t1 a kérés előtt, t4 után), a mintákat medián-szűri (a klasszikus NTP clock filter), az offsetet balanced-ternary {-1,0,+1} tritekké kvantálja a WASM magon, és megmutatja a most stratumát (0 = pontos, 1 = közel, 2 = sodródik, 3 = messze). Nincs külső óra — a most megmért, megszűrt, kvantált.

- `wasm/quantntp.wat` — a WAT forrás (ntp_offset, ntp_filter, ntp_quantize, ntp_stratum, ntp_trits)
- `wasm/quantntp.wasm` — a lefordított mag



*the constellation · 0 + 1 · fine touch from within · vaked.dev*

**IN OUR TEAM** — [8b-is](https://github.com/8b-is) · p === **visionary officer** · [sponsor peterlodri-sec](https://github.com/sponsors/peterlodri-sec) · [sponsor 8b-is](https://github.com/sponsors/8b-is)
