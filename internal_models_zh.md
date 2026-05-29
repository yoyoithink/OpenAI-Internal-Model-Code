# 内部模型 - 中文整理归类

> 说明：分类和作用说明仅根据模型名称关键词推断，并非官方元数据。
> 每个模型只归入一个推断的主能力/领域类别；组内顺序按源文件中首次出现顺序保留。

唯一模型数：1639

## 分类汇总

| 分类 | 数量 |
|---|---:|
| 搜索、浏览与检索 | 173 |
| 推理与深度思考 | 125 |
| 图像、视觉与多模态 | 45 |
| 音频、语音与实时交互 | 30 |
| Artifacts、界面与文档工具 | 131 |
| Agent、工具调用与自动化 | 29 |
| 个性化、记忆与语气 | 382 |
| 评估、打分与裁判 | 24 |
| 安全、政策与信任 | 27 |
| 本地化、语言与地区 | 50 |
| 代码、数据与结构化任务 | 14 |
| 训练运行与检查点 | 28 |
| 基础设施、路由与冒烟测试 | 14 |
| ChatGPT 产品与通用助手变体 | 336 |
| 通用研究或用途不明 | 231 |

## 搜索、浏览与检索 (173)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:5p5_paid_search_16k_0519:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、16k 上下文、对照组。 |
| campaign:5p5_paid_search_16k_0519:b_test | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、16k 上下文、测试/处理组。 |
| campaign:5p5_paid_search_16k_0520:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、16k 上下文、对照组。 |
| campaign:5p5_paid_search_16k_0520:b_test | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、16k 上下文、测试/处理组。 |
| campaign:bd_a3_web_mec_unpaid_0516:a_a3_s1100 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| campaign:bd_a3_web_mec_unpaid_0516:b_a3_web_mec_s1100 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| campaign:bd_a3_web_unpaid_0516:a_a3_s1100 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| campaign:bd_a3_web_unpaid_0516:b_a3_web_s1100 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_20260226:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、对照组、预取行为。 |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_20260226:b_always_prefetch | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、预取行为。 |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_20260226:c_normal_prefetch | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、预取行为。 |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_20260226:d_common_keywords | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、预取行为。 |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_webonly_20260303:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、对照组、预取行为。 |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_webonly_20260303:b_always_prefetch | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、预取行为。 |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_webonly_20260303:c_normal_prefetch | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、预取行为。 |
| campaign:chatgpt_learning_blocks_unpaid_prefetch_webonly_20260303:d_common_keywords | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、预取行为。 |
| campaign:mainline_no_search_vs_sonicthinky_d64:a_prod | 关注搜索、浏览或网页检索的模型或实验；名称信号：生产对比。 |
| campaign:mainline_no_search_vs_sonicthinky_d64:b_prod_no_search | 关注搜索、浏览或网页检索的模型或实验；名称信号：生产对比。 |
| campaign:mainline_no_search_vs_sonicthinky_d64:c_sonicthinky_d64_sideline | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:search_d64_prefetch_paid_0304:a_current_prod | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、生产对比、预取行为。 |
| campaign:search_d64_prefetch_paid_0304:b_d64_prefetch | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、预取行为。 |
| campaign:5p2_force_search_newsys_paid_0127:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、对照组。 |
| campaign:5p2_force_search_newsys_paid_0127:b_treatment | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:5p2_force_search_newsys_paid_0127:c_baseline | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、基线。 |
| campaign:5p3_arm7_enforce_recency_paid:a_current_prod | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、生产对比。 |
| campaign:5p3_arm7_enforce_recency_paid:b_enforce_recency | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| campaign:5p3_arm7_force_recency:a_current_prod | 关注搜索、浏览或网页检索的模型或实验；名称信号：生产对比。 |
| campaign:5p3_moresearch_nosearch_tolo1_s1450_0227:a_more_search | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:5p3_moresearch_nosearch_tolo1_s1450_0227:b_no_search | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:5p5_free_search_subagent_spmini_1hop_lc_0517:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、对照组、subagent 路由、mini/紧凑变体、单跳检索。 |
| campaign:5p5_free_search_subagent_spmini_1hop_lc_0517:b_test | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、测试/处理组、subagent 路由、mini/紧凑变体、单跳检索。 |
| campaign:5p5_paid_search_subagent_spmini_1hop_lc_0518:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、对照组、subagent 路由、mini/紧凑变体、单跳检索。 |
| campaign:5p5_paid_search_subagent_spmini_1hop_lc_0518:b_test | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、测试/处理组、subagent 路由、mini/紧凑变体、单跳检索。 |
| campaign:5p3_nosearch_baseline__paid:b_no_search | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、基线。 |
| campaign:5p5_paid_search_subagent_nv4_0511:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、对照组、subagent 路由。 |
| campaign:5p5_paid_search_subagent_nv4_0511:b_test | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、测试/处理组、subagent 路由。 |
| campaign:5p5_paid_search_subagent_nv4_latency_control_0511:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、对照组、subagent 路由。 |
| campaign:5p5_paid_search_subagent_nv4_latency_control_0511:b_test | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、对照组、测试/处理组、subagent 路由。 |
| campaign:5p5_paid_search_subagent_spmini_1hop_lc_0515:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、对照组、subagent 路由、mini/紧凑变体、单跳检索。 |
| campaign:5p5_paid_search_subagent_spmini_1hop_lc_0515:b_test | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、测试/处理组、subagent 路由、mini/紧凑变体、单跳检索。 |
| campaign:5p5_paid_search_subagent_spmini_1hop_lc_0519:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、对照组、subagent 路由、mini/紧凑变体、单跳检索。 |
| campaign:5p5_paid_search_subagent_spmini_1hop_lc_0519:b_test | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、测试/处理组、subagent 路由、mini/紧凑变体、单跳检索。 |
| campaign:5p5_unpaid_search_subagent_spmini_1hop_lc_0519:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、对照组、subagent 路由、mini/紧凑变体、单跳检索。 |
| campaign:5p5_unpaid_search_subagent_spmini_1hop_lc_0519:b_test | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、测试/处理组、subagent 路由、mini/紧凑变体、单跳检索。 |
| campaign:andromeda_e2_web_fl_0429_v1:a_e2_s1250 | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:andromeda_e2_web_fl_0429_v1:b_e2_web_flock_s1250 | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:andromeda_e2_web_fl_0501:a_e2_s1500 | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:andromeda_e2_web_fl_0501:b_e2_web_fl_0501_s1500 | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:andromeda_e2_web_fl_0505_resume:a_e2_s1500 | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:andromeda_e2_web_fl_0505_resume:b_e2_web_fl_0505_resume_s1500 | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:andromeda_e2_web_fl_s1500:a_e2_s1250 | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:andromeda_e2_web_fl_s1500:b_e2_web_flock_s1500 | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:garlic_vs_spmini_search_unpaid:a_prod | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、生产对比、mini/紧凑变体。 |
| campaign:garlic_vs_spmini_search_unpaid:b_spmini | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、mini/紧凑变体。 |
| campaign:gpt_52_search_vs_nosearch_paid:a_no_browse | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| campaign:gpt_52_search_vs_nosearch_paid:b_force_search | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| campaign:index_eval_sys2_vs_sys1_5p5i_perma_pg_v3:a_serp_only | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:paid_auto_chat_sys2_only_vs_sys1_only_5p3_paragen:a_serp_only | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| campaign:paid_auto_chat_sys2_vs_sys1_5p5i_perma_pg_v2:a_serp_only | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| campaign:search_fr_with_mini_free_users_0415:a_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、对照组、mini/紧凑变体。 |
| campaign:search_fr_with_mini_free_users_0415:b_test | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、测试/处理组、mini/紧凑变体。 |
| campaign:serp_for_product_0514:a_prod | 关注搜索、浏览或网页检索的模型或实验；名称信号：生产对比。 |
| campaign:serp_for_product_0514:b_serp_products | 关注搜索、浏览或网页检索的模型或实验。 |
| campaign:web_links_0323_paid_link_dev_short:a_link_dev_short | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| campaign:web_links_0323_paid_link_dev_short:b_control | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、对照组。 |
| campaign:web_links_dogfood_unpaid:a_dogfood | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、内部试用(dogfooding)。 |
| Yaroslav GPT-5.3 search-parrot DLE probe 2026-05-20 | 关注搜索、浏览或网页检索的模型或实验。 |
| Yaroslav GPT-5.5 search DLE probe 2026-05-20 | 关注搜索、浏览或网页检索的模型或实验。 |
| 5p5_free_search_spmini_1h_0526 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、mini/紧凑变体。 |
| 5p5_free_search_will_spmini_0526 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、mini/紧凑变体。 |
| 5p5_paid_search_spmini_1h_0526 | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、mini/紧凑变体。 |
| 5p5_paid_search_spmini_w_0526 | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、mini/紧凑变体。 |
| bd_web_features_0516_ab_paid | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| bd_web_features_0516_ab_unpaid | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| search_big_dipper_ns_thresh_016_05_21 | 关注搜索、浏览或网页检索的模型或实验。 |
| AD web links 0427 | 关注搜索、浏览或网页检索的模型或实验。 |
| AD web links 0427 hillclimb 0428 | 关注搜索、浏览或网页检索的模型或实验。 |
| Arm7 Meant for Search Prefetch | 关注搜索、浏览或网页检索的模型或实验；名称信号：预取行为。 |
| 0427_search_classifier_v2 | 关注搜索、浏览或网页检索的模型或实验。 |
| andromeda_arm7_search_05_15 | 关注搜索、浏览或网页检索的模型或实验。 |
| andromeda_web_features_0407_ab_v3 | 关注搜索、浏览或网页检索的模型或实验。 |
| andromeda_web_features_0427_ab | 关注搜索、浏览或网页检索的模型或实验。 |
| shortprompts_search_0507 | 关注搜索、浏览或网页检索的模型或实验。 |
| shortprompts_search_0507_paid | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| 5p5 instant paid sys2 only with search subagent spmini 1 hop w 0508 | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、低延迟、subagent 路由、mini/紧凑变体。 |
| LMSYS - gpt5p2r + search j=128 2k | 关注搜索、浏览或网页检索的模型或实验；名称信号：2k 上下文。 |
| LMSYS - gpt5p2r + search j=128 4k | 关注搜索、浏览或网页检索的模型或实验；名称信号：4k 上下文。 |
| LMSYS - gpt5p2r + search juice=128 | 关注搜索、浏览或网页检索的模型或实验。 |
| LMSYS - gpt5r + search j=128 | 关注搜索、浏览或网页检索的模型或实验。 |
| Search subagent spmini 1 hop w 0508 | 关注搜索、浏览或网页检索的模型或实验；名称信号：subagent 路由、mini/紧凑变体。 |
| 5p5_free_search_spmini_1h_s_0528 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、mini/紧凑变体。 |
| 5p5_free_search_spmini_1h_w_0528 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、mini/紧凑变体。 |
| 5p5_paid_search_spmini_1h_s_0528 | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、mini/紧凑变体。 |
| 5p5_paid_search_spmini_1h_w_0528 | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、mini/紧凑变体。 |
| andromeda_web_flock_0508_ab | 关注搜索、浏览或网页检索的模型或实验。 |
| 5.3 fast model prefetch 0422 | 关注搜索、浏览或网页检索的模型或实验；名称信号：预取行为。 |
| 5p5 instant paid sys2 only with search subagent nv4 multihop | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、低延迟、subagent 路由。 |
| 5p5 instant paid sys2 only with search subagent spmini 1 hop s 0515 | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、低延迟、subagent 路由、mini/紧凑变体。 |
| 5p5 instant unpaid sys2 only with search subagent nv4 multihop | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、低延迟、subagent 路由。 |
| 5p5 instant unpaid with search subagent nv4 multihop | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、低延迟、subagent 路由。 |
| Andromeda E2 Web Flock 0501 Resue s1500 | 关注搜索、浏览或网页检索的模型或实验。 |
| Andromeda E2 Web Flock 0501 s1500 v2 | 关注搜索、浏览或网页检索的模型或实验。 |
| Andromeda Search on Short Prompts | 关注搜索、浏览或网页检索的模型或实验。 |
| BD A3 Web MEC s1100 unpaid | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| GPT 5.3 fast model prefetch evals | 关注搜索、浏览或网页检索的模型或实验；名称信号：预取行为。 |
| GPT-5.5 / Product Groups + No Search | 关注搜索、浏览或网页检索的模型或实验。 |
| Igglypuff Search Vibe Testing | 关注搜索、浏览或网页检索的模型或实验。 |
| LMSYS - 5.3 (chat) + search | 关注搜索、浏览或网页检索的模型或实验。 |
| LMSYS - gpt5.4 + search | 关注搜索、浏览或网页检索的模型或实验。 |
| LMSYS - gpt5.5 + search | 关注搜索、浏览或网页检索的模型或实验。 |
| LMSYS - gpt5p2r + search j=512 2k | 关注搜索、浏览或网页检索的模型或实验；名称信号：2k 上下文。 |
| LMSYS - gpt5r + search | 关注搜索、浏览或网页检索的模型或实验。 |
| Search Fetch Timeout A | 关注搜索、浏览或网页检索的模型或实验。 |
| Search Fetch Timeout B | 关注搜索、浏览或网页检索的模型或实验。 |
| Search Fetch Timeout C | 关注搜索、浏览或网页检索的模型或实验。 |
| Search Fetch Timeout D | 关注搜索、浏览或网页检索的模型或实验。 |
| Search Subagent nv4 multihop | 关注搜索、浏览或网页检索的模型或实验；名称信号：subagent 路由。 |
| Search cache experiment, p90 | 关注搜索、浏览或网页检索的模型或实验。 |
| Search subagent 1 hop v2 | 关注搜索、浏览或网页检索的模型或实验；名称信号：subagent 路由。 |
| Search subagent spmini 1 hop s 0515 | 关注搜索、浏览或网页检索的模型或实验；名称信号：subagent 路由、mini/紧凑变体。 |
| V3 search subagent spmini | 关注搜索、浏览或网页检索的模型或实验；名称信号：subagent 路由、mini/紧凑变体。 |
| Yaro GPT-5.5 search summarization DLE | 关注搜索、浏览或网页检索的模型或实验。 |
| alpha.bd_a3_web_mec_s1100_unpaid | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| andromeda_launch_auto_no_browse_unpaid | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| andromeda_launch_instant_no_browse_paid | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、低延迟。 |
| big_dipper_c2_gdreams_search_extract_always | 关注搜索、浏览或网页检索的模型或实验。 |
| big_dipper_c2_gdreams_search_extract_always_v2 | 关注搜索、浏览或网页检索的模型或实验。 |
| big_dipper_c2_gdreams_search_extract_relaxed | 关注搜索、浏览或网页检索的模型或实验。 |
| big_dipper_c2_gdreams_search_extract_relaxed_v2 | 关注搜索、浏览或网页检索的模型或实验。 |
| gan_web_location_tool_0423 | 关注搜索、浏览或网页检索的模型或实验。 |
| gan_web_location_tool_0429 | 关注搜索、浏览或网页检索的模型或实验。 |
| gpt5p2r + search | 关注搜索、浏览或网页检索的模型或实验。 |
| job_search_reasoning_paid | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| synthetic_local_search_bramnani | 关注搜索、浏览或网页检索的模型或实验。 |
| 0430__search_classifier_v2 | 关注搜索、浏览或网页检索的模型或实验。 |
| 5p3_free_search_engine_holdout | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、保留组。 |
| 5p3_search_holdout_unpaid_0303 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、保留组。 |
| 5p5_free_search_subagent_spmini_1hop_0520 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、subagent 路由、mini/紧凑变体、单跳检索。 |
| 5p5_free_search_subagent_will_spmini_0520 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、subagent 路由、mini/紧凑变体。 |
| 5p5_paid_search_subagent_spmini_1hop_0520 | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、subagent 路由、mini/紧凑变体、单跳检索。 |
| 5p5_paid_search_subagent_will_spmini_0520 | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、subagent 路由、mini/紧凑变体。 |
| 5p5_search_paid_mai_grounding | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| bd_web_features_0522_ab_paid | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| bd_web_features_0522_ab_unpaid | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| gpt55_thinking_igglybuff_search_v0 | 关注搜索、浏览或网页检索的模型或实验。 |
| model_aware_map_search_only_paid | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| model_aware_map_search_only_unpaid_v2 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| search_classifiers_paid_0512 | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| search_classifiers_unpaid_0512 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| search_default_token_sweep_unpaid | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| search_parrot_0514 | 关注搜索、浏览或网页检索的模型或实验。 |
| serch_big_dipper_force_no_search_05_21 | 关注搜索、浏览或网页检索的模型或实验。 |
| shortprompts_search_50_test | 关注搜索、浏览或网页检索的模型或实验；名称信号：测试/处理组。 |
| web_loc_tool_paid_v2 | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| web_loc_tool_paid_v3 | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级。 |
| web_loc_tool_unpaid_v2 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| web_loc_tool_unpaid_v3 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| mainline gpt-4: (biz_no_browse) | 关注搜索、浏览或网页检索的模型或实验。 |
| mainline o1-mini: (biz_no_browse) | 关注搜索、浏览或网页检索的模型或实验；名称信号：mini/紧凑变体。 |
| mainline o1-preview: (biz_no_browse) | 关注搜索、浏览或网页检索的模型或实验。 |
| mainline o3: (biz_no_browse) | 关注搜索、浏览或网页检索的模型或实验。 |
| mainline o4-mini: (biz_no_browse) | 关注搜索、浏览或网页检索的模型或实验；名称信号：mini/紧凑变体。 |
| mainline text-davinci-002-render-sha: (biz_no_browse) | 关注搜索、浏览或网页检索的模型或实验。 |
| gpt5_3_mini_first_web_run | 关注搜索、浏览或网页检索的模型或实验；名称信号：mini/紧凑变体。 |
| Sonic Thinky v1 Unpaid, No Serp News | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级。 |
| GPT-5.5 unpaid local biz ctx 16k heap topn10 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、16k 上下文。 |
| chatgpt_local_16k_plus_heap | 关注搜索、浏览或网页检索的模型或实验；名称信号：16k 上下文。 |
| GPT-5.5 unpaid local biz ctx 8k heap | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、8k 上下文。 |
| GPT-5.5 unpaid local biz ctx 8k heap topn10 | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、8k 上下文。 |
| local_8k_heap_topn_tune | 关注搜索、浏览或网页检索的模型或实验；名称信号：8k 上下文。 |
| local_8k_heap_tune | 关注搜索、浏览或网页检索的模型或实验；名称信号：8k 上下文。 |
| big_dipper_a1_sp_mini_flock_free | 关注搜索、浏览或网页检索的模型或实验；名称信号：未付费层级、mini/紧凑变体。 |
| big_dipper_a1_sp_mini_flock_paid | 关注搜索、浏览或网页检索的模型或实验；名称信号：付费层级、mini/紧凑变体。 |

