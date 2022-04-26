const percentageOfWorld1 = population => (population / 7900) \* 100;

function describePopulation(country, population) {
let percentageOfWorld2 = percentageOfWorld1(38);
return (`${country} has ${population} mln people, which is about ${percentageOfWorld2}, % of world population`);
}

console.log(describePopulation(`Poland`, 38));
