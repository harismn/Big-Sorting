# Big-Sorting

* Problem Name : bigSorting *

* Author: _mfv_*

* url: https://www.hackerrank.com/challenges/big-sorting/problem *

* code *
unction bigSorting(arr) {
    // Complete this function
    let berurut = arr.sort((a,b) => {
        if(a.length == b.length){
            if(a > b){
                return 1
            }else {
                return -1
            }
        }
        return a.length - b.length;
    })
        console.log(berurut.join('\n'))
    }

* how to run the program *

$ node big_Sorting.js