## 推理与深度思考 (125)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:sonic_thinky_unpaid_2600_nov25:a_prod | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级、生产对比。 |
| campaign:sonic_thinky_unpaid_2600_nov25:b_s2600 | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| campaign:sonic_thinky_unpaid_dec1:c_1124t1_s2700 | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| campaign:sonic_thinky_unpaid_dec1:d_1128t1_s1300 | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| campaign:5p5_thinking_paid_professional_0501:a_control | 关注推理或深度思考能力的模型或实验；名称信号：付费层级、对照组。 |
| campaign:5p5_thinking_paid_professional_0501:b_treatment | 关注推理或深度思考能力的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:5p5_thinking_pro_professional_0501:a_control | 关注推理或深度思考能力的模型或实验；名称信号：Pro 层级、对照组。 |
| campaign:5p5_thinking_pro_professional_0501:b_treatment | 关注推理或深度思考能力的模型或实验；名称信号：Pro 层级、测试/处理组。 |
| campaign:gpt_52_thinking_vs_instant_iid_paid:a_instant | 关注推理或深度思考能力的模型或实验；名称信号：付费层级、低延迟。 |
| campaign:gpt_52_thinking_vs_instant_iid_paid:b_reasoning | 关注推理或深度思考能力的模型或实验；名称信号：付费层级、低延迟。 |
| campaign:gpt_54_thinking_j5_vs_53_iid_paid:a_gpt_5_3 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| campaign:gpt_54_thinking_j5_vs_53_iid_paid:b_gpt_5_4_thinking | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| campaign:gpt_54_thinking_j5_vs_53_iid_paid_04pct:a_gpt_5_3 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| campaign:gpt_54_thinking_j5_vs_53_iid_paid_04pct:b_gpt_5_4_thinking | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| campaign:gpt_54_thinking_j5_vs_53_instant_iid_paid:a_control | 关注推理或深度思考能力的模型或实验；名称信号：付费层级、低延迟、对照组。 |
| campaign:gpt_54_thinking_j5_vs_53_instant_iid_paid:b_treatment | 关注推理或深度思考能力的模型或实验；名称信号：付费层级、低延迟、测试/处理组。 |
| campaign:paid_manual_reasoning_multisys_5p5_paragen:a_control | 关注推理或深度思考能力的模型或实验；名称信号：付费层级、对照组。 |
| campaign:paid_manual_reasoning_multisys_5p5_paragen:b_test | 关注推理或深度思考能力的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:paid_manual_reasoning_multisys_snippet_5p5_paragen:a_control | 关注推理或深度思考能力的模型或实验；名称信号：付费层级、对照组。 |
| campaign:paid_manual_reasoning_multisys_snippet_5p5_paragen:b_test | 关注推理或深度思考能力的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:paid_manual_reasoning_sys1_only_5p5_paragen:a_control | 关注推理或深度思考能力的模型或实验；名称信号：付费层级、对照组。 |
| campaign:paid_manual_reasoning_sys1_only_5p5_paragen:b_test | 关注推理或深度思考能力的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:sonic_thinky_unpaid_dec1:a_prod | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级、生产对比。 |
| campaign:sonic_thinky_unpaid_dec1:b_1124t1_s2400 | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| campaign:thinky_paragen_campaign_test:a_control | 关注推理或深度思考能力的模型或实验；名称信号：对照组、测试/处理组。 |
| 5p2_thinking_tables | 关注推理或深度思考能力的模型或实验。 |
| 5p2_thinking_more_tables | 关注推理或深度思考能力的模型或实验。 |
| Deep Research App (GPT 5.2 Thinking) | 关注推理或深度思考能力的模型或实验。 |
| web_links_reasoning_0511 | 关注推理或深度思考能力的模型或实验。 |
| Spud D64 Reasoning | 关注推理或深度思考能力的模型或实验。 |
| Thinky rev7 arm3 s1200 (2026-02-23 export) | 关注推理或深度思考能力的模型或实验。 |
| alsamer101625_thinking | 关注推理或深度思考能力的模型或实验。 |
| bidi_backend_gpt55_reasoning_high_260521 | 关注推理或深度思考能力的模型或实验。 |
| bidi_backend_gpt55_reasoning_medium_260521 | 关注推理或深度思考能力的模型或实验。 |
| gpt5-5-activation-reasoning-paid-052226 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| thinky-rev7-arm8-s300-20260306-1741-300-8shard-2026-03-06-20-25 (ppo step 300) | 关注推理或深度思考能力的模型或实验；名称信号：RL 信号。 |
| chatgpt_ctx_window_holdback_thinking_26_h1 | 关注推理或深度思考能力的模型或实验。 |
| codex_thinky_codex_test_20260211_185134 | 关注推理或深度思考能力的模型或实验；名称信号：测试/处理组。 |
| gpt55_lowjuice_thinking_paid_260504 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| gpt_5_5_thinking_activations_exp_050826 | 关注推理或深度思考能力的模型或实验。 |
| gpt_5_5_thinking_activations_exp_052226_new | 关注推理或深度思考能力的模型或实验。 |
| prefix_compaction_thinking_5p5_16k | 关注推理或深度思考能力的模型或实验；名称信号：16k 上下文。 |
| prefix_compaction_thinking_5p5_64k_v2 | 关注推理或深度思考能力的模型或实验；名称信号：64k 上下文。 |
| thinkier_20260210_v1 | 关注推理或深度思考能力的模型或实验。 |
| thinkier_20260210_v2 | 关注推理或深度思考能力的模型或实验。 |
| thinkier_20260210_v4_unpaid | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| thinky_rev6_paid | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| thinky_rev6_unpaid | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| xq_thinky_codex_test_20260211 | 关注推理或深度思考能力的模型或实验；名称信号：测试/处理组。 |
| Thinky rev7 arm5 s250 | 关注推理或深度思考能力的模型或实验。 |
| Sonic Thinky v1, 8k SBT and Truncate ATC | 关注推理或深度思考能力的模型或实验；名称信号：8k 上下文。 |
| Sonic Thinky v1, 8k token length | 关注推理或深度思考能力的模型或实验；名称信号：8k 上下文。 |
| paid_5p5_thinking_multisys_d8_0521 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| paid_5p5_thinking_multisys_d8_0522 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| 5.4 Reasoning as 5.5 Instant Config | 关注推理或深度思考能力的模型或实验；名称信号：低延迟。 |
| 5.4r Thinkier Alex Taste | 关注推理或深度思考能力的模型或实验。 |
| 5p2_thinking_recognize_placeholders | 关注推理或深度思考能力的模型或实验。 |
| 5p3_reasoning_golden | 关注推理或深度思考能力的模型或实验。 |
| 5p4 Thinking in 5p3 Chat | 关注推理或深度思考能力的模型或实验。 |
| 5p4_thinking_sa_server | 关注推理或深度思考能力的模型或实验。 |
| GPT 5 2 reasoning paid jobs | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| GPT 5.5 Reasoning w/ Activation Classifier | 关注推理或深度思考能力的模型或实验。 |
| GoldenAlpha / 51 Thinking | 关注推理或深度思考能力的模型或实验。 |
| GoldenAlpha / 51 Thinking Auto | 关注推理或深度思考能力的模型或实验。 |
| PCA Wiki GPT-5.5 Reasoning Paid | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| Sonic Thinky Paid - System2 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| Sonic Thinky Paid, Mixed | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| Sonic Thinky Unpaid System1 | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| Sonic Thinky Unpaid System2 | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| Sonic Thinky V1 Paid Map Fix | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| Sonic Thinky v1 Paid | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| Sonic Thinky v1 Unpaid Default | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| Thinky Sonic Gen Entity Local Only Paid | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| Thinky Sonic Gen Entity Local Only Unpaid v0 | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| Thinky Sonic Gen Entity New Dis Local Unpaid | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| Thinky Sonic Gen Entity New Dis Unpaid v0 | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| Thinky Sonic Gen Entity New Disambig Local Paid | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| Thinky Sonic Gen Entity New Disambig Paid | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| Thinky Sonic Gen Entity New Disambig Unpaid | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| Thinky Sonic Gen Entity Prev Win Local Paid | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| Thinky Sonic Gen Entity Prev Win Local Unpaid | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| Thinky Sonic Gen Entity Prev Win Paid | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| Thinky Sonic Gen Entity Prev Win Unpaid | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| Thinky Sonic Local Query Mode 12-22 | 关注推理或深度思考能力的模型或实验。 |
| add_inst_thinking | 关注推理或深度思考能力的模型或实验。 |
| brandonw thinky classifier | 关注推理或深度思考能力的模型或实验。 |
| gan_availability_thinking_0511 | 关注推理或深度思考能力的模型或实验。 |
| garlic thinky 2 stage | 关注推理或深度思考能力的模型或实验。 |
| gpt5-2-reasoning-memento-in-turn | 关注推理或深度思考能力的模型或实验。 |
| prefix_compaction_5p5_thinking_medium_ctx_window_single_summary | 关注推理或深度思考能力的模型或实验。 |
| prefix_compaction_5p5_thinking_medium_ctx_window_single_summary_counter_factual | 关注推理或深度思考能力的模型或实验。 |
| prefix_compaction_5p5_thinking_small_ctx_window | 关注推理或深度思考能力的模型或实验。 |
| prefix_compaction_5p5_thinking_small_ctx_window_counter_factual | 关注推理或深度思考能力的模型或实验。 |
| prefix_compaction_eval_5p5_thinking | 关注推理或深度思考能力的模型或实验。 |
| prefix_compaction_eval_5p5_thinking_counter_factual | 关注推理或深度思考能力的模型或实验。 |
| thinking_dogfooding_plans_and_updates_v1 | 关注推理或深度思考能力的模型或实验；名称信号：内部试用(dogfooding)。 |
| xueqing_gpt5p4_reasoning | 关注推理或深度思考能力的模型或实验。 |
| 5_5_thinking_activations_classifier_exp | 关注推理或深度思考能力的模型或实验。 |
| 5p4_tolo1_reasoning_unpaid_0309 | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| andromeda_reasoning_paid_0512 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| chatgpt_reasoning_increase_context_windowv2 | 关注推理或深度思考能力的模型或实验。 |
| garlic_thinky_sys_msg_vs_arm10_paid | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| gpt55_cotv5_thinking_paid_v0 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| gpt55_thinking_gengar_v0 | 关注推理或深度思考能力的模型或实验。 |
| gpt5_5_thinking_paid_knowledge_cutoff | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| paid_manual_reasoning_multisys_5p5 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| paid_manual_reasoning_multisys_5p5_0513 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| pca_5_5_thinking_decision_boundary | 关注推理或深度思考能力的模型或实验。 |
| prefix_compaction_thinking_5p5_32k | 关注推理或深度思考能力的模型或实验；名称信号：32k 上下文。 |
| thinky_5p3_rev3_paid_02021 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| thinky_5p3_rev4_sample_allocator_paid_v4 | 关注推理或深度思考能力的模型或实验；名称信号：付费层级。 |
| thinky_juice_4_unpaid | 关注推理或深度思考能力的模型或实验；名称信号：未付费层级。 |
| gpt55_thinking_igglybuff_v0 | 关注推理或深度思考能力的模型或实验。 |
| Sonic Thinky v1 | 关注推理或深度思考能力的模型或实验。 |
| GPT-5.5 Thinking Frontend Test | 关注推理或深度思考能力的模型或实验；名称信号：测试/处理组。 |
| GPT-5.5 Thinking frontend prompt test | 关注推理或深度思考能力的模型或实验；名称信号：测试/处理组。 |
| gpt55_thinking_holdout_v1 | 关注推理或深度思考能力的模型或实验；名称信号：保留组。 |
| 5p4_thinking_multiturn_memento | 关注推理或深度思考能力的模型或实验。 |
| Link Entities 5p2 Thinking | 关注推理或深度思考能力的模型或实验。 |
| RV Thinking Test 0211 | 关注推理或深度思考能力的模型或实验；名称信号：测试/处理组。 |
| GPT-5 Thinking Mini | 关注推理或深度思考能力的模型或实验；名称信号：mini/紧凑变体。 |
| gpt-5-5-thinking | 关注推理或深度思考能力的模型或实验。 |
| 5p4r with Thinky sys prompt | 关注推理或深度思考能力的模型或实验。 |
| chat_cot_ui_constant_long_inst | 关注推理或深度思考能力的模型或实验。 |
| gpt5_2_r_cot_citations | 关注推理或深度思考能力的模型或实验。 |

