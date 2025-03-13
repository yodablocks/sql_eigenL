# table: eigenlayer_ethereum.whitelisted_strategy_latest

schema:
| name | type |
| --- | --- |
| strategy | binary |

---
# table: eigenlayer_ethereum.operator_metadata_uri_latest

schema:
| name | type |
| --- | --- |
| operator | varbinary |
| metadataURI | varchar |

---
# table: eigenlayer_ethereum.avs_metadata_uri_latest

schema:
| name | type |
| --- | --- |
| avs | varbinary |
| metadataURI | varchar |

---
# table: eigenlayer_ethereum.avs_paid_rewards

schema:
| name | type |
| --- | --- |
| avs | binary |
| metadatauri | string |

---
# table: eigenlayer_ethereum.strategy_shares_outflow_by_day

schema:
| name | type |
| --- | --- |
| strategy | binary |
| shares | decimal(38,0) |
| date | timestamp |

---
# table: eigenlayer_ethereum.strategy_shares_inflow_by_day

schema:
| name | type |
| --- | --- |
| strategy | binary |
| shares | decimal(38,0) |
| date | timestamp |

---
# table: eigenlayer_ethereum.strategy_shares_netflow_by_day

schema:
| name | type |
| --- | --- |
| strategy | binary |
| shares | decimal(38,0) |
| date | timestamp |

---
# table: eigenlayer_ethereum.underlying_token_exchange_rate_latest

schema:
| name | type |
| --- | --- |
| strategy | binary |
| exchange_rate | long |

---
# table: eigenlayer_ethereum.strategy_and_token_metadata_latest

schema:
| name | type |
| --- | --- |
| strategy | binary |
| token | binary |
| symbol | string |
| decimals | long |

---
# table: eigenlayer_ethereum.pod_shares_updated_enriched

schema:
| name | type |
| --- | --- |
| evt_tx_hash | varbinary |
| evt_index | integer |
| evt_block_time | timestamp(3) with time zone |
| evt_block_number | bigint |
| strategy | varbinary |
| shares | decimal(38,0) |

---
# table: eigenlayer_ethereum.rewards_v1_by_day

schema:
| name | type |
| --- | --- |
| token | varchar |
| daily_amount | decimal(38,0) |
| date | timestamp(3) with time zone |

---
# table: eigenlayer_ethereum.operator_shares_cumulative_by_day

schema:
| name | type |
| --- | --- |
| operator | varbinary |
| strategy | varbinary |
| date | timestamp(3) with time zone |
| cumulative_daily_shares | decimal(38,0) |

---
# table: eigenlayer_ethereum.programmatic_incentive_by_day

schema:
| name | type |
| --- | --- |
| token | varchar |
| daily_amount | decimal(38,0) |
| date | timestamp(3) with time zone |

---
# table: eigenlayer_ethereum.strategy_category

schema:
| name | type |
| --- | --- |
| strategy | binary |
| token | binary |
| category | string |
| name | string |

---
# table: eigenlayer_ethereum.avs_operator_registration_status_latest

schema:
| name | type |
| --- | --- |
| operator | varbinary |
| avs | varbinary |
| status | integer |
