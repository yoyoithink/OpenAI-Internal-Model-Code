# Internal Models - Categorized

> Note: Categories and role descriptions are inferred from model names only. They are not official metadata.
> Grouping uses an inferred primary capability/area; model order inside each category follows first appearance in the source files.

Unique entries: 1639

## Category Summary

| Category | Count |
|---|---:|
| Search, Browse, and Retrieval | 173 |
| Reasoning and Thinking | 125 |
| Image, Vision, and Multimodal | 45 |
| Audio, Voice, and Realtime | 30 |
| Artifacts, UI, and Document Tools | 131 |
| Agents, Tool Use, and Automation | 29 |
| Personalization, Memory, and Tone | 382 |
| Evaluation, Grading, and Judging | 24 |
| Safety, Policy, and Trust | 27 |
| Localization, Language, and Region | 50 |
| Coding, Data, and Structured Tasks | 14 |
| Training Runs and Checkpoints | 28 |
| Infrastructure, Routing, and Smoke Tests | 14 |
| ChatGPT Product and General Assistant Variants | 336 |
| General Research or Unclear | 231 |

## Search, Browse, and Retrieval (173)

| Model | Brief English role description |
|---|---|
| campaign:5p5_paid_search_16k_0519:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, 16k context, control arm. |
| campaign:5p5_paid_search_16k_0519:b_test | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, 16k context, test/treatment arm. |
| campaign:5p5_paid_search_16k_0520:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, 16k context, control arm. |
| campaign:5p5_paid_search_16k_0520:b_test | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, 16k context, test/treatment arm. |
| campaign:bd_a3_web_mec_unpaid_0516:a_a3_s1100 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| campaign:bd_a3_web_mec_unpaid_0516:b_a3_web_mec_s1100 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| campaign:bd_a3_web_unpaid_0516:a_a3_s1100 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| campaign:bd_a3_web_unpaid_0516:b_a3_web_s1100 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_20260226:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, control arm, prefetch behavior. |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_20260226:b_always_prefetch | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, prefetch behavior. |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_20260226:c_normal_prefetch | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, prefetch behavior. |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_20260226:d_common_keywords | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, prefetch behavior. |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_webonly_20260303:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, control arm, prefetch behavior. |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_webonly_20260303:b_always_prefetch | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, prefetch behavior. |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_webonly_20260303:c_normal_prefetch | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, prefetch behavior. |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_webonly_20260303:d_common_keywords | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, prefetch behavior. |
| campaign:mainline_no_search_vs_sonicthinky_d64:a_prod | Model or experiment focused on search, browsing, or web retrieval; signals: production comparison. |
| campaign:mainline_no_search_vs_sonicthinky_d64:b_prod_no_search | Model or experiment focused on search, browsing, or web retrieval; signals: production comparison. |
| campaign:mainline_no_search_vs_sonicthinky_d64:c_sonicthinky_d64_sideline | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:search_d64_prefetch_paid_0304:a_current_prod | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, production comparison, prefetch behavior. |
| campaign:search_d64_prefetch_paid_0304:b_d64_prefetch | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, prefetch behavior. |
| campaign:5p2_force_search_newsys_paid_0127:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, control arm. |
| campaign:5p2_force_search_newsys_paid_0127:b_treatment | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, test/treatment arm. |
| campaign:5p2_force_search_newsys_paid_0127:c_baseline | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, baseline. |
| campaign:5p3_arm7_enforce_recency_paid:a_current_prod | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, production comparison. |
| campaign:5p3_arm7_enforce_recency_paid:b_enforce_recency | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| campaign:5p3_arm7_force_recency:a_current_prod | Model or experiment focused on search, browsing, or web retrieval; signals: production comparison. |
| campaign:5p3_moresearch_nosearch_tolo1_s1450_0227:a_more_search | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:5p3_moresearch_nosearch_tolo1_s1450_0227:b_no_search | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:5p5_free_search_subagent_spmini_1hop_lc_0517:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, control arm, subagent routing, mini/compact variant, single-hop retrieval. |
| campaign:5p5_free_search_subagent_spmini_1hop_lc_0517:b_test | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, test/treatment arm, subagent routing, mini/compact variant, single-hop retrieval. |
| campaign:5p5_paid_search_subagent_spmini_1hop_lc_0518:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, control arm, subagent routing, mini/compact variant, single-hop retrieval. |
| campaign:5p5_paid_search_subagent_spmini_1hop_lc_0518:b_test | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, test/treatment arm, subagent routing, mini/compact variant, single-hop retrieval. |
| campaign:5p3_nosearch_baseline__paid:b_no_search | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, baseline. |
| campaign:5p5_paid_search_subagent_nv4_0511:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, control arm, subagent routing. |
| campaign:5p5_paid_search_subagent_nv4_0511:b_test | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, test/treatment arm, subagent routing. |
| campaign:5p5_paid_search_subagent_nv4_latency_control_0511:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, control arm, subagent routing. |
| campaign:5p5_paid_search_subagent_nv4_latency_control_0511:b_test | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, control arm, test/treatment arm, subagent routing. |
| campaign:5p5_paid_search_subagent_spmini_1hop_lc_0515:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, control arm, subagent routing, mini/compact variant, single-hop retrieval. |
| campaign:5p5_paid_search_subagent_spmini_1hop_lc_0515:b_test | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, test/treatment arm, subagent routing, mini/compact variant, single-hop retrieval. |
| campaign:5p5_paid_search_subagent_spmini_1hop_lc_0519:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, control arm, subagent routing, mini/compact variant, single-hop retrieval. |
| campaign:5p5_paid_search_subagent_spmini_1hop_lc_0519:b_test | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, test/treatment arm, subagent routing, mini/compact variant, single-hop retrieval. |
| campaign:5p5_unpaid_search_subagent_spmini_1hop_lc_0519:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, control arm, subagent routing, mini/compact variant, single-hop retrieval. |
| campaign:5p5_unpaid_search_subagent_spmini_1hop_lc_0519:b_test | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, test/treatment arm, subagent routing, mini/compact variant, single-hop retrieval. |
| campaign:andromeda_e2_web_fl_0429_v1:a_e2_s1250 | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:andromeda_e2_web_fl_0429_v1:b_e2_web_flock_s1250 | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:andromeda_e2_web_fl_0501:a_e2_s1500 | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:andromeda_e2_web_fl_0501:b_e2_web_fl_0501_s1500 | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:andromeda_e2_web_fl_0505_resume:a_e2_s1500 | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:andromeda_e2_web_fl_0505_resume:b_e2_web_fl_0505_resume_s1500 | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:andromeda_e2_web_fl_s1500:a_e2_s1250 | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:andromeda_e2_web_fl_s1500:b_e2_web_flock_s1500 | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:garlic_vs_spmini_search_unpaid:a_prod | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, production comparison, mini/compact variant. |
| campaign:garlic_vs_spmini_search_unpaid:b_spmini | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, mini/compact variant. |
| campaign:gpt_52_search_vs_nosearch_paid:a_no_browse | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| campaign:gpt_52_search_vs_nosearch_paid:b_force_search | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| campaign:index_eval_sys2_vs_sys1_5p5i_perma_pg_v3:a_serp_only | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:paid_auto_chat_sys2_only_vs_sys1_only_5p3_paragen:a_serp_only | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| campaign:paid_auto_chat_sys2_vs_sys1_5p5i_perma_pg_v2:a_serp_only | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| campaign:search_fr_with_mini_free_users_0415:a_control | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, control arm, mini/compact variant. |
| campaign:search_fr_with_mini_free_users_0415:b_test | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, test/treatment arm, mini/compact variant. |
| campaign:serp_for_product_0514:a_prod | Model or experiment focused on search, browsing, or web retrieval; signals: production comparison. |
| campaign:serp_for_product_0514:b_serp_products | Model or experiment focused on search, browsing, or web retrieval. |
| campaign:web_links_0323_paid_link_dev_short:a_link_dev_short | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| campaign:web_links_0323_paid_link_dev_short:b_control | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, control arm. |
| campaign:web_links_dogfood_unpaid:a_dogfood | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, dogfooding. |
| Yaroslav GPT-5.3 search-parrot DLE probe 2026-05-20 | Model or experiment focused on search, browsing, or web retrieval. |
| Yaroslav GPT-5.5 search DLE probe 2026-05-20 | Model or experiment focused on search, browsing, or web retrieval. |
| 5p5_free_search_spmini_1h_0526 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, mini/compact variant. |
| 5p5_free_search_will_spmini_0526 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, mini/compact variant. |
| 5p5_paid_search_spmini_1h_0526 | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, mini/compact variant. |
| 5p5_paid_search_spmini_w_0526 | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, mini/compact variant. |
| bd_web_features_0516_ab_paid | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| bd_web_features_0516_ab_unpaid | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| search_big_dipper_ns_thresh_016_05_21 | Model or experiment focused on search, browsing, or web retrieval. |
| AD web links 0427 | Model or experiment focused on search, browsing, or web retrieval. |
| AD web links 0427 hillclimb 0428 | Model or experiment focused on search, browsing, or web retrieval. |
| Arm7 Meant for Search Prefetch | Model or experiment focused on search, browsing, or web retrieval; signals: prefetch behavior. |
| 0427_search_classifier_v2 | Model or experiment focused on search, browsing, or web retrieval. |
| andromeda_arm7_search_05_15 | Model or experiment focused on search, browsing, or web retrieval. |
| andromeda_web_features_0407_ab_v3 | Model or experiment focused on search, browsing, or web retrieval. |
| andromeda_web_features_0427_ab | Model or experiment focused on search, browsing, or web retrieval. |
| shortprompts_search_0507 | Model or experiment focused on search, browsing, or web retrieval. |
| shortprompts_search_0507_paid | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| 5p5 instant paid sys2 only with search subagent spmini 1 hop w 0508 | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, low latency, subagent routing, mini/compact variant. |
| LMSYS - gpt5p2r + search j=128 2k | Model or experiment focused on search, browsing, or web retrieval; signals: 2k context. |
| LMSYS - gpt5p2r + search j=128 4k | Model or experiment focused on search, browsing, or web retrieval; signals: 4k context. |
| LMSYS - gpt5p2r + search juice=128 | Model or experiment focused on search, browsing, or web retrieval. |
| LMSYS - gpt5r + search j=128 | Model or experiment focused on search, browsing, or web retrieval. |
| Search subagent spmini 1 hop w 0508 | Model or experiment focused on search, browsing, or web retrieval; signals: subagent routing, mini/compact variant. |
| 5p5_free_search_spmini_1h_s_0528 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, mini/compact variant. |
| 5p5_free_search_spmini_1h_w_0528 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, mini/compact variant. |
| 5p5_paid_search_spmini_1h_s_0528 | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, mini/compact variant. |
| 5p5_paid_search_spmini_1h_w_0528 | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, mini/compact variant. |
| andromeda_web_flock_0508_ab | Model or experiment focused on search, browsing, or web retrieval. |
| 5.3 fast model prefetch 0422 | Model or experiment focused on search, browsing, or web retrieval; signals: prefetch behavior. |
| 5p5 instant paid sys2 only with search subagent nv4 multihop | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, low latency, subagent routing. |
| 5p5 instant paid sys2 only with search subagent spmini 1 hop s 0515 | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, low latency, subagent routing, mini/compact variant. |
| 5p5 instant unpaid sys2 only with search subagent nv4 multihop | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, low latency, subagent routing. |
| 5p5 instant unpaid with search subagent nv4 multihop | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, low latency, subagent routing. |
| Andromeda E2 Web Flock 0501 Resue s1500 | Model or experiment focused on search, browsing, or web retrieval. |
| Andromeda E2 Web Flock 0501 s1500 v2 | Model or experiment focused on search, browsing, or web retrieval. |
| Andromeda Search on Short Prompts | Model or experiment focused on search, browsing, or web retrieval. |
| BD A3 Web MEC s1100 unpaid | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| GPT 5.3 fast model prefetch evals | Model or experiment focused on search, browsing, or web retrieval; signals: prefetch behavior. |
| GPT-5.5 / Product Groups + No Search | Model or experiment focused on search, browsing, or web retrieval. |
| Igglypuff Search Vibe Testing | Model or experiment focused on search, browsing, or web retrieval. |
| LMSYS - 5.3 (chat) + search | Model or experiment focused on search, browsing, or web retrieval. |
| LMSYS - gpt5.4 + search | Model or experiment focused on search, browsing, or web retrieval. |
| LMSYS - gpt5.5 + search | Model or experiment focused on search, browsing, or web retrieval. |
| LMSYS - gpt5p2r + search j=512 2k | Model or experiment focused on search, browsing, or web retrieval; signals: 2k context. |
| LMSYS - gpt5r + search | Model or experiment focused on search, browsing, or web retrieval. |
| Search Fetch Timeout A | Model or experiment focused on search, browsing, or web retrieval. |
| Search Fetch Timeout B | Model or experiment focused on search, browsing, or web retrieval. |
| Search Fetch Timeout C | Model or experiment focused on search, browsing, or web retrieval. |
| Search Fetch Timeout D | Model or experiment focused on search, browsing, or web retrieval. |
| Search Subagent nv4 multihop | Model or experiment focused on search, browsing, or web retrieval; signals: subagent routing. |
| Search cache experiment, p90 | Model or experiment focused on search, browsing, or web retrieval. |
| Search subagent 1 hop v2 | Model or experiment focused on search, browsing, or web retrieval; signals: subagent routing. |
| Search subagent spmini 1 hop s 0515 | Model or experiment focused on search, browsing, or web retrieval; signals: subagent routing, mini/compact variant. |
| V3 search subagent spmini | Model or experiment focused on search, browsing, or web retrieval; signals: subagent routing, mini/compact variant. |
| Yaro GPT-5.5 search summarization DLE | Model or experiment focused on search, browsing, or web retrieval. |
| alpha.bd_a3_web_mec_s1100_unpaid | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| andromeda_launch_auto_no_browse_unpaid | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| andromeda_launch_instant_no_browse_paid | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, low latency. |
| big_dipper_c2_gdreams_search_extract_always | Model or experiment focused on search, browsing, or web retrieval. |
| big_dipper_c2_gdreams_search_extract_always_v2 | Model or experiment focused on search, browsing, or web retrieval. |
| big_dipper_c2_gdreams_search_extract_relaxed | Model or experiment focused on search, browsing, or web retrieval. |
| big_dipper_c2_gdreams_search_extract_relaxed_v2 | Model or experiment focused on search, browsing, or web retrieval. |
| gan_web_location_tool_0423 | Model or experiment focused on search, browsing, or web retrieval. |
| gan_web_location_tool_0429 | Model or experiment focused on search, browsing, or web retrieval. |
| gpt5p2r + search | Model or experiment focused on search, browsing, or web retrieval. |
| job_search_reasoning_paid | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| synthetic_local_search_bramnani | Model or experiment focused on search, browsing, or web retrieval. |
| 0430__search_classifier_v2 | Model or experiment focused on search, browsing, or web retrieval. |
| 5p3_free_search_engine_holdout | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, holdout arm. |
| 5p3_search_holdout_unpaid_0303 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, holdout arm. |
| 5p5_free_search_subagent_spmini_1hop_0520 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, subagent routing, mini/compact variant, single-hop retrieval. |
| 5p5_free_search_subagent_will_spmini_0520 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, subagent routing, mini/compact variant. |
| 5p5_paid_search_subagent_spmini_1hop_0520 | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, subagent routing, mini/compact variant, single-hop retrieval. |
| 5p5_paid_search_subagent_will_spmini_0520 | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, subagent routing, mini/compact variant. |
| 5p5_search_paid_mai_grounding | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| bd_web_features_0522_ab_paid | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| bd_web_features_0522_ab_unpaid | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| gpt55_thinking_igglybuff_search_v0 | Model or experiment focused on search, browsing, or web retrieval. |
| model_aware_map_search_only_paid | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| model_aware_map_search_only_unpaid_v2 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| search_classifiers_paid_0512 | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| search_classifiers_unpaid_0512 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| search_default_token_sweep_unpaid | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| search_parrot_0514 | Model or experiment focused on search, browsing, or web retrieval. |
| serch_big_dipper_force_no_search_05_21 | Model or experiment focused on search, browsing, or web retrieval. |
| shortprompts_search_50_test | Model or experiment focused on search, browsing, or web retrieval; signals: test/treatment arm. |
| web_loc_tool_paid_v2 | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| web_loc_tool_paid_v3 | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier. |
| web_loc_tool_unpaid_v2 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| web_loc_tool_unpaid_v3 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| mainline gpt-4: (biz_no_browse) | Model or experiment focused on search, browsing, or web retrieval. |
| mainline o1-mini: (biz_no_browse) | Model or experiment focused on search, browsing, or web retrieval; signals: mini/compact variant. |
| mainline o1-preview: (biz_no_browse) | Model or experiment focused on search, browsing, or web retrieval. |
| mainline o3: (biz_no_browse) | Model or experiment focused on search, browsing, or web retrieval. |
| mainline o4-mini: (biz_no_browse) | Model or experiment focused on search, browsing, or web retrieval; signals: mini/compact variant. |
| mainline text-davinci-002-render-sha: (biz_no_browse) | Model or experiment focused on search, browsing, or web retrieval. |
| gpt5_3_mini_first_web_run | Model or experiment focused on search, browsing, or web retrieval; signals: mini/compact variant. |
| Sonic Thinky v1 Unpaid, No Serp News | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier. |
| GPT-5.5 unpaid local biz ctx 16k heap topn10 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, 16k context. |
| chatgpt_local_16k_plus_heap | Model or experiment focused on search, browsing, or web retrieval; signals: 16k context. |
| GPT-5.5 unpaid local biz ctx 8k heap | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, 8k context. |
| GPT-5.5 unpaid local biz ctx 8k heap topn10 | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, 8k context. |
| local_8k_heap_topn_tune | Model or experiment focused on search, browsing, or web retrieval; signals: 8k context. |
| local_8k_heap_tune | Model or experiment focused on search, browsing, or web retrieval; signals: 8k context. |
| big_dipper_a1_sp_mini_flock_free | Model or experiment focused on search, browsing, or web retrieval; signals: unpaid tier, mini/compact variant. |
| big_dipper_a1_sp_mini_flock_paid | Model or experiment focused on search, browsing, or web retrieval; signals: paid tier, mini/compact variant. |

