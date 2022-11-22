JS Slider algoritym calculates monthly savings in fuel cost based on the number of fill ups per week.

function computeDiscount(avgGallonsPerWeek, fillUpsPerWeek, fuelCost, discount){
const gallPerWkFillUp = avgGallonsPerWeek _ fillUpsPerWeek;
const totalMonthlyGallons = gallPerWkFillUp _ 4;
totalSavings = totalMonthlyGallons _ fuelCost _ discount;
return '$' + totalSavings + ` in monthly savings`;
}
console.log(computeDiscount(315, 4, 5,.2));
