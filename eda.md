EDA
================
Yuki Joyama
2024-03-20

``` r
# read RData file
df_recov <- get(load("./data/recovery.RData")) |> 
  janitor::clean_names()

# check the response variable
# df_recov |> 
#   ggplot(aes(x = recovery_time)) +
#   geom_histogram(bins = 30, color = "black", fill = "gray")
```
