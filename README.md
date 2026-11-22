# Wildbow Wiki search indexes

Static [Pagefind](https://pagefind.app/) indexes used by the search page on the Wildbow Wiki
(https://wildbow.miraheze.org/). The wiki loads them from jsDelivr:
`https://cdn.jsdelivr.net/gh/wildbow-wiki/wildbow-wiki-search@main/wog/`

- `wog/`: Word of God entries (statements by Wildbow), one result per `WoG:` page on the wiki. Filters: universe,
  serial, source. Built by `scripts/build-wog-index.py` in the wiki's tooling. Until the wiki is public it is built
  from the import file; after launch it should be rebuilt from the wiki itself, so editors' fixes reach search.

The story text index (the serials themselves) comes from [Wooble](https://github.com/MugaSofer/Wooble).

Generated files: don't edit by hand.