## Reasoning and Thinking (125)

| Model | Brief English role description |
|---|---|
| campaign:sonic_thinky_unpaid_2600_nov25:a_prod | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier, production comparison. |
| campaign:sonic_thinky_unpaid_2600_nov25:b_s2600 | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| campaign:sonic_thinky_unpaid_dec1:c_1124t1_s2700 | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| campaign:sonic_thinky_unpaid_dec1:d_1128t1_s1300 | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| campaign:5p5_thinking_paid_professional_0501:a_control | Model or experiment focused on reasoning or extended thinking; signals: paid tier, control arm. |
| campaign:5p5_thinking_paid_professional_0501:b_treatment | Model or experiment focused on reasoning or extended thinking; signals: paid tier, test/treatment arm. |
| campaign:5p5_thinking_pro_professional_0501:a_control | Model or experiment focused on reasoning or extended thinking; signals: Pro tier, control arm. |
| campaign:5p5_thinking_pro_professional_0501:b_treatment | Model or experiment focused on reasoning or extended thinking; signals: Pro tier, test/treatment arm. |
| campaign:gpt_52_thinking_vs_instant_iid_paid:a_instant | Model or experiment focused on reasoning or extended thinking; signals: paid tier, low latency. |
| campaign:gpt_52_thinking_vs_instant_iid_paid:b_reasoning | Model or experiment focused on reasoning or extended thinking; signals: paid tier, low latency. |
| campaign:gpt_54_thinking_j5_vs_53_iid_paid:a_gpt_5_3 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| campaign:gpt_54_thinking_j5_vs_53_iid_paid:b_gpt_5_4_thinking | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| campaign:gpt_54_thinking_j5_vs_53_iid_paid_04pct:a_gpt_5_3 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| campaign:gpt_54_thinking_j5_vs_53_iid_paid_04pct:b_gpt_5_4_thinking | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| campaign:gpt_54_thinking_j5_vs_53_instant_iid_paid:a_control | Model or experiment focused on reasoning or extended thinking; signals: paid tier, low latency, control arm. |
| campaign:gpt_54_thinking_j5_vs_53_instant_iid_paid:b_treatment | Model or experiment focused on reasoning or extended thinking; signals: paid tier, low latency, test/treatment arm. |
| campaign:paid_manual_reasoning_multisys_5p5_paragen:a_control | Model or experiment focused on reasoning or extended thinking; signals: paid tier, control arm. |
| campaign:paid_manual_reasoning_multisys_5p5_paragen:b_test | Model or experiment focused on reasoning or extended thinking; signals: paid tier, test/treatment arm. |
| campaign:paid_manual_reasoning_multisys_snippet_5p5_paragen:a_control | Model or experiment focused on reasoning or extended thinking; signals: paid tier, control arm. |
| campaign:paid_manual_reasoning_multisys_snippet_5p5_paragen:b_test | Model or experiment focused on reasoning or extended thinking; signals: paid tier, test/treatment arm. |
| campaign:paid_manual_reasoning_sys1_only_5p5_paragen:a_control | Model or experiment focused on reasoning or extended thinking; signals: paid tier, control arm. |
| campaign:paid_manual_reasoning_sys1_only_5p5_paragen:b_test | Model or experiment focused on reasoning or extended thinking; signals: paid tier, test/treatment arm. |
| campaign:sonic_thinky_unpaid_dec1:a_prod | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier, production comparison. |
| campaign:sonic_thinky_unpaid_dec1:b_1124t1_s2400 | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| campaign:thinky_paragen_campaign_test:a_control | Model or experiment focused on reasoning or extended thinking; signals: control arm, test/treatment arm. |
| 5p2_thinking_tables | Model or experiment focused on reasoning or extended thinking. |
| 5p2_thinking_more_tables | Model or experiment focused on reasoning or extended thinking. |
| Deep Research App (GPT 5.2 Thinking) | Model or experiment focused on reasoning or extended thinking. |
| web_links_reasoning_0511 | Model or experiment focused on reasoning or extended thinking. |
| Spud D64 Reasoning | Model or experiment focused on reasoning or extended thinking. |
| Thinky rev7 arm3 s1200 (2026-02-23 export) | Model or experiment focused on reasoning or extended thinking. |
| alsamer101625_thinking | Model or experiment focused on reasoning or extended thinking. |
| bidi_backend_gpt55_reasoning_high_260521 | Model or experiment focused on reasoning or extended thinking. |
| bidi_backend_gpt55_reasoning_medium_260521 | Model or experiment focused on reasoning or extended thinking. |
| gpt5-5-activation-reasoning-paid-052226 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| thinky-rev7-arm8-s300-20260306-1741-300-8shard-2026-03-06-20-25 (ppo step 300) | Model or experiment focused on reasoning or extended thinking; signals: RL signal. |
| chatgpt_ctx_window_holdback_thinking_26_h1 | Model or experiment focused on reasoning or extended thinking. |
| codex_thinky_codex_test_20260211_185134 | Model or experiment focused on reasoning or extended thinking; signals: test/treatment arm. |
| gpt55_lowjuice_thinking_paid_260504 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| gpt_5_5_thinking_activations_exp_050826 | Model or experiment focused on reasoning or extended thinking. |
| gpt_5_5_thinking_activations_exp_052226_new | Model or experiment focused on reasoning or extended thinking. |
| prefix_compaction_thinking_5p5_16k | Model or experiment focused on reasoning or extended thinking; signals: 16k context. |
| prefix_compaction_thinking_5p5_64k_v2 | Model or experiment focused on reasoning or extended thinking; signals: 64k context. |
| thinkier_20260210_v1 | Model or experiment focused on reasoning or extended thinking. |
| thinkier_20260210_v2 | Model or experiment focused on reasoning or extended thinking. |
| thinkier_20260210_v4_unpaid | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| thinky_rev6_paid | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| thinky_rev6_unpaid | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| xq_thinky_codex_test_20260211 | Model or experiment focused on reasoning or extended thinking; signals: test/treatment arm. |
| Thinky rev7 arm5 s250 | Model or experiment focused on reasoning or extended thinking. |
| Sonic Thinky v1, 8k SBT and Truncate ATC | Model or experiment focused on reasoning or extended thinking; signals: 8k context. |
| Sonic Thinky v1, 8k token length | Model or experiment focused on reasoning or extended thinking; signals: 8k context. |
| paid_5p5_thinking_multisys_d8_0521 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| paid_5p5_thinking_multisys_d8_0522 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| 5.4 Reasoning as 5.5 Instant Config | Model or experiment focused on reasoning or extended thinking; signals: low latency. |
| 5.4r Thinkier Alex Taste | Model or experiment focused on reasoning or extended thinking. |
| 5p2_thinking_recognize_placeholders | Model or experiment focused on reasoning or extended thinking. |
| 5p3_reasoning_golden | Model or experiment focused on reasoning or extended thinking. |
| 5p4 Thinking in 5p3 Chat | Model or experiment focused on reasoning or extended thinking. |
| 5p4_thinking_sa_server | Model or experiment focused on reasoning or extended thinking. |
| GPT 5 2 reasoning paid jobs | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| GPT 5.5 Reasoning w/ Activation Classifier | Model or experiment focused on reasoning or extended thinking. |
| GoldenAlpha / 51 Thinking | Model or experiment focused on reasoning or extended thinking. |
| GoldenAlpha / 51 Thinking Auto | Model or experiment focused on reasoning or extended thinking. |
| PCA Wiki GPT-5.5 Reasoning Paid | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| Sonic Thinky Paid - System2 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| Sonic Thinky Paid, Mixed | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| Sonic Thinky Unpaid System1 | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| Sonic Thinky Unpaid System2 | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| Sonic Thinky V1 Paid Map Fix | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| Sonic Thinky v1 Paid | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| Sonic Thinky v1 Unpaid Default | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| Thinky Sonic Gen Entity Local Only Paid | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| Thinky Sonic Gen Entity Local Only Unpaid v0 | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| Thinky Sonic Gen Entity New Dis Local Unpaid | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| Thinky Sonic Gen Entity New Dis Unpaid v0 | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| Thinky Sonic Gen Entity New Disambig Local Paid | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| Thinky Sonic Gen Entity New Disambig Paid | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| Thinky Sonic Gen Entity New Disambig Unpaid | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| Thinky Sonic Gen Entity Prev Win Local Paid | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| Thinky Sonic Gen Entity Prev Win Local Unpaid | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| Thinky Sonic Gen Entity Prev Win Paid | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| Thinky Sonic Gen Entity Prev Win Unpaid | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| Thinky Sonic Local Query Mode 12-22 | Model or experiment focused on reasoning or extended thinking. |
| add_inst_thinking | Model or experiment focused on reasoning or extended thinking. |
| brandonw thinky classifier | Model or experiment focused on reasoning or extended thinking. |
| gan_availability_thinking_0511 | Model or experiment focused on reasoning or extended thinking. |
| garlic thinky 2 stage | Model or experiment focused on reasoning or extended thinking. |
| gpt5-2-reasoning-memento-in-turn | Model or experiment focused on reasoning or extended thinking. |
| prefix_compaction_5p5_thinking_medium_ctx_window_single_summary | Model or experiment focused on reasoning or extended thinking. |
| prefix_compaction_5p5_thinking_medium_ctx_window_single_summary_counter_factual | Model or experiment focused on reasoning or extended thinking. |
| prefix_compaction_5p5_thinking_small_ctx_window | Model or experiment focused on reasoning or extended thinking. |
| prefix_compaction_5p5_thinking_small_ctx_window_counter_factual | Model or experiment focused on reasoning or extended thinking. |
| prefix_compaction_eval_5p5_thinking | Model or experiment focused on reasoning or extended thinking. |
| prefix_compaction_eval_5p5_thinking_counter_factual | Model or experiment focused on reasoning or extended thinking. |
| thinking_dogfooding_plans_and_updates_v1 | Model or experiment focused on reasoning or extended thinking; signals: dogfooding. |
| xueqing_gpt5p4_reasoning | Model or experiment focused on reasoning or extended thinking. |
| 5_5_thinking_activations_classifier_exp | Model or experiment focused on reasoning or extended thinking. |
| 5p4_tolo1_reasoning_unpaid_0309 | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| andromeda_reasoning_paid_0512 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| chatgpt_reasoning_increase_context_windowv2 | Model or experiment focused on reasoning or extended thinking. |
| garlic_thinky_sys_msg_vs_arm10_paid | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| gpt55_cotv5_thinking_paid_v0 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| gpt55_thinking_gengar_v0 | Model or experiment focused on reasoning or extended thinking. |
| gpt5_5_thinking_paid_knowledge_cutoff | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| paid_manual_reasoning_multisys_5p5 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| paid_manual_reasoning_multisys_5p5_0513 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| pca_5_5_thinking_decision_boundary | Model or experiment focused on reasoning or extended thinking. |
| prefix_compaction_thinking_5p5_32k | Model or experiment focused on reasoning or extended thinking; signals: 32k context. |
| thinky_5p3_rev3_paid_02021 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| thinky_5p3_rev4_sample_allocator_paid_v4 | Model or experiment focused on reasoning or extended thinking; signals: paid tier. |
| thinky_juice_4_unpaid | Model or experiment focused on reasoning or extended thinking; signals: unpaid tier. |
| gpt55_thinking_igglybuff_v0 | Model or experiment focused on reasoning or extended thinking. |
| Sonic Thinky v1 | Model or experiment focused on reasoning or extended thinking. |
| GPT-5.5 Thinking Frontend Test | Model or experiment focused on reasoning or extended thinking; signals: test/treatment arm. |
| GPT-5.5 Thinking frontend prompt test | Model or experiment focused on reasoning or extended thinking; signals: test/treatment arm. |
| gpt55_thinking_holdout_v1 | Model or experiment focused on reasoning or extended thinking; signals: holdout arm. |
| 5p4_thinking_multiturn_memento | Model or experiment focused on reasoning or extended thinking. |
| Link Entities 5p2 Thinking | Model or experiment focused on reasoning or extended thinking. |
| RV Thinking Test 0211 | Model or experiment focused on reasoning or extended thinking; signals: test/treatment arm. |
| GPT-5 Thinking Mini | Model or experiment focused on reasoning or extended thinking; signals: mini/compact variant. |
| gpt-5-5-thinking | Model or experiment focused on reasoning or extended thinking. |
| 5p4r with Thinky sys prompt | Model or experiment focused on reasoning or extended thinking. |
| chat_cot_ui_constant_long_inst | Model or experiment focused on reasoning or extended thinking. |
| gpt5_2_r_cot_citations | Model or experiment focused on reasoning or extended thinking. |

## Image, Vision, and Multimodal (45)

| Model | Brief English role description |
|---|---|
| campaign:image_unpaid_sft_vs_rl0516a:a_labrador | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, SFT signal. |
| campaign:image_unpaid_sft_vs_rl0516a:b_labrador_blender_0516s180 | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, SFT signal. |
| campaign:5p3_images_blender_unpaid_arm7:a_control | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, control arm. |
| campaign:5p3_images_blender_unpaid_arm7:b_test | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, test/treatment arm. |
| campaign:5p3_blender_test_pgn:a_control | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: control arm, test/treatment arm. |
| campaign:5p3_blender_test_pgn:b_0401_v3 | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: test/treatment arm. |
| campaign:5p3_blender_test_pgn:c_0404_v1 | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: test/treatment arm. |
| campaign:andromeda_image_unpaid_sft_vs_rl0505:a_labrador | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, SFT signal. |
| campaign:andromeda_image_unpaid_sft_vs_rl0505:b_labrador_blender_0505s100 | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, SFT signal. |
| campaign:andromeda_image_unpaid_sft_vs_rl:a_labrador | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, SFT signal, RL signal. |
| campaign:andromeda_image_unpaid_sft_vs_rl:b_labrador_blender_0404_v1 | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, SFT signal, RL signal. |
| campaign:image_unpaid_sft_vs_rl0509:a_labrador | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, SFT signal. |
| campaign:image_unpaid_sft_vs_rl0509:b_labrador_blender_0509s30 | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, SFT signal. |
| campaign:image_unpaid_sft_vs_rl0515:a_labrador | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, SFT signal. |
| campaign:image_unpaid_sft_vs_rl0515:b_labrador_blender_0515s120 | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, SFT signal. |
| campaign:labrador_100p_free:a_control | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, control arm. |
| campaign:labrador_100p_free:b_force_100_labrador | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier. |
| image_index-labrador-256webp | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| Web Imagegen Auto v1 | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| Andromeda Img Group Prompt 0506 | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| ig2-hybridprod-640-v2 | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| ig2.hrm640 | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| imagegen_d64_edit_c2 | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| image_holdout_unpaid_test_0406 | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, test/treatment arm, holdout arm. |
| ig2-37p-ptw-test | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: test/treatment arm. |
| image_blender_rlv8_paid_ab | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: paid tier. |
| image_blender_rlv8_unpaid_ab | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier. |
| u18_image_groups_paid | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: paid tier. |
| u18_image_groups_unpaid | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier. |
| Amrit's Image O3 | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| Andromeda Img Prompt 0510 | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| Better Image Carousel Prompt | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| Image Gen Alpha Model Test | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: test/treatment arm. |
| ImageGen 2.0 Beta | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| Mainline images (crz) | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| dil-imagegen-dp | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| dil-imagegen-dp-v2 | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| o3.business_grader_non_labrador | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| 5p3_image_blender_index_ab_v3 | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| 5p3_image_index_v3p1_unpaid | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier. |
| andromeda_images_exp | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |
| image_blender_rl_paid_ab | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: paid tier, RL signal. |
| image_blender_rl_unpaid_ab | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: unpaid tier, RL signal. |
| image_groups_paid_holdout | Model or experiment focused on image generation, editing, vision, or multimodal behavior; signals: paid tier, holdout arm. |
| sidebar_images_blender | Model or experiment focused on image generation, editing, vision, or multimodal behavior. |

