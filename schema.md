table: eigenlayer_ethereum.whitelisted_strategy_latest

schema:
| name | type |
| --- | --- |
| strategy | binary |

---

table: eigenlayer_ethereum.operator_metadata_uri_latest

schema:
| name | type |
| --- | --- |
| operator | varbinary |
| metadataURI | varchar |

---

table: eigenlayer_ethereum.avs_metadata_uri_latest

schema:
| name | type |
| --- | --- |
| avs | varbinary |
| metadataURI | varchar |

---

table: eigenlayer_ethereum.avs_paid_rewards

schema:
| name | type |
| --- | --- |
| avs | binary |
| metadatauri | string |

---

table: eigenlayer_ethereum.strategy_shares_outflow_by_day

schema:
| name | type |
| --- | --- |
| strategy | binary |
| shares | decimal(38,0) |
| date | timestamp |

---






