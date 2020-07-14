# Find_Frquency_Algorithm
Algorithm to find the frequency of each element in the array

In this program, we have an array of elements to count the occurrence of its each element. One of the approaches to resolve this problem is to maintain one array to store the counts of each element of the array. Loop through the array and count the occurrence of each element as frequency and store it in another array fr.*/


Pseudocode:

STEP 1: START
STEP 2: INITIALIZE arr[] ={1, 2, 8, 3, 2, 2, 2, 5, 1 }.
STEP 3: CREATE fr[] of arr[] length.
STEP 4: SET visited = -1.
STEP 5: REPEAT STEP 6 to STEP 9 for(i=0;i<arr.length;i++)
STEP 6: SET count = 1
STEP 7: REPEAT STEP 8 for(j=i+1;j<arr.length;j++)
STEP 8: if(arr[i]==arr[j]) then
            count++
            fr[j] =visited
STEP 9: if(fr[i]!=visited) then
            fr[i]=count
STEP 10: PRINT "------------"
STEP 11: PRINT "Element | Frequency"
STEP 12: PRINT "-------------"
STEP 13: REPEAT STEP 14 for(i=0;i<fr.length;i++)
STEP 14: if(fr[i]!=visited) then
            PRINT arr[i] and fr[i]
STEP 15: PRINT "-------------"
STEP 16: END 
