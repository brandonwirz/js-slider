JS Slider algoritym calculates monthly savings in fuel cost based on the number of fill ups per week.

function computeDiscount(avgGallonsPerWeek, fillUpsPerWeek, fuelCost, discount){
const gallPerWkFillUp = avgGallonsPerWeek _ fillUpsPerWeek;
const totalMonthlyGallons = gallPerWkFillUp _ 4;
totalSavings = totalMonthlyGallons _ fuelCost _ discount;
return '$' + totalSavings + ` in monthly savings`;
}
console.log(computeDiscount(315, 4, 5,.2));


<img width="329" alt="Screenshot 2022-11-21 at 9 02 57 PM" src="https://user-images.githubusercontent.com/17913209/203219013-1276081c-3558-419d-9673-29dbcff13f2d.png">
