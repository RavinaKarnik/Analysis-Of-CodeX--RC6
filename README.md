# Analysis-Of-CodeX--RC6
## bfqjnfdkwf
```sql
-- Who prefers energy drink more? (male/female/non-binary?)
select count(r.respondent_id) as no_of_respondent,gender from dim_repondents r
join fact_survey_responses s on r.respondent_id=s.respondent_id
group by gender
order by no_of_respondent desc
```

```sql
-- Who prefers energy drink more? (male/female/non-binary?)
select count(r.respondent_id) as no_of_respondent,gender from dim_repondents r
join fact_survey_responses s on r.respondent_id=s.respondent_id
group by gender
order by no_of_respondent desc
```
```sql
select count(r.respondent_id) as no_of_respondent,gender from dim_repondents r

````