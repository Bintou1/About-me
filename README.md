# Bintou Doumbia, MA.
## Graduate student in the school of International Studies

I am proficient in *Data Analysis*

### Skills

Software Programing
- `R studio` especialy `tidyverse` like `gglpot(data=x,aes(y=vars1))`
- `Excell`
- `PowerBi`

Statistical and econometrics
- Data Wrangling
- Data Visualisation
- Date cleaning
- Descriptive analysis
- Regression


### Example of my skills

Here's some code I wrote in R

```# rename, reorder, recode
  df2 = df %>%
    rename(
      countryName = cname,
      womenParl = wdi_wip,
      # blah blah
    ) %>%
    mutate(
      prSystem = FctWhen(
        br_pvote == 0 ~ "Other",
        br_pvote == 1 ~ "PR system",
        TRUE ~ "n/a"
      ),
      .before = 3
      ) 
```

- 📫 How to reach me: [Linkedin] (https://www.linkedin.com/in/bintou-doumbia/)
