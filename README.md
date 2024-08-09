What is Linear Search?
Linear search is one of the simplest search algorithms. From a given list or array, it searches for the given element one by one. Linear Search iterates over the whole list and checks if any particular element is equal to the search element. It’s also called the sequential search.

Here are the steps of the flowchart:

Step 1) Read the search item, “item.”

Step 2) Initiate i=0 and index=-1

Step 3) If i<N, go to step 4. Else, go to step 8.

Step 4) If Data[i] equals to “item,” then go to step 5. Else go to step 6.

Step 5) Index = i (As the item is found at index no i). Go to step 8.

Step 6) i = i +1.

Step 7) Go to step 3.

Step 8) Stop.

[flowchart](https://github.com/user-attachments/assets/30c167bf-5071-4c9d-9f71-fb3f541b3182)


Python Code Example Linear Search:

    def linearSearch(data, item):
    
        for i in range(len(data)):
    
        if data[i] == item:
    
        return I

    return -1

    data = [1, 9, 8, 7, 6, 3, 11, 4, 6, 9, 7, 2, 0, 19, -10]

    item = int(input("Enter a number to search: "))

    idx = linearSearch(data, item)

    if idx >= 0:

        print("{} is found at index {}".format(item, idx))

    else :

        print("{} was not found".format(item))


Output:

Enter a number to search: -10

-10 is found at index 14
