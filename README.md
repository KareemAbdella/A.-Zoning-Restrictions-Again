A. Zoning Restrictions Again
time limit per test1 second
memory limit per test256 megabytes
inputstandard input
outputstandard output
You are planning to build housing on a street. There are n spots available on the street on which you can build a house. The spots are labeled from 1 to n from left to right. In each spot, you can build a house with an integer height between 0 and h.

In each spot, if a house has height a, you will gain a2 dollars from it.

The city has m zoning restrictions. The i-th restriction says that the tallest house from spots li to ri (inclusive) must be at most xi.

You would like to build houses to maximize your profit. Determine the maximum profit possible.

Input
The first line contains three integers n, h, and m (1≤n,h,m≤50) — the number of spots, the maximum height, and the number of restrictions.

Each of the next m lines contains three integers li, ri, and xi (1≤li≤ri≤n, 0≤xi≤h) — left and right limits (inclusive) of the i-th restriction and the maximum possible height in that range.

Output
Print a single integer, the maximum profit you can make.

sub : https://codeforces.com/contest/1162/submission/54003895
