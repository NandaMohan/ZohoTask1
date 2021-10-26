# ZohoTask1

<!DOCTYPE html>
<html>
<body>

    <h>Javascript Sum using recursion</h>

 <script>   
 function sum (arr)
    {   
        if (arr.length <= 0)
        {
            return 0;
        }
        else
            return arr[arr.length-1] + sum(arr, arr.length-1)
        }
}
  console.log(sum([1,2,3,4]));      

</script>
</body>
</html>
