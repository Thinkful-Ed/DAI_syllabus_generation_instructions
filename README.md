**Using folders and files from Github, here is the format of how to manually create your syllabus:**


**ftgen master-syllabus/data_analytics-301/the_day** (found here: https://github.com/Thinkful-Ed/full_time_career_path/tree/master/master-syllabus/data_analytics-301) **/content.md cohort-meta/data_analytics-301/your_cohorts_yaml_file** (create this here: https://github.com/Thinkful-Ed/full_time_career_path/tree/master/cohort-meta using your cohort's Monday start date, ex: cohort-2020-02-03.yaml for next week) **syllabi week_num week_day** (don't forget day 0 for week #1)

**For example, the first 3 days of DAI for week #1 including day #0:**

```
ftgen master-syllabus/data_analytics-301/01.0-pre-course/content.md cohort-meta/data_analytics-301/cohort-2020-02-03.yaml syllabi 1 0

ftgen master-syllabus/data_analytics-301/01.1-intro/content.md cohort-meta/data_analytics-301/cohort-2020-02-03.yaml syllabi 1 1

ftgen master-syllabus/data_analytics-301/01.2-excel-formulas-functions/content.md cohort-meta/data_analytics-301/cohort-2020-02-03.yaml syllabi 1 2

ftgen master-syllabus/data_analytics-301/01.3-excel-logic-stings-dates/content.md cohort-meta/data_analytics-301/cohort-2020-02-03.yaml syllabi 1 3
```

**For example, first day of week #2:**

```
ftgen master-syllabus/data_analytics-301/02.1-excel-pivot-tables/content.md cohort-meta/data_analytics-301/cohort-2020-02-03.yaml syllabi 2 1
```