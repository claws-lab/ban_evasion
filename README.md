# Characterizing, Detecting, and Predicting Online Ban Evasion
## Manoj Niverthi, Gaurav Verma, Srijan Kumar
### A repository containing the code and data used in the study accepted at WWW 2022

## Code Structure
- `code` contains the implementation of various scripts used during the study
	```
	code
	├── task1
	│   ├── analysis.py
	│   ├── contrib_features_task1.py
	│   ├── match_parent_blocked_users.py
	│   ├── parents_per_neg_child.py
	│   ├── scrape_edits_for_negative_samples.py
	│   ├── successful_evaders.py
	│   └── training_testing_sampling.py
	├── task2
	│   ├── analysis.py
	│   ├── contrib_analysis_scores.py
	│   ├── create_mismatched_samples.py
	│   ├── match_parent_normal_users.py
	│   ├── parents_per_neg_child.py
	│   ├── scrape_edits_for_negative_samples.py
	│   ├── scrape_normal_users.py
	│   └── training_testing_sampling.py
	└── task3
		├── analysis.py
		├── build_network.py
		├── contrib_analysis_chart.py
		├── contrib_analysis_scores.py
		├── create_mismatched_samples.py
		├── define_groups.py
		├── define_pairs.py
		├── filter_blocked_users.py
		├── filter_pairs.py
		├── find_neg_samples.py
		├── get_puppetmasters.py
		├── get_puppetmasters.pyc
		├── get_user_contrib.py
		├── group_stats.py
		├── match_children_to_false_parents.py
		├── match_socks_subcat.py
		├── parents_per_neg_child.py
		├── remove_matched_samples.py
		├── scrape_negative_creation_times.py
		├── scrape_negative_pairs.py
		├── training_testing_datasets.py
		└── training_testing_sampling.py
	```
- `data` contains the raw data files used during the study
	```
	data
	├── task1
	│   ├── task1_training_temp_samples.csv
	│   ├── task1_testing_temp_samples.csv
	│   ├── task1_positive_temp_samples.csv
	│   ├── task1_negative_temp_samples.csv
	├── task2
	│   ├── task2_training_temp_samples.csv
	│   ├── task2_testing_temp_samples.csv
	│   ├── task2_positive_temp_samples.csv
	│   ├── task2_negative_temp_samples.csv
	├── task3a
	│   ├── task3a_training_temp_samples.csv
	│   ├── task3a_testing_temp_samples.csv
	│   ├── task3a_positive_temp_samples.csv
	│   ├── task3a_negative_temp_samples.csv
	└── task3
		├── task3b_training_temp_samples.csv
		├── task3b_testing_temp_samples.csv
		├── task3b_positive_temp_samples.csv
		└── task3b_negative_temp_samples.csv
	```
