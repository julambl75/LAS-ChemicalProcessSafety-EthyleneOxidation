(1 ) We include as failure data the 5 "trivial" failures — these can be detected at the location in the process where they occur: lowPressure_source, highTemp_source, lowTemp_source, highTemp_coolingWater, lowTemp_coolingWater
(2 ) We include as failure data 6 "nontrivial" failures [default setting] — these must be detected by measuring the consequences of a failure: missingEthylene_source, lowSetpoint_flowControlLoop, lowSetpoint_tempControlLoop, leak_beforeCompressor, lowPressure_coolingWater, stuckClosed_coolingWaterOutValve
(3 ) We include as failure data 10 "nontrivial" failures: highSetpoint_flowControlLoop, highSetpoint_tempControlLoop, leak_beforeCompressor, lowSetpoint_flowControlLoop, lowSetpoint_tempControlLoop, missingEthylene_source, missingOxygen_source, stuckClosed_coolingWaterOutValve, stuckClosed_tempControlValve, stuckOpen_tempControlValve
(4 ) We include as failure data the above 10 "nontrivial" failures, and also use the full set of data rather than only 75 runs per failure

(5 ) We use numeric variables [default setting]
(6 ) We use buckets (5 of them)

(7 ) We use buckets (3 of them)
(8 ) We use buckets (5 of them) [default setting for buckets]
(9 ) We use buckets (9 of them)

(10) We only use 10 runs per failure from the dataset (split between training and evaluation)
(11) We only use 25 runs per failure from the dataset
(12) We only use 50 runs per failure from the dataset
(13) We only use 75 runs per failure from the dataset [default setting]
(14) We use all 125 runs per failure from the dataset

(15) We use the short-term data from t=2s for training and evaluation
(16) We use the short-term data from t=4s for training and evaluation
(17) We use the short-term data from t=6s for training and evaluation [default setting]
(18) We use the short-term data from t=10s for training and evaluation
(19) We use the short-term data from t=20s for training and evaluation

(20) We include all process parameters as model variables
(21) We include the following "real-world" process parameters as model variables: e2_tsi, e2_tti, k1_p1, m1_pv, m2_pv, m3_pv, r1_t2, snk1_p, snk1_t, srcr1_p, srcr1_t
(22) We include the process parameters from the flow and temperature control loops as model variables: m1_pv, m2_pv
