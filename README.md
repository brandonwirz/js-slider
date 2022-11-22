JS Slider algoritym calculates monthly savings in fuel cost based on the number of fill ups per week.

function computeDiscount(avgGallonsPerWeek, fillUpsPerWeek, fuelCost, discount){
const gallPerWkFillUp = avgGallonsPerWeek _ fillUpsPerWeek;
const totalMonthlyGallons = gallPerWkFillUp _ 4;
totalSavings = totalMonthlyGallons _ fuelCost _ discount;
return '$' + totalSavings + ` in monthly savings`;
}
console.log(computeDiscount(315, 4, 5,.2));


<img width="339" alt="Screenshot 2022-11-21 at 9 12 11 PM" src="https://user-images.githubusercontent.com/17913209/203222351-8eb583d7-c104-42a7-8705-2af123e5b4be.png">