## Audio, Voice, and Realtime (30)

| Model | Brief English role description |
|---|---|
| AVM Reasoning | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| AVM Reasoning Feather | Model or experiment focused on audio, voice, speech, or realtime interaction; signals: low latency. |
| AVM Reasoning LDM | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| AVM-RT Reasoning | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| chatgpt_voice_reasoning | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| s2s_if_fc_0913_2760 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| s2s_chive_2026_q1 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| s2s_chive_2026_q1_m45_apac_v2 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| s2s_chive_q1_2026_holdout_v1 | Model or experiment focused on audio, voice, speech, or realtime interaction; signals: holdout arm. |
| s2s_scallion_q1_2026_holdout_v3 | Model or experiment focused on audio, voice, speech, or realtime interaction; signals: holdout arm. |
| s2s_chive_20250728_arm1 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| 5p2 audio | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| 5p4 voice hung template | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| AVM | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| chatgpt_voice_vad_tuning | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| s2s_ldm_chive_noram_v2 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| s2s_scallion_q3_2025_holdout_v2 | Model or experiment focused on audio, voice, speech, or realtime interaction; signals: holdout arm. |
| s2s_chive_q3_2025_holdout_v2 | Model or experiment focused on audio, voice, speech, or realtime interaction; signals: holdout arm. |
| Scallion w/ product entities | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| chive_m3_1105_1750 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| chive_m4_1105_0700 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| chive_m4_1105_0800 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| chive_m4_800_lc_1 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| Scallion entity content_ref | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| chive_m2_1105_1350 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| chive_m3_1105_1300 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| chive_m3_1105_1400 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| chive_m4_1105_0100 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| chive_m5_1105_0100_v2 | Model or experiment focused on audio, voice, speech, or realtime interaction. |
| chive_m5_1105_0500 | Model or experiment focused on audio, voice, speech, or realtime interaction. |

## Artifacts, UI, and Document Tools (131)

