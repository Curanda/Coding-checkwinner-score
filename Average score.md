const calcAverage = (x, y ,z) => {return ((x + y + z) / 3)};


let avgDolphins = calcAverage(401, 30, 71);
let avgKoalas = calcAverage(40, 54, 49);

const checkWinner = function (avgDolphins, avgKoalas) {
    if (avgDolphins >= 2 * avgKoalas) {
        console.log(`Dolphins win ${avgDolphins} : ${avgKoalas}`);
    } else {
        if (avgKoalas >= 2 * avgDolphins) {
            console.log(`Koalas win ${avgKoalas} : ${avgDolphins}`);
        } else {
            console.log(`No team wins`);
        }
    }
};

console.log(checkWinner(avgDolphins, avgKoalas));