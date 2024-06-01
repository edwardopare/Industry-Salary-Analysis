#Question 3
# Calculate Remote Work Ratio
remote_ratio <- aggregate(remote_ratio ~ job_title, data = salary, FUN = mean)

# Identify Job Title with Highest Remote Work Ratio
highest_remote_ratio <- remote_ratio[which.max(remote_ratio$remote_ratio), ]

# Print the result
print(highest_remote_ratio)
