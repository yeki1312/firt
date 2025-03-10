fist
using System;

namespace TemperatureConversion
{
    class Program
    {
        static void Main(string[] args)
        {
            // دریافت دما به درجه سانتی‌گراد از کاربر
            Console.Write("لطفاً دما را به درجه سانتی‌گراد وارد کنید: ");
            double celsius = Convert.ToDouble(Console.ReadLine());

            // تبدیل دما به درجه فارنهایت
            double fahrenheit = (9.0 / 5.0) * celsius + 32;

            // نمایش معادل دما به درجه فارنهایت
            Console.WriteLine($"{celsius} درجه سانتی‌گراد معادل {fahrenheit} درجه فارنهایت است.");
        }
    }
}
