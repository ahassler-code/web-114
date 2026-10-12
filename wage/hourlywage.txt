// Get the hourly wage from the user
let hourlyWage = prompt("Enter your hourly wage:");
let confirmWage = confirm(`You get paid $${hourlyWage} an hour. Is that correct?`);
let hoursWorked = prompt("How many hours did you work this week");
let confirmHours = confirm(`You worked $${hoursWorked} hours this week. is that correct?`);

// Convert the input to a number
hourlyWage = Number(hourlyWage);

// Calculate weekly earnings
let weeklyEarnings = hourlyWage * hoursWorked;

// Display the result
console.log(`Your weekly earnings are: $${weeklyEarnings}`);