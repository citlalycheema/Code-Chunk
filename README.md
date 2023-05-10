# Code-Chunk

```ruby
  ggplot(df,  aes(x = urbanrate, y = internetuserate, size = incomeperperson)) +
  xlim(25,100) +
  ylim(25, 100) +
  geom_point(shape = 19, fill = "gray", position = "jitter", color = "mediumblue") +
  theme_bw() +
  labs(x = 'Urban Rate', y = 'Internet Use Rate', title = "Correlation between Internet Use Rate and Urban Rate") +
  theme(
    text = element_text(family='Times New Roman'),
    plot.title = element_text(family='Times New Roman', face = 'bold', hjust = 0.5),
    plot.background = element_rect(fill='white',color=NA)
  )
  
  ```
