**Using folders and files from Github, here is the format of how to manually create your syllabus:**


**ftgen master-syllabus/data-301/the_day** (found here: https://github.com/Thinkful-Ed/full_time_career_path/tree/master/master-syllabus/data-301) **/content.md cohort-meta/data-301/your_cohorts_yaml_file** (create this here: https://github.com/Thinkful-Ed/full_time_career_path/tree/master/cohort-meta using your cohort's Monday start date, ex: cohort-2020-02-03.yaml for next week) **syllabi week_num week_day** (don't forget day 0 for week #1)

**For example (first 3 days of DAI for week #1):**

```
ftgen master-syllabus/data-301/01.0-pre-course/content.md cohort-meta/data-301/cohort-2020-02-03.yaml syllabi 1 0

ftgen master-syllabus/data-301/01.1-git/content.md cohort-meta/data-301/cohort-2020-02-03.yaml syllabi 1 1

ftgen master-syllabus/data-301/01.2-programming/content.md cohort-meta/data-301/cohort-2020-02-03.yaml syllabi 1 2

ftgen master-syllabus/data-301/01.3-probability/content.md cohort-meta/data-301/cohort-2020-02-03.yaml syllabi 1 3
```

**For example, First day of week #2:**

```
ftgen master-syllabus/data-301/02.1-sql/content.md cohort-meta/data-301/cohort-2020-02-03.yaml syllabi 2 1
```