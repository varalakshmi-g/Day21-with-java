# Day21-with-java

Hello all, This is my Day21 with java. Today I practiced and learned how to count number of stars in pattern programming.

while writting the pattern programming, to count stars we have three approaches. Among them we have to choose the best approach which will saves our time.

Here is the first approach,

count=0;
for(i=1; i<=n; i++)
{
for(j=1; j<=i; j++)
{
count++;
}
}

In this approach, time complexity is O(n^2). It is worst case of programming.Why we are calling it as worst case means, it is time taking process to get output. And it is looping n+1 times to get output.

Here is the second approach,

count=0;
for(i=1; i<=n; i++)
{
count = count + i;
}

In this approach, time complexity is O(n).  It is also bad case in programming. Because it is iterating n times to get output.

here is the third and best approach,

count = n*(n+1)/2;

It is the best approach of programming because, it's time complexity is O(1). It is iterating only one time to get output. 

In this era, human beings are chosing the one which takes less time to get output. They can't even wait for seconds also. So 3rd approach is the best and fastest approach for all projects.




