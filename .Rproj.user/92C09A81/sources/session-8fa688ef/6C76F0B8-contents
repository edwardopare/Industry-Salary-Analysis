#Question 2
salary$work_year <- as.numeric(salary$work_year)
salary$salary_in_usd <- as.numeric(salary$salary_in_usd)

#Visuals of Relationship between work experience and salary
ggplot(data = salary)+
  geom_point(mapping = aes(x=work_year, y=salary_in_usd))+
  labs(title = "Correlation Between Years of Experience and Salary")


# Calculate correlation coefficient
correlation <- cor(salary$work_year, salary$salary_in_usd)
print(paste("Correlation Coefficient:", correlation))