| Model | Brief English role description |
|---|---|
| campaign:genui_1014_sonicberry_s320_oy7_paid:a_prod | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: paid tier, production comparison. |
| campaign:genui_1014_sonicberry_s320_oy7_paid:b_sonicberry | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: paid tier. |
| campaign:genui_1014_sonicberry_s320_oy7_paid:c_sonicberry_w_memory | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: paid tier. |
| campaign:sonicberry_v8p1_unpaid_fully_mixed_nov21:a_prod | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier, production comparison. |
| campaign:sonicberry_v8p1_unpaid_fully_mixed_nov21:b_v8p1 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:awchen_gpt5_5_unpaid_widgets_sys1:a_control | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier, control arm. |
| campaign:awchen_gpt5_5_unpaid_widgets_sys1:b_task_fit | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:awchen_gpt5_5_unpaid_widgets_sys1:c_prose | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:awchen_gpt5_5_unpaid_widgets_sys1:d_task_fit_prose | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:chart_widget_instant_0512:a_widget_disabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: low latency. |
| campaign:chart_widget_instant_0512:b_widget_enabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: low latency. |
| campaign:flight_tracker_1:a_widget_disabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| campaign:flight_tracker_1:b_widget_enabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| campaign:genui_0924_sonicberry_1:a_prod | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: production comparison. |
| campaign:genui_0924_sonicberry_1:b_sonicberry | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| campaign:genui_0924_sonicberry_1:c_sonicberry_w_memory | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| campaign:genui_0924_sonicberry_unpaid_1:a_a_prod | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier, production comparison. |
| campaign:genui_0924_sonicberry_unpaid_1:b_sonicberry | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:genui_0924_sonicberry_unpaid_1:c_sonicberry_w_memory | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:genui_1014_sonicberry_s320_unpaid:a_prod | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier, production comparison. |
| campaign:genui_1014_sonicberry_s320_unpaid:b_sonicberry | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:genui_1014_sonicberry_s320_unpaid:c_sonicberry_w_memory | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:genui_1211_1:a_current_gpt5_2_auto_paid_widgets_test | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: paid tier, test/treatment arm. |
| campaign:genui_1211_1:b_base | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| campaign:genui_widget_paragen_gpt_5_3_unpaid_user:a_widgets_enabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:genui_widget_paragen_gpt_5_3_unpaid_user:b_widgets_disabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:genui_widget_paragen_gpt_5_3_unpaid_user_prompt_v3:a_widgets_enabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:genui_widget_paragen_gpt_5_3_unpaid_user_prompt_v3:b_widgets_disabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:genui_widget_paragen_gpt_5_5_unpaid_user:a_widgets_enabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:genui_widget_paragen_gpt_5_5_unpaid_user:b_widgets_disabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:genui_widget_paragen_gpt_5_5_unpaid_user_no_automatic_placement:a_widgets_enabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:genui_widgets_1211_2:a_widgets | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| campaign:genui_widgets_1211_2:b_control | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: control arm. |
| campaign:kramerd_gen_ui_widgets_test_4:a_widgets_enabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: test/treatment arm. |
| campaign:kramerd_gen_ui_widgets_test_4:b_widgets_disabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: test/treatment arm. |
| campaign:package_tracker_1:a_widget_disabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| campaign:package_tracker_1:b_widget_enabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| campaign:parallel_genui_milestone_1b:a_web_run_with_genui | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| campaign:parallel_genui_milestone_1b:b_genui_web_run_separate | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| campaign:widget_calc_v2_vs_no_calc:a_calc_v2 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| campaign:widget_calc_v2_vs_no_calc:b_no_calc | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| campaign:widget_no_auto_place_5_5_unpaid_user:a_widgets_enabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:widget_no_auto_place_5_5_unpaid_user:b_widgets_disabled | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| campaign:widgets_dom_2_12_test:a_mainline | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: test/treatment arm. |
| campaign:widgets_dom_2_12_test:b_widgets | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: test/treatment arm. |
| 5.2 Artifacts Juice 16 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5.4 5p4_0219_s1020_v2 Artifacts J768 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5.4 5p4_0219_s1020_v2 Artifacts J96 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5.4 Artifacts Spreadsheets J16 Prompt V2 Vicky | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5.4 alpha.5p4_0219_s1020_v2_artifacts_j64 Vicky | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5p4_0219_s1020_v2_artifacts_j64 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5p4_0219_s1020_v2_artifacts_j64_memento | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| alpa.5p4_0219_s1020_v2_artifacts_j96_vicky | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| alpha.5p4_0219_s1020_v2_artifacts_j16_vicky | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5.2 Widgets (Feb 7 ELK( | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| GenUI 0731 Arm4 RL Step 250 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: RL signal. |
| 5.4 5p4_reasoning_paid_artifact_edits_j8 Vicky | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: paid tier. |
| 5.4 S1020 V2 Artifact Edit Deno J8 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5.4 S1020 V2 Artifact Edit J8 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5.4 S1020 V2 Artifact Edit J8 Testing | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5p4_0219_s1020_v2_artifacts_edits_j8 vicky | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5p4_0219_s1020_v2_artifacts_j8 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| All widgets (12/18) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| alpha.5p4_0219_s1020_v2_artifacts_j8_vicky | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| alpha.5p4_0219_s1020_v2_artifacts_j8_vicky_prompt_v2_latest | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5.2 Artifacts Juice 32 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5.2 Artifacts Juice 4 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5.2 Auto Paid Widget Gen Entity | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: paid tier. |
| 5.4 5p4_0219_s1020_v2 Artifacts Juice 32 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5.4 Artifacts Pro Judging | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: Pro tier. |
| 5.4 Artifacts Pro No Judging | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: Pro tier. |
| 5.4 Auto Reasoning Mini Artifacts Edit Vicky | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: mini/compact variant. |
| 5.4 Spreadsheet Artifacts ATV2 prompt 2 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5.4 current_gpt5_4_pro_pro Artifacts | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: Pro tier. |
| 5p2 artifacts | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5p4_0219_s1020_v2_artifacts_j4 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| Artifacts S1020 Edits FE Execution | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| Artifacts Spreadsheet ATV2 Prompt 2 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| Edward Test for 5.2 Artifacts | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: test/treatment arm. |
| GPT 5.5 Thinking Artifacts | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| GPT-5.2 Pro - Artifacts | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: Pro tier. |
| GPT-5.5 Pro Artifacts | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: Pro tier. |
| GPT-5.5 Thinking Artifacts | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| GPT-5.5 Thinking Artifacts J4 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| Map Widget 0515 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| alpha.5p4_0219_s1020_v2_artifacts_j32_vicky | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| alpha.5p4_0219_s1020_v2_artifacts_j32_vicky_prompt_v2_latest | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| alpha.5p4_0219_s1020_v2_artifacts_j4_vicky | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| alpha.5p4_0219_s1020_v2_artifacts_j4_vicky_prompt_v2_latest | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| emily_gpt5_5_reasoning_paid_artifacts | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: paid tier. |
| gp5p2_artifacts_with_skillz | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| gpt-5-4-thinking-artifacts | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| widgets eval model | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| writing-block-experimental-genui+ | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| writing_block_document_expansion_free | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| writing_block_document_expansion_paid | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: paid tier. |
| mainline gpt-4: (biz_no_browse_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| mainline gpt-4: (biz_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| mainline gpt-4o-canmore: (biz_no_browse_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| mainline gpt-4o-canmore: (biz_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| mainline o1-mini: (biz_no_browse_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: mini/compact variant. |
| mainline o1-mini: (biz_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: mini/compact variant. |
| mainline o1-preview: (biz_no_browse_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| mainline o1-preview: (biz_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| mainline o3: (biz_no_browse_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| mainline o3: (biz_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| mainline o4-mini: (biz_no_browse_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: mini/compact variant. |
| mainline o4-mini: (biz_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: mini/compact variant. |
| mainline text-davinci-002-render-sha: (biz_no_browse_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| mainline text-davinci-002-render-sha: (biz_with_canvas) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| Thinky Sonic Widget Gen Entity | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| genui.synthetics.2 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| GPT 5.4 Thinking Widgets | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| 5p4_thinking_widgets | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| Search entity (elk 1) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| Sonicberry File Search Only | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| Mainline Sonicberry Paid | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: paid tier. |
| Mainline Sonicberry Unpaid | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: unpaid tier. |
| Sonicberry (Product Cards) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| mainline gpt-4o-canmore: (paid) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: paid tier. |
| 5p2 Instant -> Lab-First Sonicberry | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: low latency. |
| Sonicberry Paid Sy1/Sy2 | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: paid tier. |
| Sonicberry Paid Sy1/Sy2 dynamic | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation; signals: paid tier. |
| Chart block alpha | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| ELK General Disambig Reason | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| ELK General Disambiguation | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| Sonicberry (Lab-first Shopping) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| sonicberry_map_on_top | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| tmp sonicberry oai_index | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| Sonicberry (4o entry point) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |
| Sonicberry (YouTube index) | Model or experiment focused on artifacts, widgets, canvas, or document/UI generation. |

## Agents, Tool Use, and Automation (29)

| Model | Brief English role description |
|---|---|
| campaign:no_product_tool_0514:a_control | Model or experiment focused on agentic workflows, tool use, subagents, or automation; signals: control arm. |
| campaign:no_product_tool_0514:b_noproduct | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| campaign:prod_vs_mini_tool_call__sonic:a_prod | Model or experiment focused on agentic workflows, tool use, subagents, or automation; signals: production comparison, mini/compact variant. |
| campaign:prod_vs_mini_tool_call__sonic:b_mini_tool_call | Model or experiment focused on agentic workflows, tool use, subagents, or automation; signals: production comparison, mini/compact variant. |
| Handoff -> Deep Research | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| brandon classifier+nosearch | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| Aura Agent D64 0 | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| [dev2] Aura Agent D64 0 | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| [dev3] Aura Agent D64 0 | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| [dev4] Aura Agent D64 0 | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| [dev5] Aura Agent D64 0 | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| classifier_exclude_tools_0506 | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| classifier_skip_tools_0506_paid | Model or experiment focused on agentic workflows, tool use, subagents, or automation; signals: paid tier. |
| Agent with Prompt Expansion | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| GPT-5.5-handoff-containment | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| GPT4o w/ o3 handoff | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| GPT5.2 auto with proactive automations | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| GPT52 Automation Override | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| Orion with tools disabled | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| Synapse Mitigation Handoff Containment | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| Synapse Mitigation Tool Skepticism | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| api_tool PE | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| api_tool_derisk_1 | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| user location tool alpha | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| classifier_skip_tools_0511 | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| classifier_skip_tools_0511_paid | Model or experiment focused on agentic workflows, tool use, subagents, or automation; signals: paid tier. |
| product_tool_ablations_0513 | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| GPT-5.5-tool-skepticism | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |
| Pulse Tool 5.2 | Model or experiment focused on agentic workflows, tool use, subagents, or automation. |

## Personalization, Memory, and Tone (382)

| Model | Brief English role description |
|---|---|
| campaign:anusha_gpt_5_5_auto_pca_paragen_20260506:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: control arm. |
| campaign:anusha_gpt_5_5_auto_pca_paragen_20260506:b_treatment | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: test/treatment arm. |
| campaign:memory_2x_test_0226:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: control arm, test/treatment arm. |
| campaign:memory_2x_test_0226:b_memory_2x | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: test/treatment arm. |
| campaign:p13n_pca_paragen_1_20260421_auto:a_pca_override_always_call_5_3 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| campaign:p13n_pca_paragen_1_20260421_auto:b_pca_override_disabled_5_3 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| campaign:p13n_pca_paragen_1_20260423_auto_always_vs_default:a_pca_override_always_call_5_3 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| campaign:p13n_pca_paragen_1_20260423_auto_always_vs_default:b_pca_override_disabled_5_3 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| campaign:5p3_tone_casual_professional_prompts_unpaid:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, control arm. |
| campaign:5p3_tone_casual_professional_prompts_unpaid:b_treatment | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, test/treatment arm. |
| campaign:5p3_tone_casual_professional_prompts_unpaid_0322_v3:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, control arm. |
| campaign:5p3_tone_casual_professional_prompts_unpaid_0322_v3:b_treatment | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, test/treatment arm. |
| campaign:5p3_tone_professional_prompts_unpaid_0322_v1:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, control arm. |
| campaign:5p3_tone_professional_prompts_unpaid_0322_v1:b_professional | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:5p3_tone_professional_prompts_unpaid_0322_v1:c_test | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, test/treatment arm. |
| campaign:gpt53_diversity_traits_all_paid:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, control arm. |
| campaign:gpt53_diversity_traits_all_paid:aa_empathetic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:ab_supportive_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:ac_supportive_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:ad_practical_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:ae_practical_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:af_optimistic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:ag_optimistic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:ah_didactic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:b_dismissive_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:c_dismissive_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:d_prose_structure_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:e_prose_structure_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:f_ironic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:g_ironic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:h_obsequious_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:i_obsequious_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:j_critical_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:k_critical_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:l_markdown_structure_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:m_markdown_structure_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:n_confident_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:o_confident_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:p_friendly_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:q_friendly_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:r_curious_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:s_curious_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:t_conversational_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:u_conversational_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:v_literal_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:w_literal_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:x_idiomatic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:y_idiomatic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_paid:z_empathetic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, control arm. |
| campaign:gpt53_diversity_traits_all_v2_free:aa_empathetic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ab_supportive_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ac_supportive_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ad_practical_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ae_practical_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:af_optimistic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ag_optimistic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ah_didactic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ai_didactic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:aj_serious_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ak_serious_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:al_simple_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:am_simple_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:an_analytical_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ao_analytical_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ap_dispassionate_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:aq_dispassionate_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ar_expository_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:as_expository_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:at_direct_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:au_direct_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:av_emoji_use_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:aw_emoji_use_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ax_succinct_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ay_succinct_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:az_agreeable_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:b_dismissive_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:ba_agreeable_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:c_dismissive_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:d_prose_structure_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:e_prose_structure_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:f_ironic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:g_ironic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:h_obsequious_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:i_obsequious_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:j_critical_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:k_critical_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:l_markdown_structure_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:m_markdown_structure_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:n_confident_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:o_confident_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:p_friendly_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:q_friendly_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:r_curious_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:s_curious_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:t_conversational_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:u_conversational_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:v_literal_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:w_literal_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:x_idiomatic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:y_idiomatic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_free:z_empathetic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, control arm. |
| campaign:gpt53_diversity_traits_all_v2_paid:aa_empathetic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ab_supportive_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ac_supportive_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ad_practical_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ae_practical_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:af_optimistic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ag_optimistic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ah_didactic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ai_didactic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:aj_serious_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ak_serious_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:al_simple_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:am_simple_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:an_analytical_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ao_analytical_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ap_dispassionate_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:aq_dispassionate_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ar_expository_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:as_expository_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:at_direct_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:au_direct_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:av_emoji_use_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:aw_emoji_use_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ax_succinct_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ay_succinct_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:az_agreeable_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:b_dismissive_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:ba_agreeable_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:c_dismissive_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:d_prose_structure_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:e_prose_structure_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:f_ironic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:g_ironic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:h_obsequious_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:i_obsequious_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:j_critical_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:k_critical_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:l_markdown_structure_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:m_markdown_structure_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:n_confident_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:o_confident_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:p_friendly_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:q_friendly_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:r_curious_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:s_curious_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:t_conversational_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:u_conversational_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:v_literal_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:w_literal_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:x_idiomatic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:y_idiomatic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_all_v2_paid:z_empathetic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, control arm. |
| campaign:gpt53_diversity_traits_paid_part2_v2:b_conversational_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:c_conversational_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:d_literal_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:e_literal_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:f_idiomatic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:g_idiomatic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:h_empathetic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:i_empathetic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:j_supportive_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:k_supportive_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:l_practical_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:m_practical_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:n_optimistic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:o_optimistic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:p_didactic_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:q_didactic_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:r_serious_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part2_v2:s_serious_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part3_v3:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, control arm. |
| campaign:gpt53_diversity_traits_paid_part3_v3:b_simple_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part3_v3:c_simple_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part3_v3:d_analytical_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part3_v3:e_analytical_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_paid_part3_v3:f_dispassionate_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| campaign:gpt53_diversity_traits_unpaid_part1:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, control arm. |
| campaign:gpt53_diversity_traits_unpaid_part1_v2:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, control arm. |
| campaign:gpt53_diversity_traits_unpaid_part1_v2:b_dismissive_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part1_v2:c_dismissive_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part1_v2:d_prose_structure_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part1_v2:e_prose_structure_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part2_v2:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, control arm. |
| campaign:gpt53_diversity_traits_unpaid_part2_v2:b_conversational_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part2_v2:c_conversational_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, control arm. |
| campaign:gpt53_diversity_traits_unpaid_part3:b_simple_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:c_simple_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:d_analytical_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:e_analytical_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:f_dispassionate_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:g_dispassionate_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:h_expository_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:i_expository_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:j_direct_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:k_direct_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:l_emoji_use_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:m_emoji_use_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:n_succinct_more | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt53_diversity_traits_unpaid_part3:o_succinct_less | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt5_unpaid_personality_axis_practicality:a_pos | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt5_unpaid_personality_axis_practicality:b_neg | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| campaign:gpt_52_personality_robot_unpaid:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, control arm. |
| campaign:gpt_52_personality_robot_unpaid:b_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, control arm. |
| campaign:gpt_52_personality_robot_unpaid:b_treatment | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, test/treatment arm. |
| campaign:gpt_5p2_emoji_less_unpaid:a_control | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, control arm. |
| campaign:gpt_5p2_emoji_less_unpaid:b_treatment | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, test/treatment arm. |
| campaign:p13n_pca_0423_avd_no_p13n_ui:a_pca_override_always_call_5_3 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| campaign:p13n_pca_0423_avd_no_p13n_ui:b_pca_override_disabled_5_3 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| campaign:rishab_pca_paragen_1:a_pca_override_always_call_5_3 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| campaign:rishab_pca_paragen_1:b_pca_override_disabled_5_3 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| Big Dipper A19 step 450 research alpha | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| Big Dipper A19 step 500 research alpha | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| Big Dipper C2 step 450 research alpha | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| Big Dipper C2 step 500 research alpha | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| pca_web_suffix_5_5 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| GPT-5 Sugar With Memory And Automations | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| pca_toolcfg_0520_g55_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| 011526-default-personality | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| 011526-personality-dogfooding | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: dogfooding. |
| dreamberry_dreams_prefs_20250310_d64 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| personality v6 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| e2_tone_0526_free_v3 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| bd_lite_c2_pca_paid_0528 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| 5.4r Alex Taste | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| April 20 PCA Dogfooding | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: dogfooding. |
| D1 s1400 new p13n mitigation no pca | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| GPT 5.2 Sugar Memory Only | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| GPT 5.4R Mini Sugar Memory | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: mini/compact variant. |
| Garlic Personality SFT Final | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: SFT signal. |
| PCA Wiki GPT-5.5 Instant Paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, low latency. |
| Personalization test gmail | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: test/treatment arm. |
| alpha.chat_cot_ui_and_personality_instant | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: low latency. |
| big_dipper_c2_s1150_g55_pca_paid_project_decision_existing_engines | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_c2_s1150_g55_pca_paid_reply_action | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_c2_s1150_g55_pca_paid_reply_action_existing_engines | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_pca_reply_action | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| chat_cot_ui_and_personality_auto | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| personality_additional_inst | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| bd_c2_s1150_pca_v2 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| big_dipper_c2_g55_pca_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_c2_s1150_g55_pca_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_c2_s1150_paid_p13n_irv2 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_c2_s1150_s1200_paid_p13nir | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_c2_s1150_s1200_unpaid_p13nir | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_c2_s1150_unpaid_p13n_irv2 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_juice_g55_pca_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_feedback_personality_auto | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| chatgpt_feedback_personality_free | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| chatgpt_feedback_personality_free2 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| chatgpt_feedback_personality_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_feedback_personality_paid2 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| chatgpt_feedback_personality_paid_i | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_feedback_personality_paid_t | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_feedback_personality_think | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| chatgpt_personality_id_slang_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_personality_id_slang_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| chatgpt_personality_in_hinglish_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_personality_in_hinglish_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| chatgpt_personality_jp_casual_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_personality_jp_casual_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| chatgpt_personality_jp_idioms_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_personality_jp_idioms_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| chatgpt_personality_jp_katakana_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_personality_jp_katakana_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| chatgpt_personality_kr_emoticons_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_personality_kr_emoticons_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| chatgpt_personality_kr_idioms_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_personality_kr_idioms_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| chatgpt_personality_mec_code_switch_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_personality_mec_code_switch_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| chatgpt_personality_tone_match_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| chatgpt_personality_tone_match_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| chatgpt_zs_p13n_prompt_paid_v4 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| e2_tone_0522_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| hi_taste_james_paid_set53_2x | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| hi_taste_james_paid_set55_2x | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| hi_taste_james_unpaid_set53_2x | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| hi_taste_james_unpaid_set55_2x | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| memory_citation_mainline_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| memory_compression_0225_ab | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| multilingual_jp_context_tone_warmth | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| p13n_derisk_paid_2 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| p13n_derisk_paid_3 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| pca_big_dipper_free | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| pca_free_55 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| pca_free_55_v3 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| pca_free_55_v4 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| pca_go_55_v2 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| pca_go_55_v3 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| pca_go_55_v4 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| personality_concise_traits_experiment_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| 5p2c_p13n_no_money_20251209_v2 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| GPT5 Cocoon Memory Only | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| Pro Memory 30k | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: Pro tier, 30k context. |
| ToneStyle_v1_2 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| gpt 4o Memory 30k | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: 30k context. |
| e2_tone_0522_free | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| e2_tone_0523_free_v2 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| memory_off_free | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| p13n_5p2_ff_0103_pro | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: Pro tier. |
| Big Dipper A3 step 950 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| big_dipper_smoke2_s675 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| big_dipper_smoke2_s675_5p5base | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| GPT-5.3 paid prod arm7 s950 with prose-style developer message | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, production comparison. |
| big_dipper_smoke1_s1350_5p5base | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| big_dipper_smoke1_s1350 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| big_dipper_wb_doc_0513_free_0526 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_wb_doc_0513_paid_0526 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| Big Dipper A11 s1150 unpaid 0527 Feather | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, low latency. |
| Big Dipper A11 s850 unpaid 0527 Feather | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, low latency. |
| Big Dipper A20 S1000 J8 paid Feather 0517 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, low latency. |
| Big Dipper A20 S800 J8 paid Feather 0517 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, low latency. |
| Big Dipper A12 newline j8 unpaid 0519 Feather | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, low latency. |
| Big Dipper A14 s1100 j8 paid 0519 Feather | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, low latency. |
| Big Dipper A14 s1100 j8 paid 0519 Feather 2 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, low latency. |
| Big Dipper A19 S1400 j4 paid 0518 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| Big Dipper A19 S1400 j8 paid 0518 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| Big Dipper A19 s1400 j8 unpaid 0520 Feather | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, low latency. |
| Big Dipper A20 S1000 j8 paid 0515 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| Big Dipper A20 S800 j4 paid 0515 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| Big Dipper A20 S800 j8 paid 0515 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| Big Dipper A3 S950 J2 Unpaid 0508 Feather | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, low latency. |
| Big Dipper A3 S950 J8 Unpaid 0508 Feather | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, low latency. |
| Big Dipper C2 S1150 j8 paid 0518 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| Big Dipper C2 S1200 j8 paid 0518 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| Big Dipper C2 s1150 j8 unpaid 0520 Feather | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, low latency. |
| Big Dipper C2 s1200 j8 unpaid 0520 Feather | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, low latency. |
| big_dipper_c2_s1150_paid_juice8 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| mem3_big_dipper_c2_s1150_s1200_paid.c2_s1150_j8 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a11_s850_s1150_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a11_s850_s1150_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_a20_s800_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a20_s800_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| Big Dipper A12 S1200 paid Feather 0515 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, low latency. |
| Big Dipper A12 S1300 paid Feather 0515 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, low latency. |
| Big Dipper A14 S900 g5p3 j4 paid Feather 0513 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, low latency. |
| Big Dipper A14 S900 nopctx v2 j4 paid Feather 0515 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier, low latency. |
| Big Dipper A20 S1000 j4 paid 0515 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| Big Dipper A3 S950 g5p3 j2 unpaid Feather 0510 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier, low latency. |
| Big Dipper Auto Golden Alpha Paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| Big Dipper Auto Golden Alpha Unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| Big Dipper RevA Hackfree s1500 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| big_dipper_chat_paid_0514 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_chat_unpaid_0514 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_a12_newline_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a12_newline_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_a12_s1200_s1300_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a12_s1200_s1300_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_a14_s1100_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a14_s1100_paid_v2 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a14_s1100_paid_v3 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a14_s1100_unpaid_v2 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_a14_s1100_unpaid_v3 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_a14_s900_juice_paid_g5p3 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a14_s900_juice_paid_nopctx_v2 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a14_s900_juice_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_a19_c2_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a19_c2_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_a19_s1400_paid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a19_s1400_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_a3_s950_juice_paid_g5p3 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a3_s950_juice_paid_v2 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_a3_s950_juice_unpaid_g5p3 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_a3_s950_juice_unpaid_v2 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_c2_s1150_s1200_unpaid | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| big_dipper_wb_doc_mode_paid_0522 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: paid tier. |
| big_dipper_wb_doc_mode_free_0522 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: unpaid tier. |
| gpt-5-mini for cocoon | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: mini/compact variant. |
| Big Dipper arm a25 s1100 v3 | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| GPT5R Sugar Dedicated | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| big dipper a3 s950 awchen | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| trait_merge | Model or experiment focused on personalization, memory, preferences, tone, or personality. |
| big dipper test 1 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: test/treatment arm. |
| big_dipper_test_2 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: test/treatment arm. |
| big_dipper_test_3 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: test/treatment arm. |
| big_dipper_test_4 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: test/treatment arm. |
| Drew Dogfood 1 | Model or experiment focused on personalization, memory, preferences, tone, or personality; signals: dogfooding. |

## Evaluation, Grading, and Judging (24)

| Model | Brief English role description |
|---|---|
| campaign:sendos_evd_down_vs_control_paid_20260521:a_control | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: paid tier, control arm. |
| campaign:sendos_evd_down_vs_control_paid_20260521:b_evd_down | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: paid tier, control arm. |
| campaign:sendos_evd_up_vs_control_paid_20260521:a_control | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: paid tier, control arm. |
| campaign:sendos_evd_up_vs_control_paid_20260521:b_evd_up | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: paid tier, control arm. |
| campaign:sonic_ranking_5p5_unpaid_pg_oracle_d8:a_prod | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: unpaid tier, production comparison. |
| campaign:sonic_ranking_5p5_unpaid_pg_oracle_d8:b_oracle | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: unpaid tier. |
| campaign:andromeda_web_no_pairwise_s1300_v2:a_smoke_t3_s1400 | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: smoke testing. |
| campaign:andromeda_web_no_pairwise_s1300_v2:b_no_pairwise_s1300 | Model or experiment focused on evaluation, grading, judging, or reward modeling. |
| campaign:index_eval_sys2_vs_sys1_5p5i_perma_pg_v3:b_oai_index_only | Model or experiment focused on evaluation, grading, judging, or reward modeling. |
| campaign:pairwise_web_feature_additive_paragen_latency_control:a_additive_s1000 | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: control arm. |
| campaign:pairwise_web_feature_additive_paragen_latency_control:a_tolo1_s1000 | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: control arm. |
| campaign:pairwise_web_feature_additive_paragen_same_dev_msg:a_tolo1_s1000 | Model or experiment focused on evaluation, grading, judging, or reward modeling. |
| campaign:pairwise_web_feature_additive_paragen_same_dev_msg:b_additive_s1000 | Model or experiment focused on evaluation, grading, judging, or reward modeling. |
| campaign:sonic_ranking_5p5_unpaid_pg_oracle_bert:a_prod | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: unpaid tier, production comparison. |
| campaign:sonic_ranking_5p5_unpaid_pg_oracle_bert:b_test | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: unpaid tier, test/treatment arm. |
| GPT-5.5 Pro judge KC 202406 | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: Pro tier. |
| alsamer_grader_092625 | Model or experiment focused on evaluation, grading, judging, or reward modeling. |
| 5.5 Local Grader | Model or experiment focused on evaluation, grading, judging, or reward modeling. |
| Andromeda revE arm2 monolingual hackgrader t2 step 1200 | Model or experiment focused on evaluation, grading, judging, or reward modeling. |
| O3 Business Grader | Model or experiment focused on evaluation, grading, judging, or reward modeling. |
| User Signals Medley w/ Multiplicative Hack Reward | Model or experiment focused on evaluation, grading, judging, or reward modeling. |
| prefix compaction eval | Model or experiment focused on evaluation, grading, judging, or reward modeling. |
| 5pt3_hackgrader_flock_upweight_unpaid_v1 | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: unpaid tier. |
| sonic_oracle_oaibert_5p5_unpaid_ab | Model or experiment focused on evaluation, grading, judging, or reward modeling; signals: unpaid tier. |

## Safety, Policy, and Trust (27)

| Model | Brief English role description |
|---|---|
| campaign:gpt_5_5_iid_no_auth:a_control | Model or experiment focused on safety, policy, authentication, trust, or moderation; signals: control arm. |
| campaign:gpt_5_5_iid_no_auth:b_treatment | Model or experiment focused on safety, policy, authentication, trust, or moderation; signals: test/treatment arm. |
| campaign:gpt_5_5_lupo_no_auth:a_control | Model or experiment focused on safety, policy, authentication, trust, or moderation; signals: control arm. |
| campaign:gpt_5_5_lupo_no_auth:b_treatment | Model or experiment focused on safety, policy, authentication, trust, or moderation; signals: test/treatment arm. |
| campaign:gpt_5_5_lupo_no_auth:c_treatment_fork | Model or experiment focused on safety, policy, authentication, trust, or moderation; signals: test/treatment arm. |
| campaign:search_fr_with_mini_no_auth_users_paragen_0415:a_control | Model or experiment focused on safety, policy, authentication, trust, or moderation; signals: control arm, mini/compact variant. |
| campaign:search_fr_with_mini_no_auth_users_paragen_0415:b_test | Model or experiment focused on safety, policy, authentication, trust, or moderation; signals: test/treatment arm, mini/compact variant. |
| AD 0428 URLs Safety | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| mainline gpt-4o-mini: (no_auth_search) | Model or experiment focused on safety, policy, authentication, trust, or moderation; signals: mini/compact variant. |
| mainline gpt-5-chat-safety: (no_auth_search) | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| mainline gpt-4o-mini: (no_auth_no_tools) | Model or experiment focused on safety, policy, authentication, trust, or moderation; signals: mini/compact variant. |
| mainline gpt-5-chat-safety: (no_auth_no_tools) | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| mainline text-davinci-002-render-sha: (no_auth_no_tools) | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| spot_20260130_default_no_auth | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| Andromeda Safety T11 S1500 5p3 ES8 Feather | Model or experiment focused on safety, policy, authentication, trust, or moderation; signals: low latency. |
| andromeda-safety-t11-s1500-5p3-es8 | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| GPT-5.5-authority-clarification | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| Synapse Mitigation Authority Clarification | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| andromeda-safety-t11-s1500-5p4r | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| yungsung-andromeda-safety-t11-s1500 | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| 0519_shopping_product_policy_update | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| mainline gpt-4o-mini: (no_auth) | Model or experiment focused on safety, policy, authentication, trust, or moderation; signals: mini/compact variant. |
| mainline gpt-4o-mini: (no_auth_apple_punch_out) | Model or experiment focused on safety, policy, authentication, trust, or moderation; signals: mini/compact variant. |
| mainline gpt-4o: (no_auth_apple_punch_out) | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| mainline gpt-5-chat-safety: (no_auth) | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| mainline text-davinci-002-render-sha: (no_auth) | Model or experiment focused on safety, policy, authentication, trust, or moderation. |
| mainline text-davinci-002-render-sha: (no_auth_apple_punch_out) | Model or experiment focused on safety, policy, authentication, trust, or moderation. |

## Localization, Language, and Region (50)

| Model | Brief English role description |
|---|---|
| campaign:gpt_53_lupo_ctry_bulgarian_paid_geo_v1:a_control | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, control arm. |
| campaign:gpt_53_lupo_ctry_bulgarian_paid_geo_v1:b_control_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, control arm. |
| campaign:gpt_53_lupo_ctry_bulgarian_paid_geo_v1:c_treatment | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_bulgarian_paid_geo_v1:d_treatment_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_czech_unpaid_geo_v1:a_control | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: unpaid tier, control arm. |
| campaign:gpt_53_lupo_ctry_czech_unpaid_geo_v1:b_control_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: unpaid tier, control arm. |
| campaign:gpt_53_lupo_ctry_czech_unpaid_geo_v1:c_treatment | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: unpaid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_czech_unpaid_geo_v1:d_treatment_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: unpaid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_danish_paid_geo_v1:a_control | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, control arm. |
| campaign:gpt_53_lupo_ctry_danish_paid_geo_v1:b_control_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, control arm. |
| campaign:gpt_53_lupo_ctry_danish_paid_geo_v1:c_treatment | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_danish_paid_geo_v1:d_treatment_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_dutch_paid_geo_v1:a_control | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, control arm. |
| campaign:gpt_53_lupo_ctry_dutch_paid_geo_v1:b_control_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, control arm. |
| campaign:gpt_53_lupo_ctry_dutch_paid_geo_v1:c_treatment | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_dutch_paid_geo_v1:d_treatment_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_finnish_paid_geo_v1:a_control | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, control arm. |
| campaign:gpt_53_lupo_ctry_finnish_paid_geo_v1:b_control_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, control arm. |
| campaign:gpt_53_lupo_ctry_finnish_paid_geo_v1:c_treatment | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_finnish_paid_geo_v1:d_treatment_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_latvian_paid_geo_v1:a_control | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, control arm. |
| campaign:gpt_53_lupo_ctry_latvian_paid_geo_v1:b_control_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, control arm. |
| campaign:gpt_53_lupo_ctry_latvian_paid_geo_v1:c_treatment | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_latvian_paid_geo_v1:d_treatment_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_malaysia_paid_geo_v1:a_control | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, control arm. |
| campaign:gpt_53_lupo_ctry_malaysia_paid_geo_v1:b_control_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, control arm. |
| campaign:gpt_53_lupo_ctry_malaysia_paid_geo_v1:c_treatment | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_malaysia_paid_geo_v1:d_treatment_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: paid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_spain_unpaid_geo_v1:a_control | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: unpaid tier, control arm. |
| campaign:gpt_53_lupo_ctry_spain_unpaid_geo_v1:b_control_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: unpaid tier, control arm. |
| campaign:gpt_53_lupo_ctry_spain_unpaid_geo_v1:c_treatment | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: unpaid tier, test/treatment arm. |
| campaign:gpt_53_lupo_ctry_spain_unpaid_geo_v1:d_treatment_fork | Model or experiment focused on multilingual, localization, or region-sensitive behavior; signals: unpaid tier, test/treatment arm. |
| Multilingual_Japan_v0_6 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_Brazil_v0_2 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_Brazil_v0_4 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_Germany_v0_0 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_Germany_v0_1 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_Germany_v1_2 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_India_v0_3 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_India_v1_1 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_India_v1_2 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_Indonesia_v0_2 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_Indonesia_v1_0 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_Indonesia_v1_2 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_Japan_v0_0 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_Japan_v0_2 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_Japan_v0_5 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_SouthKorea_v0_0 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_SouthKorea_v0_4 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |
| Multilingual_SouthKorea_v0_5 | Model or experiment focused on multilingual, localization, or region-sensitive behavior. |

## Coding, Data, and Structured Tasks (14)

| Model | Brief English role description |
|---|---|
| life science biotools ez test | Model or experiment focused on coding, functions, structured data, or task environments; signals: test/treatment arm. |
| Codex Personalization Gmai | Model or experiment focused on coding, functions, structured data, or task environments. |
| Karel BD D4 s1000 20260527 | Model or experiment focused on coding, functions, structured data, or task environments. |
| Karel BD D5 s1150 20260527 | Model or experiment focused on coding, functions, structured data, or task environments. |
| codex_u18_2026_04_23 | Model or experiment focused on coding, functions, structured data, or task environments. |
| karel-bd-c2-s1150-20260518-1150-8shard-2026-05-18-18-32 (ppo step 1150) | Model or experiment focused on coding, functions, structured data, or task environments; signals: RL signal. |
| karel-bd-c2-s900-20260517-900-8shard-2026-05-18-00-31 (ppo step 900) | Model or experiment focused on coding, functions, structured data, or task environments; signals: RL signal. |
| Karel D8 DelphiV4 m2.1 s1450 | Model or experiment focused on coding, functions, structured data, or task environments. |
| Karel D8 DelphiV4 m2.1 s1500 | Model or experiment focused on coding, functions, structured data, or task environments. |
| Karel d8_multi DelphiV4 S1000 | Model or experiment focused on coding, functions, structured data, or task environments. |
| bidi pro dual slim grammar with decoder fix | Model or experiment focused on coding, functions, structured data, or task environments; signals: Pro tier. |
| GPT 5.2 codex | Model or experiment focused on coding, functions, structured data, or task environments. |
| bidi pro dual slim grammar | Model or experiment focused on coding, functions, structured data, or task environments; signals: Pro tier. |
| Sean / Stanley Berry Grammar | Model or experiment focused on coding, functions, structured data, or task environments. |

## Training Runs and Checkpoints (28)

| Model | Brief English role description |
|---|---|
| campaign:local_synthetic_index:a_sft_v1_fixed_dogfood_current_index | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: SFT signal, dogfooding. |
| campaign:local_synthetic_index:b_sft_v1_fixed_dogfood_synthetic_index | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: SFT signal, dogfooding. |
| Dakota D1 S650 SFT Draft EV3 No Browse | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: SFT signal. |
| Andromeda RKLD Unpaid 0421 D1 650 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: unpaid tier, RL signal. |
| Dakota D1 S650 SFT Draft EV3 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: SFT signal. |
| GPT-5.3 old good Garlic DLE 2026-05-20 | Training run or checkpoint from SFT / RL / draft / step / shard-based development. |
| RV_Andromeda_rkld_unpaid_0421_D1_650 V2 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: unpaid tier, RL signal. |
| Andromeda RKLD WB paid 0428 t1 Feather | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: paid tier, low latency, RL signal. |
| Andromeda RKLD WB unpaid 0428 t1 Feather | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: unpaid tier, low latency, RL signal. |
| andromeda_rkld_wb_paid_0428_t1_instant | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: paid tier, low latency, RL signal. |
| lifesci rkld100 s80 -> rl s300 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: RL signal. |
| andromeda_rkld_latency_paid_0428 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: paid tier, RL signal. |
| andromeda_rkld_suffix_paid_0428 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: paid tier, RL signal. |
| Dakota D1 C0 SFT Draft EV3 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: SFT signal. |
| Dakota D1 C1 SFT Draft EV3 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: SFT signal. |
| Dakota D1 N0 SFT Draft EV3 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: SFT signal. |
| Dakota D1 N1 SFT Draft EV3 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: SFT signal. |
| hczhao_persimmon_sft | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: SFT signal. |
| andromeda_rkld_wb_paid_0429 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: paid tier, RL signal. |
| andromeda_rkld_wb_unpaid_0429 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: unpaid tier, RL signal. |
| IMO h3 RKLD | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: RL signal. |
| rkld_run3_s100_dogfood | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: RL signal, dogfooding. |
| bidi_05_06_clone | Training run or checkpoint from SFT / RL / draft / step / shard-based development. |
| 05_07_pro_clone | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: Pro tier. |
| 05_12_clone_final | Training run or checkpoint from SFT / RL / draft / step / shard-based development. |
| Yaro GPT-5.3 Instant DLE Rev5 | Training run or checkpoint from SFT / RL / draft / step / shard-based development; signals: low latency. |
| Yaro GPT-5.3 Tolo1 DLE May19 | Training run or checkpoint from SFT / RL / draft / step / shard-based development. |
| Yaro GPT-5.3 Tolo1 DLE Spud May19 | Training run or checkpoint from SFT / RL / draft / step / shard-based development. |

## Infrastructure, Routing, and Smoke Tests (14)

| Model | Brief English role description |
|---|---|
| campaign:5p1_smoke_paragen_manual_1027_try2:a_gpt5t_control | Infrastructure, routing, or smoke-test entry; signals: control arm, smoke testing. |
| campaign:5p1_smoke_paragen_manual_1027_try2:b_gpt5p1_smoke | Infrastructure, routing, or smoke-test entry; signals: smoke testing. |
| campaign:dummy_campaign:a_gpt52 | Infrastructure, routing, or smoke-test entry. |
| ChatGPT bridge snapshot compose s650 smoke | Infrastructure, routing, or smoke-test entry; signals: smoke testing. |
| ChatGPT bridge snapshot multiyield s650 smoke | Infrastructure, routing, or smoke-test entry; signals: smoke testing. |
| ChatGPT bridge snapshot proxy s650 smoke | Infrastructure, routing, or smoke-test entry; signals: smoke testing. |
| ChatGPT bridge snapshot r-c7 s650 smoke | Infrastructure, routing, or smoke-test entry; signals: smoke testing. |
| ChatGPT bridge snapshot repoint s650 smoke | Infrastructure, routing, or smoke-test entry; signals: smoke testing. |
| ChatGPT bridge snapshot s650 smoke | Infrastructure, routing, or smoke-test entry; signals: smoke testing. |
| andromeda_smoke_paid | Infrastructure, routing, or smoke-test entry; signals: paid tier, smoke testing. |
| andromeda_smoke_unpaid_1000 | Infrastructure, routing, or smoke-test entry; signals: unpaid tier, smoke testing. |
| andromeda_smoke_unpaid_1400 | Infrastructure, routing, or smoke-test entry; signals: unpaid tier, smoke testing. |
| 5p4r_mini_smoke | Infrastructure, routing, or smoke-test entry; signals: mini/compact variant, smoke testing. |
| 5p4r_mini_smoke_2 | Infrastructure, routing, or smoke-test entry; signals: mini/compact variant, smoke testing. |

## ChatGPT Product and General Assistant Variants (336)

| Model | Brief English role description |
|---|---|
| campaign:spot_20260128_default_paid_paragen:a_control | ChatGPT product or general assistant variant; signals: paid tier, control arm. |
| campaign:spot_20260128_default_paid_paragen:b_20260128_default_0 | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:spot_20260128_default_paid_paragen:c_20260128_default_1 | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:spot_20260128_default_paid_paragen:d_20260128_default_2 | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:spot_20260128_default_paid_paragen:e_20260128_default_3 | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:5p3_arm7_s950_vs_s1450_unpaid_v1:a_control | ChatGPT product or general assistant variant; signals: unpaid tier, control arm. |
| campaign:5p3_arm7_s950_vs_s1450_unpaid_v1:b_treatment | ChatGPT product or general assistant variant; signals: unpaid tier, test/treatment arm. |
| campaign:5p3_vs_chathack_s1000_paid:a_arm7 | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:4o_vs_52auto_paid:a_5p2auto | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:4o_vs_52auto_paid:b_4o | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:5p3_casual_formal_prompts_free:a_control | ChatGPT product or general assistant variant; signals: unpaid tier, control arm. |
| campaign:5p3_casual_formal_prompts_free:b_treatment | ChatGPT product or general assistant variant; signals: unpaid tier, test/treatment arm. |
| campaign:5p3_instant_mini_vs_5p3_instant_paid:a_control_5p3_instant | ChatGPT product or general assistant variant; signals: paid tier, low latency, control arm, mini/compact variant. |
| campaign:5p3_instant_mini_vs_5p3_instant_paid:b_5p3_instant_mini | ChatGPT product or general assistant variant; signals: paid tier, low latency, mini/compact variant. |
| campaign:5p3_nosearch_baseline__paid:a_prod | ChatGPT product or general assistant variant; signals: paid tier, baseline, production comparison. |
| campaign:5p3_vs_5p4r_unpaid_0404:a_5p3 | ChatGPT product or general assistant variant; signals: unpaid tier. |
| campaign:5p3_vs_5p4r_unpaid_0404:b_5p4r | ChatGPT product or general assistant variant; signals: unpaid tier. |
| campaign:5p3_vs_chathack_s1000_paid:b_hack_s1000 | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:5p3c_mini_arm3_vs_5p3c_paid2:a_control_5p3_instant | ChatGPT product or general assistant variant; signals: low latency, control arm, mini/compact variant. |
| campaign:5p3c_mini_arm3_vs_5p3c_paid2:b_sp_mini_chat_rev4_arm3 | ChatGPT product or general assistant variant; signals: mini/compact variant. |
| campaign:5p5_instant_free_professional_0512:a_control | ChatGPT product or general assistant variant; signals: unpaid tier, low latency, control arm. |
| campaign:5p5_instant_free_professional_0512:b_treatment | ChatGPT product or general assistant variant; signals: unpaid tier, low latency, test/treatment arm. |
| campaign:5p5_instant_paid_professional_0512:a_control | ChatGPT product or general assistant variant; signals: paid tier, low latency, control arm. |
| campaign:5p5_instant_paid_professional_0512:b_treatment | ChatGPT product or general assistant variant; signals: paid tier, low latency, test/treatment arm. |
| campaign:5p5_instant_pro_professional_0512:a_control | ChatGPT product or general assistant variant; signals: Pro tier, low latency, control arm. |
| campaign:5p5_instant_pro_professional_0512:b_treatment | ChatGPT product or general assistant variant; signals: Pro tier, low latency, test/treatment arm. |
| campaign:chatgpt_mobile_two_line_entity_metadata_button_paid:a_control | ChatGPT product or general assistant variant; signals: paid tier, control arm. |
| campaign:chatgpt_mobile_two_line_entity_metadata_button_paid:b_test | ChatGPT product or general assistant variant; signals: paid tier, test/treatment arm. |
| campaign:chatgpt_mobile_two_line_entity_metadata_button_unpaid:a_control | ChatGPT product or general assistant variant; signals: unpaid tier, control arm. |
| campaign:chatgpt_mobile_two_line_entity_metadata_button_unpaid:b_test | ChatGPT product or general assistant variant; signals: unpaid tier, test/treatment arm. |
| campaign:chatgpt_mobile_two_line_entity_metadata_paid:a_control | ChatGPT product or general assistant variant; signals: paid tier, control arm. |
| campaign:chatgpt_mobile_two_line_entity_metadata_paid:b_test | ChatGPT product or general assistant variant; signals: paid tier, test/treatment arm. |
| campaign:chatgpt_mobile_two_line_entity_metadata_unpaid:a_control | ChatGPT product or general assistant variant; signals: unpaid tier, control arm. |
| campaign:chatgpt_mobile_two_line_entity_metadata_unpaid:b_test | ChatGPT product or general assistant variant; signals: unpaid tier, test/treatment arm. |
| campaign:cw_para_paid_auto_55_writing_comm_v1:a_control | ChatGPT product or general assistant variant; signals: paid tier, control arm. |
| campaign:cw_para_paid_auto_55_writing_comm_v1:b_long_para | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:cw_para_paid_auto_55_writing_comm_v1:c_exclusive_para | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:cw_para_paid_auto_55_writing_comm_v1:d_avoid_frag | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:gpt52_vs_4o_unpaid:a_5p2 | ChatGPT product or general assistant variant; signals: unpaid tier. |
| campaign:gpt52_vs_4o_unpaid:b_4o_gg | ChatGPT product or general assistant variant; signals: unpaid tier. |
| campaign:gpt5_2_longer_ctx_free_paragen:a_prod | ChatGPT product or general assistant variant; signals: unpaid tier, production comparison. |
| campaign:gpt5_2_longer_ctx_free_paragen:b_long_n_ctx | ChatGPT product or general assistant variant; signals: unpaid tier. |
| campaign:gpt5p1_smoketest_paragen_auto:a_gpt5p1_smoketest | ChatGPT product or general assistant variant. |
| campaign:gpt_55r_iid:a_control | ChatGPT product or general assistant variant; signals: control arm. |
| campaign:gpt_55r_iid:b_treatment | ChatGPT product or general assistant variant; signals: test/treatment arm. |
| campaign:gpt_5_5_henry_free:a_control | ChatGPT product or general assistant variant; signals: unpaid tier, control arm. |
| campaign:gpt_5_5_henry_free:b_treatment | ChatGPT product or general assistant variant; signals: unpaid tier, test/treatment arm. |
| campaign:gpt_5_5_henry_paid:a_control | ChatGPT product or general assistant variant; signals: paid tier, control arm. |
| campaign:gpt_5_5_henry_paid:b_treatment | ChatGPT product or general assistant variant; signals: paid tier, test/treatment arm. |
| campaign:gpt_5_5_iid_free:a_control | ChatGPT product or general assistant variant; signals: unpaid tier, control arm. |
| campaign:gpt_5_5_iid_free:b_treatment | ChatGPT product or general assistant variant; signals: unpaid tier, test/treatment arm. |
| campaign:gpt_5_5_iid_paid:a_treatment | ChatGPT product or general assistant variant; signals: paid tier, test/treatment arm. |
| campaign:gpt_5_5_iid_paid:b_control | ChatGPT product or general assistant variant; signals: paid tier, control arm. |
| campaign:gpt_5_5_iid_pro:a_treatment | ChatGPT product or general assistant variant; signals: Pro tier, test/treatment arm. |
| campaign:gpt_5_5_iid_pro:b_control | ChatGPT product or general assistant variant; signals: Pro tier, control arm. |
| campaign:gpt_5_5_lupo_free:a_control | ChatGPT product or general assistant variant; signals: unpaid tier, control arm. |
| campaign:gpt_5_5_lupo_free:b_treatment | ChatGPT product or general assistant variant; signals: unpaid tier, test/treatment arm. |
| campaign:gpt_5_5_lupo_free:c_treatment_fork | ChatGPT product or general assistant variant; signals: unpaid tier, test/treatment arm. |
| campaign:gpt_5_5_lupo_paid:a_control | ChatGPT product or general assistant variant; signals: paid tier, control arm. |
| campaign:gpt_5_5_lupo_paid:b_treatment | ChatGPT product or general assistant variant; signals: paid tier, test/treatment arm. |
| campaign:gpt_5_5_lupo_paid:c_treatment_fork | ChatGPT product or general assistant variant; signals: paid tier, test/treatment arm. |
| campaign:gpt_5_5_lupo_pro:a_control | ChatGPT product or general assistant variant; signals: Pro tier, control arm. |
| campaign:gpt_5_5_lupo_pro:b_treatment | ChatGPT product or general assistant variant; signals: Pro tier, test/treatment arm. |
| campaign:gpt_5_5_lupo_pro:c_treatment_fork | ChatGPT product or general assistant variant; signals: Pro tier, test/treatment arm. |
| campaign:gpt_5p2_concise_more_paid:a_control | ChatGPT product or general assistant variant; signals: paid tier, control arm. |
| campaign:gpt_5p2_concise_more_paid:b_treatment | ChatGPT product or general assistant variant; signals: paid tier, test/treatment arm. |
| campaign:gpt_5p5r_iid_pro:a_control | ChatGPT product or general assistant variant; signals: Pro tier, control arm. |
| campaign:gpt_5p5r_iid_pro:b_treatment | ChatGPT product or general assistant variant; signals: Pro tier, test/treatment arm. |
| campaign:gpt_5p5r_lupo_paid:a_control | ChatGPT product or general assistant variant; signals: paid tier, control arm. |
| campaign:gpt_5p5r_lupo_paid:b_treatment | ChatGPT product or general assistant variant; signals: paid tier, test/treatment arm. |
| campaign:gpt_5p5r_lupo_paid:c_treatment_fork | ChatGPT product or general assistant variant; signals: paid tier, test/treatment arm. |
| campaign:gpt_5p5r_lupo_pro:a_control | ChatGPT product or general assistant variant; signals: Pro tier, control arm. |
| campaign:gpt_5p5r_lupo_pro:b_treatment | ChatGPT product or general assistant variant; signals: Pro tier, test/treatment arm. |
| campaign:gpt_5p5r_lupo_pro:c_treatment_fork | ChatGPT product or general assistant variant; signals: Pro tier, test/treatment arm. |
| campaign:paid_auto_chat_sys2_only_vs_sys1_only_5p3_paragen:b_oai_index_only | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:paid_auto_chat_sys2_vs_sys1_5p5i_perma_pg_v2:b_oai_index_only | ChatGPT product or general assistant variant; signals: paid tier. |
| campaign:tiancheng_5p2_241212_rewriting:a_2_step_gen | ChatGPT product or general assistant variant. |
| campaign:tiancheng_5p2_241212_rewriting:b_3_step_gen | ChatGPT product or general assistant variant. |
| campaign:tiancheng_5p2_241212_rewriting:c_1_step_gen | ChatGPT product or general assistant variant. |
| campaign:yilin_capability_targeting_gpt_52_iid_free:a_control | ChatGPT product or general assistant variant; signals: unpaid tier, control arm. |
| campaign:yilin_capability_targeting_gpt_52_iid_free:b_treatment | ChatGPT product or general assistant variant; signals: unpaid tier, test/treatment arm. |
| 5p2-tables | ChatGPT product or general assistant variant. |
| mainline gpt-4o-mini: (biz_no_browse_with_canvas) | ChatGPT product or general assistant variant; signals: mini/compact variant. |
| mainline gpt-4o-mini: (biz_with_canvas) | ChatGPT product or general assistant variant; signals: mini/compact variant. |
| mainline gpt-4o: (biz_no_browse_with_canvas) | ChatGPT product or general assistant variant. |
| mainline gpt-4o: (biz_with_canvas) | ChatGPT product or general assistant variant. |
| presearch_mainline_0528 | ChatGPT product or general assistant variant. |
| andromeda_atc_parrot_0514 | ChatGPT product or general assistant variant. |
| mainline gpt-4o-mini: (biz_no_browse) | ChatGPT product or general assistant variant; signals: mini/compact variant. |
| mainline gpt-4o: (biz_no_browse) | ChatGPT product or general assistant variant. |
| 011526_default_person_inst | ChatGPT product or general assistant variant. |
| andromeda_d1_s1250_unpaid_p13nmiti | ChatGPT product or general assistant variant; signals: unpaid tier. |
| andromeda_d1_s1400_unpaid_p13nmiti | ChatGPT product or general assistant variant; signals: unpaid tier. |
| garlic_a19_fingerling_54t_s240 | ChatGPT product or general assistant variant. |
| garlic_jsd_a19_fingerling_54t_s240 | ChatGPT product or general assistant variant. |
| 5p2_spot_hhcheckpoint_paid_v1 | ChatGPT product or general assistant variant; signals: paid tier. |
| 5p2_spot_hhcheckpoint_unpaid_v1 | ChatGPT product or general assistant variant; signals: unpaid tier. |
| garlic_longer_context_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier. |
| Sonic Switcher Old 10/16 | ChatGPT product or general assistant variant. |
| bidi_backend_gpt55_instant_260520 | ChatGPT product or general assistant variant; signals: low latency. |
| bidi_backend_gpt55_instant_260527 | ChatGPT product or general assistant variant; signals: low latency. |
| Auto Switcher Paid 20250804 | ChatGPT product or general assistant variant; signals: paid tier. |
| 5p4-chat-e2-baseline | ChatGPT product or general assistant variant; signals: baseline. |
| Bidi backend gpt5.5 instant XL testing | ChatGPT product or general assistant variant; signals: low latency. |
| ChatGPT bridge snapshot dynamic probe on r-c3-ev3-lutetium-d000-i000 | ChatGPT product or general assistant variant. |
| ChatGPT bridge snapshot probe | ChatGPT product or general assistant variant. |
| GPT-4.5 Mainline | ChatGPT product or general assistant variant. |
| PAGI Mainline Slot 0 | ChatGPT product or general assistant variant. |
| PAGI Mainline Slot 1 | ChatGPT product or general assistant variant. |
| PAGI Mainline Slot 2 | ChatGPT product or general assistant variant. |
| PAGI Mainline Slot 3 | ChatGPT product or general assistant variant. |
| chatgpt_bridge_snapshot_probe_vm_mutated | ChatGPT product or general assistant variant. |
| rashad_testing_mainline_searc | ChatGPT product or general assistant variant. |
| yungsung-5p5-baseline-5p4g-s300 | ChatGPT product or general assistant variant; signals: baseline. |
| yungsung_baseline_5p1 | ChatGPT product or general assistant variant; signals: baseline. |
| mainline_follow_up_fix | ChatGPT product or general assistant variant. |
| mainline_follow_up_fix_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier. |
| mainline_holdout_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier, holdout arm. |
| mainline gpt-4: (biz) | ChatGPT product or general assistant variant. |
| mainline gpt-4: (paid) | ChatGPT product or general assistant variant; signals: paid tier. |
| mainline gpt-4: (pro) | ChatGPT product or general assistant variant; signals: Pro tier. |
| mainline gpt-4o-canmore: (pro) | ChatGPT product or general assistant variant; signals: Pro tier. |
| mainline gpt-4o-mini: (biz) | ChatGPT product or general assistant variant; signals: mini/compact variant. |
| mainline gpt-4o-mini: (paid) | ChatGPT product or general assistant variant; signals: paid tier, mini/compact variant. |
| mainline gpt-4o-mini: (pro) | ChatGPT product or general assistant variant; signals: Pro tier, mini/compact variant. |
| mainline gpt-4o-mini: (unpaid) | ChatGPT product or general assistant variant; signals: unpaid tier, mini/compact variant. |
| mainline gpt-4o: (biz) | ChatGPT product or general assistant variant. |
| mainline gpt-4o: (paid) | ChatGPT product or general assistant variant; signals: paid tier. |
| mainline gpt-4o: (pro) | ChatGPT product or general assistant variant; signals: Pro tier. |
| mainline gpt-4o: (unpaid) | ChatGPT product or general assistant variant; signals: unpaid tier. |
| mainline o1-mini: (biz) | ChatGPT product or general assistant variant; signals: mini/compact variant. |
| mainline o1-mini: (paid) | ChatGPT product or general assistant variant; signals: paid tier, mini/compact variant. |
| mainline o1-mini: (pro) | ChatGPT product or general assistant variant; signals: Pro tier, mini/compact variant. |
| mainline o1-mini: (unpaid) | ChatGPT product or general assistant variant; signals: unpaid tier, mini/compact variant. |
| mainline o1-preview: (biz) | ChatGPT product or general assistant variant. |
| mainline o1-preview: (paid) | ChatGPT product or general assistant variant; signals: paid tier. |
| mainline o1-preview: (pro) | ChatGPT product or general assistant variant; signals: Pro tier. |
| mainline o3: (biz) | ChatGPT product or general assistant variant. |
| mainline o3: (paid) | ChatGPT product or general assistant variant; signals: paid tier. |
| mainline o3: (pro) | ChatGPT product or general assistant variant; signals: Pro tier. |
| mainline o4-mini: (biz) | ChatGPT product or general assistant variant; signals: mini/compact variant. |
| mainline o4-mini: (paid) | ChatGPT product or general assistant variant; signals: paid tier, mini/compact variant. |
| mainline o4-mini: (pro) | ChatGPT product or general assistant variant; signals: Pro tier, mini/compact variant. |
| mainline text-davinci-002-render-sha: (biz) | ChatGPT product or general assistant variant. |
| mainline text-davinci-002-render-sha: (paid) | ChatGPT product or general assistant variant; signals: paid tier. |
| mainline text-davinci-002-render-sha: (pro) | ChatGPT product or general assistant variant; signals: Pro tier. |
| mainline text-davinci-002-render-sha: (unpaid) | ChatGPT product or general assistant variant; signals: unpaid tier. |
| GPT-5.5 w/ Product Groups | ChatGPT product or general assistant variant. |
| GPT-5.5 unpaid local biz ctx 16k | ChatGPT product or general assistant variant; signals: unpaid tier, 16k context. |
| SP Mini Chat Rev2 Arm2 s600 | ChatGPT product or general assistant variant; signals: mini/compact variant. |
| bidi_be_gpt55_instant_260528 | ChatGPT product or general assistant variant; signals: low latency. |
| chatgpt_local_16k | ChatGPT product or general assistant variant; signals: 16k context. |
| spud_d64_pro_0320 | ChatGPT product or general assistant variant; signals: Pro tier. |
| andromeda_d10_2500_paid_0416 | ChatGPT product or general assistant variant; signals: paid tier. |
| andromeda_d10_2500_unpaid_0416 | ChatGPT product or general assistant variant; signals: unpaid tier. |
| chatgpt_ctx_window_holdback_paid_26_h1 | ChatGPT product or general assistant variant; signals: paid tier. |
| chatgpt_ctx_window_holdback_unpaid_26_h1_v2 | ChatGPT product or general assistant variant; signals: unpaid tier. |
| gpt55_chatrs_paid_260508 | ChatGPT product or general assistant variant; signals: paid tier. |
| gpt55_chatrs_yap2_paid_260515 | ChatGPT product or general assistant variant; signals: paid tier. |
| gpt55_pro_kc_202406 | ChatGPT product or general assistant variant; signals: Pro tier. |
| gpt55_spud_chat_paid_260527 | ChatGPT product or general assistant variant; signals: paid tier. |
| holdout_chat_gpt53_2026_05 | ChatGPT product or general assistant variant; signals: holdout arm. |
| paid_instant_andromeda_multisys_0516 | ChatGPT product or general assistant variant; signals: paid tier, low latency. |
| spot_20260130_default_paid | ChatGPT product or general assistant variant; signals: paid tier. |
| spot_20260130_default_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier. |
| spud_d64_chat_auto_paid_v3 | ChatGPT product or general assistant variant; signals: paid tier. |
| SP-Mini Chat Rev2 Arm4 s175 | ChatGPT product or general assistant variant; signals: mini/compact variant. |
| bidi-pro-05-07 | ChatGPT product or general assistant variant; signals: Pro tier. |
| bidi-pro-05-07-rd-testing | ChatGPT product or general assistant variant; signals: Pro tier. |
| gpt_5_3_mini_paid_04_17 | ChatGPT product or general assistant variant; signals: paid tier, mini/compact variant. |
| 5p3_separate_pool_unpaid_0217 | ChatGPT product or general assistant variant; signals: unpaid tier. |
| andromeda_d4_baby_fix_es8_paid_0427 | ChatGPT product or general assistant variant; signals: paid tier. |
| andromeda_d4_baby_fix_es8_unpaid_0427 | ChatGPT product or general assistant variant; signals: unpaid tier. |
| andromeda_e2_pers_0507_paid | ChatGPT product or general assistant variant; signals: paid tier. |
| paid_chat_cq_e7_multisys | ChatGPT product or general assistant variant; signals: paid tier. |
| paid_instant_cq_e7_multisys_0511 | ChatGPT product or general assistant variant; signals: paid tier, low latency. |
| paid_5p5_instant_multisys_d8_0521 | ChatGPT product or general assistant variant; signals: paid tier, low latency. |
| 4o with Proactive | ChatGPT product or general assistant variant. |
| 5.2 Chat Mini | ChatGPT product or general assistant variant; signals: mini/compact variant. |
| 5.3 Instant Feather | ChatGPT product or general assistant variant; signals: low latency. |
| 5.5i Feather | ChatGPT product or general assistant variant; signals: low latency. |
| 5p4r in chat | ChatGPT product or general assistant variant. |
| A12 Feather | ChatGPT product or general assistant variant; signals: low latency. |
| Andromeda D1 1400 GPT-5.3 Instant | ChatGPT product or general assistant variant; signals: low latency. |
| Andromeda E2 Pers1c S1000 Unpaid 0501 Feather | ChatGPT product or general assistant variant; signals: unpaid tier, low latency. |
| C2 Feather | ChatGPT product or general assistant variant; signals: low latency. |
| Current Pulse Expanded | ChatGPT product or general assistant variant. |
| Feather 4o | ChatGPT product or general assistant variant; signals: low latency. |
| GPT-5.2 Instant | ChatGPT product or general assistant variant; signals: low latency. |
| GPT-5.2 Pro Pathfinder | ChatGPT product or general assistant variant; signals: Pro tier. |
| GPT-5.3 Andromeda D11 Paid Dedicated | ChatGPT product or general assistant variant; signals: paid tier. |
| GPT-5.3 Auto Paid Boundary High | ChatGPT product or general assistant variant; signals: paid tier. |
| GPT-5.5 Instant | ChatGPT product or general assistant variant; signals: low latency. |
| Golden Alpha / 5p3 Auto Paid | ChatGPT product or general assistant variant; signals: paid tier. |
| Golden Alpha / 5p3 Instant | ChatGPT product or general assistant variant; signals: low latency. |
| Golden Alpha / Spud Chat | ChatGPT product or general assistant variant. |
| GoldenAlpha / 5.1 Instant | ChatGPT product or general assistant variant; signals: low latency. |
| Manuka Pers1c s1000 Feather | ChatGPT product or general assistant variant; signals: low latency. |
| Pro Galapagos | ChatGPT product or general assistant variant; signals: Pro tier. |
| Proactive Dreams | ChatGPT product or general assistant variant. |
| andromeda_atc_default_0515 | ChatGPT product or general assistant variant. |
| andromeda_golden_template_paid | ChatGPT product or general assistant variant; signals: paid tier. |
| andromeda_golden_template_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier. |
| andromeda_launch_auto_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier. |
| andromeda_launch_instant_paid | ChatGPT product or general assistant variant; signals: paid tier, low latency. |
| bidi-pro-latest | ChatGPT product or general assistant variant; signals: Pro tier. |
| bidi_pro_loadtest | ChatGPT product or general assistant variant; signals: Pro tier. |
| chat_cot_ui_constant_instant | ChatGPT product or general assistant variant; signals: low latency. |
| chat_cot_ui_constant_long_auto | ChatGPT product or general assistant variant. |
| chat_cot_ui_summary_auto | ChatGPT product or general assistant variant. |
| chat_cot_ui_summary_instant | ChatGPT product or general assistant variant; signals: low latency. |
| crest-pro-alpha | ChatGPT product or general assistant variant; signals: Pro tier. |
| evanz_pro_preamble_summarizer | ChatGPT product or general assistant variant; signals: Pro tier. |
| gpt 5.3 unpaid - | ChatGPT product or general assistant variant; signals: unpaid tier. |
| gpt_5_5_instant_model_aware_map | ChatGPT product or general assistant variant; signals: low latency. |
| instant_auto_1400_2_paid | ChatGPT product or general assistant variant; signals: paid tier, low latency. |
| instant_auto_1500_paid | ChatGPT product or general assistant variant; signals: paid tier, low latency. |
| prefix_compaction_5p5_instant_medium_ctx_window_single_summary | ChatGPT product or general assistant variant; signals: low latency. |
| prefix_compaction_5p5_instant_medium_ctx_window_single_summary_counter_factual | ChatGPT product or general assistant variant; signals: low latency. |
| robin_instant | ChatGPT product or general assistant variant; signals: low latency. |
| system_prompt_blocks_example_5p4 | ChatGPT product or general assistant variant. |
| test_block_current_gpt5_5_auto_paid | ChatGPT product or general assistant variant; signals: paid tier, test/treatment arm. |
| test_system_prompt_blocks_5_5_chat | ChatGPT product or general assistant variant; signals: test/treatment arm. |
| test_system_prompt_current_gpt5_5_auto_paid | ChatGPT product or general assistant variant; signals: paid tier, test/treatment arm. |
| tiancheng_5p2_system_prompt_tuner | ChatGPT product or general assistant variant. |
| 5p3_followups_dev_msg_paid_v1 | ChatGPT product or general assistant variant; signals: paid tier. |
| 5p3_large_context_free_v1 | ChatGPT product or general assistant variant; signals: unpaid tier. |
| 5p3_large_context_paid_v1 | ChatGPT product or general assistant variant; signals: paid tier. |
| 5p3_spmini_arm3_arm4_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier, mini/compact variant. |
| 5p3_stolo_paid_0224 | ChatGPT product or general assistant variant; signals: paid tier. |
| 5p5_auto_paid_longer_context_window | ChatGPT product or general assistant variant; signals: paid tier. |
| 5p5_auto_paid_very_long_context_window | ChatGPT product or general assistant variant; signals: paid tier. |
| andromeda_d1_s1250_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier. |
| andromeda_e2_pers3b_0511_free | ChatGPT product or general assistant variant; signals: unpaid tier. |
| andromeda_mono_hg_free | ChatGPT product or general assistant variant; signals: unpaid tier. |
| andromeda_mono_hg_paid | ChatGPT product or general assistant variant; signals: paid tier. |
| andromeda_mva2_0409_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier. |
| andromeda_no_chat_1_auto_switching | ChatGPT product or general assistant variant. |
| awchen_gpt5_5_unpaid_wid_sys1 | ChatGPT product or general assistant variant; signals: unpaid tier. |
| chat_exp_platform_test | ChatGPT product or general assistant variant; signals: test/treatment arm. |
| chatgpt_feedback_v2_free_auto | ChatGPT product or general assistant variant; signals: unpaid tier. |
| chatgpt_feedback_v2_paid_auto | ChatGPT product or general assistant variant; signals: paid tier. |
| chatgpt_jobs_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier. |
| chatgpt_mec_recent_convo_desc | ChatGPT product or general assistant variant. |
| cw_para_paid_auto_55_v1 | ChatGPT product or general assistant variant; signals: paid tier. |
| cw_para_paid_auto_v1 | ChatGPT product or general assistant variant; signals: paid tier. |
| gpt52_shrink_factor_paid | ChatGPT product or general assistant variant; signals: paid tier. |
| gpt53_alsoran_holdout_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier, holdout arm. |
| gpt55_auto_wb_pi_order_paid | ChatGPT product or general assistant variant; signals: paid tier. |
| gpt55_auto_wb_pi_order_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier. |
| gpt55_cotv5_instant_paid_v0 | ChatGPT product or general assistant variant; signals: paid tier, low latency. |
| gpt5_5_unpaid_mec_tbt_dedicated_v2 | ChatGPT product or general assistant variant; signals: unpaid tier. |
| gpt_55_fp32_paid | ChatGPT product or general assistant variant; signals: paid tier. |
| local_biz_ctx_gpt55_paid_v2 | ChatGPT product or general assistant variant; signals: paid tier. |
| local_biz_ctx_gpt55_unpaid | ChatGPT product or general assistant variant; signals: unpaid tier. |
| sonic_summary_message_paid_0415 | ChatGPT product or general assistant variant; signals: paid tier. |
| bidi-pro-04-13 | ChatGPT product or general assistant variant; signals: Pro tier. |
| bidi-pro-05-01 | ChatGPT product or general assistant variant; signals: Pro tier. |
| bidi-pro-05-13-XL-testing | ChatGPT product or general assistant variant; signals: Pro tier. |
| wb_devmsg_gpt55_pro | ChatGPT product or general assistant variant; signals: Pro tier. |
| gpt55_cotv5_pro_v0 | ChatGPT product or general assistant variant; signals: Pro tier. |
| 5p5_sys_prompt_test | ChatGPT product or general assistant variant; signals: test/treatment arm. |
| xueqing_gpt5p4_pro | ChatGPT product or general assistant variant; signals: Pro tier. |
| gpt55_53_mem_free | ChatGPT product or general assistant variant; signals: unpaid tier. |
| gpt55_54_mem_free | ChatGPT product or general assistant variant; signals: unpaid tier. |
| gpt_55_fp32_free | ChatGPT product or general assistant variant; signals: unpaid tier. |
| m3m_test_pro | ChatGPT product or general assistant variant; signals: Pro tier, test/treatment arm. |
| gpt55_tpp_pro_v0 | ChatGPT product or general assistant variant; signals: Pro tier. |
| gpt55_tpp_pro_v1 | ChatGPT product or general assistant variant; signals: Pro tier. |
| Potion 5rmini Pro | ChatGPT product or general assistant variant; signals: Pro tier. |
| spot_prompt_1219 | ChatGPT product or general assistant variant. |
| 5p4_0219_s1020_v4_pro | ChatGPT product or general assistant variant; signals: Pro tier. |
| o3 Pro | ChatGPT product or general assistant variant; signals: Pro tier. |
| 5p4_1020_pro | ChatGPT product or general assistant variant; signals: Pro tier. |
| gpt52_q1_2026_model_holdout | ChatGPT product or general assistant variant; signals: holdout arm. |
| andromeda_learning_blocks_trigger_v7 | ChatGPT product or general assistant variant. |
| andromeda_shopping_sysmsg_0507 | ChatGPT product or general assistant variant. |
| andromeda_learning_blocks_trigger_v8 | ChatGPT product or general assistant variant. |
| 5p5-pd-drop-a | ChatGPT product or general assistant variant. |
| Andromeda e2 s1500 | ChatGPT product or general assistant variant. |
| Calpico o3 | ChatGPT product or general assistant variant. |
| GPT 4o + Clickable Followups | ChatGPT product or general assistant variant. |
| GPT 5 Health Mode 2 | ChatGPT product or general assistant variant. |
| GPT 5.5 - Flaffy | ChatGPT product or general assistant variant. |
| GPT-5.5 with activation classifiers onboard | ChatGPT product or general assistant variant. |
| GPT-5.5-capability-separation | ChatGPT product or general assistant variant. |
| GPT5 Health Mode | ChatGPT product or general assistant variant. |
| GPT5 auto with sonic shopping | ChatGPT product or general assistant variant. |
| GPT5.5 + activations 05_22 | ChatGPT product or general assistant variant. |
| GPT5.5 dil_alpha2 | ChatGPT product or general assistant variant. |
| GoldenAlpha / 5.1 Auto | ChatGPT product or general assistant variant. |
| Health Connectors GPT-5 | ChatGPT product or general assistant variant. |
| RV Andromeda D10_2500 D10_1 V2 | ChatGPT product or general assistant variant. |
| RV Andromeda D10_2500 D10_2 V2 | ChatGPT product or general assistant variant. |
| Synapse Control | ChatGPT product or general assistant variant; signals: control arm. |
| Synapse Mitigation Capability Separation | ChatGPT product or general assistant variant. |
| gpt4o + Clickable DR Followups | ChatGPT product or general assistant variant. |
| gpt5.5-activations | ChatGPT product or general assistant variant. |
| o3 test ca | ChatGPT product or general assistant variant; signals: test/treatment arm. |
| pulse expanded variant B | ChatGPT product or general assistant variant. |
| pulse expanded variant C | ChatGPT product or general assistant variant. |
| pulse expanded variant D | ChatGPT product or general assistant variant. |
| pulse expanded variant E | ChatGPT product or general assistant variant. |
| sca_5p1_cheap_s350 | ChatGPT product or general assistant variant. |
| tiancheng_5p2_251211 | ChatGPT product or general assistant variant. |
| tiancheng_5p2_251211_plus | ChatGPT product or general assistant variant. |
| yungsung-5p2-pd-drop-a | ChatGPT product or general assistant variant. |
| 0511_sonic_sideline_gpt55_ab | ChatGPT product or general assistant variant. |
| 0511_sonic_sideline_modes_ab | ChatGPT product or general assistant variant. |
| 0511_sonic_sideline_modes_ab_gpt55 | ChatGPT product or general assistant variant. |
| 0511_sonic_sideline_modes_ab_v2 | ChatGPT product or general assistant variant. |
| 5p3_collab_utility_v1_4_sp | ChatGPT product or general assistant variant. |
| 5p3_collab_v1_5_sp | ChatGPT product or general assistant variant. |
| 5p3_separate_pool_tolo_0219v2 | ChatGPT product or general assistant variant. |
| 5p4_summary_v3 | ChatGPT product or general assistant variant. |
| andromeda_high_juice_autoswitch | ChatGPT product or general assistant variant. |
| andromeda_learning_blocks_staging | ChatGPT product or general assistant variant. |
| andromeda_learning_blocks_trigger_v2 | ChatGPT product or general assistant variant. |
| andromeda_shopping_sys_message_v1 | ChatGPT product or general assistant variant. |
| GPT-froge-hide-on-bush | ChatGPT product or general assistant variant. |
| o3 with connectors | ChatGPT product or general assistant variant. |
| ecosystem_5p3_rev2_v2 | ChatGPT product or general assistant variant. |
| spot_testing | ChatGPT product or general assistant variant. |
| GPT 5.5 s1350 | ChatGPT product or general assistant variant. |
| GPT 5.5 s1450 | ChatGPT product or general assistant variant. |
| GPT 5.5 s1500 | ChatGPT product or general assistant variant. |
| GPT-4o | ChatGPT product or general assistant variant. |
| GPT-5.2 | ChatGPT product or general assistant variant. |
| GPT-5.3 | ChatGPT product or general assistant variant. |
| GPT-5.5 | ChatGPT product or general assistant variant. |
| gpt 5-3 | ChatGPT product or general assistant variant. |
| gpt-4o | ChatGPT product or general assistant variant. |
| gpt-5-3 | ChatGPT product or general assistant variant. |
| gpt4o | ChatGPT product or general assistant variant. |
| gpt55_tpp_v0 | ChatGPT product or general assistant variant. |
| 5p1-s350 | ChatGPT product or general assistant variant. |

## General Research or Unclear (231)

| Model | Brief English role description |
|---|---|
| campaign:shashank_paragen_test6:a_control | General model family or research checkpoint with no clear product role inferable from the name; signals: control arm. |
| campaign:shashank_paragen_test6:b_treatment | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| campaign:test_shashank_aug_0217:a_control | General model family or research checkpoint with no clear product role inferable from the name; signals: control arm, test/treatment arm. |
| campaign:test_shashank_aug_0217:b_treatment | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| campaign:arm8g_s2100_paragen_inverted:a_step2100 | General model family or research checkpoint with no clear product role inferable from the name. |
| campaign:arm8g_s2100_paragen_inverted:b_control | General model family or research checkpoint with no clear product role inferable from the name; signals: control arm. |
| campaign:augmented_dev_msg_test:a_developer_prompt_append_extra_instructions | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| campaign:augmented_dev_msg_test:b_augment | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| campaign:gpt5p1_smoketest_paragen:a_gpt5p1_smoketest | General model family or research checkpoint with no clear product role inferable from the name. |
| campaign:gpt5p1_smoketest_paragen:b_gpt5p1_smoketest | General model family or research checkpoint with no clear product role inferable from the name. |
| campaign:instruction_gen_paragen_test:a_control | General model family or research checkpoint with no clear product role inferable from the name; signals: control arm, test/treatment arm. |
| campaign:instruction_gen_paragen_test:b_t1 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| campaign:model_aware_map:a_control | General model family or research checkpoint with no clear product role inferable from the name; signals: control arm. |
| campaign:model_aware_map:b_test | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| campaign:revamp3_shopping_unpaid_sysmsg:a_prod | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier, production comparison. |
| campaign:revamp3_shopping_unpaid_sysmsg:b_revampv3 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| campaign:revampv3_shopping_unpaid:a_prod_notools | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier, production comparison. |
| campaign:revampv3_shopping_unpaid:b_revampv3 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| campaign:shashank_paragen_test3:a_control | General model family or research checkpoint with no clear product role inferable from the name; signals: control arm. |
| campaign:shashank_paragen_test3:b_treatment | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| d8_delphiv4_w2p1_parrot_v2 | General model family or research checkpoint with no clear product role inferable from the name. |
| d8_delphiv4_w2p1_parrot_v2_paid | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| Deep Research Mini (Mar 24) | General model family or research checkpoint with no clear product role inferable from the name; signals: mini/compact variant. |
| Ghostrider final (no parrot) | General model family or research checkpoint with no clear product role inferable from the name. |
| Math blocks (allis 210) | General model family or research checkpoint with no clear product role inferable from the name. |
| math_blocks_allis_0210_exp | General model family or research checkpoint with no clear product role inferable from the name. |
| Kaus S1400 NoEmoji P13nFix Tolo | General model family or research checkpoint with no clear product role inferable from the name. |
| d8_s1400 baseline step 1400 | General model family or research checkpoint with no clear product role inferable from the name; signals: baseline. |
| C2 step 450 \ | General model family or research checkpoint with no clear product role inferable from the name. |
| evanz_fingerling_test | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| life sciences early access v1 | General model family or research checkpoint with no clear product role inferable from the name. |
| lifesciences burnout krao step40 | General model family or research checkpoint with no clear product role inferable from the name. |
| 5p4g-baseline | General model family or research checkpoint with no clear product role inferable from the name; signals: baseline. |
| A3 Baseline | General model family or research checkpoint with no clear product role inferable from the name; signals: baseline. |
| autoswitcher_paid_remove_dev_messages | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| Current Mercury d64 | General model family or research checkpoint with no clear product role inferable from the name. |
| Local Synthetic 600 | General model family or research checkpoint with no clear product role inferable from the name. |
| bd_shop_prompt_abl_0526_unpaid | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| Arm7 Paid with Local Changes | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| ads_self_knowledge_holdout_unpaid_0427 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier, holdout arm. |
| yanming_mva2_paid_04_07_02 | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| bd a14 s1100 paid j8 berry cs | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| ads_self_knowledge_long_holdout_unpaid_0508 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier, holdout arm. |
| wb_doc_boundary_ctl_g55_free_0518 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| wb_doc_boundary_ctl_g55_paid_0518 | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| 5.2 Minimal Sysprompt | General model family or research checkpoint with no clear product role inferable from the name. |
| COMBINATION_PROMPTS_V2_0_BASE | General model family or research checkpoint with no clear product role inferable from the name. |
| Daydream Full Convo Free | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| Golden Alpha / Bidi spmini | General model family or research checkpoint with no clear product role inferable from the name; signals: mini/compact variant. |
| Professional V5 | General model family or research checkpoint with no clear product role inferable from the name. |
| SP Mini Arm 4 | General model family or research checkpoint with no clear product role inferable from the name; signals: mini/compact variant. |
| an_formatting_prompt | General model family or research checkpoint with no clear product role inferable from the name. |
| d1 sys prompt rohan | General model family or research checkpoint with no clear product role inferable from the name. |
| miaolin_test_spmini | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm, mini/compact variant. |
| no-chatbait | General model family or research checkpoint with no clear product role inferable from the name. |
| spmini local synth | General model family or research checkpoint with no clear product role inferable from the name; signals: mini/compact variant. |
| system_prompt_blocks_example | General model family or research checkpoint with no clear product role inferable from the name. |
| test_cademy_prompt | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| 5p4r_mini_s210_paid | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier, mini/compact variant. |
| 5p4r_mini_s210_teams | General model family or research checkpoint with no clear product role inferable from the name; signals: mini/compact variant. |
| 5pt3_clickbait_fix_unpaid_v1 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| 5pt3_clickbait_fix_unpaid_v2 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| 5pt3_clickbait_upweighted_paid_v1 | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| ads_self_knowledge_long_holdout_unpaid_0501 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier, holdout arm. |
| emperical_priority_bump_free | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| generic_entity_paid_holdout | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier, holdout arm. |
| generic_entity_unpaid_holdout | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier, holdout arm. |
| lupoy_unpaid_0324 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| mec_holdout_paid_2 | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier, holdout arm. |
| no_money_ext_dedicate_free | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| renderer_nctx_buffer_paid | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| skills_enablement_for_paid_users | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| st_fully_system2_paid | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| vita_health_prompt_r3_0520_paid | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| vita_health_prompt_r4_0521_unpaid | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| wb_doc_boundary_ctl_g55_free_0513 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| wb_doc_boundary_ctl_g55_paid_0513 | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| wb_doc_boundary_g55_free_0513 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| wb_doc_boundary_g55_paid_0513 | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| write_block_dedicated_free | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| write_block_dedicated_free_v2 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| write_block_dedicated_free_v3 | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier. |
| write_block_dedicated_paid_v3 | General model family or research checkpoint with no clear product role inferable from the name; signals: paid tier. |
| xxiang_test_prompt_exp_0 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| Better Writing Prompt | General model family or research checkpoint with no clear product role inferable from the name. |
| current_bidi_mini_v2 | General model family or research checkpoint with no clear product role inferable from the name; signals: mini/compact variant. |
| dominik gruber | General model family or research checkpoint with no clear product role inferable from the name. |
| system_prompt_blocks_test | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| Current Mercury | General model family or research checkpoint with no clear product role inferable from the name. |
| Low NCTX | General model family or research checkpoint with no clear product role inferable from the name. |
| mec_holdout_free | General model family or research checkpoint with no clear product role inferable from the name; signals: unpaid tier, holdout arm. |
| 5_3_mini_test | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm, mini/compact variant. |
| test_system_prompt_5 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| C2_delphiv6_s450 | General model family or research checkpoint with no clear product role inferable from the name. |
| alsamer021726 | General model family or research checkpoint with no clear product role inferable from the name. |
| alsamer101625 | General model family or research checkpoint with no clear product role inferable from the name. |
| arcanine_s690 | General model family or research checkpoint with no clear product role inferable from the name. |
| bidi-05-06 | General model family or research checkpoint with no clear product role inferable from the name. |
| jane_nux_v6 | General model family or research checkpoint with no clear product role inferable from the name. |
| jj6a1150 | General model family or research checkpoint with no clear product role inferable from the name. |
| rev6 arm6 s1300 (2026-02-19 export) | General model family or research checkpoint with no clear product role inferable from the name. |
| yanming_test_04_06 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| yanming_test_04_06_03 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| 5p4r_s610_s930 | General model family or research checkpoint with no clear product role inferable from the name. |
| gan_availability_0527_v2 | General model family or research checkpoint with no clear product role inferable from the name. |
| yanming_test_05_27 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| ads_self_knowledge_holdout_go_0427 | General model family or research checkpoint with no clear product role inferable from the name; signals: holdout arm. |
| LMSYS - 5p4r - j128 (high) | General model family or research checkpoint with no clear product role inferable from the name. |
| User Signals Medley Model (s850) | General model family or research checkpoint with no clear product role inferable from the name. |
| alsamer100825 | General model family or research checkpoint with no clear product role inferable from the name. |
| bd a14 s1100 j8 berry cs | General model family or research checkpoint with no clear product role inferable from the name. |
| gift_80k | General model family or research checkpoint with no clear product role inferable from the name; signals: 80k context. |
| ads_self_knowledge_long_holdout_go_0508 | General model family or research checkpoint with no clear product role inferable from the name; signals: holdout arm. |
| d8_delphiv4_w2p1 | General model family or research checkpoint with no clear product role inferable from the name. |
| kenny_test_05_08 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| 5.5i / health sysmsg | General model family or research checkpoint with no clear product role inferable from the name. |
| Aidan Test | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| Bio Stream | General model family or research checkpoint with no clear product role inferable from the name. |
| Bristy Jan 29 | General model family or research checkpoint with no clear product role inferable from the name. |
| Cached Recent Convo | General model family or research checkpoint with no clear product role inferable from the name. |
| Creative V4 | General model family or research checkpoint with no clear product role inferable from the name. |
| Creative Writing | General model family or research checkpoint with no clear product role inferable from the name. |
| Creative Writing 🥄 | General model family or research checkpoint with no clear product role inferable from the name. |
| DBV4 Extra Log | General model family or research checkpoint with no clear product role inferable from the name. |
| Entity Sidebar (10/15) | General model family or research checkpoint with no clear product role inferable from the name. |
| Experimental DIL Alpha | General model family or research checkpoint with no clear product role inferable from the name. |
| Glean Demo | General model family or research checkpoint with no clear product role inferable from the name. |
| Gmail Dreamer | General model family or research checkpoint with no clear product role inferable from the name. |
| Golden Alpha / Bidi | General model family or research checkpoint with no clear product role inferable from the name. |
| Personal Context Ship Candidate | General model family or research checkpoint with no clear product role inferable from the name. |
| Personal Context v0.1 | General model family or research checkpoint with no clear product role inferable from the name. |
| Synth Data Spud 2 stage | General model family or research checkpoint with no clear product role inferable from the name. |
| TOLO DelphiV4 originalfresh S1050 | General model family or research checkpoint with no clear product role inferable from the name. |
| Test Onboarding model | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| alpha.bidi_05_12 | General model family or research checkpoint with no clear product role inferable from the name. |
| answer_highlighting | General model family or research checkpoint with no clear product role inferable from the name. |
| belbute dev rap | General model family or research checkpoint with no clear product role inferable from the name. |
| bidi-latest | General model family or research checkpoint with no clear product role inferable from the name. |
| bidi-nv4a-fe-bb | General model family or research checkpoint with no clear product role inferable from the name. |
| brandonw test 5.2 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| checklist_251219_append | General model family or research checkpoint with no clear product role inferable from the name. |
| citron_v4_noautoswitch | General model family or research checkpoint with no clear product role inferable from the name. |
| crest-alpha | General model family or research checkpoint with no clear product role inferable from the name. |
| drew_behavior_test01 | General model family or research checkpoint with no clear product role inferable from the name. |
| dynamic 52 | General model family or research checkpoint with no clear product role inferable from the name. |
| evanz test | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| evanz_test_1 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| evanz_testing_3 | General model family or research checkpoint with no clear product role inferable from the name. |
| feedback_alpha_v2 | General model family or research checkpoint with no clear product role inferable from the name. |
| galapagos-alpha | General model family or research checkpoint with no clear product role inferable from the name. |
| gan_availability_0515 | General model family or research checkpoint with no clear product role inferable from the name. |
| gan_no_entity_metadata_caching | General model family or research checkpoint with no clear product role inferable from the name. |
| garys_test_model | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| gpt54r xpanded db | General model family or research checkpoint with no clear product role inferable from the name. |
| hack_1400 | General model family or research checkpoint with no clear product role inferable from the name. |
| jane_nux_v2 | General model family or research checkpoint with no clear product role inferable from the name. |
| jane_nux_v3 | General model family or research checkpoint with no clear product role inferable from the name. |
| just a test | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| kennan_test | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| max_consecutive_model_messages | General model family or research checkpoint with no clear product role inferable from the name. |
| mm_2a1900_sys_msg | General model family or research checkpoint with no clear product role inferable from the name. |
| onboarding_bot_new | General model family or research checkpoint with no clear product role inferable from the name. |
| pauldb wrapper | General model family or research checkpoint with no clear product role inferable from the name. |
| random_test_model | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| rashad_testing_migration_2 | General model family or research checkpoint with no clear product role inferable from the name. |
| rastan_dil | General model family or research checkpoint with no clear product role inferable from the name. |
| romie_onboarding1 | General model family or research checkpoint with no clear product role inferable from the name. |
| romie_ratelimit1 | General model family or research checkpoint with no clear product role inferable from the name. |
| sherman-r4 | General model family or research checkpoint with no clear product role inferable from the name. |
| sherman_r4 | General model family or research checkpoint with no clear product role inferable from the name. |
| sherman_r5 | General model family or research checkpoint with no clear product role inferable from the name. |
| spud-0324-run1-54t-cbv9-teacher | General model family or research checkpoint with no clear product role inferable from the name. |
| spud-0324-run3-gpt54-teacher | General model family or research checkpoint with no clear product role inferable from the name. |
| tetaetata | General model family or research checkpoint with no clear product role inferable from the name. |
| tmp-test-alpha | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| will random testing | General model family or research checkpoint with no clear product role inferable from the name. |
| writing_id_match | General model family or research checkpoint with no clear product role inferable from the name. |
| xue_march_2 | General model family or research checkpoint with no clear product role inferable from the name. |
| yanming_test_05_19 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| yilei_paragen_title | General model family or research checkpoint with no clear product role inferable from the name. |
| 5p5r_large_context_v1 | General model family or research checkpoint with no clear product role inferable from the name. |
| ads_self_knowledge_long_holdout_go_0501 | General model family or research checkpoint with no clear product role inferable from the name; signals: holdout arm. |
| header_openings | General model family or research checkpoint with no clear product role inferable from the name. |
| model_aware_map_ab | General model family or research checkpoint with no clear product role inferable from the name. |
| onboarding_interview_mode | General model family or research checkpoint with no clear product role inferable from the name. |
| test_dev_message_experimnt | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| test_exp_raunak_2 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| text_exp_raunak_1 | General model family or research checkpoint with no clear product role inferable from the name. |
| xxiang_test_exp_11 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| Double Click | General model family or research checkpoint with no clear product role inferable from the name. |
| Jobs | General model family or research checkpoint with no clear product role inferable from the name. |
| MM-1b-s2450-sys-msg | General model family or research checkpoint with no clear product role inferable from the name. |
| bidi-juno-v20-v4 | General model family or research checkpoint with no clear product role inferable from the name. |
| bidi_renderer_2 | General model family or research checkpoint with no clear product role inferable from the name. |
| bidi_verbose_debug_engine | General model family or research checkpoint with no clear product role inferable from the name. |
| bowen_test | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| C2_s1200 | General model family or research checkpoint with no clear product role inferable from the name. |
| Chinese_Test_Style_v5 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| Florence 5p2t | General model family or research checkpoint with no clear product role inferable from the name. |
| Pers1c s1000 | General model family or research checkpoint with no clear product role inferable from the name. |
| chris_test_5_4 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| citron_v4 | General model family or research checkpoint with no clear product role inferable from the name. |
| citron_v5 | General model family or research checkpoint with no clear product role inferable from the name. |
| jj0cs1500 | General model family or research checkpoint with no clear product role inferable from the name. |
| tomye pc test off | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| tomye pc test on | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| D1 honest/h1 | General model family or research checkpoint with no clear product role inferable from the name. |
| D1 honest/h1 (v2) | General model family or research checkpoint with no clear product role inferable from the name. |
| High Reintro D11 | General model family or research checkpoint with no clear product role inferable from the name. |
| High reintro D11 s1500 | General model family or research checkpoint with no clear product role inferable from the name. |
| Low reintro D4 | General model family or research checkpoint with no clear product role inferable from the name. |
| Low reintro D4 s1500 | General model family or research checkpoint with no clear product role inferable from the name. |
| old_ht | General model family or research checkpoint with no clear product role inferable from the name. |
| test_render_revert | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| yungsung-pd-new | General model family or research checkpoint with no clear product role inferable from the name. |
| Joke Expert | General model family or research checkpoint with no clear product role inferable from the name. |
| No Money Extreme | General model family or research checkpoint with no clear product role inferable from the name. |
| fp_refresh_e2_s150 | General model family or research checkpoint with no clear product role inferable from the name. |
| henry_vs_system | General model family or research checkpoint with no clear product role inferable from the name. |
| jou_test | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| new_ht | General model family or research checkpoint with no clear product role inferable from the name. |
| qwe | General model family or research checkpoint with no clear product role inferable from the name. |
| tomye test 01 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| tomye_test | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| yungsung_qwe2 | General model family or research checkpoint with no clear product role inferable from the name. |
| tmp_experiment_0511 | General model family or research checkpoint with no clear product role inferable from the name. |
| tomye_test_2 | General model family or research checkpoint with no clear product role inferable from the name; signals: test/treatment arm. |
| yungsung_2 | General model family or research checkpoint with no clear product role inferable from the name. |
| yungsung_5 | General model family or research checkpoint with no clear product role inferable from the name. |
| yungsung_tmp1 | General model family or research checkpoint with no clear product role inferable from the name. |
| iris | General model family or research checkpoint with no clear product role inferable from the name. |

