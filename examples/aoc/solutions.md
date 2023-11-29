[2017 day 1](https://squint-cljs.github.io/squint/?boilerplate=https%3A%2F%2Fgist.githubusercontent.com%2Fborkdude%2Fcf94b492d948f7f418aa81ba54f428ff%2Fraw%2Fa64b304b4025cceb1fefc0acd2812692a2dcdb9c%2Faoc_ui.cljs&src=OzsgSGVscGVyIGZ1bmN0aW9uczoKOzsgKGZldGNoLWlucHV0IHllYXIgZGF5KSAtIGdldCBBT0MgaW5wdXQKOzsgKGFwcGVuZCBzdHIpIC0gYXBwZW5kIHN0ciB0byBET00KOzsgKHNweSB4KSAtIGxvZyB4IHRvIGNvbnNvbGUgYW5kIHJldHVybiB4CgooZGVmIGlucHV0IChzdHIvdHJpbSAoanMtYXdhaXQgKGZldGNoLWlucHV0IDIwMTcgMSkpKSkKCihkZWZuIGNoYXItY29kZSBbY2hhcl0KICAjPyg6Y2xqIChpbnQgY2hhcikKICAgICA6Y2xqcyAoLmNoYXJDb2RlQXQgY2hhciAwKSkpCgooY29tbWVudAogIChjaGFyLWNvZGUgXGEpCiAgKQoKKGRlZm4tIGNzLT5udW1zIFtjc10KICAobWFwdiAjKC0gKGNoYXItY29kZSAlKSAoY2hhci1jb2RlIFwwKSkgY3MpKQoKKGNvbW1lbnQKICAoY3MtPm51bXMgaW5wdXQpCiAgKQoKKGRlZm4gc29sdmUxIFtjc10KICAobGV0IFtucyAoY3MtPm51bXMgY3MpCiAgICAgICAgYyAoZmlyc3QgbnMpXQogICAgKC0%2BPiAoY29uY2F0IG5zIFtjXSkKICAgICAgKHBhcnRpdGlvbiAyIDEpCiAgICAgIChmaWx0ZXIgKGZuIFtbeCB5XV0gKD0geCB5KSkpCiAgICAgIChtYXAgZmlyc3QpCiAgICAgIChhcHBseSArKSkpKQoKKGRlZm4gc29sdmUyIFtjc10KICAobGV0IFtsZW4gKGNvdW50IGNzKQogICAgICAgIG5zIChjeWNsZSAoY3MtPm51bXMgY3MpKV0KICAgICgtPj4gKG1hcCBsaXN0IG5zIChkcm9wIChxdW90IGxlbiAyKSBucykpCiAgICAgICAgICh0YWtlIGxlbikKICAgICAgICAgKGZpbHRlciAoZm4gW1t4IHldXSAoPSB4IHkpKSkKICAgICAgICAgKG1hcCBmaXJzdCkKICAgICAgICAgKGFwcGx5ICspKSkpCgojXyhzb2x2ZTEgaW5wdXQpCihzb2x2ZTIgaW5wdXQp&repl=true) based on [this](https://github.com/borkdude/advent-of-cljc/blob/master/src/aoc/y2017/d01/athos.cljc) solution

[2017 day 2](https://squint-cljs.github.io/squint/?boilerplate=https%3A%2F%2Fgist.githubusercontent.com%2Fborkdude%2Fcf94b492d948f7f418aa81ba54f428ff%2Fraw%2Fa64b304b4025cceb1fefc0acd2812692a2dcdb9c%2Faoc_ui.cljs&src=OzsgSGVscGVyIGZ1bmN0aW9uczoKOzsgKGZldGNoLWlucHV0IHllYXIgZGF5KSAtIGdldCBBT0MgaW5wdXQKOzsgKGFwcGVuZCBzdHIpIC0gYXBwZW5kIHN0ciB0byBET00KOzsgKHNweSB4KSAtIGxvZyB4IHRvIGNvbnNvbGUgYW5kIHJldHVybiB4CgooY29tbWVudAogICh3YXJuLW9uLWxhenktcmV1c2FnZSEpCiAgKQoKKGRlZiBpbnB1dCAoLT4%2BIChqcy1hd2FpdCAoZmV0Y2gtaW5wdXQgMjAxNyAyKSkKICAgICAgICAgICAgICNfc3B5CiAgICAgICAgICAgICBzdHIvdHJpbQogICAgICAgICAgICAgc3RyL3NwbGl0LWxpbmVzKSkKCihkZWZuLSBsaW5lLW51bXMgW2xpbmVdCiAgKGpzL0pTT04ucGFyc2UgKHN0ciAiWyIgKHN0ci9yZXBsYWNlIGxpbmUgIlx0IiAiLCIpICJdIikpKQoKKGNvbW1lbnQKICAobGluZS1udW1zIChmaXJzdCBpbnB1dCkpCiAgKQoKKGRlZm4gc29sdmUxIFtsaW5lc10KICAobGV0Zm4gWyhsaW5lLWRpZmYgW2xpbmVdCiAgICAgICAgICAgICgtPj4gKGxpbmUtbnVtcyBsaW5lKQogICAgICAgICAgICAgIHNweQogICAgICAgICAgICAgICgoanV4dCAjKGFwcGx5IG1heCAlKSAjKGFwcGx5IG1pbiAlKSkpCiAgICAgICAgICAgICAgKGFwcGx5IC0pKSldCiAgICAodHJhbnNkdWNlIChtYXAgbGluZS1kaWZmKSArIDAgbGluZXMpKSkKCihjb21tZW50CiAgKHNvbHZlMSBpbnB1dCkKICApCgooZGVmbiBzb2x2ZTIgW2xpbmVzXQogIChsZXRmbiBbKGxpbmUtZGl2IFtsaW5lXQogICAgICAgICAgICAoZmlyc3QKICAgICAgICAgICAgICAoZm9yIFtbeCAmIHlzXSAoLT4%2BIChsaW5lLW51bXMgbGluZSkKICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgIChpdGVyYXRlIChjb21wIHZlYyByZXN0KSkKICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICh0YWtlLXdoaWxlIHNlcSkpCiAgICAgICAgICAgICAgICAgICAgeSB5cwogICAgICAgICAgICAgICAgICAgIDp3aGVuIChvciAoemVybz8gKG1vZCB4IHkpKQogICAgICAgICAgICAgICAgICAgICAgICAgICAoemVybz8gKG1vZCB5IHgpKSldCiAgICAgICAgICAgICAgICAoLyAobWF4IHggeSkgKG1pbiB4IHkpKSkpKV0KICAgICh0cmFuc2R1Y2UgKG1hcCBsaW5lLWRpdikgKyAwIGxpbmVzKSkpCgooY29tbWVudAogIChzb2x2ZTIgaW5wdXQpCiAgKQ%3D%3D&repl=true)

[2017 day 3](https://squint-cljs.github.io/squint/?boilerplate=https%3A%2F%2Fgist.githubusercontent.com%2Fborkdude%2Fcf94b492d948f7f418aa81ba54f428ff%2Fraw%2Fa64b304b4025cceb1fefc0acd2812692a2dcdb9c%2Faoc_ui.cljs&repl=true&src=OzsgSGVscGVyIGZ1bmN0aW9uczoKOzsgKGZldGNoLWlucHV0IHllYXIgZGF5KSAtIGdldCBBT0MgaW5wdXQKOzsgKGFwcGVuZCBzdHIpIC0gYXBwZW5kIHN0ciB0byBET00KOzsgKHNweSB4KSAtIGxvZyB4IHRvIGNvbnNvbGUgYW5kIHJldHVybiB4CgooZGVmIGlucHV0IChwYXJzZS1sb25nCiAgICAgICAgICAgICAoc3RyL3RyaW0gKGpzLWF3YWl0IChmZXRjaC1pbnB1dCAyMDE3IDMpKSkpKQoKKGRlZiBkaXJlY3Rpb25zCiAgIkluZml0ZSBzZXEgb2YgZGlyZWN0aW9ucyB0aHJvdWdoCiAgc3BpcmFsOiA6cmlnaHQgOnVwIDpsZWZ0IDpsZWZ0IDpkb3duLCBldGMuIgogIChsZXQgW2RpcnMgKGN5Y2xlIFtbOnJpZ2h0IDp1cF0gWzpsZWZ0IDpkb3duXV0pCiAgICAgICAgYW1vdW50IChtYXAgaW5jIChyYW5nZSkpXQogICAgKG1hcGNhdCAoZm4gW1tkMSBkMl0gYW1vdW50XQogICAgICAgICAgICAgIChjb25jYXQgKHJlcGVhdCBhbW91bnQgZDEpCiAgICAgICAgICAgICAgICAocmVwZWF0IGFtb3VudCBkMikpKQogICAgICBkaXJzCiAgICAgIGFtb3VudCkpKQoKKGNvbW1lbnQKICAodmVjICh0YWtlIDEwIGRpcmVjdGlvbnMpKQogICkKCihkZWZuIG5leHQtdGlsZQogICJDYWxjdWxhdGVzIChuKzEpdGggdGlsZSBmcm9tIG50aCB0aWxlIiAKICBbdGlsZSBkaXJlY3Rpb25dCiAgKGxldCBbW2F4aXMgZGVsdGFdCiAgICAgICAgKGNhc2UgZGlyZWN0aW9uCiAgICAgICAgICA6cmlnaHQgWzp4IDFdCiAgICAgICAgICA6bGVmdCBbOnggLTFdCiAgICAgICAgICA6ZG93biBbOnkgMV0KICAgICAgICAgIDp1cCBbOnkgLTFdKV0KICAgICh1cGRhdGUgdGlsZSBheGlzICsgZGVsdGEpKSkKCihkZWZuIHRpbGUtYXQKICAiUmV0dXJucyBudGggdGlsZSBpbiBzcGlyYWwiIAogIFtuXQogIChyZWR1Y2UgbmV4dC10aWxlCiAgICB7OnggMCA6eSAwfQogICAgKHRha2UgKGRlYyBuKQogICAgICBkaXJlY3Rpb25zKSkpCgooZGVmbiBzb2x2ZS0xIFtdCiAgKGxldCBbdGlsZSAodGlsZS1hdCBpbnB1dCldCiAgICAoKyAoanMvTWF0aC5hYnMgKDp4IHRpbGUpKQogICAgICAoanMvTWF0aC5hYnMgKDp5IHRpbGUpKSkpKQoKKGNvbW1lbnQKICAoc29sdmUtMSkKICApCgooZGVmbiBzdW0tb2YtbmVpZ2hib3VycwogICJTdW0gb2YgbmVpZ2hib3VyaW5nIHRpbGVzIiAKICBbezprZXlzIFt4IHldfQogICB0aWxlc10KICAobGV0IFtuZWlnaGJvdXItcG9zaXRpb25zCiAgICAgICAgKGZvciBbZHggWy0xIDAgMV0KICAgICAgICAgICAgICBkeSBbLTEgMCAxXQogICAgICAgICAgICAgIDp3aGVuIChub3Q9IDAgZHggZHkpXQogICAgICAgICAgWygrIHggZHgpCiAgICAgICAgICAgKCsgeSBkeSldKQogICAgICAgIG5laWdoYm91cnMgKGtlZXAgIyhnZXQgdGlsZXMgJSkKICAgICAgICAgICAgICAgICAgICAgbmVpZ2hib3VyLXBvc2l0aW9ucyldCiAgICAocmVkdWNlICsgKG1hcCA6diBuZWlnaGJvdXJzKSkpKQoKKGRlZm4gdGlsZS13aXRoLWJpZ2dlci1zdW0KICAiUmV0dXJucyBmaXJzdCB0aWxlIHdpdGggc3VtID4gbiIgCiAgW25dCiAgKGxldCBbaW5pdC10aWxlIHs6eCAwIDp5IDAgOnYgMX1dCiAgICAobG9vcCBbdGlsZSBpbml0LXRpbGUKICAgICAgICAgICB0aWxlcyB7IjAsMCIgaW5pdC10aWxlfQogICAgICAgICAgIGRpcmVjdGlvbnMgZGlyZWN0aW9uc10KICAgICAgKGxldCBbbmV4dC1kaXJlY3Rpb24gKGZpcnN0IGRpcmVjdGlvbnMpCiAgICAgICAgICAgIG5ldy10aWxlIChuZXh0LXRpbGUgdGlsZSBuZXh0LWRpcmVjdGlvbikKICAgICAgICAgICAgc3VtIChzdW0tb2YtbmVpZ2hib3VycwogICAgICAgICAgICAgICAgICBuZXctdGlsZQogICAgICAgICAgICAgICAgICB0aWxlcykKICAgICAgICAgICAgbmV3LXRpbGUgKGFzc29jIG5ldy10aWxlIDp2IHN1bSldCiAgICAgICAgKGlmICg%2BIHN1bSBuKQogICAgICAgICAgbmV3LXRpbGUKICAgICAgICAgIChyZWN1ciBuZXctdGlsZQogICAgICAgICAgICAoYXNzb2MgdGlsZXMgWyg6eCBuZXctdGlsZSkKICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICg6eSBuZXctdGlsZSldCiAgICAgICAgICAgICAgbmV3LXRpbGUpCiAgICAgICAgICAgIChyZXN0IGRpcmVjdGlvbnMpKSkpKSkpCgooZGVmbiBzb2x2ZS0yIFtdCiAgKDp2ICh0aWxlLXdpdGgtYmlnZ2VyLXN1bSBpbnB1dCkpKQoKKGNvbW1lbnQKICAoc29sdmUtMikp)

[2017 day 4](https://squint-cljs.github.io/squint/?boilerplate=https%3A%2F%2Fgist.githubusercontent.com%2Fborkdude%2Fcf94b492d948f7f418aa81ba54f428ff%2Fraw%2Fa64b304b4025cceb1fefc0acd2812692a2dcdb9c%2Faoc_ui.cljs&repl=true&src=OzsgSGVscGVyIGZ1bmN0aW9uczoKOzsgKGZldGNoLWlucHV0IHllYXIgZGF5KSAtIGdldCBBT0MgaW5wdXQKOzsgKGFwcGVuZCBzdHIpIC0gYXBwZW5kIHN0ciB0byBET00KOzsgKHNweSB4KSAtIGxvZyB4IHRvIGNvbnNvbGUgYW5kIHJldHVybiB4CgooZGVmIGlucHV0CiAgKC0%2BPgogICAgKGpzLWF3YWl0IChmZXRjaC1pbnB1dCAyMDE3IDQpKQogICAgc3RyL3RyaW0pKQoKKGRlZm4gdmFsaWQtcGFzc3BocmFzZT8gW3NdCiAgKGxldCBbd29yZHMgKHN0ci9zcGxpdCBzICMiXHMrIildCiAgICAoPSAoY291bnQgd29yZHMpIChjb3VudCAoaW50byAje30gd29yZHMpKSkpKQoKKGRlZm4gc3RyaWN0LXBhc3NwaHJhc2U%2FIFtzXQogIChsZXQgW3dvcmRzIChzdHIvc3BsaXQgcyAjIlxzKyIpCiAgICAgICAgY2hhcnNldHMgKGludG8gI3t9IChtYXAgKGNvbXAgc3RyL2pvaW4gc29ydCkgd29yZHMpKV0KICAgICg9IChjb3VudCB3b3JkcykgKGNvdW50IGNoYXJzZXRzKSkpKQoKKGRlZm4gcGFydC0xCiAgW10KICAoLT4%2BIChzdHIvc3BsaXQgaW5wdXQgIyJcbiIpCiAgICAoZmlsdGVyIHZhbGlkLXBhc3NwaHJhc2U%2FKQogICAgY291bnQpKQoKKGNvbW1lbnQKICAocGFydC0xKQogICkKCihkZWZuIHBhcnQtMgogIFtdCiAgKC0%2BPiAoc3RyL3NwbGl0IGlucHV0ICMiXG4iKQogICAgKGZpbHRlciBzdHJpY3QtcGFzc3BocmFzZT8pCiAgICBjb3VudCkpCgooY29tbWVudAogIChwYXJ0LTIpCiAgKQ%3D%3D)

[2017 day 5](https://squint-cljs.github.io/squint/?boilerplate=https%3A%2F%2Fgist.githubusercontent.com%2Fborkdude%2Fcf94b492d948f7f418aa81ba54f428ff%2Fraw%2Fa64b304b4025cceb1fefc0acd2812692a2dcdb9c%2Faoc_ui.cljs&repl=true&src=OzsgSGVscGVyIGZ1bmN0aW9uczoKOzsgKGZldGNoLWlucHV0IHllYXIgZGF5KSAtIGdldCBBT0MgaW5wdXQKOzsgKGFwcGVuZCBzdHIpIC0gYXBwZW5kIHN0ciB0byBET00KOzsgKHNweSB4KSAtIGxvZyB4IHRvIGNvbnNvbGUgYW5kIHJldHVybiB4CgooZGVmIGlucHV0IChzdHIvdHJpbSAoanMtYXdhaXQgKGZldGNoLWlucHV0IDIwMTcgNSkpKSkKCihkZWZuIHNvbHZlLTEgW10KICAobG9vcCBbbWF6ZSAoaW50byBbXQogICAgICAgICAgICAgICAgKG1hcCAjKHBhcnNlLWxvbmcgJSkpCiAgICAgICAgICAgICAgICAoc3RyL3NwbGl0LWxpbmVzIGlucHV0KSkKICAgICAgICAgY3VyLXBvcyAwCiAgICAgICAgIHN0ZXBzIDBdCiAgICAoaWYtbGV0IFtjdXItdmFsIChnZXQgbWF6ZSBjdXItcG9zKV0KICAgICAgKGxldCBbbmV4dC1tYXplIChhc3NvYyBtYXplIGN1ci1wb3MgKGluYyBjdXItdmFsKSkKICAgICAgICAgICAgbmV4dC1wb3MgKCsgY3VyLXBvcyBjdXItdmFsKV0KICAgICAgICAocmVjdXIgbmV4dC1tYXplIG5leHQtcG9zIChpbmMgc3RlcHMpKSkKICAgICAgc3RlcHMpKSkKCihjb21tZW50CiAgKHNvbHZlLTEpCiAgKQoKKGRlZm4gc29sdmUtMiBbXQogIChsZXQgW15pbnRzIG1hemUKICAgICAgICAoLT4%2BCiAgICAgICAgIChpbnRvIFtdCiAgICAgICAgICAgICAgIChtYXAgIyhwYXJzZS1sb25nICUpKQogICAgICAgICAgICAgICAoc3RyL3NwbGl0LWxpbmVzIGlucHV0KSkKICAgICAgICAgKGludG8tYXJyYXkgIz8oOmNsaiBJbnRlZ2VyL1RZUEUpKSkKICAgICAgICBsZW5ndGggXmludCAoYWxlbmd0aCBtYXplKV0KICAgIChsb29wIFtjdXItcG9zIDAKICAgICAgICAgICBzdGVwcyAwXQogICAgICAoaWYgKDwgY3VyLXBvcyBsZW5ndGgpCiAgICAgICAgKGxldCBbY3VyLXZhbCAoYWdldCBtYXplIGN1ci1wb3MpXQogICAgICAgICAgKGlmICh6ZXJvPyBjdXItdmFsKQogICAgICAgICAgICAoZG8KICAgICAgICAgICAgICAoZG90byBtYXplCiAgICAgICAgICAgICAgICAoYXNldCBjdXItcG9zIDIpKQogICAgICAgICAgICAgIChyZWN1cgogICAgICAgICAgICAgICAoaW5jIGN1ci1wb3MpCiAgICAgICAgICAgICAgICgrIHN0ZXBzIDIpKSkKICAgICAgICAgICAgKGRvIChkb3RvIG1hemUKICAgICAgICAgICAgICAgICAgKGFzZXQKICAgICAgICAgICAgICAgICAgIGN1ci1wb3MKICAgICAgICAgICAgICAgICAgIChpZiAoPj0gY3VyLXZhbCAzKQogICAgICAgICAgICAgICAgICAgICAoZGVjIGN1ci12YWwpCiAgICAgICAgICAgICAgICAgICAgIChpbmMgY3VyLXZhbCkpKSkKICAgICAgICAgICAgICAgIChyZWN1cgogICAgICAgICAgICAgICAgICgrIGN1ci1wb3MgY3VyLXZhbCkKICAgICAgICAgICAgICAgICAoaW5jIHN0ZXBzKSkpKSkKICAgICAgICBzdGVwcykpKSkKCihjb21tZW50CiAgKHNvbHZlLTIpKQ%3D%3D)

[2017 day 6](https://squint-cljs.github.io/squint/?boilerplate=https%3A%2F%2Fgist.githubusercontent.com%2Fborkdude%2Fcf94b492d948f7f418aa81ba54f428ff%2Fraw%2Fa64b304b4025cceb1fefc0acd2812692a2dcdb9c%2Faoc_ui.cljs&repl=true&src=OzsgSGVscGVyIGZ1bmN0aW9uczoKOzsgKGZldGNoLWlucHV0IHllYXIgZGF5KSAtIGdldCBBT0MgaW5wdXQKOzsgKGFwcGVuZCBzdHIpIC0gYXBwZW5kIHN0ciB0byBET00KOzsgKHNweSB4KSAtIGxvZyB4IHRvIGNvbnNvbGUgYW5kIHJldHVybiB4CgooZGVmIGlucHV0ICgtPj4gKGpzLWF3YWl0IChmZXRjaC1pbnB1dCAyMDE3IDYpKQogICAgICAgICAgICAgI19zcHkKICAgICAgICAgICAgIHN0ci90cmltKSkKCihkZWZuIGRhdGEgW10KICAoYXMtPiBpbnB1dCAkCiAgICAoc3RyL3NwbGl0ICQgIyJccyIpCiAgICAobWFwdiBwYXJzZS1sb25nICQpKSkKCihkZWZuIGZpcnN0LW1heC1wb3MKICBbbnVtc10KICAocmVkdWNlIChmbiBbW18gbWF4LXZhbCA6YXMgbV0KICAgICAgICAgICAgICAgW18gY3VyLXZhbCA6YXMgY11dCiAgICAgICAgICAgIChpZiAoPiBjdXItdmFsIG1heC12YWwpCiAgICAgICAgICAgICAgYyBtKSkKICAgIChtYXAgdmVjdG9yIChyYW5nZSkgbnVtcykpKQoKKGRlZm4gbmV4dC1wb3MKICBbc3RhdGUgY3VyLXBvc10KICAobW9kIChpbmMgY3VyLXBvcykgKGNvdW50IHN0YXRlKSkpCgooZGVmbiBuZXh0LXN0YXRlCiAgW3N0YXRlXQogIChsZXQgW1ttYXgtcG9zIG1heC12YWxdIChmaXJzdC1tYXgtcG9zIHN0YXRlKQogICAgICAgIGRpc3Qtc2l6ZSAoLT4KICAgICAgICAgICAgICAgICAgICAoLyBtYXgtdmFsIChjb3VudCBzdGF0ZSkpCiAgICAgICAgICAgICAgICAgICAganMvTWF0aC5jZWlsKV0KICAgIChsb29wIFtzdGF0ZSBzdGF0ZQogICAgICAgICAgIHBvcyAobmV4dC1wb3Mgc3RhdGUgbWF4LXBvcyldCiAgICAgIChsZXQgW2xlZnQgKGdldCBzdGF0ZSBtYXgtcG9zKV0KICAgICAgICAoaWYgKG9yCiAgICAgICAgICAgICAgKHplcm8%2FIGxlZnQpCiAgICAgICAgICAgICAgKD0gcG9zIG1heC1wb3MpKQogICAgICAgICAgc3RhdGUKICAgICAgICAgIChyZWN1cgogICAgICAgICAgICAoLT4KICAgICAgICAgICAgICBzdGF0ZQogICAgICAgICAgICAgICh1cGRhdGUgcG9zICsgZGlzdC1zaXplKQogICAgICAgICAgICAgICh1cGRhdGUgbWF4LXBvcyAtIGRpc3Qtc2l6ZSkpCiAgICAgICAgICAgIChuZXh0LXBvcyBzdGF0ZSBwb3MpKSkpKSkpCgooZGVmbiBzdGF0ZS1rZXkgW3N0YXRlXQogIChzdHIvam9pbiAiLCIgc3RhdGUpKQoKKGRlZm4gc29sdmUKICBbZGF0YV0KICAobG9vcCBbc3RhdGVzIHsoc3RhdGUta2V5IGRhdGEpIGRhdGF9CiAgICAgICAgIHN0YXRlIGRhdGEKICAgICAgICAgbiAxXQogICAgKGxldCBbc3RhdGUnIChuZXh0LXN0YXRlIHN0YXRlKQogICAgICAgICAgayAoc3RhdGUta2V5IHN0YXRlJyldCiAgICAgIChpZiAoY29udGFpbnM%2FIHN0YXRlcyBrKQogICAgICAgIFtzdGF0ZScgbl0KICAgICAgICAocmVjdXIgKGFzc29jIHN0YXRlcyBrIHN0YXRlJykKICAgICAgICAgIHN0YXRlJwogICAgICAgICAgKGluYyBuKSkpKSkpCgooZGVmbiBzb2x2ZS0xIFtdCiAgKHNlY29uZCAoc29sdmUgKGRhdGEpKSkpCgooZGVmbiBzb2x2ZS0yIFtdCiAgKHNlY29uZCAoc29sdmUgKGZpcnN0IChzb2x2ZSAoZGF0YSkpKSkpKQoKKGNvbW1lbnQKICAodGltZSAoc29sdmUtMSkpCiAgKHRpbWUgKHNvbHZlLTIpKQogICk%3D)