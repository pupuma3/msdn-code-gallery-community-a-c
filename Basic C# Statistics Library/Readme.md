# Basic C# Statistics Library
## Requires
- Visual Studio 2015
## License
- MIT
## Technologies
- C#
- Windows Forms
- Visual C#
- Visual Studio 2015
## Topics
- C#
- Numerical Computing
- Statistics
## Updated
- 11/29/2015
## Description

<h1>Introduction</h1>
<p><span style="font-family:calibri; font-size:small">In this&nbsp;project we&nbsp;design and implement a small statistics library. Not everyone has the funds to afford Office and Visual Studio versions with the interoperability software so some individuals
 do not have C# access to the wealth of statistical functions in Excel. We attempt to fill this niche with a functioning statistics partial solution.</span></p>
<p><strong>&nbsp;</strong><em>&nbsp;</em></p>
<h1><span>Building the Sample</span></h1>
<p><em>This project should build as is using Visual Studio 2015.</em></p>
<p><span style="font-size:20px; font-weight:bold">Description</span></p>
<p><span style="font-family:calibri; font-size:small">The statistics library and test program use C# .NET Framework 4.5.2. The structure of the statistics class library is shown as a multilevel list with public classes numbered and publicly accessible methods
 lettered and in Roman numerals:</span></p>
<ol>
<li>
<p>Analysis</p>
<ol>
<li>
<p>Data Analysis</p>
<ol>
<li>
<p>Single Sample</p>
<ol>
<li>
<p>Count</p>
</li><li>
<p>Mean</p>
</li><li>
<p>Median</p>
</li><li>
<p>Maximum</p>
</li><li>
<p>Minimum</p>
</li><li>
<p>Kurtosis Sample</p>
</li><li>
<p>Kurtosis Population Estimate</p>
</li><li>
<p>Skewness</p>
</li><li>
<p>Standard Deviation</p>
</li><li>
<p>Variance</p>
</li></ol>
</li><li>
<p>Two Samples</p>
<ol>
<li>
<p>Correlation</p>
</li><li>
<p>Covariance</p>
</li><li>
<p>t-Statistic</p>
</li><li>
<p>Degrees of Freedom for t-Test</p>
</li><li>
<p>t-Test corresponds to Excel T.TEST(array1, array2, 2, 3)</p>
</li><li>
<p>Welch&rsquo;s t-Statistic</p>
</li><li>
<p>Degrees of Freedom for Welch&rsquo;s t-Test</p>
</li><li>
<p>Welch&rsquo;s t-Test similar to 5</p>
</li><li>
<p>F-Statistic</p>
</li></ol>
</li></ol>
</li></ol>
</li><li>
<p>Distributions</p>
<ol>
<li>
<p>Binomial</p>
</li><li>
<p>Chi-Square</p>
</li><li>
<p>Hypergeometric</p>
</li><li>
<p>Negative Binomial</p>
</li><li>
<p>Normal</p>
</li><li>
<p>Student&rsquo;s t</p>
</li></ol>
</li><li>
<p>F-Distribution</p>
</li><li>
<p>Functions</p>
<ol>
<li>
<p>Student&rsquo;s A</p>
</li><li>
<p>Binomial Coefficient</p>
</li><li>
<p>Factorial</p>
</li><li>
<p>Gamma</p>
</li><li>
<p>Incomplete Beta</p>
<ol>
<li>
<p>Continued Fraction 0</p>
</li><li>
<p>Continued Fraction 1</p>
</li><li>
<p>Continued Fraction 2</p>
</li><li>
<p>Hypergeometric Series</p>
</li><li>
<p>Integration</p>
</li></ol>
</li><li>
<p>Incomplete Gamma</p>
<ol>
<li>
<p>Continued Fraction</p>
</li><li>
<p>Integration</p>
</li></ol>
</li><li>
<p>Log Gamma</p>
</li></ol>
</li><li>
<p>Integration</p>
<ol>
<li>
<p>Generate Gaussian-Legendre Abscissas and Weights</p>
</li><li>
<p>Gaussian-Legendre Integration over [-1, 1]</p>
</li><li>
<p>Gaussian-Legendre Integration over [a, b]</p>
</li></ol>
</li><li>
<p>Orthogonal Polynomials</p>
<ol>
<li>
<p>Polynomials and Their Derivatives</p>
<ol>
<li>
<p>Chebyshev</p>
</li><li>
<p>Gegenbauer</p>
</li><li>
<p>Jacobi</p>
</li><li>
<p>Laguerre</p>
</li><li>
<p>Generalized Laguerre</p>
</li><li>
<p>Legendre</p>
</li></ol>
</li></ol>
</li><li>
<p>Probability Functions</p>
<ol>
<li>
<p>Chi-Square</p>
</li><li>
<p>Normal</p>
</li></ol>
</li><li>
<p>Sample Statistics</p>
<ol>
<li>
<p>Correlation</p>
</li><li>
<p>Covariance</p>
</li><li>
<p>F-Statistic</p>
</li><li>
<p>Kurtosis Sample</p>
</li><li>
<p>Kurtosis Population</p>
</li><li>
<p>Mean</p>
</li><li>
<p>Median</p>
</li><li>
<p>Max</p>
</li><li>
<p>Min</p>
</li><li>
<p>Moment</p>
</li><li>
<p>Skewness</p>
</li><li>
<p>Standard Deviation</p>
</li><li>
<p>Student&rsquo;s t-Statistic</p>
</li><li>
<p>Variance</p>
</li><li>
<p>Welch&rsquo;s t-Statistic</p>
</li></ol>
</li><li>
<p>XY Scatter</p>
<ol>
<li>
<p>Draw Lines</p>
</li><li>
<p>Plot Points</p>
</li></ol>
</li><li>
<p>Zeros of Orthogonal Polynomials</p>
</li></ol>
<p><span style="font-family:calibri; font-size:small">The following table displays the number of lines of C# code for each of the preceding ten classes:</span></p>
<table border="1" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">Class</span></p>
</td>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">Lines of C# Code</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">Analysis</span></p>
</td>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">71</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">Distributions</span></p>
</td>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">85</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">FDistribution</span></p>
</td>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">208</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">Functions</span></p>
</td>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">751</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">Integration</span></p>
</td>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">88</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">OrthogonalPolynomials</span></p>
</td>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">170</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">ProbabilityFunctions</span></p>
</td>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">54</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">SampleStatistics</span></p>
</td>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">241</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">XYScatter</span></p>
</td>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">358</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">Zeros</span></p>
</td>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">285</span></p>
</td>
</tr>
<tr>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">Total Lines of C# Code</span></p>
</td>
<td valign="top">
<p><span style="font-family:calibri; font-size:small">2311</span></p>
</td>
</tr>
</tbody>
</table>
<p><strong>&nbsp;</strong><em>&nbsp;</em></p>
<p><span style="font-family:calibri; font-size:small">The analysis class is pretty straight-forward and allows for analysis of a single or paired arrays of numbers. The following two screen-shots show the Analysis class in action:</span></p>
<p><strong></strong><em></em></p>
<p><em><img id="145264" width="586" height="593" src="145264-analysis%20graph.png" alt=""><img id="145265" width="586" height="593" src="145265-analysis.png" alt="">&nbsp;&nbsp;</em></p>
<p>&nbsp;</p>
<div class="scriptcode">
<div class="pluginEditHolder" pluginCommand="mceScriptCode">
<div class="title"><span>C#</span></div>
<div class="pluginLinkHolder"><span class="pluginEditHolderLink">Edit</span>|<span class="pluginRemoveHolderLink">Remove</span></div>
<span class="hidden">csharp</span>
<pre class="hidden">using System;

namespace StatisticsLibrary
{
    public class Functions
    {
        private double icbA, icbB, icgA;
        private double[] xi, wi;
        private int ni;
        private Integration integ;

        public Functions(int ni)
        {
            this.ni = ni;
            xi = new double[ni];
            wi = new double[ni];
            integ = new Integration();
            integ.GenerateGaussianLegendreAbscissasAndWeights(ni, xi, wi);
        }