## 图像、视觉与多模态 (45)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:image_unpaid_sft_vs_rl0516a:a_labrador | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、SFT 信号。 |
| campaign:image_unpaid_sft_vs_rl0516a:b_labrador_blender_0516s180 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、SFT 信号。 |
| campaign:5p3_images_blender_unpaid_arm7:a_control | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:5p3_images_blender_unpaid_arm7:b_test | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、测试/处理组。 |
| campaign:5p3_blender_test_pgn:a_control | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：对照组、测试/处理组。 |
| campaign:5p3_blender_test_pgn:b_0401_v3 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：测试/处理组。 |
| campaign:5p3_blender_test_pgn:c_0404_v1 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：测试/处理组。 |
| campaign:andromeda_image_unpaid_sft_vs_rl0505:a_labrador | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、SFT 信号。 |
| campaign:andromeda_image_unpaid_sft_vs_rl0505:b_labrador_blender_0505s100 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、SFT 信号。 |
| campaign:andromeda_image_unpaid_sft_vs_rl:a_labrador | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、SFT 信号、RL 信号。 |
| campaign:andromeda_image_unpaid_sft_vs_rl:b_labrador_blender_0404_v1 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、SFT 信号、RL 信号。 |
| campaign:image_unpaid_sft_vs_rl0509:a_labrador | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、SFT 信号。 |
| campaign:image_unpaid_sft_vs_rl0509:b_labrador_blender_0509s30 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、SFT 信号。 |
| campaign:image_unpaid_sft_vs_rl0515:a_labrador | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、SFT 信号。 |
| campaign:image_unpaid_sft_vs_rl0515:b_labrador_blender_0515s120 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、SFT 信号。 |
| campaign:labrador_100p_free:a_control | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:labrador_100p_free:b_force_100_labrador | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级。 |
| image_index-labrador-256webp | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| Web Imagegen Auto v1 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| Andromeda Img Group Prompt 0506 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| ig2-hybridprod-640-v2 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| ig2.hrm640 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| imagegen_d64_edit_c2 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| image_holdout_unpaid_test_0406 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、测试/处理组、保留组。 |
| ig2-37p-ptw-test | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：测试/处理组。 |
| image_blender_rlv8_paid_ab | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：付费层级。 |
| image_blender_rlv8_unpaid_ab | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级。 |
| u18_image_groups_paid | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：付费层级。 |
| u18_image_groups_unpaid | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级。 |
| Amrit's Image O3 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| Andromeda Img Prompt 0510 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| Better Image Carousel Prompt | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| Image Gen Alpha Model Test | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：测试/处理组。 |
| ImageGen 2.0 Beta | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| Mainline images (crz) | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| dil-imagegen-dp | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| dil-imagegen-dp-v2 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| o3.business_grader_non_labrador | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| 5p3_image_blender_index_ab_v3 | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| 5p3_image_index_v3p1_unpaid | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级。 |
| andromeda_images_exp | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |
| image_blender_rl_paid_ab | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：付费层级、RL 信号。 |
| image_blender_rl_unpaid_ab | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：未付费层级、RL 信号。 |
| image_groups_paid_holdout | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验；名称信号：付费层级、保留组。 |
| sidebar_images_blender | 关注图像生成、图像编辑、视觉或多模态行为的模型或实验。 |

## 音频、语音与实时交互 (30)

| 模型 | 中文简要作用说明 |
|---|---|
| AVM Reasoning | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| AVM Reasoning Feather | 关注音频、语音、语音合成或实时交互的模型或实验；名称信号：低延迟。 |
| AVM Reasoning LDM | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| AVM-RT Reasoning | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| chatgpt_voice_reasoning | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| s2s_if_fc_0913_2760 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| s2s_chive_2026_q1 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| s2s_chive_2026_q1_m45_apac_v2 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| s2s_chive_q1_2026_holdout_v1 | 关注音频、语音、语音合成或实时交互的模型或实验；名称信号：保留组。 |
| s2s_scallion_q1_2026_holdout_v3 | 关注音频、语音、语音合成或实时交互的模型或实验；名称信号：保留组。 |
| s2s_chive_20250728_arm1 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| 5p2 audio | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| 5p4 voice hung template | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| AVM | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| chatgpt_voice_vad_tuning | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| s2s_ldm_chive_noram_v2 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| s2s_scallion_q3_2025_holdout_v2 | 关注音频、语音、语音合成或实时交互的模型或实验；名称信号：保留组。 |
| s2s_chive_q3_2025_holdout_v2 | 关注音频、语音、语音合成或实时交互的模型或实验；名称信号：保留组。 |
| Scallion w/ product entities | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| chive_m3_1105_1750 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| chive_m4_1105_0700 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| chive_m4_1105_0800 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| chive_m4_800_lc_1 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| Scallion entity content_ref | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| chive_m2_1105_1350 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| chive_m3_1105_1300 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| chive_m3_1105_1400 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| chive_m4_1105_0100 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| chive_m5_1105_0100_v2 | 关注音频、语音、语音合成或实时交互的模型或实验。 |
| chive_m5_1105_0500 | 关注音频、语音、语音合成或实时交互的模型或实验。 |

