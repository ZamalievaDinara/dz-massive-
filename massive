using System;

int[] arr = new int[12] { 5, 1, 24, 4, 1, 4, 2, 8, 4, 4, 1, 3 };
int max = 0;
int minV = 0;

for (int i = 0; i < arr.Length; i++)
{
    for (int j = 0; j < arr.Length; j++)
    {
        if (((arr[j] - arr[i]) > max) && (arr[i] < arr[j]))
        {
            max = arr[j] - arr[i];
            minV = arr[i];
        }
    }
}
int maxV = minV + max;
int[] output_nums = new int[2] { minV, maxV };
for (int i = 0; i < output_nums.Length; i++)
    Console.WriteLine(output_nums[i]);