        public double A(double t, int nu)
        {
            // Equations 26.7.3 and 26.7.4 page 948
            // Handbook of Mathematical Functions
            // Edited by Milton Abramowitz and Irene A. Stegun

            double sum = 0, theta = Math.Atan(t / Math.Sqrt(nu));
            double cos = Math.Cos(theta), sin = Math.Sin(theta);
            double cos2 = cos * cos;

            if (nu == 1)
                return 2.0 * theta / Math.PI;

            if (nu % 2 == 1)
            {
                double pcos = cos;

                for (int i = 1; i &lt;= nu - 2; i &#43;= 2)
                {
                    double denom = 1, numer = 1;

                    for (int j = 1; j &lt;= (i - 1) / 2; j&#43;&#43;)
                        numer *= 2 * j;

                    for (int j = 1; j &lt;= (i - 1) / 2; j&#43;&#43;)
                        denom *= 2 * j &#43; 1;

                    sum &#43;= numer * pcos / denom;
                    pcos *= cos2;
                }

                sum = 2.0 * (theta &#43; sin * sum) / Math.PI;
            }

            else
            {
                double pcos = cos2;

                for (int i = 2; i &lt;= nu - 2; i &#43;= 2)
                {
                    double denom = 1, numer = 1;

                    for (int j = 1; j &lt;= i / 2; j&#43;&#43;)
                        denom *= 2 * j;

                    for (int j = 1; j &lt;= i / 2; j&#43;&#43;)
                        numer *= 2 * j - 1;

                    sum &#43;= numer * pcos / denom;
                    pcos *= cos2;
                }

                sum = sin * (1.0 &#43; sum);
            }

            return sum;
        }

        public double DADt(double t, int nu)
        {
            // Found by differentiation of
            // Equations 26.7.3 and 26.7.4 page 948
            // Handbook of Mathematical Functions
            // Edited by Milton Abramowitz and Irene A. Stegun

            double sum1 = 0, sum2 = 0, theta = Math.Atan(t / Math.Sqrt(nu));
            double cos = Math.Cos(theta), sin = Math.Sin(theta);
            double cos2 = cos * cos;
            double thetap = 1.0 / ((1.0 &#43; t * t / nu) * Math.Sqrt(nu));

            if (nu == 1)
                return 2.0 * thetap / Math.PI;

            if (nu % 2 == 1)
            {
                double pcos = cos;

                for (int i = 1; i &lt;= nu - 2; i &#43;= 2)
                {
                    double denom = 1, numer = 1;

                    for (int j = 1; j &lt;= (i - 1) / 2; j&#43;&#43;)
                        numer *= 2 * j;

                    for (int j = 1; j &lt;= (i - 1) / 2; j&#43;&#43;)
                        denom *= 2 * j &#43; 1;

                    sum1 &#43;= numer * pcos / denom;
                    pcos *= cos2;
                }

                sum1 = 2.0 * thetap * (1.0 &#43; cos * sum1) / Math.PI;

                pcos = 1.0;

                for (int i = 1; i &lt;= nu - 2; i &#43;= 2)
                {
                    double denom = 1, numer = 1;

                    for (int j = 1; j &lt;= (i - 1) / 2; j&#43;&#43;)
                        numer *= 2 * j;

                    for (int j = 1; j &lt;= (i - 1) / 2; j&#43;&#43;)
                        denom *= 2 * j &#43; 1;

                    sum2 &#43;= i * numer * pcos / denom;
                    pcos *= cos2;
                }

                sum1 &#43;= -2.0 * thetap * sin * sin * sum2 / Math.PI;
            }

            else
            {
                double pcos = cos2;

                for (int i = 2; i &lt;= nu - 2; i &#43;= 2)
                {
                    double denom = 1, numer = 1;

                    for (int j = 1; j &lt;= i / 2; j&#43;&#43;)
                        denom *= 2 * j;

                    for (int j = 1; j &lt;= i / 2; j&#43;&#43;)
                        numer *= 2 * j - 1;

                    sum1 &#43;= numer * pcos / denom;
                    pcos *= cos2;
                }

                sum1 = thetap * cos * (1.0 &#43; sum1);

                pcos = cos;

                for (int i = 2; i &lt;= nu - 2; i &#43;= 2)
                {
                    double denom = 1, numer = 1;

                    for (int j = 1; j &lt;= i / 2; j&#43;&#43;)
                        denom *= 2 * j;

                    for (int j = 1; j &lt;= i / 2; j&#43;&#43;)
                        numer *= 2 * j - 1;

                    sum2 &#43;= i * numer * pcos / denom;
                    pcos *= cos2;
                }

                sum1 &#43;= -thetap * sin * sin * sum2;
            }

            return sum1;
        }
        
        public double Beta(double p, double q)
        {
            return Gamma(p) * Gamma(q) / Gamma(p &#43; q);
        }

        public double BinomialCoefficient(int m, int n)
        {
            return Factorial(m) / (Factorial(m - n) * Factorial(n));
        }

        public double Factorial(int n)
        {
            if (n &lt;= 1)
                return 1;
            else
                return n * Factorial(n - 1);
        }

        public double DIncompleteBetaDx(double x, double a, double b)
        {
            double f = Math.Pow(x, a - 1) * Math.Pow(1 - x, b - 1);

            return f / Beta(a, b);
        }

        // the three methods below are translated from the C functions
        // found in a &quot;Numerical Library in C for Scientists and Engineers&quot;
        // Chapter 6 Special Functions by H.T. Lau, PhD
        
        public double Gamma(double x)
        {
            int inv;
            double y, s, f = 0, g, odd = 0, even = 0;

            if (x &lt; 0.5)
            {
                y = x - Math.Floor(x / 2.0) * 2;
                s = Math.PI;
                if (y &gt;= 1.0)
                {
                    s = -s;
                    y = 2.0 - y;
                }
                if (y &gt;= 0.5) y = 1.0 - y;
                inv = 1;
                x = 1.0 - x;
                f = s / Math.Sin(Math.PI * y);
            }
            else
                inv = 0;
            if (x &gt; 22.0)
                g = Math.Exp(LogGamma(x));
            else
            {
                s = 1.0;
                while (x &gt; 1.5)
                {
                    x = x - 1.0;
                    s *= x;
                }
                g = s / ReciprocalGamma(1.0 - x, ref odd, ref even);
            }
            return (inv == 1 ? f / g : g);
        }

        public double LogGamma(double x)
        {
            int i;
            double r, x2, y, f, u0, u1, u, z;
            double[] b = new double[19];

            if (x &gt; 13.0)
            {
                r = 1.0;
                while (x &lt;= 22.0)
                {
                    r /= x;
                    x &#43;= 1.0;
                }
                x2 = -1.0 / (x * x);
                r = Math.Log(r);
                return Math.Log(x) * (x - 0.5) - x &#43; r &#43; 0.918938533204672 &#43;
                        (((0.595238095238095e-3 * x2 &#43; 0.793650793650794e-3) * x2 &#43;
                        0.277777777777778e-2) * x2 &#43; 0.833333333333333e-1) / x;
            }
            else
            {
                f = 1.0;
                u0 = u1 = 0.0;
                b[1] = -0.0761141616704358; b[2] = 0.0084323249659328;
                b[3] = -0.0010794937263286; b[4] = 0.0001490074800369;
                b[5] = -0.0000215123998886; b[6] = 0.0000031979329861;
                b[7] = -0.0000004851693012; b[8] = 0.0000000747148782;
                b[9] = -0.0000000116382967; b[10] = 0.0000000018294004;
                b[11] = -0.0000000002896918; b[12] = 0.0000000000461570;
                b[13] = -0.0000000000073928; b[14] = 0.0000000000011894;
                b[15] = -0.0000000000001921; b[16] = 0.0000000000000311;
                b[17] = -0.0000000000000051; b[18] = 0.0000000000000008;
                if (x &lt; 1.0)
                {
                    f = 1.0 / x;
                    x &#43;= 1.0;
                }
                else
                    while (x &gt; 2.0)
                    {
                        x -= 1.0;
                        f *= x;
                    }
                f = Math.Log(f);
                y = x &#43; x - 3.0;
                z = y &#43; y;
                for (i = 18; i &gt;= 1; i--)
                {
                    u = u0;
                    u0 = z * u0 &#43; b[i] - u1;
                    u1 = u;
                }
                return (u0 * y &#43; 0.491415393029387 - u1) * (x - 1.0) * (x - 2.0) &#43; f;
            }
        }

        public double ReciprocalGamma(double x, ref double odd, ref double even)
        {
            int i;
            double alfa, beta, x2;
            double[] b = new double[13];

            b[1] = -0.283876542276024; b[2] = -0.076852840844786;
            b[3] = 0.001706305071096; b[4] = 0.001271927136655;
            b[5] = 0.000076309597586; b[6] = -0.000004971736704;
            b[7] = -0.000000865920800; b[8] = -0.000000033126120;
            b[9] = 0.000000001745136; b[10] = 0.000000000242310;
            b[11] = 0.000000000009161; b[12] = -0.000000000000170;
            x2 = x * x * 8.0;
            alfa = -0.000000000000001;
            beta = 0.0;
            for (i = 12; i &gt;= 2; i -= 2)
            {
                beta = -(alfa * 2.0 &#43; beta);
                alfa = -beta * x2 - alfa &#43; b[i];
            }
            even = (beta / 2.0 &#43; alfa) * x2 - alfa &#43; 0.921870293650453;
            alfa = -0.000000000000034;
            beta = 0.0;
            for (i = 11; i &gt;= 1; i -= 2)
            {
                beta = -(alfa * 2.0 &#43; beta);
                alfa = -beta * x2 - alfa &#43; b[i];
            }
            odd = (alfa &#43; beta) * 2.0;
            return (odd) * x &#43; (even);
        }

        // Gauss series

        public double HypergeometricSeries(
            double b, double a, double c, double x, double epsilon)
        {
            if (c - a - b &lt;= 0)
                return 0;

            double sum = 0, term = 0, z = 1;
            int n = 0;

            while (true)
            {
                term = Gamma(a &#43; n) * Gamma(b &#43; n) * z / Gamma(c &#43; n) / Factorial(n);

                if (Math.Abs(term) &lt; epsilon)
                    break;

                sum &#43;= term;
                z *= x;
                n&#43;&#43;;

                if (n == 75)
                    return 0;
            }

            return Gamma(c) * sum / Gamma(a) / Gamma(b);
        }

        public double HyperIncompleteBeta(double x, double a, double b, double epsilon)
        {
            return Math.Pow(x, a) * HypergeometricSeries(a, 1 - b, a &#43; 1, x, epsilon) / (a * Beta(a, b));
        }

        // the method below are translated from the C functions
        // found in a &quot;Numerical Library in C for Scientists and Engineers&quot;
        // Chapter 6 Special Functions by H.T. Lau, PhD

        public double IncompleteBeta(double x, double p, double q, double eps)
        {
            int m, n, neven = 0, recur = 0;
            double g, f, fn, fn1, fn2, gn, gn1, gn2, dn, pq;

            if (x == 0.0 || x == 1.0)
                return x;
            else
            {
                if (x &gt; 0.5)
                {
                    f = p;
                    p = q;
                    q = f;
                    x = 1.0 - x;
                    recur = 1;
                }
                else
                    recur = 0;
                g = fn2 = 0.0;
                m = 0;
                pq = p &#43; q;
                f = fn1 = gn1 = gn2 = 1.0;
                neven = 0;
                n = 1;
                do
                {
                    if (neven == 1)
                    {
                        m&#43;&#43;;
                        dn = m * x * (q - m) / (p &#43; n - 1.0) / (p &#43; n);
                    }
                    else
                        dn = -x * (p &#43; m) * (pq &#43; m) / (p &#43; n - 1.0) / (p &#43; n);
                    g = f;
                    fn = fn1 &#43; dn * fn2;
                    gn = gn1 &#43; dn * gn2;
                    f = fn / gn;
                    fn2 = fn1;
                    fn1 = fn;
                    gn2 = gn1;
                    gn1 = gn;
                    n&#43;&#43;;
                    neven = n % 2 == 0 ? 1 : 0;
                } while (Math.Abs((f - g) / f) &gt; eps);
                f = f * Math.Pow(x, p) * Math.Pow(1.0 - x, q) * Gamma(p &#43; q) / Gamma(p &#43; 1.0) / Gamma(q);
                if (recur == 1) f = 1.0 - f;
                return f;
            }
        }

        private double d2m1(double x, double a, double b, int m)
        {
            return -(a &#43; m) * (a &#43; b &#43; m) * x / ((a &#43; 2 * m) * (a &#43; 2 * m &#43; 1));
        }

        private double d2m(double x, double a, double b, int m)
        {
            return m * (b - m) * x / ((a &#43; 2 * m - 1) * (a &#43; 2 * m));
        }

        public double IncompleteBetaFunctionCF1(double x, double a, double b, double epsilon)
        {
            // p. 944 &quot;Handbook of Mathematical Functions&quot;
            // Edited by Milton Abrmowitz and Irene A. Stegun
            // Also see p. 19

            if (x == 0 || x == 1)
                return x;

            if (Math.Abs(x) &gt; 1)
                return 0;

            bool recur;

            if (x &gt; 0.5)
            {
                double t = a;

                a = b;
                b = t;
                x = 1 - x;
                recur = true;
            }

            else
                recur = false;

            double A0 = 0, B0 = 1;
            double A1 = 1, B1 = 1, A2 = 0, B2 = 0;
            double A3 = 0, B3 = 0, A4 = 0, B4 = 0;
            double d1 = 0, d2 = 0, d3 = 0;
            double f3 = 0, f4 = 0;
            int m = 0;

            d1 = d2m1(x, a, b, m);
            A2 = A1 &#43; d1 * A0;
            B2 = B1 &#43; d1 * B0;
            m&#43;&#43;;

            while (true)
            {
                d2 = d2m(x, a, b, m);
                A3 = A2 &#43; d2 * A1;
                B3 = B2 &#43; d2 * B1;
                f3 = A3 / B3;
                d3 = d2m1(x, a, b, m);
                A4 = A3 &#43; d3 * A2;
                B4 = B3 &#43; d3 * B2;
                f4 = A4 / B4;

                if (Math.Abs((f4 - f3) / f4) &lt; epsilon)
                    break;

                A1 = A3;
                B1 = B3;
                A2 = A4;
                B2 = B4;
                m&#43;&#43;;

                if (m == 100)
                    return double.NaN;
            }

            f4 *= Math.Pow(x, a) * Math.Pow(1 - x, b) / a / Beta(a, b);

            if (recur)
                f4 = 1 - f4;

            return f4;
        }

        private double e2m(double x2, double a, double b, int m)
        {
            return -(a &#43; m &#43; 1) * (b - m) * x2 / ((a &#43; 2 * m - 2) * (a &#43; 2 * m - 1));
        }

        private double e2m1(double x2, double a, double b, int m)
        {
            return m * (a &#43; b - 1 &#43; m) * x2 / ((a &#43; 2 * m - 1) * (a &#43; 2 * m));
        }

        public double IncompleteBetaFunctionCF2(double x, double a, double b, double epsilon)
        {
            // p. 944 &quot;Handbook of Mathematical Functions&quot;
            // Edited by Milton Abrmowitz and Irene A. Stegun
            // Also see p. 19

            if (x == 0 || x == 1)
                return x;

            if (Math.Abs(x) &gt; 1)
                return 0;

            bool recur;

            if (x &gt; 0.5)
            {
                double t = a;

                a = b;
                b = t;
                x = 1 - x;
                recur = true;
            }

            else
                recur = false;

            if (x &gt;= (a - 1) / (a &#43; b - 2))
                return double.NaN;

            double x1 = 1 - x;
            double x2 = x / x1;
            double Am = 1, Bm = 0, A0 = 0, B0 = 1;
            double A1 = 0, B1 = 0, A2 = 0, B2 = 0;
            double A3 = 0, B3 = 0;
            double e1 = 1, e2 = 0, e3 = 0;
            double f2 = 0, f3 = 0;
            int m = 1;

            A1 = A0 &#43; e1 * Am;
            B1 = B0 &#43; e1 * Bm;

            while (true)
            {
                e2 = e2m(x2, a, b, m);
                A2 = A1 &#43; e2 * A0;
                B2 = B1 &#43; e2 * B0;
                f2 = A2 / B2;
                e3 = e2m1(x2, a, b, m);
                A3 = A2 &#43; e3 * A1;
                B3 = B2 &#43; e3 * B1;
                f3 = A3 / B3;
                m&#43;&#43;;

                if (Math.Abs((f3 - f2) / f3) &lt; epsilon)
                    break;

                A0 = A2;
                B0 = B2;
                A1 = A3;
                B1 = B3;

                if (m &gt;= 100)
                    return double.NaN;
            }

            f3 *= Math.Pow(x, a) * Math.Pow(x1, b - 1) / a / Beta(a, b);

            if (recur)
                f3 = 1 - f3;

            return f3;
        }

        private double icbft(double t)
        {
            return Math.Pow(t, icbA - 1) * Math.Pow(1 - t, icbB - 1);
        }

        public double IncompleteBetaFunctionIntegration(
            double x, double a, double b, double epsilon)
        {
            if (x == 0 || x == 1)
                return x;

            bool recur;

            if (x &gt; 0.5)
            {
                double t = a;

                a = b;
                b = t;
                x = 1 - x;
                recur = true;
            }

            else
                recur = false;

            icbA = a;
            icbB = b;

            double ibf = integ.GLIntegrateAB(ni, 0, x, xi, wi, icbft) / Beta(icbA, icbB);

            if (double.IsInfinity(ibf))
                ibf = 0;

            if (recur)
                ibf = 1 - ibf;

            return ibf;
        }

        private double icgft(double t)
        {
            return Math.Exp(-t) * Math.Pow(t, icgA - 1);
        }

        public double IncompleteGammaIntegration(double a, double x, double infinity)
        {
            icgA = a;
            return integ.GLIntegrateAB(ni, x, infinity, xi, wi, icgft);
        }

        public double IncompleteGammaCF(double a, double x, double epsilon)
        {
            // p. 263 &quot;Handbook of Mathematical Functions&quot;
            // Edited by Milton Abrmowitz and Irene A. Stegun
            // Also see p. 19

            double A0 = 0, B0 = 1;
            double A1 = 1, B1 = x, A2 = 0, B2 = 0;
            double A3 = 0, B3 = 0, fk2 = 0, fk3 = 0;
            int k = 1;

            while (true)
            {
                A2 = A1 &#43; (k - a) * A0;
                B2 = B1 &#43; (k - a) * B0;
                fk2 = A2 / B2;
                A3 = x * A2 &#43; k * A1;
                B3 = x * B2 &#43; k * B1;
                fk3 = A3 / B3;

                if (Math.Abs((fk2 - fk3) / fk2) &lt; epsilon)
                    break;

                A0 = A2;
                B0 = B2;
                A1 = A3;
                B1 = B3;
                k&#43;&#43;;

                if (k == 100)
                    return double.NaN;
            }

            return Math.Exp(-x) * Math.Pow(x, a) * fk2;
        }

        // the two methods below are translated from the C functions
        // found in a &quot;Numerical Library in C for Scientists and Engineers&quot;
        // Chapter 6 Special Functions by H.T. Lau, PhD

        public void ErrorFunction(double x, out double erf, out double erfc)
        {
            if (x &gt; 26.0)
            {
                erf = 1.0;
                erfc = 0.0;
                return;
            }
            else if (x &lt; -5.5)
            {
                erf = -1.0;
                erfc = 2.0;
                return;
            }
            else
            {
                double absx, c, p, q;
                absx = Math.Abs(x);
                if (absx &lt;= 0.5)
                {
                    c = x * x;
                    p = ((-0.356098437018154e-1 * c &#43; 0.699638348861914e1) * c &#43;
                            0.219792616182942e2) * c &#43; 0.242667955230532e3;
                    q = ((c &#43; 0.150827976304078e2) * c &#43; 0.911649054045149e2) * c &#43;
                            0.215058875869861e3;
                    erf = x * p / q;
                    erfc = 1.0 - (erf);
                }
                else
                {
                    erfc = Math.Exp(-x * x) * NonExperFc(absx);
                    erf = 1.0 - (erfc);
                    if (x &lt; 0.0)
                    {
                        erf = -(erf);
                        erfc = 2.0 - (erfc);
                    }
                }
            }
        }

        private double NonExperFc(double x)
        { 
            double absx, erf, erfc, c, p, q;

            absx = Math.Abs(x);
            if (absx &lt;= 0.5)
            {
                ErrorFunction(x,  out erf, out erfc);
                return Math.Exp(x * x) * erfc;
            }
            else if (absx &lt; 4.0)
            {
                c = absx;
                p = ((((((-0.136864857382717e-6 * c &#43; 0.564195517478974e0) * c &#43;
                        0.721175825088309e1) * c &#43; 0.431622272220567e2) * c &#43;
                        0.152989285046940e3) * c &#43; 0.339320816734344e3) * c &#43;
                        0.451918953711873e3) * c &#43; 0.300459261020162e3;
                q = ((((((c &#43; 0.127827273196294e2) * c &#43; 0.770001529352295e2) * c &#43;
                        0.277585444743988e3) * c &#43; 0.638980264465631e3) * c &#43;
                        0.931354094850610e3) * c &#43; 0.790950925327898e3) * c &#43;
                        0.300459260956983e3;
                return ((x &gt; 0.0) ? p / q : Math.Exp(x * x) * 2.0 - p / q);
            }
            else
            {
                c = 1.0 / x / x;
                p = (((0.223192459734185e-1 * c &#43; 0.278661308609648e0) * c &#43;
                        0.226956593539687e0) * c &#43; 0.494730910623251e-1) * c &#43;
                        0.299610707703542e-2;
                q = (((c &#43; 0.198733201817135e1) * c &#43; 0.105167510706793e1) * c &#43;
                        0.191308926107830e0) * c &#43; 0.106209230528468e-1;
                c = (c * (-p) / q &#43; 0.564189583547756) / absx;
                return ((x &gt; 0.0) ? c : Math.Exp(x * x) * 2.0 - c);
            }
        }
    }
}</pre>
<div class="preview">
<pre class="csharp"><span class="cs__keyword">using</span>&nbsp;System;&nbsp;
&nbsp;
<span class="cs__keyword">namespace</span>&nbsp;StatisticsLibrary&nbsp;
{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">class</span>&nbsp;Functions&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">private</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;icbA,&nbsp;icbB,&nbsp;icgA;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">private</span>&nbsp;<span class="cs__keyword">double</span>[]&nbsp;xi,&nbsp;wi;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">private</span>&nbsp;<span class="cs__keyword">int</span>&nbsp;ni;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">private</span>&nbsp;Integration&nbsp;integ;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;Functions(<span class="cs__keyword">int</span>&nbsp;ni)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">this</span>.ni&nbsp;=&nbsp;ni;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;xi&nbsp;=&nbsp;<span class="cs__keyword">new</span>&nbsp;<span class="cs__keyword">double</span>[ni];&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;wi&nbsp;=&nbsp;<span class="cs__keyword">new</span>&nbsp;<span class="cs__keyword">double</span>[ni];&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;integ&nbsp;=&nbsp;<span class="cs__keyword">new</span>&nbsp;Integration();&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;integ.GenerateGaussianLegendreAbscissasAndWeights(ni,&nbsp;xi,&nbsp;wi);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;A(<span class="cs__keyword">double</span>&nbsp;t,&nbsp;<span class="cs__keyword">int</span>&nbsp;nu)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Equations&nbsp;26.7.3&nbsp;and&nbsp;26.7.4&nbsp;page&nbsp;948</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Handbook&nbsp;of&nbsp;Mathematical&nbsp;Functions</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Edited&nbsp;by&nbsp;Milton&nbsp;Abramowitz&nbsp;and&nbsp;Irene&nbsp;A.&nbsp;Stegun</span>&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;sum&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;theta&nbsp;=&nbsp;Math.Atan(t&nbsp;/&nbsp;Math.Sqrt(nu));&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;cos&nbsp;=&nbsp;Math.Cos(theta),&nbsp;sin&nbsp;=&nbsp;Math.Sin(theta);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;cos2&nbsp;=&nbsp;cos&nbsp;*&nbsp;cos;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(nu&nbsp;==&nbsp;<span class="cs__number">1</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;<span class="cs__number">2.0</span>&nbsp;*&nbsp;theta&nbsp;/&nbsp;Math.PI;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(nu&nbsp;%&nbsp;<span class="cs__number">2</span>&nbsp;==&nbsp;<span class="cs__number">1</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;pcos&nbsp;=&nbsp;cos;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;i&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;i&nbsp;&lt;=&nbsp;nu&nbsp;-&nbsp;<span class="cs__number">2</span>;&nbsp;i&nbsp;&#43;=&nbsp;<span class="cs__number">2</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;denom&nbsp;=&nbsp;<span class="cs__number">1</span>,&nbsp;numer&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;j&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;j&nbsp;&lt;=&nbsp;(i&nbsp;-&nbsp;<span class="cs__number">1</span>)&nbsp;/&nbsp;<span class="cs__number">2</span>;&nbsp;j&#43;&#43;)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;numer&nbsp;*=&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;j;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;j&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;j&nbsp;&lt;=&nbsp;(i&nbsp;-&nbsp;<span class="cs__number">1</span>)&nbsp;/&nbsp;<span class="cs__number">2</span>;&nbsp;j&#43;&#43;)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;denom&nbsp;*=&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;j&nbsp;&#43;&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum&nbsp;&#43;=&nbsp;numer&nbsp;*&nbsp;pcos&nbsp;/&nbsp;denom;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pcos&nbsp;*=&nbsp;cos2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum&nbsp;=&nbsp;<span class="cs__number">2.0</span>&nbsp;*&nbsp;(theta&nbsp;&#43;&nbsp;sin&nbsp;*&nbsp;sum)&nbsp;/&nbsp;Math.PI;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;pcos&nbsp;=&nbsp;cos2;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;i&nbsp;=&nbsp;<span class="cs__number">2</span>;&nbsp;i&nbsp;&lt;=&nbsp;nu&nbsp;-&nbsp;<span class="cs__number">2</span>;&nbsp;i&nbsp;&#43;=&nbsp;<span class="cs__number">2</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;denom&nbsp;=&nbsp;<span class="cs__number">1</span>,&nbsp;numer&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;j&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;j&nbsp;&lt;=&nbsp;i&nbsp;/&nbsp;<span class="cs__number">2</span>;&nbsp;j&#43;&#43;)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;denom&nbsp;*=&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;j;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;j&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;j&nbsp;&lt;=&nbsp;i&nbsp;/&nbsp;<span class="cs__number">2</span>;&nbsp;j&#43;&#43;)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;numer&nbsp;*=&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;j&nbsp;-&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum&nbsp;&#43;=&nbsp;numer&nbsp;*&nbsp;pcos&nbsp;/&nbsp;denom;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pcos&nbsp;*=&nbsp;cos2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum&nbsp;=&nbsp;sin&nbsp;*&nbsp;(<span class="cs__number">1.0</span>&nbsp;&#43;&nbsp;sum);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;sum;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;DADt(<span class="cs__keyword">double</span>&nbsp;t,&nbsp;<span class="cs__keyword">int</span>&nbsp;nu)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Found&nbsp;by&nbsp;differentiation&nbsp;of</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Equations&nbsp;26.7.3&nbsp;and&nbsp;26.7.4&nbsp;page&nbsp;948</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Handbook&nbsp;of&nbsp;Mathematical&nbsp;Functions</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Edited&nbsp;by&nbsp;Milton&nbsp;Abramowitz&nbsp;and&nbsp;Irene&nbsp;A.&nbsp;Stegun</span>&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;sum1&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;sum2&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;theta&nbsp;=&nbsp;Math.Atan(t&nbsp;/&nbsp;Math.Sqrt(nu));&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;cos&nbsp;=&nbsp;Math.Cos(theta),&nbsp;sin&nbsp;=&nbsp;Math.Sin(theta);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;cos2&nbsp;=&nbsp;cos&nbsp;*&nbsp;cos;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;thetap&nbsp;=&nbsp;<span class="cs__number">1.0</span>&nbsp;/&nbsp;((<span class="cs__number">1.0</span>&nbsp;&#43;&nbsp;t&nbsp;*&nbsp;t&nbsp;/&nbsp;nu)&nbsp;*&nbsp;Math.Sqrt(nu));&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(nu&nbsp;==&nbsp;<span class="cs__number">1</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;<span class="cs__number">2.0</span>&nbsp;*&nbsp;thetap&nbsp;/&nbsp;Math.PI;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(nu&nbsp;%&nbsp;<span class="cs__number">2</span>&nbsp;==&nbsp;<span class="cs__number">1</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;pcos&nbsp;=&nbsp;cos;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;i&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;i&nbsp;&lt;=&nbsp;nu&nbsp;-&nbsp;<span class="cs__number">2</span>;&nbsp;i&nbsp;&#43;=&nbsp;<span class="cs__number">2</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;denom&nbsp;=&nbsp;<span class="cs__number">1</span>,&nbsp;numer&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;j&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;j&nbsp;&lt;=&nbsp;(i&nbsp;-&nbsp;<span class="cs__number">1</span>)&nbsp;/&nbsp;<span class="cs__number">2</span>;&nbsp;j&#43;&#43;)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;numer&nbsp;*=&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;j;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;j&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;j&nbsp;&lt;=&nbsp;(i&nbsp;-&nbsp;<span class="cs__number">1</span>)&nbsp;/&nbsp;<span class="cs__number">2</span>;&nbsp;j&#43;&#43;)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;denom&nbsp;*=&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;j&nbsp;&#43;&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum1&nbsp;&#43;=&nbsp;numer&nbsp;*&nbsp;pcos&nbsp;/&nbsp;denom;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pcos&nbsp;*=&nbsp;cos2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum1&nbsp;=&nbsp;<span class="cs__number">2.0</span>&nbsp;*&nbsp;thetap&nbsp;*&nbsp;(<span class="cs__number">1.0</span>&nbsp;&#43;&nbsp;cos&nbsp;*&nbsp;sum1)&nbsp;/&nbsp;Math.PI;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pcos&nbsp;=&nbsp;<span class="cs__number">1.0</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;i&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;i&nbsp;&lt;=&nbsp;nu&nbsp;-&nbsp;<span class="cs__number">2</span>;&nbsp;i&nbsp;&#43;=&nbsp;<span class="cs__number">2</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;denom&nbsp;=&nbsp;<span class="cs__number">1</span>,&nbsp;numer&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;j&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;j&nbsp;&lt;=&nbsp;(i&nbsp;-&nbsp;<span class="cs__number">1</span>)&nbsp;/&nbsp;<span class="cs__number">2</span>;&nbsp;j&#43;&#43;)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;numer&nbsp;*=&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;j;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;j&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;j&nbsp;&lt;=&nbsp;(i&nbsp;-&nbsp;<span class="cs__number">1</span>)&nbsp;/&nbsp;<span class="cs__number">2</span>;&nbsp;j&#43;&#43;)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;denom&nbsp;*=&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;j&nbsp;&#43;&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum2&nbsp;&#43;=&nbsp;i&nbsp;*&nbsp;numer&nbsp;*&nbsp;pcos&nbsp;/&nbsp;denom;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pcos&nbsp;*=&nbsp;cos2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum1&nbsp;&#43;=&nbsp;-<span class="cs__number">2.0</span>&nbsp;*&nbsp;thetap&nbsp;*&nbsp;sin&nbsp;*&nbsp;sin&nbsp;*&nbsp;sum2&nbsp;/&nbsp;Math.PI;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;pcos&nbsp;=&nbsp;cos2;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;i&nbsp;=&nbsp;<span class="cs__number">2</span>;&nbsp;i&nbsp;&lt;=&nbsp;nu&nbsp;-&nbsp;<span class="cs__number">2</span>;&nbsp;i&nbsp;&#43;=&nbsp;<span class="cs__number">2</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;denom&nbsp;=&nbsp;<span class="cs__number">1</span>,&nbsp;numer&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;j&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;j&nbsp;&lt;=&nbsp;i&nbsp;/&nbsp;<span class="cs__number">2</span>;&nbsp;j&#43;&#43;)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;denom&nbsp;*=&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;j;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;j&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;j&nbsp;&lt;=&nbsp;i&nbsp;/&nbsp;<span class="cs__number">2</span>;&nbsp;j&#43;&#43;)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;numer&nbsp;*=&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;j&nbsp;-&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum1&nbsp;&#43;=&nbsp;numer&nbsp;*&nbsp;pcos&nbsp;/&nbsp;denom;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pcos&nbsp;*=&nbsp;cos2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum1&nbsp;=&nbsp;thetap&nbsp;*&nbsp;cos&nbsp;*&nbsp;(<span class="cs__number">1.0</span>&nbsp;&#43;&nbsp;sum1);&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pcos&nbsp;=&nbsp;cos;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;i&nbsp;=&nbsp;<span class="cs__number">2</span>;&nbsp;i&nbsp;&lt;=&nbsp;nu&nbsp;-&nbsp;<span class="cs__number">2</span>;&nbsp;i&nbsp;&#43;=&nbsp;<span class="cs__number">2</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;denom&nbsp;=&nbsp;<span class="cs__number">1</span>,&nbsp;numer&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;j&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;j&nbsp;&lt;=&nbsp;i&nbsp;/&nbsp;<span class="cs__number">2</span>;&nbsp;j&#43;&#43;)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;denom&nbsp;*=&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;j;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(<span class="cs__keyword">int</span>&nbsp;j&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;j&nbsp;&lt;=&nbsp;i&nbsp;/&nbsp;<span class="cs__number">2</span>;&nbsp;j&#43;&#43;)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;numer&nbsp;*=&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;j&nbsp;-&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum2&nbsp;&#43;=&nbsp;i&nbsp;*&nbsp;numer&nbsp;*&nbsp;pcos&nbsp;/&nbsp;denom;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pcos&nbsp;*=&nbsp;cos2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum1&nbsp;&#43;=&nbsp;-thetap&nbsp;*&nbsp;sin&nbsp;*&nbsp;sin&nbsp;*&nbsp;sum2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;sum1;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;Beta(<span class="cs__keyword">double</span>&nbsp;p,&nbsp;<span class="cs__keyword">double</span>&nbsp;q)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;Gamma(p)&nbsp;*&nbsp;Gamma(q)&nbsp;/&nbsp;Gamma(p&nbsp;&#43;&nbsp;q);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;BinomialCoefficient(<span class="cs__keyword">int</span>&nbsp;m,&nbsp;<span class="cs__keyword">int</span>&nbsp;n)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;Factorial(m)&nbsp;/&nbsp;(Factorial(m&nbsp;-&nbsp;n)&nbsp;*&nbsp;Factorial(n));&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;Factorial(<span class="cs__keyword">int</span>&nbsp;n)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(n&nbsp;&lt;=&nbsp;<span class="cs__number">1</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;n&nbsp;*&nbsp;Factorial(n&nbsp;-&nbsp;<span class="cs__number">1</span>);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;DIncompleteBetaDx(<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">double</span>&nbsp;a,&nbsp;<span class="cs__keyword">double</span>&nbsp;b)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;f&nbsp;=&nbsp;Math.Pow(x,&nbsp;a&nbsp;-&nbsp;<span class="cs__number">1</span>)&nbsp;*&nbsp;Math.Pow(<span class="cs__number">1</span>&nbsp;-&nbsp;x,&nbsp;b&nbsp;-&nbsp;<span class="cs__number">1</span>);&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;f&nbsp;/&nbsp;Beta(a,&nbsp;b);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;the&nbsp;three&nbsp;methods&nbsp;below&nbsp;are&nbsp;translated&nbsp;from&nbsp;the&nbsp;C&nbsp;functions</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;found&nbsp;in&nbsp;a&nbsp;&quot;Numerical&nbsp;Library&nbsp;in&nbsp;C&nbsp;for&nbsp;Scientists&nbsp;and&nbsp;Engineers&quot;</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Chapter&nbsp;6&nbsp;Special&nbsp;Functions&nbsp;by&nbsp;H.T.&nbsp;Lau,&nbsp;PhD</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;Gamma(<span class="cs__keyword">double</span>&nbsp;x)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">int</span>&nbsp;inv;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;y,&nbsp;s,&nbsp;f&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;g,&nbsp;odd&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;even&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;&lt;&nbsp;<span class="cs__number">0.5</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;y&nbsp;=&nbsp;x&nbsp;-&nbsp;Math.Floor(x&nbsp;/&nbsp;<span class="cs__number">2.0</span>)&nbsp;*&nbsp;<span class="cs__number">2</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;s&nbsp;=&nbsp;Math.PI;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(y&nbsp;&gt;=&nbsp;<span class="cs__number">1.0</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;s&nbsp;=&nbsp;-s;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;y&nbsp;=&nbsp;<span class="cs__number">2.0</span>&nbsp;-&nbsp;y;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(y&nbsp;&gt;=&nbsp;<span class="cs__number">0.5</span>)&nbsp;y&nbsp;=&nbsp;<span class="cs__number">1.0</span>&nbsp;-&nbsp;y;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;inv&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;x&nbsp;=&nbsp;<span class="cs__number">1.0</span>&nbsp;-&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f&nbsp;=&nbsp;s&nbsp;/&nbsp;Math.Sin(Math.PI&nbsp;*&nbsp;y);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;inv&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;&gt;&nbsp;<span class="cs__number">22.0</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;g&nbsp;=&nbsp;Math.Exp(LogGamma(x));&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;s&nbsp;=&nbsp;<span class="cs__number">1.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">while</span>&nbsp;(x&nbsp;&gt;&nbsp;<span class="cs__number">1.5</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;x&nbsp;=&nbsp;x&nbsp;-&nbsp;<span class="cs__number">1.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;s&nbsp;*=&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;g&nbsp;=&nbsp;s&nbsp;/&nbsp;ReciprocalGamma(<span class="cs__number">1.0</span>&nbsp;-&nbsp;x,&nbsp;<span class="cs__keyword">ref</span>&nbsp;odd,&nbsp;<span class="cs__keyword">ref</span>&nbsp;even);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;(inv&nbsp;==&nbsp;<span class="cs__number">1</span>&nbsp;?&nbsp;f&nbsp;/&nbsp;g&nbsp;:&nbsp;g);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;LogGamma(<span class="cs__keyword">double</span>&nbsp;x)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">int</span>&nbsp;i;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;r,&nbsp;x2,&nbsp;y,&nbsp;f,&nbsp;u0,&nbsp;u1,&nbsp;u,&nbsp;z;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>[]&nbsp;b&nbsp;=&nbsp;<span class="cs__keyword">new</span>&nbsp;<span class="cs__keyword">double</span>[<span class="cs__number">19</span>];&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;&gt;&nbsp;<span class="cs__number">13.0</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;r&nbsp;=&nbsp;<span class="cs__number">1.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">while</span>&nbsp;(x&nbsp;&lt;=&nbsp;<span class="cs__number">22.0</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;r&nbsp;/=&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;x&nbsp;&#43;=&nbsp;<span class="cs__number">1.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;x2&nbsp;=&nbsp;-<span class="cs__number">1.0</span>&nbsp;/&nbsp;(x&nbsp;*&nbsp;x);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;r&nbsp;=&nbsp;Math.Log(r);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;Math.Log(x)&nbsp;*&nbsp;(x&nbsp;-&nbsp;<span class="cs__number">0.5</span>)&nbsp;-&nbsp;x&nbsp;&#43;&nbsp;r&nbsp;&#43;&nbsp;<span class="cs__number">0.918938533204672</span>&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(((<span class="cs__number">0.595238095238095e-3</span>&nbsp;*&nbsp;x2&nbsp;&#43;&nbsp;<span class="cs__number">0.793650793650794e-3</span>)&nbsp;*&nbsp;x2&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__number">0.277777777777778e-2</span>)&nbsp;*&nbsp;x2&nbsp;&#43;&nbsp;<span class="cs__number">0.833333333333333e-1</span>)&nbsp;/&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f&nbsp;=&nbsp;<span class="cs__number">1.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;u0&nbsp;=&nbsp;u1&nbsp;=&nbsp;<span class="cs__number">0.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">1</span>]&nbsp;=&nbsp;-<span class="cs__number">0.0761141616704358</span>;&nbsp;b[<span class="cs__number">2</span>]&nbsp;=&nbsp;<span class="cs__number">0.0084323249659328</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">3</span>]&nbsp;=&nbsp;-<span class="cs__number">0.0010794937263286</span>;&nbsp;b[<span class="cs__number">4</span>]&nbsp;=&nbsp;<span class="cs__number">0.0001490074800369</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">5</span>]&nbsp;=&nbsp;-<span class="cs__number">0.0000215123998886</span>;&nbsp;b[<span class="cs__number">6</span>]&nbsp;=&nbsp;<span class="cs__number">0.0000031979329861</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">7</span>]&nbsp;=&nbsp;-<span class="cs__number">0.0000004851693012</span>;&nbsp;b[<span class="cs__number">8</span>]&nbsp;=&nbsp;<span class="cs__number">0.0000000747148782</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">9</span>]&nbsp;=&nbsp;-<span class="cs__number">0.0000000116382967</span>;&nbsp;b[<span class="cs__number">10</span>]&nbsp;=&nbsp;<span class="cs__number">0.0000000018294004</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">11</span>]&nbsp;=&nbsp;-<span class="cs__number">0.0000000002896918</span>;&nbsp;b[<span class="cs__number">12</span>]&nbsp;=&nbsp;<span class="cs__number">0.0000000000461570</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">13</span>]&nbsp;=&nbsp;-<span class="cs__number">0.0000000000073928</span>;&nbsp;b[<span class="cs__number">14</span>]&nbsp;=&nbsp;<span class="cs__number">0.0000000000011894</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">15</span>]&nbsp;=&nbsp;-<span class="cs__number">0.0000000000001921</span>;&nbsp;b[<span class="cs__number">16</span>]&nbsp;=&nbsp;<span class="cs__number">0.0000000000000311</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">17</span>]&nbsp;=&nbsp;-<span class="cs__number">0.0000000000000051</span>;&nbsp;b[<span class="cs__number">18</span>]&nbsp;=&nbsp;<span class="cs__number">0.0000000000000008</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;&lt;&nbsp;<span class="cs__number">1.0</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f&nbsp;=&nbsp;<span class="cs__number">1.0</span>&nbsp;/&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;x&nbsp;&#43;=&nbsp;<span class="cs__number">1.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">while</span>&nbsp;(x&nbsp;&gt;&nbsp;<span class="cs__number">2.0</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;x&nbsp;-=&nbsp;<span class="cs__number">1.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f&nbsp;*=&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f&nbsp;=&nbsp;Math.Log(f);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;y&nbsp;=&nbsp;x&nbsp;&#43;&nbsp;x&nbsp;-&nbsp;<span class="cs__number">3.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;z&nbsp;=&nbsp;y&nbsp;&#43;&nbsp;y;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(i&nbsp;=&nbsp;<span class="cs__number">18</span>;&nbsp;i&nbsp;&gt;=&nbsp;<span class="cs__number">1</span>;&nbsp;i--)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;u&nbsp;=&nbsp;u0;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;u0&nbsp;=&nbsp;z&nbsp;*&nbsp;u0&nbsp;&#43;&nbsp;b[i]&nbsp;-&nbsp;u1;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;u1&nbsp;=&nbsp;u;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;(u0&nbsp;*&nbsp;y&nbsp;&#43;&nbsp;<span class="cs__number">0.491415393029387</span>&nbsp;-&nbsp;u1)&nbsp;*&nbsp;(x&nbsp;-&nbsp;<span class="cs__number">1.0</span>)&nbsp;*&nbsp;(x&nbsp;-&nbsp;<span class="cs__number">2.0</span>)&nbsp;&#43;&nbsp;f;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;ReciprocalGamma(<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">ref</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;odd,&nbsp;<span class="cs__keyword">ref</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;even)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">int</span>&nbsp;i;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;alfa,&nbsp;beta,&nbsp;x2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>[]&nbsp;b&nbsp;=&nbsp;<span class="cs__keyword">new</span>&nbsp;<span class="cs__keyword">double</span>[<span class="cs__number">13</span>];&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">1</span>]&nbsp;=&nbsp;-<span class="cs__number">0.283876542276024</span>;&nbsp;b[<span class="cs__number">2</span>]&nbsp;=&nbsp;-<span class="cs__number">0.076852840844786</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">3</span>]&nbsp;=&nbsp;<span class="cs__number">0.001706305071096</span>;&nbsp;b[<span class="cs__number">4</span>]&nbsp;=&nbsp;<span class="cs__number">0.001271927136655</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">5</span>]&nbsp;=&nbsp;<span class="cs__number">0.000076309597586</span>;&nbsp;b[<span class="cs__number">6</span>]&nbsp;=&nbsp;-<span class="cs__number">0.000004971736704</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">7</span>]&nbsp;=&nbsp;-<span class="cs__number">0.000000865920800</span>;&nbsp;b[<span class="cs__number">8</span>]&nbsp;=&nbsp;-<span class="cs__number">0.000000033126120</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">9</span>]&nbsp;=&nbsp;<span class="cs__number">0.000000001745136</span>;&nbsp;b[<span class="cs__number">10</span>]&nbsp;=&nbsp;<span class="cs__number">0.000000000242310</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b[<span class="cs__number">11</span>]&nbsp;=&nbsp;<span class="cs__number">0.000000000009161</span>;&nbsp;b[<span class="cs__number">12</span>]&nbsp;=&nbsp;-<span class="cs__number">0.000000000000170</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;x2&nbsp;=&nbsp;x&nbsp;*&nbsp;x&nbsp;*&nbsp;<span class="cs__number">8.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;alfa&nbsp;=&nbsp;-<span class="cs__number">0.000000000000001</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;beta&nbsp;=&nbsp;<span class="cs__number">0.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(i&nbsp;=&nbsp;<span class="cs__number">12</span>;&nbsp;i&nbsp;&gt;=&nbsp;<span class="cs__number">2</span>;&nbsp;i&nbsp;-=&nbsp;<span class="cs__number">2</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;beta&nbsp;=&nbsp;-(alfa&nbsp;*&nbsp;<span class="cs__number">2.0</span>&nbsp;&#43;&nbsp;beta);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;alfa&nbsp;=&nbsp;-beta&nbsp;*&nbsp;x2&nbsp;-&nbsp;alfa&nbsp;&#43;&nbsp;b[i];&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;even&nbsp;=&nbsp;(beta&nbsp;/&nbsp;<span class="cs__number">2.0</span>&nbsp;&#43;&nbsp;alfa)&nbsp;*&nbsp;x2&nbsp;-&nbsp;alfa&nbsp;&#43;&nbsp;<span class="cs__number">0.921870293650453</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;alfa&nbsp;=&nbsp;-<span class="cs__number">0.000000000000034</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;beta&nbsp;=&nbsp;<span class="cs__number">0.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">for</span>&nbsp;(i&nbsp;=&nbsp;<span class="cs__number">11</span>;&nbsp;i&nbsp;&gt;=&nbsp;<span class="cs__number">1</span>;&nbsp;i&nbsp;-=&nbsp;<span class="cs__number">2</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;beta&nbsp;=&nbsp;-(alfa&nbsp;*&nbsp;<span class="cs__number">2.0</span>&nbsp;&#43;&nbsp;beta);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;alfa&nbsp;=&nbsp;-beta&nbsp;*&nbsp;x2&nbsp;-&nbsp;alfa&nbsp;&#43;&nbsp;b[i];&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;odd&nbsp;=&nbsp;(alfa&nbsp;&#43;&nbsp;beta)&nbsp;*&nbsp;<span class="cs__number">2.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;(odd)&nbsp;*&nbsp;x&nbsp;&#43;&nbsp;(even);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Gauss&nbsp;series</span>&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;HypergeometricSeries(&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;b,&nbsp;<span class="cs__keyword">double</span>&nbsp;a,&nbsp;<span class="cs__keyword">double</span>&nbsp;c,&nbsp;<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">double</span>&nbsp;epsilon)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(c&nbsp;-&nbsp;a&nbsp;-&nbsp;b&nbsp;&lt;=&nbsp;<span class="cs__number">0</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;sum&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;term&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;z&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">int</span>&nbsp;n&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">while</span>&nbsp;(<span class="cs__keyword">true</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;term&nbsp;=&nbsp;Gamma(a&nbsp;&#43;&nbsp;n)&nbsp;*&nbsp;Gamma(b&nbsp;&#43;&nbsp;n)&nbsp;*&nbsp;z&nbsp;/&nbsp;Gamma(c&nbsp;&#43;&nbsp;n)&nbsp;/&nbsp;Factorial(n);&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(Math.Abs(term)&nbsp;&lt;&nbsp;epsilon)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">break</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sum&nbsp;&#43;=&nbsp;term;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;z&nbsp;*=&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;n&#43;&#43;;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(n&nbsp;==&nbsp;<span class="cs__number">75</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;Gamma(c)&nbsp;*&nbsp;sum&nbsp;/&nbsp;Gamma(a)&nbsp;/&nbsp;Gamma(b);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;HyperIncompleteBeta(<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">double</span>&nbsp;a,&nbsp;<span class="cs__keyword">double</span>&nbsp;b,&nbsp;<span class="cs__keyword">double</span>&nbsp;epsilon)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;Math.Pow(x,&nbsp;a)&nbsp;*&nbsp;HypergeometricSeries(a,&nbsp;<span class="cs__number">1</span>&nbsp;-&nbsp;b,&nbsp;a&nbsp;&#43;&nbsp;<span class="cs__number">1</span>,&nbsp;x,&nbsp;epsilon)&nbsp;/&nbsp;(a&nbsp;*&nbsp;Beta(a,&nbsp;b));&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;the&nbsp;method&nbsp;below&nbsp;are&nbsp;translated&nbsp;from&nbsp;the&nbsp;C&nbsp;functions</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;found&nbsp;in&nbsp;a&nbsp;&quot;Numerical&nbsp;Library&nbsp;in&nbsp;C&nbsp;for&nbsp;Scientists&nbsp;and&nbsp;Engineers&quot;</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Chapter&nbsp;6&nbsp;Special&nbsp;Functions&nbsp;by&nbsp;H.T.&nbsp;Lau,&nbsp;PhD</span>&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;IncompleteBeta(<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">double</span>&nbsp;p,&nbsp;<span class="cs__keyword">double</span>&nbsp;q,&nbsp;<span class="cs__keyword">double</span>&nbsp;eps)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">int</span>&nbsp;m,&nbsp;n,&nbsp;neven&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;recur&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;g,&nbsp;f,&nbsp;fn,&nbsp;fn1,&nbsp;fn2,&nbsp;gn,&nbsp;gn1,&nbsp;gn2,&nbsp;dn,&nbsp;pq;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;==&nbsp;<span class="cs__number">0.0</span>&nbsp;||&nbsp;x&nbsp;==&nbsp;<span class="cs__number">1.0</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;&gt;&nbsp;<span class="cs__number">0.5</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f&nbsp;=&nbsp;p;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;p&nbsp;=&nbsp;q;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;q&nbsp;=&nbsp;f;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;x&nbsp;=&nbsp;<span class="cs__number">1.0</span>&nbsp;-&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;recur&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;recur&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;g&nbsp;=&nbsp;fn2&nbsp;=&nbsp;<span class="cs__number">0.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;m&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pq&nbsp;=&nbsp;p&nbsp;&#43;&nbsp;q;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f&nbsp;=&nbsp;fn1&nbsp;=&nbsp;gn1&nbsp;=&nbsp;gn2&nbsp;=&nbsp;<span class="cs__number">1.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;neven&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;n&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">do</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(neven&nbsp;==&nbsp;<span class="cs__number">1</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;m&#43;&#43;;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dn&nbsp;=&nbsp;m&nbsp;*&nbsp;x&nbsp;*&nbsp;(q&nbsp;-&nbsp;m)&nbsp;/&nbsp;(p&nbsp;&#43;&nbsp;n&nbsp;-&nbsp;<span class="cs__number">1.0</span>)&nbsp;/&nbsp;(p&nbsp;&#43;&nbsp;n);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dn&nbsp;=&nbsp;-x&nbsp;*&nbsp;(p&nbsp;&#43;&nbsp;m)&nbsp;*&nbsp;(pq&nbsp;&#43;&nbsp;m)&nbsp;/&nbsp;(p&nbsp;&#43;&nbsp;n&nbsp;-&nbsp;<span class="cs__number">1.0</span>)&nbsp;/&nbsp;(p&nbsp;&#43;&nbsp;n);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;g&nbsp;=&nbsp;f;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;fn&nbsp;=&nbsp;fn1&nbsp;&#43;&nbsp;dn&nbsp;*&nbsp;fn2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;gn&nbsp;=&nbsp;gn1&nbsp;&#43;&nbsp;dn&nbsp;*&nbsp;gn2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f&nbsp;=&nbsp;fn&nbsp;/&nbsp;gn;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;fn2&nbsp;=&nbsp;fn1;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;fn1&nbsp;=&nbsp;fn;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;gn2&nbsp;=&nbsp;gn1;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;gn1&nbsp;=&nbsp;gn;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;n&#43;&#43;;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;neven&nbsp;=&nbsp;n&nbsp;%&nbsp;<span class="cs__number">2</span>&nbsp;==&nbsp;<span class="cs__number">0</span>&nbsp;?&nbsp;<span class="cs__number">1</span>&nbsp;:&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;<span class="cs__keyword">while</span>&nbsp;(Math.Abs((f&nbsp;-&nbsp;g)&nbsp;/&nbsp;f)&nbsp;&gt;&nbsp;eps);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f&nbsp;=&nbsp;f&nbsp;*&nbsp;Math.Pow(x,&nbsp;p)&nbsp;*&nbsp;Math.Pow(<span class="cs__number">1.0</span>&nbsp;-&nbsp;x,&nbsp;q)&nbsp;*&nbsp;Gamma(p&nbsp;&#43;&nbsp;q)&nbsp;/&nbsp;Gamma(p&nbsp;&#43;&nbsp;<span class="cs__number">1.0</span>)&nbsp;/&nbsp;Gamma(q);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(recur&nbsp;==&nbsp;<span class="cs__number">1</span>)&nbsp;f&nbsp;=&nbsp;<span class="cs__number">1.0</span>&nbsp;-&nbsp;f;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;f;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">private</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;d2m1(<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">double</span>&nbsp;a,&nbsp;<span class="cs__keyword">double</span>&nbsp;b,&nbsp;<span class="cs__keyword">int</span>&nbsp;m)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;-(a&nbsp;&#43;&nbsp;m)&nbsp;*&nbsp;(a&nbsp;&#43;&nbsp;b&nbsp;&#43;&nbsp;m)&nbsp;*&nbsp;x&nbsp;/&nbsp;((a&nbsp;&#43;&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;m)&nbsp;*&nbsp;(a&nbsp;&#43;&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;m&nbsp;&#43;&nbsp;<span class="cs__number">1</span>));&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">private</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;d2m(<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">double</span>&nbsp;a,&nbsp;<span class="cs__keyword">double</span>&nbsp;b,&nbsp;<span class="cs__keyword">int</span>&nbsp;m)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;m&nbsp;*&nbsp;(b&nbsp;-&nbsp;m)&nbsp;*&nbsp;x&nbsp;/&nbsp;((a&nbsp;&#43;&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;m&nbsp;-&nbsp;<span class="cs__number">1</span>)&nbsp;*&nbsp;(a&nbsp;&#43;&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;m));&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;IncompleteBetaFunctionCF1(<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">double</span>&nbsp;a,&nbsp;<span class="cs__keyword">double</span>&nbsp;b,&nbsp;<span class="cs__keyword">double</span>&nbsp;epsilon)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;p.&nbsp;944&nbsp;&quot;Handbook&nbsp;of&nbsp;Mathematical&nbsp;Functions&quot;</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Edited&nbsp;by&nbsp;Milton&nbsp;Abrmowitz&nbsp;and&nbsp;Irene&nbsp;A.&nbsp;Stegun</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Also&nbsp;see&nbsp;p.&nbsp;19</span>&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;==&nbsp;<span class="cs__number">0</span>&nbsp;||&nbsp;x&nbsp;==&nbsp;<span class="cs__number">1</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;x;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(Math.Abs(x)&nbsp;&gt;&nbsp;<span class="cs__number">1</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">bool</span>&nbsp;recur;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;&gt;&nbsp;<span class="cs__number">0.5</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;t&nbsp;=&nbsp;a;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a&nbsp;=&nbsp;b;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b&nbsp;=&nbsp;t;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;x&nbsp;=&nbsp;<span class="cs__number">1</span>&nbsp;-&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;recur&nbsp;=&nbsp;<span class="cs__keyword">true</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;recur&nbsp;=&nbsp;<span class="cs__keyword">false</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;A0&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;B0&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;A1&nbsp;=&nbsp;<span class="cs__number">1</span>,&nbsp;B1&nbsp;=&nbsp;<span class="cs__number">1</span>,&nbsp;A2&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;B2&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;A3&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;B3&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;A4&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;B4&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;d1&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;d2&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;d3&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;f3&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;f4&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">int</span>&nbsp;m&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d1&nbsp;=&nbsp;d2m1(x,&nbsp;a,&nbsp;b,&nbsp;m);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A2&nbsp;=&nbsp;A1&nbsp;&#43;&nbsp;d1&nbsp;*&nbsp;A0;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B2&nbsp;=&nbsp;B1&nbsp;&#43;&nbsp;d1&nbsp;*&nbsp;B0;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;m&#43;&#43;;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">while</span>&nbsp;(<span class="cs__keyword">true</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d2&nbsp;=&nbsp;d2m(x,&nbsp;a,&nbsp;b,&nbsp;m);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A3&nbsp;=&nbsp;A2&nbsp;&#43;&nbsp;d2&nbsp;*&nbsp;A1;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B3&nbsp;=&nbsp;B2&nbsp;&#43;&nbsp;d2&nbsp;*&nbsp;B1;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f3&nbsp;=&nbsp;A3&nbsp;/&nbsp;B3;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d3&nbsp;=&nbsp;d2m1(x,&nbsp;a,&nbsp;b,&nbsp;m);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A4&nbsp;=&nbsp;A3&nbsp;&#43;&nbsp;d3&nbsp;*&nbsp;A2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B4&nbsp;=&nbsp;B3&nbsp;&#43;&nbsp;d3&nbsp;*&nbsp;B2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f4&nbsp;=&nbsp;A4&nbsp;/&nbsp;B4;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(Math.Abs((f4&nbsp;-&nbsp;f3)&nbsp;/&nbsp;f4)&nbsp;&lt;&nbsp;epsilon)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">break</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A1&nbsp;=&nbsp;A3;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B1&nbsp;=&nbsp;B3;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A2&nbsp;=&nbsp;A4;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B2&nbsp;=&nbsp;B4;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;m&#43;&#43;;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(m&nbsp;==&nbsp;<span class="cs__number">100</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;<span class="cs__keyword">double</span>.NaN;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f4&nbsp;*=&nbsp;Math.Pow(x,&nbsp;a)&nbsp;*&nbsp;Math.Pow(<span class="cs__number">1</span>&nbsp;-&nbsp;x,&nbsp;b)&nbsp;/&nbsp;a&nbsp;/&nbsp;Beta(a,&nbsp;b);&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(recur)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f4&nbsp;=&nbsp;<span class="cs__number">1</span>&nbsp;-&nbsp;f4;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;f4;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">private</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;e2m(<span class="cs__keyword">double</span>&nbsp;x2,&nbsp;<span class="cs__keyword">double</span>&nbsp;a,&nbsp;<span class="cs__keyword">double</span>&nbsp;b,&nbsp;<span class="cs__keyword">int</span>&nbsp;m)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;-(a&nbsp;&#43;&nbsp;m&nbsp;&#43;&nbsp;<span class="cs__number">1</span>)&nbsp;*&nbsp;(b&nbsp;-&nbsp;m)&nbsp;*&nbsp;x2&nbsp;/&nbsp;((a&nbsp;&#43;&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;m&nbsp;-&nbsp;<span class="cs__number">2</span>)&nbsp;*&nbsp;(a&nbsp;&#43;&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;m&nbsp;-&nbsp;<span class="cs__number">1</span>));&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">private</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;e2m1(<span class="cs__keyword">double</span>&nbsp;x2,&nbsp;<span class="cs__keyword">double</span>&nbsp;a,&nbsp;<span class="cs__keyword">double</span>&nbsp;b,&nbsp;<span class="cs__keyword">int</span>&nbsp;m)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;m&nbsp;*&nbsp;(a&nbsp;&#43;&nbsp;b&nbsp;-&nbsp;<span class="cs__number">1</span>&nbsp;&#43;&nbsp;m)&nbsp;*&nbsp;x2&nbsp;/&nbsp;((a&nbsp;&#43;&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;m&nbsp;-&nbsp;<span class="cs__number">1</span>)&nbsp;*&nbsp;(a&nbsp;&#43;&nbsp;<span class="cs__number">2</span>&nbsp;*&nbsp;m));&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;IncompleteBetaFunctionCF2(<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">double</span>&nbsp;a,&nbsp;<span class="cs__keyword">double</span>&nbsp;b,&nbsp;<span class="cs__keyword">double</span>&nbsp;epsilon)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;p.&nbsp;944&nbsp;&quot;Handbook&nbsp;of&nbsp;Mathematical&nbsp;Functions&quot;</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Edited&nbsp;by&nbsp;Milton&nbsp;Abrmowitz&nbsp;and&nbsp;Irene&nbsp;A.&nbsp;Stegun</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Also&nbsp;see&nbsp;p.&nbsp;19</span>&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;==&nbsp;<span class="cs__number">0</span>&nbsp;||&nbsp;x&nbsp;==&nbsp;<span class="cs__number">1</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;x;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(Math.Abs(x)&nbsp;&gt;&nbsp;<span class="cs__number">1</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">bool</span>&nbsp;recur;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;&gt;&nbsp;<span class="cs__number">0.5</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;t&nbsp;=&nbsp;a;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a&nbsp;=&nbsp;b;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b&nbsp;=&nbsp;t;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;x&nbsp;=&nbsp;<span class="cs__number">1</span>&nbsp;-&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;recur&nbsp;=&nbsp;<span class="cs__keyword">true</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;recur&nbsp;=&nbsp;<span class="cs__keyword">false</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;&gt;=&nbsp;(a&nbsp;-&nbsp;<span class="cs__number">1</span>)&nbsp;/&nbsp;(a&nbsp;&#43;&nbsp;b&nbsp;-&nbsp;<span class="cs__number">2</span>))&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;<span class="cs__keyword">double</span>.NaN;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;x1&nbsp;=&nbsp;<span class="cs__number">1</span>&nbsp;-&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;x2&nbsp;=&nbsp;x&nbsp;/&nbsp;x1;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;Am&nbsp;=&nbsp;<span class="cs__number">1</span>,&nbsp;Bm&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;A0&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;B0&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;A1&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;B1&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;A2&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;B2&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;A3&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;B3&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;e1&nbsp;=&nbsp;<span class="cs__number">1</span>,&nbsp;e2&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;e3&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;f2&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;f3&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">int</span>&nbsp;m&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A1&nbsp;=&nbsp;A0&nbsp;&#43;&nbsp;e1&nbsp;*&nbsp;Am;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B1&nbsp;=&nbsp;B0&nbsp;&#43;&nbsp;e1&nbsp;*&nbsp;Bm;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">while</span>&nbsp;(<span class="cs__keyword">true</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e2&nbsp;=&nbsp;e2m(x2,&nbsp;a,&nbsp;b,&nbsp;m);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A2&nbsp;=&nbsp;A1&nbsp;&#43;&nbsp;e2&nbsp;*&nbsp;A0;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B2&nbsp;=&nbsp;B1&nbsp;&#43;&nbsp;e2&nbsp;*&nbsp;B0;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f2&nbsp;=&nbsp;A2&nbsp;/&nbsp;B2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e3&nbsp;=&nbsp;e2m1(x2,&nbsp;a,&nbsp;b,&nbsp;m);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A3&nbsp;=&nbsp;A2&nbsp;&#43;&nbsp;e3&nbsp;*&nbsp;A1;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B3&nbsp;=&nbsp;B2&nbsp;&#43;&nbsp;e3&nbsp;*&nbsp;B1;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f3&nbsp;=&nbsp;A3&nbsp;/&nbsp;B3;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;m&#43;&#43;;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(Math.Abs((f3&nbsp;-&nbsp;f2)&nbsp;/&nbsp;f3)&nbsp;&lt;&nbsp;epsilon)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">break</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A0&nbsp;=&nbsp;A2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B0&nbsp;=&nbsp;B2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A1&nbsp;=&nbsp;A3;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B1&nbsp;=&nbsp;B3;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(m&nbsp;&gt;=&nbsp;<span class="cs__number">100</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;<span class="cs__keyword">double</span>.NaN;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f3&nbsp;*=&nbsp;Math.Pow(x,&nbsp;a)&nbsp;*&nbsp;Math.Pow(x1,&nbsp;b&nbsp;-&nbsp;<span class="cs__number">1</span>)&nbsp;/&nbsp;a&nbsp;/&nbsp;Beta(a,&nbsp;b);&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(recur)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f3&nbsp;=&nbsp;<span class="cs__number">1</span>&nbsp;-&nbsp;f3;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;f3;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">private</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;icbft(<span class="cs__keyword">double</span>&nbsp;t)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;Math.Pow(t,&nbsp;icbA&nbsp;-&nbsp;<span class="cs__number">1</span>)&nbsp;*&nbsp;Math.Pow(<span class="cs__number">1</span>&nbsp;-&nbsp;t,&nbsp;icbB&nbsp;-&nbsp;<span class="cs__number">1</span>);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;IncompleteBetaFunctionIntegration(&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">double</span>&nbsp;a,&nbsp;<span class="cs__keyword">double</span>&nbsp;b,&nbsp;<span class="cs__keyword">double</span>&nbsp;epsilon)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;==&nbsp;<span class="cs__number">0</span>&nbsp;||&nbsp;x&nbsp;==&nbsp;<span class="cs__number">1</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;x;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">bool</span>&nbsp;recur;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;&gt;&nbsp;<span class="cs__number">0.5</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;t&nbsp;=&nbsp;a;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a&nbsp;=&nbsp;b;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b&nbsp;=&nbsp;t;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;x&nbsp;=&nbsp;<span class="cs__number">1</span>&nbsp;-&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;recur&nbsp;=&nbsp;<span class="cs__keyword">true</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;recur&nbsp;=&nbsp;<span class="cs__keyword">false</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;icbA&nbsp;=&nbsp;a;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;icbB&nbsp;=&nbsp;b;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;ibf&nbsp;=&nbsp;integ.GLIntegrateAB(ni,&nbsp;<span class="cs__number">0</span>,&nbsp;x,&nbsp;xi,&nbsp;wi,&nbsp;icbft)&nbsp;/&nbsp;Beta(icbA,&nbsp;icbB);&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(<span class="cs__keyword">double</span>.IsInfinity(ibf))&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ibf&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(recur)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ibf&nbsp;=&nbsp;<span class="cs__number">1</span>&nbsp;-&nbsp;ibf;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;ibf;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">private</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;icgft(<span class="cs__keyword">double</span>&nbsp;t)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;Math.Exp(-t)&nbsp;*&nbsp;Math.Pow(t,&nbsp;icgA&nbsp;-&nbsp;<span class="cs__number">1</span>);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;IncompleteGammaIntegration(<span class="cs__keyword">double</span>&nbsp;a,&nbsp;<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">double</span>&nbsp;infinity)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;icgA&nbsp;=&nbsp;a;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;integ.GLIntegrateAB(ni,&nbsp;x,&nbsp;infinity,&nbsp;xi,&nbsp;wi,&nbsp;icgft);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;IncompleteGammaCF(<span class="cs__keyword">double</span>&nbsp;a,&nbsp;<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">double</span>&nbsp;epsilon)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;p.&nbsp;263&nbsp;&quot;Handbook&nbsp;of&nbsp;Mathematical&nbsp;Functions&quot;</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Edited&nbsp;by&nbsp;Milton&nbsp;Abrmowitz&nbsp;and&nbsp;Irene&nbsp;A.&nbsp;Stegun</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Also&nbsp;see&nbsp;p.&nbsp;19</span>&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;A0&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;B0&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;A1&nbsp;=&nbsp;<span class="cs__number">1</span>,&nbsp;B1&nbsp;=&nbsp;x,&nbsp;A2&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;B2&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;A3&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;B3&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;fk2&nbsp;=&nbsp;<span class="cs__number">0</span>,&nbsp;fk3&nbsp;=&nbsp;<span class="cs__number">0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">int</span>&nbsp;k&nbsp;=&nbsp;<span class="cs__number">1</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">while</span>&nbsp;(<span class="cs__keyword">true</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A2&nbsp;=&nbsp;A1&nbsp;&#43;&nbsp;(k&nbsp;-&nbsp;a)&nbsp;*&nbsp;A0;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B2&nbsp;=&nbsp;B1&nbsp;&#43;&nbsp;(k&nbsp;-&nbsp;a)&nbsp;*&nbsp;B0;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;fk2&nbsp;=&nbsp;A2&nbsp;/&nbsp;B2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A3&nbsp;=&nbsp;x&nbsp;*&nbsp;A2&nbsp;&#43;&nbsp;k&nbsp;*&nbsp;A1;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B3&nbsp;=&nbsp;x&nbsp;*&nbsp;B2&nbsp;&#43;&nbsp;k&nbsp;*&nbsp;B1;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;fk3&nbsp;=&nbsp;A3&nbsp;/&nbsp;B3;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(Math.Abs((fk2&nbsp;-&nbsp;fk3)&nbsp;/&nbsp;fk2)&nbsp;&lt;&nbsp;epsilon)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">break</span>;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A0&nbsp;=&nbsp;A2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B0&nbsp;=&nbsp;B2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A1&nbsp;=&nbsp;A3;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B1&nbsp;=&nbsp;B3;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;k&#43;&#43;;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(k&nbsp;==&nbsp;<span class="cs__number">100</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;<span class="cs__keyword">double</span>.NaN;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;Math.Exp(-x)&nbsp;*&nbsp;Math.Pow(x,&nbsp;a)&nbsp;*&nbsp;fk2;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;the&nbsp;two&nbsp;methods&nbsp;below&nbsp;are&nbsp;translated&nbsp;from&nbsp;the&nbsp;C&nbsp;functions</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;found&nbsp;in&nbsp;a&nbsp;&quot;Numerical&nbsp;Library&nbsp;in&nbsp;C&nbsp;for&nbsp;Scientists&nbsp;and&nbsp;Engineers&quot;</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__com">//&nbsp;Chapter&nbsp;6&nbsp;Special&nbsp;Functions&nbsp;by&nbsp;H.T.&nbsp;Lau,&nbsp;PhD</span>&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">public</span>&nbsp;<span class="cs__keyword">void</span>&nbsp;ErrorFunction(<span class="cs__keyword">double</span>&nbsp;x,&nbsp;<span class="cs__keyword">out</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;erf,&nbsp;<span class="cs__keyword">out</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;erfc)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;&gt;&nbsp;<span class="cs__number">26.0</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;erf&nbsp;=&nbsp;<span class="cs__number">1.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;erfc&nbsp;=&nbsp;<span class="cs__number">0.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;&lt;&nbsp;-<span class="cs__number">5.5</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;erf&nbsp;=&nbsp;-<span class="cs__number">1.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;erfc&nbsp;=&nbsp;<span class="cs__number">2.0</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;absx,&nbsp;c,&nbsp;p,&nbsp;q;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;absx&nbsp;=&nbsp;Math.Abs(x);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(absx&nbsp;&lt;=&nbsp;<span class="cs__number">0.5</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c&nbsp;=&nbsp;x&nbsp;*&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;p&nbsp;=&nbsp;((-<span class="cs__number">0.356098437018154e-1</span>&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.699638348861914e1</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__number">0.219792616182942e2</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.242667955230532e3</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;q&nbsp;=&nbsp;((c&nbsp;&#43;&nbsp;<span class="cs__number">0.150827976304078e2</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.911649054045149e2</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__number">0.215058875869861e3</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;erf&nbsp;=&nbsp;x&nbsp;*&nbsp;p&nbsp;/&nbsp;q;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;erfc&nbsp;=&nbsp;<span class="cs__number">1.0</span>&nbsp;-&nbsp;(erf);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;erfc&nbsp;=&nbsp;Math.Exp(-x&nbsp;*&nbsp;x)&nbsp;*&nbsp;NonExperFc(absx);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;erf&nbsp;=&nbsp;<span class="cs__number">1.0</span>&nbsp;-&nbsp;(erfc);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(x&nbsp;&lt;&nbsp;<span class="cs__number">0.0</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;erf&nbsp;=&nbsp;-(erf);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;erfc&nbsp;=&nbsp;<span class="cs__number">2.0</span>&nbsp;-&nbsp;(erfc);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">private</span>&nbsp;<span class="cs__keyword">double</span>&nbsp;NonExperFc(<span class="cs__keyword">double</span>&nbsp;x)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">double</span>&nbsp;absx,&nbsp;erf,&nbsp;erfc,&nbsp;c,&nbsp;p,&nbsp;q;&nbsp;
&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;absx&nbsp;=&nbsp;Math.Abs(x);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">if</span>&nbsp;(absx&nbsp;&lt;=&nbsp;<span class="cs__number">0.5</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ErrorFunction(x,&nbsp;&nbsp;<span class="cs__keyword">out</span>&nbsp;erf,&nbsp;<span class="cs__keyword">out</span>&nbsp;erfc);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;Math.Exp(x&nbsp;*&nbsp;x)&nbsp;*&nbsp;erfc;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;<span class="cs__keyword">if</span>&nbsp;(absx&nbsp;&lt;&nbsp;<span class="cs__number">4.0</span>)&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c&nbsp;=&nbsp;absx;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;p&nbsp;=&nbsp;((((((-<span class="cs__number">0.136864857382717e-6</span>&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.564195517478974e0</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__number">0.721175825088309e1</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.431622272220567e2</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__number">0.152989285046940e3</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.339320816734344e3</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__number">0.451918953711873e3</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.300459261020162e3</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;q&nbsp;=&nbsp;((((((c&nbsp;&#43;&nbsp;<span class="cs__number">0.127827273196294e2</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.770001529352295e2</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__number">0.277585444743988e3</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.638980264465631e3</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__number">0.931354094850610e3</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.790950925327898e3</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__number">0.300459260956983e3</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;((x&nbsp;&gt;&nbsp;<span class="cs__number">0.0</span>)&nbsp;?&nbsp;p&nbsp;/&nbsp;q&nbsp;:&nbsp;Math.Exp(x&nbsp;*&nbsp;x)&nbsp;*&nbsp;<span class="cs__number">2.0</span>&nbsp;-&nbsp;p&nbsp;/&nbsp;q);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">else</span>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c&nbsp;=&nbsp;<span class="cs__number">1.0</span>&nbsp;/&nbsp;x&nbsp;/&nbsp;x;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;p&nbsp;=&nbsp;(((<span class="cs__number">0.223192459734185e-1</span>&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.278661308609648e0</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__number">0.226956593539687e0</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.494730910623251e-1</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__number">0.299610707703542e-2</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;q&nbsp;=&nbsp;(((c&nbsp;&#43;&nbsp;<span class="cs__number">0.198733201817135e1</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.105167510706793e1</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__number">0.191308926107830e0</span>)&nbsp;*&nbsp;c&nbsp;&#43;&nbsp;<span class="cs__number">0.106209230528468e-1</span>;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c&nbsp;=&nbsp;(c&nbsp;*&nbsp;(-p)&nbsp;/&nbsp;q&nbsp;&#43;&nbsp;<span class="cs__number">0.564189583547756</span>)&nbsp;/&nbsp;absx;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="cs__keyword">return</span>&nbsp;((x&nbsp;&gt;&nbsp;<span class="cs__number">0.0</span>)&nbsp;?&nbsp;c&nbsp;:&nbsp;Math.Exp(x&nbsp;*&nbsp;x)&nbsp;*&nbsp;<span class="cs__number">2.0</span>&nbsp;-&nbsp;c);&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;}&nbsp;
}</pre>
</div>
</div>
</div>
<h1><span>Source Code Files</span></h1>
<ul>
<li><em>Analysis.cs&nbsp;-&nbsp;simple sample statistics.</em> </li><li><em><em>Zeros.cs&nbsp;-&nbsp;zeros of orthogonal polynomials in particular the Legendre polynomials used in Gauss-Legendre integration formulas.</em></em>
</li></ul>
<h1>More Information</h1>
<p><em>For more information on statistics, see the <strong>Handbook of Mathematical Functions</strong> edited by Milton Abramowitz&nbsp;and Irene A. Stegun.</em></p>