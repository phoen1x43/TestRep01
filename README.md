using System;

public class Task31
{
    public static void Main(string[] args)
    {
        public RndOrHands(int a; bool t = false)
        {
            if (!t)
            {
                RndFill();
            }
            else
            {
                FillByUser();
            }
        }
    }
    public static RndFill()
    {
        Random rnd = new Random;
        int[] array = new int[rnd];
        for (int i = 0; i<rnd; i++)
        {
            array[i] = rnd.Next(100);
        }
    }

    public static FillByUser()
    {
        int n = Console.ReadLine();
        int[] array = new int[n];
        Console.WriteLine("Введите элементы массива");
        for (int i = 0; i<n; i++)
        {
            int input = Console.ReadLine();
        }
    }

}

public class OneMassive
{
    public double GetAverage(int n)
    {
        int count = 0
        foreach (int i in array)
        {
            count += i;
            return count / n;
        }
    }

    public int[] DeleteMoreThanOneHundred(int[] array)    
    {    
        int[] minnumbers = new int[];
        minnumbersindex = 0;
        foreach (int i in array)
        {
            if (Math.Abs(i) < 100)
            {
                minnumbers[minnumbersindex] = array[i];
                minnumbersindex++;
            }      
        }
        array = new int[minnumbersindex];
        for (int i = 0; i < minnumbersindex; i++)
        {
            numbers[i] = minnumbers[i];
            return minnumbers;
        }
    }
}
