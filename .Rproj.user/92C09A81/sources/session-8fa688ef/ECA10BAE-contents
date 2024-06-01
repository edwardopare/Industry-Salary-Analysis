#Question 5
# Group data by employment type and calculate average salary
avg_salary_by_employment <- aggregate(salary_in_usd ~ employment_type, data = salary, FUN = mean)

# Visualization
ggplot(avg_salary_by_employment, aes(x = employment_type, y = salary_in_usd, fill = employment_type)) +
  geom_bar(stat = "identity") +
  geom_text(aes(label = paste("$", round(salary_in_usd, 2))), vjust = -0.5, size = 3, color = "black") + 
  labs(x = "Employment Type", y = "Average Salary (USD)", title = "Average Salary by Employment Type") 
