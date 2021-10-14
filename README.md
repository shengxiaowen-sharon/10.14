# 10.14
function getArrMax(arr) {
            var max= arr[0];
            for(var i = 1; i <= arr.length; i++){
                if(arr[i] > max){
                    max = arr[i];
                }
                return max;
            }
            
        }
       
        var re = getArrMax([5,2,99,101,67,77]);
