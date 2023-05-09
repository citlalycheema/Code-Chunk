# Code-Chunk

```ruby
ggplot(df1, aes(y = school, x = lifeexp, color = Status)) +
  geom_point(shape = 21) +
  geom_smooth(method = 'lm', se = F) +
  ggtitle('Impact of Years of Schooling on Life Expectancy') +
  labs(x = 'Life expectancy',
       y = 'Years of Schooling') + # labels
  theme_minimal() +
  theme(plot.title = element_text(face = 'bold', hjust = 0.5))
  
  ```
