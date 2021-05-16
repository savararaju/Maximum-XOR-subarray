# Maximum-XOR-subarray

class Aditya {
    static int maxSubarrayXOR(int arr[], int n)
    {
        int a[]=new int[n];
        for(int i=0;i<n-1;i++)
        {
        int a=arr[i]^arr[i+1];
        int r=Math.max(a);
        }
        return r;
    }
      
    // Driver program to test above functions
    public static void main(String args[])
    {
        int arr[] = {1,2,3,4};
        int n = arr.length;
        System.out.println("Max subarray XOR is " +
                                 maxSubarrayXOR(arr, n));
    }
}
