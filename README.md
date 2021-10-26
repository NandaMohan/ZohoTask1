# ZohoTask1

<!DOCTYPE html>
<html>
<body>

    <h>Javascript Sum using recursion</h>

 <script>   
    function sum (arr)
    {   
        let x = arr.length ;
        if (x <= 0)
        {
            return 0;
        }
        else
            return arr[x] + sum(arr, x+1)
     }

    console.log(sum([1,2,3,4]));      

</script>
</body>
</html>
