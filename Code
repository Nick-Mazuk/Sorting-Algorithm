//Sort an Array

var sort = function(array) {
    
    var length = array.length-1; 
    
    for(i=0;i<array.length;i++) {
        
        var sorted = true;
        
        for(j=0;j<length;j++) {
            if(array[j]>array[j+1]) {
                array.splice(j,2,array[j+1],array[j]);
                sorted = false;
            }
        }
        
        if(sorted) {
            return array;
        }
        
        length--;
        
    }
    
    return array;
};

sort([2,1,3,4,2,6,4,7,8,6,5,9]);
