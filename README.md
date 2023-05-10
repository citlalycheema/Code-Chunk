# Code-Chunk

During this course, we have focused heavily on data visualization, which has been a fun learning experience. Below is a code chunk that showcases my data visualization abilities, especially with `ggplot`. It shows how I properly set the limits on the x- and y-axis, set the plot theme, label the axis, and add a title. Additionally, this specific output demonstrates the adding a variable under size can help a plot become more informative.

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


![myplot](https://github.com/citlalycheema/Code-Chunk/assets/123214295/4338b580-6809-47f5-aab8-3d00dfe11656)
