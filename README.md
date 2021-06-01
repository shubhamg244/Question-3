# Question-3
# Suppose you have an array of 101 integers. This array is already sorted and all numbers in this array are consecutive. Each number only occurs once in the array except one number which occurs twice. Write a js code to find the repeated number.

<script>
    function printRepeating(arr , size)
    {
        var i, j;
        document.write("Repeated Elements are :");
        for (i = 0; i < size; i++)
        {
            for (j = i + 1; j < size; j++)
            {
                if (arr[i] == arr[j])
                    document.write(arr[i] + " ");
            }
        }
    }
 
var arr = [0,1,2,3,4,5,6,7,7,8,9,10,12,11,13,14,15,1,2,10];
var arr_size = arr.length;
printRepeating(arr, arr_size);
 
</script>
