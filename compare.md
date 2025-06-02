| 配置項 | botonchain/config.toml | program config.toml.example | 狀態 |
|--------|----------------------|-------------------|------|
| **Bot 配置** |
| compute_unit_limit | ✅ 600_000 | ✅ 600000 | Common |
| merge_mints | ✅ 有 | ❌ 無 | Unique to botonchain |
| base_mint | ✅ 有 | ❌ 無 | Unique to botonchain |
| memo | ✅ 有 | ❌ 無 | Unique to botonchain |
| **Routing 配置** |
| mint_config_list | ✅ 有 | ✅ 有 | Common |
| pump_pool_list | ✅ 有 | ✅ 有 | Common |
| raydium_pool_list | ✅ 有 | ✅ 有 | Common |
| raydium_cp_pool_list | ✅ 有 | ✅ 有 | Common |
| raydium_clmm_pool_list | ✅ 有 | ✅ 有 | Common |
| whirlpool_pool_list | ✅ 有 | ✅ 有 | Common |
| meteora_dlmm_pool_list | ✅ 有 | ✅ 有 | Common |
| meteora_damm_pool_list | ✅ 有 | ❌ 無 | Unique to botonchain |
| meteora_dammv2_pool_list | ✅ 有 | ❌ 無 | Unique to botonchain |
| solfi_pool_list | ✅ 有 | ❌ 無 | Unique to botonchain |
| lookup_table_accounts | ✅ 有 | ✅ 有 | Common |
| process_delay | ✅ 400 | ✅ 400 | Common |
| **RPC 配置** |
| url | ✅ 有 | ✅ 有 | Common |
| **Spam 配置** |
| enabled | ✅ 有 | ✅ 有 | Common |
| sending_rpc_urls | ✅ 多個 | ✅ 單一 | Different |
| compute_unit_price | ✅ 複雜配置 | ✅ 簡單配置 | Different |
| max_retries | ✅ 10 | ✅ 3 | Different |
| enable_simple_send | ✅ 有 | ❌ 無 | Unique to botonchain |
| **Jito 配置** |
| enabled | ✅ 有 | ❌ 無 | Unique to botonchain |
| block_engine_urls | ✅ 有 | ❌ 無 | Unique to botonchain |
| tip_config | ✅ 有 | ❌ 無 | Unique to botonchain |
| **Flashloan 配置** |
| 配置名稱 | [flashloan] | [kamino_flashloan] | Different |
| enabled | ✅ 有 | ✅ 有 | Common |
| **Wallet 配置** |
| private_key | ✅ 有 | ✅ 有 | Common |