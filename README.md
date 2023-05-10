# Code-Chunk

```ruby
  ggplot(df,  aes(x = urbanrate, y = internetuserate, size = incomeperperson)) +
  xlim(25,100) + #set x-axis
  ylim(25, 100) + #set y-axis
  geom_point(shape = 19, fill = "gray", position = "jitter", color = "mediumblue") +
  theme_bw() + # white background with grid lines
  labs(x = 'Urban Rate', y = 'Internet Use Rate', title = "Correlation between Internet Use Rate and Urban Rate") + #label
  theme(
    text = element_text(family='Times New Roman'), #font
    plot.title = element_text(family='Times New Roman', face = 'bold', hjust = 0.5), # center title
    plot.background = element_rect(fill='white',color=NA)
  )
  
  ```

```{r fig1, out.width = '450px'}
  knitr::include_graphics('myplot.svg')
```