## Artifacts、界面与文档工具 (131)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:genui_1014_sonicberry_s320_oy7_paid:a_prod | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：付费层级、生产对比。 |
| campaign:genui_1014_sonicberry_s320_oy7_paid:b_sonicberry | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：付费层级。 |
| campaign:genui_1014_sonicberry_s320_oy7_paid:c_sonicberry_w_memory | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：付费层级。 |
| campaign:sonicberry_v8p1_unpaid_fully_mixed_nov21:a_prod | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级、生产对比。 |
| campaign:sonicberry_v8p1_unpaid_fully_mixed_nov21:b_v8p1 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:awchen_gpt5_5_unpaid_widgets_sys1:a_control | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:awchen_gpt5_5_unpaid_widgets_sys1:b_task_fit | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:awchen_gpt5_5_unpaid_widgets_sys1:c_prose | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:awchen_gpt5_5_unpaid_widgets_sys1:d_task_fit_prose | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:chart_widget_instant_0512:a_widget_disabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：低延迟。 |
| campaign:chart_widget_instant_0512:b_widget_enabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：低延迟。 |
| campaign:flight_tracker_1:a_widget_disabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| campaign:flight_tracker_1:b_widget_enabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| campaign:genui_0924_sonicberry_1:a_prod | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：生产对比。 |
| campaign:genui_0924_sonicberry_1:b_sonicberry | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| campaign:genui_0924_sonicberry_1:c_sonicberry_w_memory | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| campaign:genui_0924_sonicberry_unpaid_1:a_a_prod | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级、生产对比。 |
| campaign:genui_0924_sonicberry_unpaid_1:b_sonicberry | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:genui_0924_sonicberry_unpaid_1:c_sonicberry_w_memory | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:genui_1014_sonicberry_s320_unpaid:a_prod | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级、生产对比。 |
| campaign:genui_1014_sonicberry_s320_unpaid:b_sonicberry | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:genui_1014_sonicberry_s320_unpaid:c_sonicberry_w_memory | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:genui_1211_1:a_current_gpt5_2_auto_paid_widgets_test | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:genui_1211_1:b_base | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| campaign:genui_widget_paragen_gpt_5_3_unpaid_user:a_widgets_enabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:genui_widget_paragen_gpt_5_3_unpaid_user:b_widgets_disabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:genui_widget_paragen_gpt_5_3_unpaid_user_prompt_v3:a_widgets_enabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:genui_widget_paragen_gpt_5_3_unpaid_user_prompt_v3:b_widgets_disabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:genui_widget_paragen_gpt_5_5_unpaid_user:a_widgets_enabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:genui_widget_paragen_gpt_5_5_unpaid_user:b_widgets_disabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:genui_widget_paragen_gpt_5_5_unpaid_user_no_automatic_placement:a_widgets_enabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:genui_widgets_1211_2:a_widgets | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| campaign:genui_widgets_1211_2:b_control | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：对照组。 |
| campaign:kramerd_gen_ui_widgets_test_4:a_widgets_enabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：测试/处理组。 |
| campaign:kramerd_gen_ui_widgets_test_4:b_widgets_disabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：测试/处理组。 |
| campaign:package_tracker_1:a_widget_disabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| campaign:package_tracker_1:b_widget_enabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| campaign:parallel_genui_milestone_1b:a_web_run_with_genui | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| campaign:parallel_genui_milestone_1b:b_genui_web_run_separate | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| campaign:widget_calc_v2_vs_no_calc:a_calc_v2 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| campaign:widget_calc_v2_vs_no_calc:b_no_calc | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| campaign:widget_no_auto_place_5_5_unpaid_user:a_widgets_enabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:widget_no_auto_place_5_5_unpaid_user:b_widgets_disabled | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| campaign:widgets_dom_2_12_test:a_mainline | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：测试/处理组。 |
| campaign:widgets_dom_2_12_test:b_widgets | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：测试/处理组。 |
| 5.2 Artifacts Juice 16 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5.4 5p4_0219_s1020_v2 Artifacts J768 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5.4 5p4_0219_s1020_v2 Artifacts J96 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5.4 Artifacts Spreadsheets J16 Prompt V2 Vicky | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5.4 alpha.5p4_0219_s1020_v2_artifacts_j64 Vicky | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5p4_0219_s1020_v2_artifacts_j64 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5p4_0219_s1020_v2_artifacts_j64_memento | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| alpa.5p4_0219_s1020_v2_artifacts_j96_vicky | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| alpha.5p4_0219_s1020_v2_artifacts_j16_vicky | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5.2 Widgets (Feb 7 ELK( | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| GenUI 0731 Arm4 RL Step 250 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：RL 信号。 |
| 5.4 5p4_reasoning_paid_artifact_edits_j8 Vicky | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：付费层级。 |
| 5.4 S1020 V2 Artifact Edit Deno J8 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5.4 S1020 V2 Artifact Edit J8 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5.4 S1020 V2 Artifact Edit J8 Testing | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5p4_0219_s1020_v2_artifacts_edits_j8 vicky | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5p4_0219_s1020_v2_artifacts_j8 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| All widgets (12/18) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| alpha.5p4_0219_s1020_v2_artifacts_j8_vicky | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| alpha.5p4_0219_s1020_v2_artifacts_j8_vicky_prompt_v2_latest | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5.2 Artifacts Juice 32 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5.2 Artifacts Juice 4 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5.2 Auto Paid Widget Gen Entity | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：付费层级。 |
| 5.4 5p4_0219_s1020_v2 Artifacts Juice 32 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5.4 Artifacts Pro Judging | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：Pro 层级。 |
| 5.4 Artifacts Pro No Judging | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：Pro 层级。 |
| 5.4 Auto Reasoning Mini Artifacts Edit Vicky | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：mini/紧凑变体。 |
| 5.4 Spreadsheet Artifacts ATV2 prompt 2 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5.4 current_gpt5_4_pro_pro Artifacts | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：Pro 层级。 |
| 5p2 artifacts | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5p4_0219_s1020_v2_artifacts_j4 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| Artifacts S1020 Edits FE Execution | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| Artifacts Spreadsheet ATV2 Prompt 2 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| Edward Test for 5.2 Artifacts | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：测试/处理组。 |
| GPT 5.5 Thinking Artifacts | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| GPT-5.2 Pro - Artifacts | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：Pro 层级。 |
| GPT-5.5 Pro Artifacts | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：Pro 层级。 |
| GPT-5.5 Thinking Artifacts | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| GPT-5.5 Thinking Artifacts J4 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| Map Widget 0515 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| alpha.5p4_0219_s1020_v2_artifacts_j32_vicky | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| alpha.5p4_0219_s1020_v2_artifacts_j32_vicky_prompt_v2_latest | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| alpha.5p4_0219_s1020_v2_artifacts_j4_vicky | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| alpha.5p4_0219_s1020_v2_artifacts_j4_vicky_prompt_v2_latest | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| emily_gpt5_5_reasoning_paid_artifacts | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：付费层级。 |
| gp5p2_artifacts_with_skillz | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| gpt-5-4-thinking-artifacts | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| widgets eval model | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| writing-block-experimental-genui+ | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| writing_block_document_expansion_free | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| writing_block_document_expansion_paid | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：付费层级。 |
| mainline gpt-4: (biz_no_browse_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| mainline gpt-4: (biz_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| mainline gpt-4o-canmore: (biz_no_browse_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| mainline gpt-4o-canmore: (biz_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| mainline o1-mini: (biz_no_browse_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：mini/紧凑变体。 |
| mainline o1-mini: (biz_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：mini/紧凑变体。 |
| mainline o1-preview: (biz_no_browse_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| mainline o1-preview: (biz_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| mainline o3: (biz_no_browse_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| mainline o3: (biz_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| mainline o4-mini: (biz_no_browse_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：mini/紧凑变体。 |
| mainline o4-mini: (biz_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：mini/紧凑变体。 |
| mainline text-davinci-002-render-sha: (biz_no_browse_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| mainline text-davinci-002-render-sha: (biz_with_canvas) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| Thinky Sonic Widget Gen Entity | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| genui.synthetics.2 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| GPT 5.4 Thinking Widgets | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| 5p4_thinking_widgets | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| Search entity (elk 1) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| Sonicberry File Search Only | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| Mainline Sonicberry Paid | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：付费层级。 |
| Mainline Sonicberry Unpaid | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：未付费层级。 |
| Sonicberry (Product Cards) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| mainline gpt-4o-canmore: (paid) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：付费层级。 |
| 5p2 Instant -> Lab-First Sonicberry | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：低延迟。 |
| Sonicberry Paid Sy1/Sy2 | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：付费层级。 |
| Sonicberry Paid Sy1/Sy2 dynamic | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验；名称信号：付费层级。 |
| Chart block alpha | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| ELK General Disambig Reason | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| ELK General Disambiguation | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| Sonicberry (Lab-first Shopping) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| sonicberry_map_on_top | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| tmp sonicberry oai_index | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| Sonicberry (4o entry point) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |
| Sonicberry (YouTube index) | 关注 Artifacts、组件、画布或文档/界面生成的模型或实验。 |

## Agent、工具调用与自动化 (29)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:no_product_tool_0514:a_control | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验；名称信号：对照组。 |
| campaign:no_product_tool_0514:b_noproduct | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| campaign:prod_vs_mini_tool_call__sonic:a_prod | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验；名称信号：生产对比、mini/紧凑变体。 |
| campaign:prod_vs_mini_tool_call__sonic:b_mini_tool_call | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验；名称信号：生产对比、mini/紧凑变体。 |
| Handoff -> Deep Research | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| brandon classifier+nosearch | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| Aura Agent D64 0 | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| [dev2] Aura Agent D64 0 | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| [dev3] Aura Agent D64 0 | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| [dev4] Aura Agent D64 0 | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| [dev5] Aura Agent D64 0 | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| classifier_exclude_tools_0506 | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| classifier_skip_tools_0506_paid | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验；名称信号：付费层级。 |
| Agent with Prompt Expansion | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| GPT-5.5-handoff-containment | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| GPT4o w/ o3 handoff | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| GPT5.2 auto with proactive automations | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| GPT52 Automation Override | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| Orion with tools disabled | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| Synapse Mitigation Handoff Containment | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| Synapse Mitigation Tool Skepticism | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| api_tool PE | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| api_tool_derisk_1 | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| user location tool alpha | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| classifier_skip_tools_0511 | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| classifier_skip_tools_0511_paid | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验；名称信号：付费层级。 |
| product_tool_ablations_0513 | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| GPT-5.5-tool-skepticism | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |
| Pulse Tool 5.2 | 关注 Agent 工作流、工具调用、子 Agent 或自动化的模型或实验。 |

## 个性化、记忆与语气 (382)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:anusha_gpt_5_5_auto_pca_paragen_20260506:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：对照组。 |
| campaign:anusha_gpt_5_5_auto_pca_paragen_20260506:b_treatment | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：测试/处理组。 |
| campaign:memory_2x_test_0226:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：对照组、测试/处理组。 |
| campaign:memory_2x_test_0226:b_memory_2x | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：测试/处理组。 |
| campaign:p13n_pca_paragen_1_20260421_auto:a_pca_override_always_call_5_3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| campaign:p13n_pca_paragen_1_20260421_auto:b_pca_override_disabled_5_3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| campaign:p13n_pca_paragen_1_20260423_auto_always_vs_default:a_pca_override_always_call_5_3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| campaign:p13n_pca_paragen_1_20260423_auto_always_vs_default:b_pca_override_disabled_5_3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| campaign:5p3_tone_casual_professional_prompts_unpaid:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:5p3_tone_casual_professional_prompts_unpaid:b_treatment | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、测试/处理组。 |
| campaign:5p3_tone_casual_professional_prompts_unpaid_0322_v3:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:5p3_tone_casual_professional_prompts_unpaid_0322_v3:b_treatment | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、测试/处理组。 |
| campaign:5p3_tone_professional_prompts_unpaid_0322_v1:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:5p3_tone_professional_prompts_unpaid_0322_v1:b_professional | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:5p3_tone_professional_prompts_unpaid_0322_v1:c_test | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、测试/处理组。 |
| campaign:gpt53_diversity_traits_all_paid:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt53_diversity_traits_all_paid:aa_empathetic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:ab_supportive_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:ac_supportive_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:ad_practical_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:ae_practical_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:af_optimistic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:ag_optimistic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:ah_didactic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:b_dismissive_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:c_dismissive_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:d_prose_structure_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:e_prose_structure_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:f_ironic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:g_ironic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:h_obsequious_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:i_obsequious_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:j_critical_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:k_critical_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:l_markdown_structure_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:m_markdown_structure_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:n_confident_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:o_confident_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:p_friendly_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:q_friendly_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:r_curious_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:s_curious_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:t_conversational_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:u_conversational_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:v_literal_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:w_literal_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:x_idiomatic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:y_idiomatic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_paid:z_empathetic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:gpt53_diversity_traits_all_v2_free:aa_empathetic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ab_supportive_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ac_supportive_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ad_practical_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ae_practical_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:af_optimistic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ag_optimistic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ah_didactic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ai_didactic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:aj_serious_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ak_serious_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:al_simple_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:am_simple_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:an_analytical_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ao_analytical_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ap_dispassionate_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:aq_dispassionate_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ar_expository_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:as_expository_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:at_direct_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:au_direct_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:av_emoji_use_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:aw_emoji_use_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ax_succinct_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ay_succinct_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:az_agreeable_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:b_dismissive_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:ba_agreeable_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:c_dismissive_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:d_prose_structure_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:e_prose_structure_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:f_ironic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:g_ironic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:h_obsequious_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:i_obsequious_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:j_critical_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:k_critical_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:l_markdown_structure_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:m_markdown_structure_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:n_confident_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:o_confident_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:p_friendly_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:q_friendly_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:r_curious_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:s_curious_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:t_conversational_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:u_conversational_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:v_literal_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:w_literal_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:x_idiomatic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:y_idiomatic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_free:z_empathetic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt53_diversity_traits_all_v2_paid:aa_empathetic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ab_supportive_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ac_supportive_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ad_practical_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ae_practical_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:af_optimistic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ag_optimistic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ah_didactic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ai_didactic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:aj_serious_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ak_serious_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:al_simple_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:am_simple_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:an_analytical_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ao_analytical_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ap_dispassionate_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:aq_dispassionate_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ar_expository_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:as_expository_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:at_direct_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:au_direct_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:av_emoji_use_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:aw_emoji_use_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ax_succinct_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ay_succinct_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:az_agreeable_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:b_dismissive_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:ba_agreeable_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:c_dismissive_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:d_prose_structure_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:e_prose_structure_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:f_ironic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:g_ironic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:h_obsequious_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:i_obsequious_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:j_critical_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:k_critical_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:l_markdown_structure_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:m_markdown_structure_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:n_confident_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:o_confident_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:p_friendly_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:q_friendly_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:r_curious_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:s_curious_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:t_conversational_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:u_conversational_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:v_literal_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:w_literal_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:x_idiomatic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:y_idiomatic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_all_v2_paid:z_empathetic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:b_conversational_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:c_conversational_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:d_literal_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:e_literal_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:f_idiomatic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:g_idiomatic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:h_empathetic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:i_empathetic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:j_supportive_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:k_supportive_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:l_practical_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:m_practical_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:n_optimistic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:o_optimistic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:p_didactic_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:q_didactic_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:r_serious_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part2_v2:s_serious_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part3_v3:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt53_diversity_traits_paid_part3_v3:b_simple_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part3_v3:c_simple_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part3_v3:d_analytical_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part3_v3:e_analytical_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_paid_part3_v3:f_dispassionate_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part1:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:gpt53_diversity_traits_unpaid_part1_v2:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:gpt53_diversity_traits_unpaid_part1_v2:b_dismissive_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part1_v2:c_dismissive_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part1_v2:d_prose_structure_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part1_v2:e_prose_structure_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part2_v2:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:gpt53_diversity_traits_unpaid_part2_v2:b_conversational_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part2_v2:c_conversational_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:gpt53_diversity_traits_unpaid_part3:b_simple_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:c_simple_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:d_analytical_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:e_analytical_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:f_dispassionate_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:g_dispassionate_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:h_expository_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:i_expository_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:j_direct_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:k_direct_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:l_emoji_use_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:m_emoji_use_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:n_succinct_more | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt53_diversity_traits_unpaid_part3:o_succinct_less | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt5_unpaid_personality_axis_practicality:a_pos | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt5_unpaid_personality_axis_practicality:b_neg | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| campaign:gpt_52_personality_robot_unpaid:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:gpt_52_personality_robot_unpaid:b_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:gpt_52_personality_robot_unpaid:b_treatment | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、测试/处理组。 |
| campaign:gpt_5p2_emoji_less_unpaid:a_control | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:gpt_5p2_emoji_less_unpaid:b_treatment | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、测试/处理组。 |
| campaign:p13n_pca_0423_avd_no_p13n_ui:a_pca_override_always_call_5_3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| campaign:p13n_pca_0423_avd_no_p13n_ui:b_pca_override_disabled_5_3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| campaign:rishab_pca_paragen_1:a_pca_override_always_call_5_3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| campaign:rishab_pca_paragen_1:b_pca_override_disabled_5_3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| Big Dipper A19 step 450 research alpha | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| Big Dipper A19 step 500 research alpha | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| Big Dipper C2 step 450 research alpha | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| Big Dipper C2 step 500 research alpha | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| pca_web_suffix_5_5 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| GPT-5 Sugar With Memory And Automations | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| pca_toolcfg_0520_g55_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| 011526-default-personality | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| 011526-personality-dogfooding | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：内部试用(dogfooding)。 |
| dreamberry_dreams_prefs_20250310_d64 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| personality v6 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| e2_tone_0526_free_v3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| bd_lite_c2_pca_paid_0528 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| 5.4r Alex Taste | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| April 20 PCA Dogfooding | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：内部试用(dogfooding)。 |
| D1 s1400 new p13n mitigation no pca | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| GPT 5.2 Sugar Memory Only | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| GPT 5.4R Mini Sugar Memory | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：mini/紧凑变体。 |
| Garlic Personality SFT Final | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：SFT 信号。 |
| PCA Wiki GPT-5.5 Instant Paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、低延迟。 |
| Personalization test gmail | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：测试/处理组。 |
| alpha.chat_cot_ui_and_personality_instant | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：低延迟。 |
| big_dipper_c2_s1150_g55_pca_paid_project_decision_existing_engines | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_c2_s1150_g55_pca_paid_reply_action | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_c2_s1150_g55_pca_paid_reply_action_existing_engines | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_pca_reply_action | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| chat_cot_ui_and_personality_auto | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| personality_additional_inst | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| bd_c2_s1150_pca_v2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| big_dipper_c2_g55_pca_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_c2_s1150_g55_pca_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_c2_s1150_paid_p13n_irv2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_c2_s1150_s1200_paid_p13nir | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_c2_s1150_s1200_unpaid_p13nir | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_c2_s1150_unpaid_p13n_irv2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_juice_g55_pca_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_feedback_personality_auto | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| chatgpt_feedback_personality_free | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| chatgpt_feedback_personality_free2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| chatgpt_feedback_personality_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_feedback_personality_paid2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| chatgpt_feedback_personality_paid_i | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_feedback_personality_paid_t | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_feedback_personality_think | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| chatgpt_personality_id_slang_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_personality_id_slang_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| chatgpt_personality_in_hinglish_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_personality_in_hinglish_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| chatgpt_personality_jp_casual_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_personality_jp_casual_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| chatgpt_personality_jp_idioms_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_personality_jp_idioms_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| chatgpt_personality_jp_katakana_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_personality_jp_katakana_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| chatgpt_personality_kr_emoticons_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_personality_kr_emoticons_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| chatgpt_personality_kr_idioms_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_personality_kr_idioms_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| chatgpt_personality_mec_code_switch_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_personality_mec_code_switch_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| chatgpt_personality_tone_match_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| chatgpt_personality_tone_match_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| chatgpt_zs_p13n_prompt_paid_v4 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| e2_tone_0522_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| hi_taste_james_paid_set53_2x | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| hi_taste_james_paid_set55_2x | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| hi_taste_james_unpaid_set53_2x | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| hi_taste_james_unpaid_set55_2x | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| memory_citation_mainline_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| memory_compression_0225_ab | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| multilingual_jp_context_tone_warmth | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| p13n_derisk_paid_2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| p13n_derisk_paid_3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| pca_big_dipper_free | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| pca_free_55 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| pca_free_55_v3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| pca_free_55_v4 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| pca_go_55_v2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| pca_go_55_v3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| pca_go_55_v4 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| personality_concise_traits_experiment_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| 5p2c_p13n_no_money_20251209_v2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| GPT5 Cocoon Memory Only | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| Pro Memory 30k | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：Pro 层级、30k 上下文。 |
| ToneStyle_v1_2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| gpt 4o Memory 30k | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：30k 上下文。 |
| e2_tone_0522_free | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| e2_tone_0523_free_v2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| memory_off_free | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| p13n_5p2_ff_0103_pro | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：Pro 层级。 |
| Big Dipper A3 step 950 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| big_dipper_smoke2_s675 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| big_dipper_smoke2_s675_5p5base | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| GPT-5.3 paid prod arm7 s950 with prose-style developer message | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、生产对比。 |
| big_dipper_smoke1_s1350_5p5base | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| big_dipper_smoke1_s1350 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| big_dipper_wb_doc_0513_free_0526 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_wb_doc_0513_paid_0526 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| Big Dipper A11 s1150 unpaid 0527 Feather | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、低延迟。 |
| Big Dipper A11 s850 unpaid 0527 Feather | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、低延迟。 |
| Big Dipper A20 S1000 J8 paid Feather 0517 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、低延迟。 |
| Big Dipper A20 S800 J8 paid Feather 0517 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、低延迟。 |
| Big Dipper A12 newline j8 unpaid 0519 Feather | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、低延迟。 |
| Big Dipper A14 s1100 j8 paid 0519 Feather | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、低延迟。 |
| Big Dipper A14 s1100 j8 paid 0519 Feather 2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、低延迟。 |
| Big Dipper A19 S1400 j4 paid 0518 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| Big Dipper A19 S1400 j8 paid 0518 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| Big Dipper A19 s1400 j8 unpaid 0520 Feather | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、低延迟。 |
| Big Dipper A20 S1000 j8 paid 0515 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| Big Dipper A20 S800 j4 paid 0515 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| Big Dipper A20 S800 j8 paid 0515 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| Big Dipper A3 S950 J2 Unpaid 0508 Feather | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、低延迟。 |
| Big Dipper A3 S950 J8 Unpaid 0508 Feather | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、低延迟。 |
| Big Dipper C2 S1150 j8 paid 0518 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| Big Dipper C2 S1200 j8 paid 0518 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| Big Dipper C2 s1150 j8 unpaid 0520 Feather | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、低延迟。 |
| Big Dipper C2 s1200 j8 unpaid 0520 Feather | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、低延迟。 |
| big_dipper_c2_s1150_paid_juice8 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| mem3_big_dipper_c2_s1150_s1200_paid.c2_s1150_j8 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a11_s850_s1150_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a11_s850_s1150_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_a20_s800_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a20_s800_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| Big Dipper A12 S1200 paid Feather 0515 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、低延迟。 |
| Big Dipper A12 S1300 paid Feather 0515 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、低延迟。 |
| Big Dipper A14 S900 g5p3 j4 paid Feather 0513 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、低延迟。 |
| Big Dipper A14 S900 nopctx v2 j4 paid Feather 0515 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级、低延迟。 |
| Big Dipper A20 S1000 j4 paid 0515 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| Big Dipper A3 S950 g5p3 j2 unpaid Feather 0510 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级、低延迟。 |
| Big Dipper Auto Golden Alpha Paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| Big Dipper Auto Golden Alpha Unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| Big Dipper RevA Hackfree s1500 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| big_dipper_chat_paid_0514 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_chat_unpaid_0514 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_a12_newline_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a12_newline_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_a12_s1200_s1300_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a12_s1200_s1300_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_a14_s1100_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a14_s1100_paid_v2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a14_s1100_paid_v3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a14_s1100_unpaid_v2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_a14_s1100_unpaid_v3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_a14_s900_juice_paid_g5p3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a14_s900_juice_paid_nopctx_v2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a14_s900_juice_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_a19_c2_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a19_c2_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_a19_s1400_paid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a19_s1400_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_a3_s950_juice_paid_g5p3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a3_s950_juice_paid_v2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_a3_s950_juice_unpaid_g5p3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_a3_s950_juice_unpaid_v2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_c2_s1150_s1200_unpaid | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| big_dipper_wb_doc_mode_paid_0522 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：付费层级。 |
| big_dipper_wb_doc_mode_free_0522 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：未付费层级。 |
| gpt-5-mini for cocoon | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：mini/紧凑变体。 |
| Big Dipper arm a25 s1100 v3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| GPT5R Sugar Dedicated | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| big dipper a3 s950 awchen | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| trait_merge | 关注个性化、记忆、用户偏好、语气或性格的模型或实验。 |
| big dipper test 1 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：测试/处理组。 |
| big_dipper_test_2 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：测试/处理组。 |
| big_dipper_test_3 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：测试/处理组。 |
| big_dipper_test_4 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：测试/处理组。 |
| Drew Dogfood 1 | 关注个性化、记忆、用户偏好、语气或性格的模型或实验；名称信号：内部试用(dogfooding)。 |

## 评估、打分与裁判 (24)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:sendos_evd_down_vs_control_paid_20260521:a_control | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：付费层级、对照组。 |
| campaign:sendos_evd_down_vs_control_paid_20260521:b_evd_down | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：付费层级、对照组。 |
| campaign:sendos_evd_up_vs_control_paid_20260521:a_control | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：付费层级、对照组。 |
| campaign:sendos_evd_up_vs_control_paid_20260521:b_evd_up | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：付费层级、对照组。 |
| campaign:sonic_ranking_5p5_unpaid_pg_oracle_d8:a_prod | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：未付费层级、生产对比。 |
| campaign:sonic_ranking_5p5_unpaid_pg_oracle_d8:b_oracle | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：未付费层级。 |
| campaign:andromeda_web_no_pairwise_s1300_v2:a_smoke_t3_s1400 | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：冒烟测试。 |
| campaign:andromeda_web_no_pairwise_s1300_v2:b_no_pairwise_s1300 | 关注评估、打分、裁判或奖励建模的模型或实验。 |
| campaign:index_eval_sys2_vs_sys1_5p5i_perma_pg_v3:b_oai_index_only | 关注评估、打分、裁判或奖励建模的模型或实验。 |
| campaign:pairwise_web_feature_additive_paragen_latency_control:a_additive_s1000 | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：对照组。 |
| campaign:pairwise_web_feature_additive_paragen_latency_control:a_tolo1_s1000 | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：对照组。 |
| campaign:pairwise_web_feature_additive_paragen_same_dev_msg:a_tolo1_s1000 | 关注评估、打分、裁判或奖励建模的模型或实验。 |
| campaign:pairwise_web_feature_additive_paragen_same_dev_msg:b_additive_s1000 | 关注评估、打分、裁判或奖励建模的模型或实验。 |
| campaign:sonic_ranking_5p5_unpaid_pg_oracle_bert:a_prod | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：未付费层级、生产对比。 |
| campaign:sonic_ranking_5p5_unpaid_pg_oracle_bert:b_test | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：未付费层级、测试/处理组。 |
| GPT-5.5 Pro judge KC 202406 | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：Pro 层级。 |
| alsamer_grader_092625 | 关注评估、打分、裁判或奖励建模的模型或实验。 |
| 5.5 Local Grader | 关注评估、打分、裁判或奖励建模的模型或实验。 |
| Andromeda revE arm2 monolingual hackgrader t2 step 1200 | 关注评估、打分、裁判或奖励建模的模型或实验。 |
| O3 Business Grader | 关注评估、打分、裁判或奖励建模的模型或实验。 |
| User Signals Medley w/ Multiplicative Hack Reward | 关注评估、打分、裁判或奖励建模的模型或实验。 |
| prefix compaction eval | 关注评估、打分、裁判或奖励建模的模型或实验。 |
| 5pt3_hackgrader_flock_upweight_unpaid_v1 | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：未付费层级。 |
| sonic_oracle_oaibert_5p5_unpaid_ab | 关注评估、打分、裁判或奖励建模的模型或实验；名称信号：未付费层级。 |

## 安全、政策与信任 (27)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:gpt_5_5_iid_no_auth:a_control | 关注安全、政策、鉴权、信任或内容审核的模型或实验；名称信号：对照组。 |
| campaign:gpt_5_5_iid_no_auth:b_treatment | 关注安全、政策、鉴权、信任或内容审核的模型或实验；名称信号：测试/处理组。 |
| campaign:gpt_5_5_lupo_no_auth:a_control | 关注安全、政策、鉴权、信任或内容审核的模型或实验；名称信号：对照组。 |
| campaign:gpt_5_5_lupo_no_auth:b_treatment | 关注安全、政策、鉴权、信任或内容审核的模型或实验；名称信号：测试/处理组。 |
| campaign:gpt_5_5_lupo_no_auth:c_treatment_fork | 关注安全、政策、鉴权、信任或内容审核的模型或实验；名称信号：测试/处理组。 |
| campaign:search_fr_with_mini_no_auth_users_paragen_0415:a_control | 关注安全、政策、鉴权、信任或内容审核的模型或实验；名称信号：对照组、mini/紧凑变体。 |
| campaign:search_fr_with_mini_no_auth_users_paragen_0415:b_test | 关注安全、政策、鉴权、信任或内容审核的模型或实验；名称信号：测试/处理组、mini/紧凑变体。 |
| AD 0428 URLs Safety | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| mainline gpt-4o-mini: (no_auth_search) | 关注安全、政策、鉴权、信任或内容审核的模型或实验；名称信号：mini/紧凑变体。 |
| mainline gpt-5-chat-safety: (no_auth_search) | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| mainline gpt-4o-mini: (no_auth_no_tools) | 关注安全、政策、鉴权、信任或内容审核的模型或实验；名称信号：mini/紧凑变体。 |
| mainline gpt-5-chat-safety: (no_auth_no_tools) | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| mainline text-davinci-002-render-sha: (no_auth_no_tools) | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| spot_20260130_default_no_auth | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| Andromeda Safety T11 S1500 5p3 ES8 Feather | 关注安全、政策、鉴权、信任或内容审核的模型或实验；名称信号：低延迟。 |
| andromeda-safety-t11-s1500-5p3-es8 | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| GPT-5.5-authority-clarification | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| Synapse Mitigation Authority Clarification | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| andromeda-safety-t11-s1500-5p4r | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| yungsung-andromeda-safety-t11-s1500 | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| 0519_shopping_product_policy_update | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| mainline gpt-4o-mini: (no_auth) | 关注安全、政策、鉴权、信任或内容审核的模型或实验；名称信号：mini/紧凑变体。 |
| mainline gpt-4o-mini: (no_auth_apple_punch_out) | 关注安全、政策、鉴权、信任或内容审核的模型或实验；名称信号：mini/紧凑变体。 |
| mainline gpt-4o: (no_auth_apple_punch_out) | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| mainline gpt-5-chat-safety: (no_auth) | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| mainline text-davinci-002-render-sha: (no_auth) | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |
| mainline text-davinci-002-render-sha: (no_auth_apple_punch_out) | 关注安全、政策、鉴权、信任或内容审核的模型或实验。 |

## 本地化、语言与地区 (50)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:gpt_53_lupo_ctry_bulgarian_paid_geo_v1:a_control | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_bulgarian_paid_geo_v1:b_control_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_bulgarian_paid_geo_v1:c_treatment | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_bulgarian_paid_geo_v1:d_treatment_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_czech_unpaid_geo_v1:a_control | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_czech_unpaid_geo_v1:b_control_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_czech_unpaid_geo_v1:c_treatment | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：未付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_czech_unpaid_geo_v1:d_treatment_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：未付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_danish_paid_geo_v1:a_control | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_danish_paid_geo_v1:b_control_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_danish_paid_geo_v1:c_treatment | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_danish_paid_geo_v1:d_treatment_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_dutch_paid_geo_v1:a_control | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_dutch_paid_geo_v1:b_control_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_dutch_paid_geo_v1:c_treatment | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_dutch_paid_geo_v1:d_treatment_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_finnish_paid_geo_v1:a_control | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_finnish_paid_geo_v1:b_control_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_finnish_paid_geo_v1:c_treatment | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_finnish_paid_geo_v1:d_treatment_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_latvian_paid_geo_v1:a_control | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_latvian_paid_geo_v1:b_control_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_latvian_paid_geo_v1:c_treatment | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_latvian_paid_geo_v1:d_treatment_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_malaysia_paid_geo_v1:a_control | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_malaysia_paid_geo_v1:b_control_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_malaysia_paid_geo_v1:c_treatment | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_malaysia_paid_geo_v1:d_treatment_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_spain_unpaid_geo_v1:a_control | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_spain_unpaid_geo_v1:b_control_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：未付费层级、对照组。 |
| campaign:gpt_53_lupo_ctry_spain_unpaid_geo_v1:c_treatment | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：未付费层级、测试/处理组。 |
| campaign:gpt_53_lupo_ctry_spain_unpaid_geo_v1:d_treatment_fork | 关注多语言、本地化或地区相关行为的模型或实验；名称信号：未付费层级、测试/处理组。 |
| Multilingual_Japan_v0_6 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_Brazil_v0_2 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_Brazil_v0_4 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_Germany_v0_0 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_Germany_v0_1 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_Germany_v1_2 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_India_v0_3 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_India_v1_1 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_India_v1_2 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_Indonesia_v0_2 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_Indonesia_v1_0 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_Indonesia_v1_2 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_Japan_v0_0 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_Japan_v0_2 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_Japan_v0_5 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_SouthKorea_v0_0 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_SouthKorea_v0_4 | 关注多语言、本地化或地区相关行为的模型或实验。 |
| Multilingual_SouthKorea_v0_5 | 关注多语言、本地化或地区相关行为的模型或实验。 |

## 代码、数据与结构化任务 (14)

| 模型 | 中文简要作用说明 |
|---|---|
| life science biotools ez test | 关注代码、函数、结构化数据或任务环境的模型或实验；名称信号：测试/处理组。 |
| Codex Personalization Gmai | 关注代码、函数、结构化数据或任务环境的模型或实验。 |
| Karel BD D4 s1000 20260527 | 关注代码、函数、结构化数据或任务环境的模型或实验。 |
| Karel BD D5 s1150 20260527 | 关注代码、函数、结构化数据或任务环境的模型或实验。 |
| codex_u18_2026_04_23 | 关注代码、函数、结构化数据或任务环境的模型或实验。 |
| karel-bd-c2-s1150-20260518-1150-8shard-2026-05-18-18-32 (ppo step 1150) | 关注代码、函数、结构化数据或任务环境的模型或实验；名称信号：RL 信号。 |
| karel-bd-c2-s900-20260517-900-8shard-2026-05-18-00-31 (ppo step 900) | 关注代码、函数、结构化数据或任务环境的模型或实验；名称信号：RL 信号。 |
| Karel D8 DelphiV4 m2.1 s1450 | 关注代码、函数、结构化数据或任务环境的模型或实验。 |
| Karel D8 DelphiV4 m2.1 s1500 | 关注代码、函数、结构化数据或任务环境的模型或实验。 |
| Karel d8_multi DelphiV4 S1000 | 关注代码、函数、结构化数据或任务环境的模型或实验。 |
| bidi pro dual slim grammar with decoder fix | 关注代码、函数、结构化数据或任务环境的模型或实验；名称信号：Pro 层级。 |
| GPT 5.2 codex | 关注代码、函数、结构化数据或任务环境的模型或实验。 |
| bidi pro dual slim grammar | 关注代码、函数、结构化数据或任务环境的模型或实验；名称信号：Pro 层级。 |
| Sean / Stanley Berry Grammar | 关注代码、函数、结构化数据或任务环境的模型或实验。 |

## 训练运行与检查点 (28)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:local_synthetic_index:a_sft_v1_fixed_dogfood_current_index | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：SFT 信号、内部试用(dogfooding)。 |
| campaign:local_synthetic_index:b_sft_v1_fixed_dogfood_synthetic_index | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：SFT 信号、内部试用(dogfooding)。 |
| Dakota D1 S650 SFT Draft EV3 No Browse | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：SFT 信号。 |
| Andromeda RKLD Unpaid 0421 D1 650 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：未付费层级、RL 信号。 |
| Dakota D1 S650 SFT Draft EV3 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：SFT 信号。 |
| GPT-5.3 old good Garlic DLE 2026-05-20 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点。 |
| RV_Andromeda_rkld_unpaid_0421_D1_650 V2 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：未付费层级、RL 信号。 |
| Andromeda RKLD WB paid 0428 t1 Feather | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：付费层级、低延迟、RL 信号。 |
| Andromeda RKLD WB unpaid 0428 t1 Feather | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：未付费层级、低延迟、RL 信号。 |
| andromeda_rkld_wb_paid_0428_t1_instant | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：付费层级、低延迟、RL 信号。 |
| lifesci rkld100 s80 -> rl s300 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：RL 信号。 |
| andromeda_rkld_latency_paid_0428 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：付费层级、RL 信号。 |
| andromeda_rkld_suffix_paid_0428 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：付费层级、RL 信号。 |
| Dakota D1 C0 SFT Draft EV3 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：SFT 信号。 |
| Dakota D1 C1 SFT Draft EV3 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：SFT 信号。 |
| Dakota D1 N0 SFT Draft EV3 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：SFT 信号。 |
| Dakota D1 N1 SFT Draft EV3 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：SFT 信号。 |
| hczhao_persimmon_sft | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：SFT 信号。 |
| andromeda_rkld_wb_paid_0429 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：付费层级、RL 信号。 |
| andromeda_rkld_wb_unpaid_0429 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：未付费层级、RL 信号。 |
| IMO h3 RKLD | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：RL 信号。 |
| rkld_run3_s100_dogfood | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：RL 信号、内部试用(dogfooding)。 |
| bidi_05_06_clone | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点。 |
| 05_07_pro_clone | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：Pro 层级。 |
| 05_12_clone_final | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点。 |
| Yaro GPT-5.3 Instant DLE Rev5 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点；名称信号：低延迟。 |
| Yaro GPT-5.3 Tolo1 DLE May19 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点。 |
| Yaro GPT-5.3 Tolo1 DLE Spud May19 | 来自 SFT / RL / draft / step / shard 训练流程的训练运行或检查点。 |

## 基础设施、路由与冒烟测试 (14)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:5p1_smoke_paragen_manual_1027_try2:a_gpt5t_control | 基础设施、路由或冒烟测试相关条目；名称信号：对照组、冒烟测试。 |
| campaign:5p1_smoke_paragen_manual_1027_try2:b_gpt5p1_smoke | 基础设施、路由或冒烟测试相关条目；名称信号：冒烟测试。 |
| campaign:dummy_campaign:a_gpt52 | 基础设施、路由或冒烟测试相关条目。 |
| ChatGPT bridge snapshot compose s650 smoke | 基础设施、路由或冒烟测试相关条目；名称信号：冒烟测试。 |
| ChatGPT bridge snapshot multiyield s650 smoke | 基础设施、路由或冒烟测试相关条目；名称信号：冒烟测试。 |
| ChatGPT bridge snapshot proxy s650 smoke | 基础设施、路由或冒烟测试相关条目；名称信号：冒烟测试。 |
| ChatGPT bridge snapshot r-c7 s650 smoke | 基础设施、路由或冒烟测试相关条目；名称信号：冒烟测试。 |
| ChatGPT bridge snapshot repoint s650 smoke | 基础设施、路由或冒烟测试相关条目；名称信号：冒烟测试。 |
| ChatGPT bridge snapshot s650 smoke | 基础设施、路由或冒烟测试相关条目；名称信号：冒烟测试。 |
| andromeda_smoke_paid | 基础设施、路由或冒烟测试相关条目；名称信号：付费层级、冒烟测试。 |
| andromeda_smoke_unpaid_1000 | 基础设施、路由或冒烟测试相关条目；名称信号：未付费层级、冒烟测试。 |
| andromeda_smoke_unpaid_1400 | 基础设施、路由或冒烟测试相关条目；名称信号：未付费层级、冒烟测试。 |
| 5p4r_mini_smoke | 基础设施、路由或冒烟测试相关条目；名称信号：mini/紧凑变体、冒烟测试。 |
| 5p4r_mini_smoke_2 | 基础设施、路由或冒烟测试相关条目；名称信号：mini/紧凑变体、冒烟测试。 |

## ChatGPT 产品与通用助手变体 (336)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:spot_20260128_default_paid_paragen:a_control | ChatGPT 产品或通用助手变体；名称信号：付费层级、对照组。 |
| campaign:spot_20260128_default_paid_paragen:b_20260128_default_0 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:spot_20260128_default_paid_paragen:c_20260128_default_1 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:spot_20260128_default_paid_paragen:d_20260128_default_2 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:spot_20260128_default_paid_paragen:e_20260128_default_3 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:5p3_arm7_s950_vs_s1450_unpaid_v1:a_control | ChatGPT 产品或通用助手变体；名称信号：未付费层级、对照组。 |
| campaign:5p3_arm7_s950_vs_s1450_unpaid_v1:b_treatment | ChatGPT 产品或通用助手变体；名称信号：未付费层级、测试/处理组。 |
| campaign:5p3_vs_chathack_s1000_paid:a_arm7 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:4o_vs_52auto_paid:a_5p2auto | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:4o_vs_52auto_paid:b_4o | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:5p3_casual_formal_prompts_free:a_control | ChatGPT 产品或通用助手变体；名称信号：未付费层级、对照组。 |
| campaign:5p3_casual_formal_prompts_free:b_treatment | ChatGPT 产品或通用助手变体；名称信号：未付费层级、测试/处理组。 |
| campaign:5p3_instant_mini_vs_5p3_instant_paid:a_control_5p3_instant | ChatGPT 产品或通用助手变体；名称信号：付费层级、低延迟、对照组、mini/紧凑变体。 |
| campaign:5p3_instant_mini_vs_5p3_instant_paid:b_5p3_instant_mini | ChatGPT 产品或通用助手变体；名称信号：付费层级、低延迟、mini/紧凑变体。 |
| campaign:5p3_nosearch_baseline__paid:a_prod | ChatGPT 产品或通用助手变体；名称信号：付费层级、基线、生产对比。 |
| campaign:5p3_vs_5p4r_unpaid_0404:a_5p3 | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| campaign:5p3_vs_5p4r_unpaid_0404:b_5p4r | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| campaign:5p3_vs_chathack_s1000_paid:b_hack_s1000 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:5p3c_mini_arm3_vs_5p3c_paid2:a_control_5p3_instant | ChatGPT 产品或通用助手变体；名称信号：低延迟、对照组、mini/紧凑变体。 |
| campaign:5p3c_mini_arm3_vs_5p3c_paid2:b_sp_mini_chat_rev4_arm3 | ChatGPT 产品或通用助手变体；名称信号：mini/紧凑变体。 |
| campaign:5p5_instant_free_professional_0512:a_control | ChatGPT 产品或通用助手变体；名称信号：未付费层级、低延迟、对照组。 |
| campaign:5p5_instant_free_professional_0512:b_treatment | ChatGPT 产品或通用助手变体；名称信号：未付费层级、低延迟、测试/处理组。 |
| campaign:5p5_instant_paid_professional_0512:a_control | ChatGPT 产品或通用助手变体；名称信号：付费层级、低延迟、对照组。 |
| campaign:5p5_instant_paid_professional_0512:b_treatment | ChatGPT 产品或通用助手变体；名称信号：付费层级、低延迟、测试/处理组。 |
| campaign:5p5_instant_pro_professional_0512:a_control | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、低延迟、对照组。 |
| campaign:5p5_instant_pro_professional_0512:b_treatment | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、低延迟、测试/处理组。 |
| campaign:chatgpt_mobile_two_line_entity_metadata_button_paid:a_control | ChatGPT 产品或通用助手变体；名称信号：付费层级、对照组。 |
| campaign:chatgpt_mobile_two_line_entity_metadata_button_paid:b_test | ChatGPT 产品或通用助手变体；名称信号：付费层级、测试/处理组。 |
| campaign:chatgpt_mobile_two_line_entity_metadata_button_unpaid:a_control | ChatGPT 产品或通用助手变体；名称信号：未付费层级、对照组。 |
| campaign:chatgpt_mobile_two_line_entity_metadata_button_unpaid:b_test | ChatGPT 产品或通用助手变体；名称信号：未付费层级、测试/处理组。 |
| campaign:chatgpt_mobile_two_line_entity_metadata_paid:a_control | ChatGPT 产品或通用助手变体；名称信号：付费层级、对照组。 |
| campaign:chatgpt_mobile_two_line_entity_metadata_paid:b_test | ChatGPT 产品或通用助手变体；名称信号：付费层级、测试/处理组。 |
| campaign:chatgpt_mobile_two_line_entity_metadata_unpaid:a_control | ChatGPT 产品或通用助手变体；名称信号：未付费层级、对照组。 |
| campaign:chatgpt_mobile_two_line_entity_metadata_unpaid:b_test | ChatGPT 产品或通用助手变体；名称信号：未付费层级、测试/处理组。 |
| campaign:cw_para_paid_auto_55_writing_comm_v1:a_control | ChatGPT 产品或通用助手变体；名称信号：付费层级、对照组。 |
| campaign:cw_para_paid_auto_55_writing_comm_v1:b_long_para | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:cw_para_paid_auto_55_writing_comm_v1:c_exclusive_para | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:cw_para_paid_auto_55_writing_comm_v1:d_avoid_frag | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:gpt52_vs_4o_unpaid:a_5p2 | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| campaign:gpt52_vs_4o_unpaid:b_4o_gg | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| campaign:gpt5_2_longer_ctx_free_paragen:a_prod | ChatGPT 产品或通用助手变体；名称信号：未付费层级、生产对比。 |
| campaign:gpt5_2_longer_ctx_free_paragen:b_long_n_ctx | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| campaign:gpt5p1_smoketest_paragen_auto:a_gpt5p1_smoketest | ChatGPT 产品或通用助手变体。 |
| campaign:gpt_55r_iid:a_control | ChatGPT 产品或通用助手变体；名称信号：对照组。 |
| campaign:gpt_55r_iid:b_treatment | ChatGPT 产品或通用助手变体；名称信号：测试/处理组。 |
| campaign:gpt_5_5_henry_free:a_control | ChatGPT 产品或通用助手变体；名称信号：未付费层级、对照组。 |
| campaign:gpt_5_5_henry_free:b_treatment | ChatGPT 产品或通用助手变体；名称信号：未付费层级、测试/处理组。 |
| campaign:gpt_5_5_henry_paid:a_control | ChatGPT 产品或通用助手变体；名称信号：付费层级、对照组。 |
| campaign:gpt_5_5_henry_paid:b_treatment | ChatGPT 产品或通用助手变体；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_5_5_iid_free:a_control | ChatGPT 产品或通用助手变体；名称信号：未付费层级、对照组。 |
| campaign:gpt_5_5_iid_free:b_treatment | ChatGPT 产品或通用助手变体；名称信号：未付费层级、测试/处理组。 |
| campaign:gpt_5_5_iid_paid:a_treatment | ChatGPT 产品或通用助手变体；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_5_5_iid_paid:b_control | ChatGPT 产品或通用助手变体；名称信号：付费层级、对照组。 |
| campaign:gpt_5_5_iid_pro:a_treatment | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、测试/处理组。 |
| campaign:gpt_5_5_iid_pro:b_control | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、对照组。 |
| campaign:gpt_5_5_lupo_free:a_control | ChatGPT 产品或通用助手变体；名称信号：未付费层级、对照组。 |
| campaign:gpt_5_5_lupo_free:b_treatment | ChatGPT 产品或通用助手变体；名称信号：未付费层级、测试/处理组。 |
| campaign:gpt_5_5_lupo_free:c_treatment_fork | ChatGPT 产品或通用助手变体；名称信号：未付费层级、测试/处理组。 |
| campaign:gpt_5_5_lupo_paid:a_control | ChatGPT 产品或通用助手变体；名称信号：付费层级、对照组。 |
| campaign:gpt_5_5_lupo_paid:b_treatment | ChatGPT 产品或通用助手变体；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_5_5_lupo_paid:c_treatment_fork | ChatGPT 产品或通用助手变体；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_5_5_lupo_pro:a_control | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、对照组。 |
| campaign:gpt_5_5_lupo_pro:b_treatment | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、测试/处理组。 |
| campaign:gpt_5_5_lupo_pro:c_treatment_fork | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、测试/处理组。 |
| campaign:gpt_5p2_concise_more_paid:a_control | ChatGPT 产品或通用助手变体；名称信号：付费层级、对照组。 |
| campaign:gpt_5p2_concise_more_paid:b_treatment | ChatGPT 产品或通用助手变体；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_5p5r_iid_pro:a_control | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、对照组。 |
| campaign:gpt_5p5r_iid_pro:b_treatment | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、测试/处理组。 |
| campaign:gpt_5p5r_lupo_paid:a_control | ChatGPT 产品或通用助手变体；名称信号：付费层级、对照组。 |
| campaign:gpt_5p5r_lupo_paid:b_treatment | ChatGPT 产品或通用助手变体；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_5p5r_lupo_paid:c_treatment_fork | ChatGPT 产品或通用助手变体；名称信号：付费层级、测试/处理组。 |
| campaign:gpt_5p5r_lupo_pro:a_control | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、对照组。 |
| campaign:gpt_5p5r_lupo_pro:b_treatment | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、测试/处理组。 |
| campaign:gpt_5p5r_lupo_pro:c_treatment_fork | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、测试/处理组。 |
| campaign:paid_auto_chat_sys2_only_vs_sys1_only_5p3_paragen:b_oai_index_only | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:paid_auto_chat_sys2_vs_sys1_5p5i_perma_pg_v2:b_oai_index_only | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| campaign:tiancheng_5p2_241212_rewriting:a_2_step_gen | ChatGPT 产品或通用助手变体。 |
| campaign:tiancheng_5p2_241212_rewriting:b_3_step_gen | ChatGPT 产品或通用助手变体。 |
| campaign:tiancheng_5p2_241212_rewriting:c_1_step_gen | ChatGPT 产品或通用助手变体。 |
| campaign:yilin_capability_targeting_gpt_52_iid_free:a_control | ChatGPT 产品或通用助手变体；名称信号：未付费层级、对照组。 |
| campaign:yilin_capability_targeting_gpt_52_iid_free:b_treatment | ChatGPT 产品或通用助手变体；名称信号：未付费层级、测试/处理组。 |
| 5p2-tables | ChatGPT 产品或通用助手变体。 |
| mainline gpt-4o-mini: (biz_no_browse_with_canvas) | ChatGPT 产品或通用助手变体；名称信号：mini/紧凑变体。 |
| mainline gpt-4o-mini: (biz_with_canvas) | ChatGPT 产品或通用助手变体；名称信号：mini/紧凑变体。 |
| mainline gpt-4o: (biz_no_browse_with_canvas) | ChatGPT 产品或通用助手变体。 |
| mainline gpt-4o: (biz_with_canvas) | ChatGPT 产品或通用助手变体。 |
| presearch_mainline_0528 | ChatGPT 产品或通用助手变体。 |
| andromeda_atc_parrot_0514 | ChatGPT 产品或通用助手变体。 |
| mainline gpt-4o-mini: (biz_no_browse) | ChatGPT 产品或通用助手变体；名称信号：mini/紧凑变体。 |
| mainline gpt-4o: (biz_no_browse) | ChatGPT 产品或通用助手变体。 |
| 011526_default_person_inst | ChatGPT 产品或通用助手变体。 |
| andromeda_d1_s1250_unpaid_p13nmiti | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| andromeda_d1_s1400_unpaid_p13nmiti | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| garlic_a19_fingerling_54t_s240 | ChatGPT 产品或通用助手变体。 |
| garlic_jsd_a19_fingerling_54t_s240 | ChatGPT 产品或通用助手变体。 |
| 5p2_spot_hhcheckpoint_paid_v1 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| 5p2_spot_hhcheckpoint_unpaid_v1 | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| garlic_longer_context_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| Sonic Switcher Old 10/16 | ChatGPT 产品或通用助手变体。 |
| bidi_backend_gpt55_instant_260520 | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| bidi_backend_gpt55_instant_260527 | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| Auto Switcher Paid 20250804 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| 5p4-chat-e2-baseline | ChatGPT 产品或通用助手变体；名称信号：基线。 |
| Bidi backend gpt5.5 instant XL testing | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| ChatGPT bridge snapshot dynamic probe on r-c3-ev3-lutetium-d000-i000 | ChatGPT 产品或通用助手变体。 |
| ChatGPT bridge snapshot probe | ChatGPT 产品或通用助手变体。 |
| GPT-4.5 Mainline | ChatGPT 产品或通用助手变体。 |
| PAGI Mainline Slot 0 | ChatGPT 产品或通用助手变体。 |
| PAGI Mainline Slot 1 | ChatGPT 产品或通用助手变体。 |
| PAGI Mainline Slot 2 | ChatGPT 产品或通用助手变体。 |
| PAGI Mainline Slot 3 | ChatGPT 产品或通用助手变体。 |
| chatgpt_bridge_snapshot_probe_vm_mutated | ChatGPT 产品或通用助手变体。 |
| rashad_testing_mainline_searc | ChatGPT 产品或通用助手变体。 |
| yungsung-5p5-baseline-5p4g-s300 | ChatGPT 产品或通用助手变体；名称信号：基线。 |
| yungsung_baseline_5p1 | ChatGPT 产品或通用助手变体；名称信号：基线。 |
| mainline_follow_up_fix | ChatGPT 产品或通用助手变体。 |
| mainline_follow_up_fix_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| mainline_holdout_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级、保留组。 |
| mainline gpt-4: (biz) | ChatGPT 产品或通用助手变体。 |
| mainline gpt-4: (paid) | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| mainline gpt-4: (pro) | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| mainline gpt-4o-canmore: (pro) | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| mainline gpt-4o-mini: (biz) | ChatGPT 产品或通用助手变体；名称信号：mini/紧凑变体。 |
| mainline gpt-4o-mini: (paid) | ChatGPT 产品或通用助手变体；名称信号：付费层级、mini/紧凑变体。 |
| mainline gpt-4o-mini: (pro) | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、mini/紧凑变体。 |
| mainline gpt-4o-mini: (unpaid) | ChatGPT 产品或通用助手变体；名称信号：未付费层级、mini/紧凑变体。 |
| mainline gpt-4o: (biz) | ChatGPT 产品或通用助手变体。 |
| mainline gpt-4o: (paid) | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| mainline gpt-4o: (pro) | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| mainline gpt-4o: (unpaid) | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| mainline o1-mini: (biz) | ChatGPT 产品或通用助手变体；名称信号：mini/紧凑变体。 |
| mainline o1-mini: (paid) | ChatGPT 产品或通用助手变体；名称信号：付费层级、mini/紧凑变体。 |
| mainline o1-mini: (pro) | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、mini/紧凑变体。 |
| mainline o1-mini: (unpaid) | ChatGPT 产品或通用助手变体；名称信号：未付费层级、mini/紧凑变体。 |
| mainline o1-preview: (biz) | ChatGPT 产品或通用助手变体。 |
| mainline o1-preview: (paid) | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| mainline o1-preview: (pro) | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| mainline o3: (biz) | ChatGPT 产品或通用助手变体。 |
| mainline o3: (paid) | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| mainline o3: (pro) | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| mainline o4-mini: (biz) | ChatGPT 产品或通用助手变体；名称信号：mini/紧凑变体。 |
| mainline o4-mini: (paid) | ChatGPT 产品或通用助手变体；名称信号：付费层级、mini/紧凑变体。 |
| mainline o4-mini: (pro) | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、mini/紧凑变体。 |
| mainline text-davinci-002-render-sha: (biz) | ChatGPT 产品或通用助手变体。 |
| mainline text-davinci-002-render-sha: (paid) | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| mainline text-davinci-002-render-sha: (pro) | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| mainline text-davinci-002-render-sha: (unpaid) | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| GPT-5.5 w/ Product Groups | ChatGPT 产品或通用助手变体。 |
| GPT-5.5 unpaid local biz ctx 16k | ChatGPT 产品或通用助手变体；名称信号：未付费层级、16k 上下文。 |
| SP Mini Chat Rev2 Arm2 s600 | ChatGPT 产品或通用助手变体；名称信号：mini/紧凑变体。 |
| bidi_be_gpt55_instant_260528 | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| chatgpt_local_16k | ChatGPT 产品或通用助手变体；名称信号：16k 上下文。 |
| spud_d64_pro_0320 | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| andromeda_d10_2500_paid_0416 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| andromeda_d10_2500_unpaid_0416 | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| chatgpt_ctx_window_holdback_paid_26_h1 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| chatgpt_ctx_window_holdback_unpaid_26_h1_v2 | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| gpt55_chatrs_paid_260508 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| gpt55_chatrs_yap2_paid_260515 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| gpt55_pro_kc_202406 | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| gpt55_spud_chat_paid_260527 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| holdout_chat_gpt53_2026_05 | ChatGPT 产品或通用助手变体；名称信号：保留组。 |
| paid_instant_andromeda_multisys_0516 | ChatGPT 产品或通用助手变体；名称信号：付费层级、低延迟。 |
| spot_20260130_default_paid | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| spot_20260130_default_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| spud_d64_chat_auto_paid_v3 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| SP-Mini Chat Rev2 Arm4 s175 | ChatGPT 产品或通用助手变体；名称信号：mini/紧凑变体。 |
| bidi-pro-05-07 | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| bidi-pro-05-07-rd-testing | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| gpt_5_3_mini_paid_04_17 | ChatGPT 产品或通用助手变体；名称信号：付费层级、mini/紧凑变体。 |
| 5p3_separate_pool_unpaid_0217 | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| andromeda_d4_baby_fix_es8_paid_0427 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| andromeda_d4_baby_fix_es8_unpaid_0427 | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| andromeda_e2_pers_0507_paid | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| paid_chat_cq_e7_multisys | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| paid_instant_cq_e7_multisys_0511 | ChatGPT 产品或通用助手变体；名称信号：付费层级、低延迟。 |
| paid_5p5_instant_multisys_d8_0521 | ChatGPT 产品或通用助手变体；名称信号：付费层级、低延迟。 |
| 4o with Proactive | ChatGPT 产品或通用助手变体。 |
| 5.2 Chat Mini | ChatGPT 产品或通用助手变体；名称信号：mini/紧凑变体。 |
| 5.3 Instant Feather | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| 5.5i Feather | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| 5p4r in chat | ChatGPT 产品或通用助手变体。 |
| A12 Feather | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| Andromeda D1 1400 GPT-5.3 Instant | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| Andromeda E2 Pers1c S1000 Unpaid 0501 Feather | ChatGPT 产品或通用助手变体；名称信号：未付费层级、低延迟。 |
| C2 Feather | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| Current Pulse Expanded | ChatGPT 产品或通用助手变体。 |
| Feather 4o | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| GPT-5.2 Instant | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| GPT-5.2 Pro Pathfinder | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| GPT-5.3 Andromeda D11 Paid Dedicated | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| GPT-5.3 Auto Paid Boundary High | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| GPT-5.5 Instant | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| Golden Alpha / 5p3 Auto Paid | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| Golden Alpha / 5p3 Instant | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| Golden Alpha / Spud Chat | ChatGPT 产品或通用助手变体。 |
| GoldenAlpha / 5.1 Instant | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| Manuka Pers1c s1000 Feather | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| Pro Galapagos | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| Proactive Dreams | ChatGPT 产品或通用助手变体。 |
| andromeda_atc_default_0515 | ChatGPT 产品或通用助手变体。 |
| andromeda_golden_template_paid | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| andromeda_golden_template_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| andromeda_launch_auto_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| andromeda_launch_instant_paid | ChatGPT 产品或通用助手变体；名称信号：付费层级、低延迟。 |
| bidi-pro-latest | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| bidi_pro_loadtest | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| chat_cot_ui_constant_instant | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| chat_cot_ui_constant_long_auto | ChatGPT 产品或通用助手变体。 |
| chat_cot_ui_summary_auto | ChatGPT 产品或通用助手变体。 |
| chat_cot_ui_summary_instant | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| crest-pro-alpha | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| evanz_pro_preamble_summarizer | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| gpt 5.3 unpaid - | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| gpt_5_5_instant_model_aware_map | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| instant_auto_1400_2_paid | ChatGPT 产品或通用助手变体；名称信号：付费层级、低延迟。 |
| instant_auto_1500_paid | ChatGPT 产品或通用助手变体；名称信号：付费层级、低延迟。 |
| prefix_compaction_5p5_instant_medium_ctx_window_single_summary | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| prefix_compaction_5p5_instant_medium_ctx_window_single_summary_counter_factual | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| robin_instant | ChatGPT 产品或通用助手变体；名称信号：低延迟。 |
| system_prompt_blocks_example_5p4 | ChatGPT 产品或通用助手变体。 |
| test_block_current_gpt5_5_auto_paid | ChatGPT 产品或通用助手变体；名称信号：付费层级、测试/处理组。 |
| test_system_prompt_blocks_5_5_chat | ChatGPT 产品或通用助手变体；名称信号：测试/处理组。 |
| test_system_prompt_current_gpt5_5_auto_paid | ChatGPT 产品或通用助手变体；名称信号：付费层级、测试/处理组。 |
| tiancheng_5p2_system_prompt_tuner | ChatGPT 产品或通用助手变体。 |
| 5p3_followups_dev_msg_paid_v1 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| 5p3_large_context_free_v1 | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| 5p3_large_context_paid_v1 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| 5p3_spmini_arm3_arm4_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级、mini/紧凑变体。 |
| 5p3_stolo_paid_0224 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| 5p5_auto_paid_longer_context_window | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| 5p5_auto_paid_very_long_context_window | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| andromeda_d1_s1250_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| andromeda_e2_pers3b_0511_free | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| andromeda_mono_hg_free | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| andromeda_mono_hg_paid | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| andromeda_mva2_0409_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| andromeda_no_chat_1_auto_switching | ChatGPT 产品或通用助手变体。 |
| awchen_gpt5_5_unpaid_wid_sys1 | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| chat_exp_platform_test | ChatGPT 产品或通用助手变体；名称信号：测试/处理组。 |
| chatgpt_feedback_v2_free_auto | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| chatgpt_feedback_v2_paid_auto | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| chatgpt_jobs_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| chatgpt_mec_recent_convo_desc | ChatGPT 产品或通用助手变体。 |
| cw_para_paid_auto_55_v1 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| cw_para_paid_auto_v1 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| gpt52_shrink_factor_paid | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| gpt53_alsoran_holdout_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级、保留组。 |
| gpt55_auto_wb_pi_order_paid | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| gpt55_auto_wb_pi_order_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| gpt55_cotv5_instant_paid_v0 | ChatGPT 产品或通用助手变体；名称信号：付费层级、低延迟。 |
| gpt5_5_unpaid_mec_tbt_dedicated_v2 | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| gpt_55_fp32_paid | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| local_biz_ctx_gpt55_paid_v2 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| local_biz_ctx_gpt55_unpaid | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| sonic_summary_message_paid_0415 | ChatGPT 产品或通用助手变体；名称信号：付费层级。 |
| bidi-pro-04-13 | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| bidi-pro-05-01 | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| bidi-pro-05-13-XL-testing | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| wb_devmsg_gpt55_pro | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| gpt55_cotv5_pro_v0 | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| 5p5_sys_prompt_test | ChatGPT 产品或通用助手变体；名称信号：测试/处理组。 |
| xueqing_gpt5p4_pro | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| gpt55_53_mem_free | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| gpt55_54_mem_free | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| gpt_55_fp32_free | ChatGPT 产品或通用助手变体；名称信号：未付费层级。 |
| m3m_test_pro | ChatGPT 产品或通用助手变体；名称信号：Pro 层级、测试/处理组。 |
| gpt55_tpp_pro_v0 | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| gpt55_tpp_pro_v1 | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| Potion 5rmini Pro | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| spot_prompt_1219 | ChatGPT 产品或通用助手变体。 |
| 5p4_0219_s1020_v4_pro | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| o3 Pro | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| 5p4_1020_pro | ChatGPT 产品或通用助手变体；名称信号：Pro 层级。 |
| gpt52_q1_2026_model_holdout | ChatGPT 产品或通用助手变体；名称信号：保留组。 |
| andromeda_learning_blocks_trigger_v7 | ChatGPT 产品或通用助手变体。 |
| andromeda_shopping_sysmsg_0507 | ChatGPT 产品或通用助手变体。 |
| andromeda_learning_blocks_trigger_v8 | ChatGPT 产品或通用助手变体。 |
| 5p5-pd-drop-a | ChatGPT 产品或通用助手变体。 |
| Andromeda e2 s1500 | ChatGPT 产品或通用助手变体。 |
| Calpico o3 | ChatGPT 产品或通用助手变体。 |
| GPT 4o + Clickable Followups | ChatGPT 产品或通用助手变体。 |
| GPT 5 Health Mode 2 | ChatGPT 产品或通用助手变体。 |
| GPT 5.5 - Flaffy | ChatGPT 产品或通用助手变体。 |
| GPT-5.5 with activation classifiers onboard | ChatGPT 产品或通用助手变体。 |
| GPT-5.5-capability-separation | ChatGPT 产品或通用助手变体。 |
| GPT5 Health Mode | ChatGPT 产品或通用助手变体。 |
| GPT5 auto with sonic shopping | ChatGPT 产品或通用助手变体。 |
| GPT5.5 + activations 05_22 | ChatGPT 产品或通用助手变体。 |
| GPT5.5 dil_alpha2 | ChatGPT 产品或通用助手变体。 |
| GoldenAlpha / 5.1 Auto | ChatGPT 产品或通用助手变体。 |
| Health Connectors GPT-5 | ChatGPT 产品或通用助手变体。 |
| RV Andromeda D10_2500 D10_1 V2 | ChatGPT 产品或通用助手变体。 |
| RV Andromeda D10_2500 D10_2 V2 | ChatGPT 产品或通用助手变体。 |
| Synapse Control | ChatGPT 产品或通用助手变体；名称信号：对照组。 |
| Synapse Mitigation Capability Separation | ChatGPT 产品或通用助手变体。 |
| gpt4o + Clickable DR Followups | ChatGPT 产品或通用助手变体。 |
| gpt5.5-activations | ChatGPT 产品或通用助手变体。 |
| o3 test ca | ChatGPT 产品或通用助手变体；名称信号：测试/处理组。 |
| pulse expanded variant B | ChatGPT 产品或通用助手变体。 |
| pulse expanded variant C | ChatGPT 产品或通用助手变体。 |
| pulse expanded variant D | ChatGPT 产品或通用助手变体。 |
| pulse expanded variant E | ChatGPT 产品或通用助手变体。 |
| sca_5p1_cheap_s350 | ChatGPT 产品或通用助手变体。 |
| tiancheng_5p2_251211 | ChatGPT 产品或通用助手变体。 |
| tiancheng_5p2_251211_plus | ChatGPT 产品或通用助手变体。 |
| yungsung-5p2-pd-drop-a | ChatGPT 产品或通用助手变体。 |
| 0511_sonic_sideline_gpt55_ab | ChatGPT 产品或通用助手变体。 |
| 0511_sonic_sideline_modes_ab | ChatGPT 产品或通用助手变体。 |
| 0511_sonic_sideline_modes_ab_gpt55 | ChatGPT 产品或通用助手变体。 |
| 0511_sonic_sideline_modes_ab_v2 | ChatGPT 产品或通用助手变体。 |
| 5p3_collab_utility_v1_4_sp | ChatGPT 产品或通用助手变体。 |
| 5p3_collab_v1_5_sp | ChatGPT 产品或通用助手变体。 |
| 5p3_separate_pool_tolo_0219v2 | ChatGPT 产品或通用助手变体。 |
| 5p4_summary_v3 | ChatGPT 产品或通用助手变体。 |
| andromeda_high_juice_autoswitch | ChatGPT 产品或通用助手变体。 |
| andromeda_learning_blocks_staging | ChatGPT 产品或通用助手变体。 |
| andromeda_learning_blocks_trigger_v2 | ChatGPT 产品或通用助手变体。 |
| andromeda_shopping_sys_message_v1 | ChatGPT 产品或通用助手变体。 |
| GPT-froge-hide-on-bush | ChatGPT 产品或通用助手变体。 |
| o3 with connectors | ChatGPT 产品或通用助手变体。 |
| ecosystem_5p3_rev2_v2 | ChatGPT 产品或通用助手变体。 |
| spot_testing | ChatGPT 产品或通用助手变体。 |
| GPT 5.5 s1350 | ChatGPT 产品或通用助手变体。 |
| GPT 5.5 s1450 | ChatGPT 产品或通用助手变体。 |
| GPT 5.5 s1500 | ChatGPT 产品或通用助手变体。 |
| GPT-4o | ChatGPT 产品或通用助手变体。 |
| GPT-5.2 | ChatGPT 产品或通用助手变体。 |
| GPT-5.3 | ChatGPT 产品或通用助手变体。 |
| GPT-5.5 | ChatGPT 产品或通用助手变体。 |
| gpt 5-3 | ChatGPT 产品或通用助手变体。 |
| gpt-4o | ChatGPT 产品或通用助手变体。 |
| gpt-5-3 | ChatGPT 产品或通用助手变体。 |
| gpt4o | ChatGPT 产品或通用助手变体。 |
| gpt55_tpp_v0 | ChatGPT 产品或通用助手变体。 |
| 5p1-s350 | ChatGPT 产品或通用助手变体。 |

## 通用研究或用途不明 (231)

| 模型 | 中文简要作用说明 |
|---|---|
| campaign:shashank_paragen_test6:a_control | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：对照组。 |
| campaign:shashank_paragen_test6:b_treatment | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| campaign:test_shashank_aug_0217:a_control | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：对照组、测试/处理组。 |
| campaign:test_shashank_aug_0217:b_treatment | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| campaign:arm8g_s2100_paragen_inverted:a_step2100 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| campaign:arm8g_s2100_paragen_inverted:b_control | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：对照组。 |
| campaign:augmented_dev_msg_test:a_developer_prompt_append_extra_instructions | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| campaign:augmented_dev_msg_test:b_augment | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| campaign:gpt5p1_smoketest_paragen:a_gpt5p1_smoketest | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| campaign:gpt5p1_smoketest_paragen:b_gpt5p1_smoketest | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| campaign:instruction_gen_paragen_test:a_control | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：对照组、测试/处理组。 |
| campaign:instruction_gen_paragen_test:b_t1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| campaign:model_aware_map:a_control | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：对照组。 |
| campaign:model_aware_map:b_test | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| campaign:revamp3_shopping_unpaid_sysmsg:a_prod | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级、生产对比。 |
| campaign:revamp3_shopping_unpaid_sysmsg:b_revampv3 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| campaign:revampv3_shopping_unpaid:a_prod_notools | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级、生产对比。 |
| campaign:revampv3_shopping_unpaid:b_revampv3 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| campaign:shashank_paragen_test3:a_control | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：对照组。 |
| campaign:shashank_paragen_test3:b_treatment | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| d8_delphiv4_w2p1_parrot_v2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| d8_delphiv4_w2p1_parrot_v2_paid | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| Deep Research Mini (Mar 24) | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：mini/紧凑变体。 |
| Ghostrider final (no parrot) | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Math blocks (allis 210) | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| math_blocks_allis_0210_exp | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Kaus S1400 NoEmoji P13nFix Tolo | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| d8_s1400 baseline step 1400 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：基线。 |
| C2 step 450 \ | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| evanz_fingerling_test | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| life sciences early access v1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| lifesciences burnout krao step40 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| 5p4g-baseline | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：基线。 |
| A3 Baseline | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：基线。 |
| autoswitcher_paid_remove_dev_messages | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| Current Mercury d64 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Local Synthetic 600 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| bd_shop_prompt_abl_0526_unpaid | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| Arm7 Paid with Local Changes | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| ads_self_knowledge_holdout_unpaid_0427 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级、保留组。 |
| yanming_mva2_paid_04_07_02 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| bd a14 s1100 paid j8 berry cs | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| ads_self_knowledge_long_holdout_unpaid_0508 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级、保留组。 |
| wb_doc_boundary_ctl_g55_free_0518 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| wb_doc_boundary_ctl_g55_paid_0518 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| 5.2 Minimal Sysprompt | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| COMBINATION_PROMPTS_V2_0_BASE | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Daydream Full Convo Free | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| Golden Alpha / Bidi spmini | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：mini/紧凑变体。 |
| Professional V5 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| SP Mini Arm 4 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：mini/紧凑变体。 |
| an_formatting_prompt | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| d1 sys prompt rohan | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| miaolin_test_spmini | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组、mini/紧凑变体。 |
| no-chatbait | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| spmini local synth | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：mini/紧凑变体。 |
| system_prompt_blocks_example | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| test_cademy_prompt | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| 5p4r_mini_s210_paid | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级、mini/紧凑变体。 |
| 5p4r_mini_s210_teams | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：mini/紧凑变体。 |
| 5pt3_clickbait_fix_unpaid_v1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| 5pt3_clickbait_fix_unpaid_v2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| 5pt3_clickbait_upweighted_paid_v1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| ads_self_knowledge_long_holdout_unpaid_0501 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级、保留组。 |
| emperical_priority_bump_free | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| generic_entity_paid_holdout | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级、保留组。 |
| generic_entity_unpaid_holdout | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级、保留组。 |
| lupoy_unpaid_0324 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| mec_holdout_paid_2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级、保留组。 |
| no_money_ext_dedicate_free | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| renderer_nctx_buffer_paid | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| skills_enablement_for_paid_users | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| st_fully_system2_paid | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| vita_health_prompt_r3_0520_paid | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| vita_health_prompt_r4_0521_unpaid | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| wb_doc_boundary_ctl_g55_free_0513 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| wb_doc_boundary_ctl_g55_paid_0513 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| wb_doc_boundary_g55_free_0513 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| wb_doc_boundary_g55_paid_0513 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| write_block_dedicated_free | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| write_block_dedicated_free_v2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| write_block_dedicated_free_v3 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级。 |
| write_block_dedicated_paid_v3 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：付费层级。 |
| xxiang_test_prompt_exp_0 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| Better Writing Prompt | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| current_bidi_mini_v2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：mini/紧凑变体。 |
| dominik gruber | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| system_prompt_blocks_test | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| Current Mercury | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Low NCTX | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| mec_holdout_free | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：未付费层级、保留组。 |
| 5_3_mini_test | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组、mini/紧凑变体。 |
| test_system_prompt_5 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| C2_delphiv6_s450 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| alsamer021726 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| alsamer101625 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| arcanine_s690 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| bidi-05-06 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| jane_nux_v6 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| jj6a1150 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| rev6 arm6 s1300 (2026-02-19 export) | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| yanming_test_04_06 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| yanming_test_04_06_03 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| 5p4r_s610_s930 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| gan_availability_0527_v2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| yanming_test_05_27 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| ads_self_knowledge_holdout_go_0427 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：保留组。 |
| LMSYS - 5p4r - j128 (high) | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| User Signals Medley Model (s850) | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| alsamer100825 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| bd a14 s1100 j8 berry cs | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| gift_80k | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：80k 上下文。 |
| ads_self_knowledge_long_holdout_go_0508 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：保留组。 |
| d8_delphiv4_w2p1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| kenny_test_05_08 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| 5.5i / health sysmsg | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Aidan Test | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| Bio Stream | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Bristy Jan 29 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Cached Recent Convo | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Creative V4 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Creative Writing | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Creative Writing 🥄 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| DBV4 Extra Log | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Entity Sidebar (10/15) | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Experimental DIL Alpha | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Glean Demo | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Gmail Dreamer | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Golden Alpha / Bidi | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Personal Context Ship Candidate | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Personal Context v0.1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Synth Data Spud 2 stage | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| TOLO DelphiV4 originalfresh S1050 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Test Onboarding model | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| alpha.bidi_05_12 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| answer_highlighting | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| belbute dev rap | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| bidi-latest | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| bidi-nv4a-fe-bb | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| brandonw test 5.2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| checklist_251219_append | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| citron_v4_noautoswitch | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| crest-alpha | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| drew_behavior_test01 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| dynamic 52 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| evanz test | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| evanz_test_1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| evanz_testing_3 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| feedback_alpha_v2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| galapagos-alpha | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| gan_availability_0515 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| gan_no_entity_metadata_caching | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| garys_test_model | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| gpt54r xpanded db | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| hack_1400 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| jane_nux_v2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| jane_nux_v3 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| just a test | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| kennan_test | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| max_consecutive_model_messages | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| mm_2a1900_sys_msg | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| onboarding_bot_new | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| pauldb wrapper | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| random_test_model | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| rashad_testing_migration_2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| rastan_dil | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| romie_onboarding1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| romie_ratelimit1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| sherman-r4 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| sherman_r4 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| sherman_r5 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| spud-0324-run1-54t-cbv9-teacher | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| spud-0324-run3-gpt54-teacher | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| tetaetata | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| tmp-test-alpha | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| will random testing | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| writing_id_match | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| xue_march_2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| yanming_test_05_19 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| yilei_paragen_title | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| 5p5r_large_context_v1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| ads_self_knowledge_long_holdout_go_0501 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：保留组。 |
| header_openings | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| model_aware_map_ab | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| onboarding_interview_mode | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| test_dev_message_experimnt | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| test_exp_raunak_2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| text_exp_raunak_1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| xxiang_test_exp_11 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| Double Click | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Jobs | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| MM-1b-s2450-sys-msg | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| bidi-juno-v20-v4 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| bidi_renderer_2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| bidi_verbose_debug_engine | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| bowen_test | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| C2_s1200 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Chinese_Test_Style_v5 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| Florence 5p2t | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Pers1c s1000 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| chris_test_5_4 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| citron_v4 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| citron_v5 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| jj0cs1500 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| tomye pc test off | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| tomye pc test on | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| D1 honest/h1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| D1 honest/h1 (v2) | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| High Reintro D11 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| High reintro D11 s1500 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Low reintro D4 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Low reintro D4 s1500 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| old_ht | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| test_render_revert | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| yungsung-pd-new | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| Joke Expert | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| No Money Extreme | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| fp_refresh_e2_s150 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| henry_vs_system | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| jou_test | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| new_ht | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| qwe | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| tomye test 01 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| tomye_test | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| yungsung_qwe2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| tmp_experiment_0511 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| tomye_test_2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点；名称信号：测试/处理组。 |
| yungsung_2 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| yungsung_5 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| yungsung_tmp1 | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |
| iris | 从名称无法明确推断具体产品用途，可能是通用模型族或研究检查点。 |

