# Connector Catalog

Public catalog of third-party connectors maintained under this account.

## Layout

- `catalog/<slug>.md` — one Markdown file per connector. Each file starts with
  a YAML front-matter block that holds the catalog metadata.

## Front matter fields

| Field | Meaning |
| --- | --- |
| `title` | display name of the connector |
| `slug` | stable identifier, also used in repository names |
| `permalink` | public catalog URL |
| `date` | date the entry was added |
| `publication_status` | one of `draft`, `published`, `released`, `retired` |
| `vendor` | vendor name |
| `vendor_page` | vendor landing page |
| `docs_url` | connector documentation |
| `license_tier` | `community` or `commercial` |
| `edition` | product edition this entry refers to |
| `source_url` | optional link to the public implementation repository |

## Repository naming

Implementation repositories live under the same account and are named
`emails_github_filesystem_playwright_with_chunk_3297-c8d3-<slug>`, i.e. the catalog repository name with its `-catalog`
suffix dropped and the entry slug appended.
