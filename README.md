# budget-tracker
const username = 'Mahbeer Partho';
const income = 5000;


//Expenses
let rent =  1200;
let groceries = 600;
let transport = 200;
let entertainment = 300;

//Total Expenses
let totalExpenses = rent + groceries + transport + entertainment;

//Tax Deduction (10% of income)
let tax = income * 0.10;

//net income after the tax
let netIncome = income - tax;

//remaining balance
let balance = netIncome - totalExpenses;

//Savings (20% of remaining balance)
let Savings = balance * 0.20;

console.log('Personal Budget Tracker App');
console.log('User: ' + username);
console.log('Total income: $' + income);
console.log('Total Expenses: $' + totalExpenses);
console.log('Total tax: $' + tax);
console.log('Total remaining balance: $' + balance);
console.log('Total Savings balance: $' + Savings);

//template String
console.log(`Total Savings balance: $${Savings}`);
